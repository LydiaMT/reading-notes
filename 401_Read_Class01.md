## Read: Class 01 - Node Ecosystem, TDD, CI/CD

### Review, Research, and Discussion

**1. Describe (in plain English) what Array.map() does**

Array.map() Iterates over an array and returns a **new array** of the same length as the original array. Does not modify the original array. It does the same thing to all the values in the original array. The .map() method creates a new array populated with the results of calling a **provided function** on every element in the calling array. *Sources: [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) , [CodeFellows](https://codefellows.github.io/code-301-guide/curriculum/class-07/challenges/)*


**2. Describe (in plain English) what Array.reduce() does**

The .reduce() method executes a **reducer function** (that you provide) on each element of the array, resulting in single output value. It runs a callback on every element. It requires an accumulator, and sometimes uses an initializer (initalValue) which can be a variety of data types (number, array, object, etc.). Great way to restructure something into something else i.e. reshaping data by turning an array of objects into an array of key: value pairs, for example. *Sources: [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce) , [CodeFellows](https://codefellows.github.io/code-301-guide/curriculum/class-09/challenges/)*

**3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result**

  **- With normal Promise .then() syntax**
  
  Example from [My Book App](https://github.com/LydiaMT/book_app)
  ```js
  app.post('/searches', (request, response) => {
    const url = `https://www.googleapis.com/books/v1/volumes?q=in${request.body.search}:${request.body.search_input}`;
    superagent.get(url)
      .then(bookThatComesBack => {
        const bookArray = bookThatComesBack.body.items.map( bookValue => new Books(bookValue));
        response.render('pages/searches/show.ejs', {bookArray: bookArray});
      })
      .catch(errorThatComesBack => {
        console.log(errorThatComesBack);
        response.status(500).send('Sorry something went wrong');
      });
  });
  ```

  **- Again with async / await syntax**
  
  Example from [My async/await code challenge](https://replit.com/@LydiaMinehanTub/AsyncAwait)
  ```js
  const getCityData = (name) => {
    superagent.get(`https://geocode.xyz/${name}?json=1`)
      .then((data) => {
        const parsedData = JSON.parse(data.res.text)
        if(parsedData.error){
          console.log(parsedData.error.description)
        } else {
          console.log(`latitude: ${parsedData.latt}, longitude: ${parsedData.longt}`)
        }
      }).catch(error => {
        console.error('Oops, something went wrong', error)
      }) 
  }

  async function cityData(city) {
    try{
      await getCityData(city);
    } catch(error) {
      console.error('Oops, something went wrong', error)
    }
  }
  cityData('Seattle')
  ```
**4. Explain promises as though you were mentoring a Code 301 level student**

Think of a promise in terms of a real life situation. Say you are at a restaurant with your friends. You order food and the waiter takes your order and brings it back to the kitchen. During that time you can talk with your friends, have your drinks, and take place in other activities while the waiter is placing your order with the kitchen. If the waiter is able to place your order, then your order is 'resolved'. However if they are unable to place your order they will come back to the table and say 'We are out of that dish, what else would you like to order instead?' which is an example of your order being 'rejected'. Promises are like the relationship between the waiter and your table party. Your table party does not have to full stop while the waiter is placing your order, just like in script the function is still able to run while the promise is fetching information. *Source [Emma Bostian on Shop Talk](https://shoptalkshow.com/458/)*

**5. Are all callback functions considered to be Asynchronous? Why or Why Not?**

In short: No, it depends on the situation. Callbacks invoke other functions whereas Asynchronous functions await a Promise. 

[⬅ Back to README Home](README.md)
