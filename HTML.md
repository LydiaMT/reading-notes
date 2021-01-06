# HTML Notes
This is a compilation of my reading notes from the book HTML & CSS

## Chapter 18: Process & Design
Design your website for your target audience i.e. individuals vs companies, income, age, etc

Determine **WHY** people visit your website? What are they *motivations* and *goals*. Also determine **WHAT** your visitors are trying to achieve i.e. key tasks and motivations. **WHAT** information do your visitors need such as are the visitors familiar with your brand or do you need to explain it?. You also want to think about how frequently people will visit your site i.e. once, twice, daily. This will help you determine how often you need to update your site. 

Now that you know who is coming, why they are coming, and how they are using your site, let's create a sight map. Organize your site map with the **cart sorting** method, and make sure to think about how your visitors will want things organized over how you want things organized. Common card sorting organization will start with HOME as the main category, then have sub categories like ABOUT, ARTICLES, VISIT, SHOP, CONTACT, etc.

WIREFRAMES: sketch of the key information that needs to go on each page of your website. These are simple outlines with no color, fonts, images, etc. Your designer will support with those elements. Be prepared to share wire frames with clients. 

Create your CONTENT. PRIORITIZE what content is the most important and make it distinct with design elements that pop to create a visual hierarchy. ORGANIZE or group related content into blocks. 

VISUAL HIERARCHY: "refers to the order in which your eyes perceive what they see. Since most users will skim your page, create hierarchy through SIZE, COLOR, and STYLE. Larger elements will grab attention. Foreground and background color can create attention. Style can make important elements stand out. Images also create strong visual contract to draw viewers in. Remember, most of this is subliminal to the viewer. Be intentional. 

GROUPING & SIMILARITY: Grouping items or making them similar will help your viewer relate items to each other. Things that create this include proximity, closure, continuance, white space, color, boarders. Stay consistent with your style. Headings can be very helpful. 

DESIGNING NAVIGATION: concise (try to limit to 8), clear (predictable), selective, context (colors in the text to indicate which page the viewer is on), interactive (link changes when mouse hovers over it), consistent (keep the navigation the same across all pages)

## Chapter 1

## Chapter 17: HTML5 Layout
* Old HTML layout: developers used div tags with id's to define the purpose of the div i.e. header, navigation, sidebar, etc. 
* New HTML layout: now, some div's are replaced with the id name; so rather than ```<div id=header>``` you will see ```<header>```. This new way of writing HTML tags helps the author describe the structure of the page. 
* header & footer: Header may contain site name and main navigation. Footer may contain copyright info. If you have multiple articles on your page you may want headers and footers for each article.
* nav: Navigation contains major navigational blocks for the site i.e. home, about, classes, contact, etc.
* article: acts as a container for any section of a page that could stand alone i.e. article, blog, comment forum, etc. If a page has multiple articles you will create multiple article tags that are their own section. You can next article tags. 
* aside: When used in an article tag, aside should contain content related to the article. When used on its own, it acts as a container for content related to the entire page i.e. links to other sections of the site, search box, etc. 
* section: element group that relates content together
* hgroup: group one or more headers so they are treated as one single header (controversial)
* figure and figcaption: use for images, videos, graphs, diagrams, code samples, or text that supports the main body of an article. Accompany with a text description caption.  
* div: used to group together related elements. 
* linking around block-level elements: allows you to turn an entire block into a link
* helping older browsers understand: to help older browsers understand HTML5, include the following line of CSS which states new elements should be rendered as block-level elements

CSS
`header, section, footer, aside, nav, article, figure, figcaption  {
    display: block;
}`

HTML *(ignore ` in below statement)*
`<!--[if It IE 9]>
  <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
<!-- and -->`

## Chapter 8: Extra Markup

##### The evolution of HTML
* HTML 4 (1997): phased out center, font, and strike
* XHTML 1.0 (2000): Introduced some new rules. Other than img, every element needed closing tags. Attributes names had to be lower case. All attributes required a value in double quotes. Deprecated elements no longer used. Elements need to be open and closed within their parent element. 
* HTML5 (present)

#### Enter: HTML5
* Start HTML files with `<!DOCTYPE html>`
* Make comments with `<!-- -->`
* id attributes are use to uniquely identify that element from another element. No two elements should share the same id. Useful for CSS styling. 
* class attributes help you identify several elements as being different from other elements. 
* Block elements: start a new line i.e. h1, p, ul, li
* Inline Elements: continue on the same line i.e. a, b, em, img
* div: allows you to group a set of elements together. beck practice is to use a comment at the end with the same language you picked for your div's id
* span: inline div equivalent. Used to control appearance of these specific elements with CSS. Because of this, span is usually accompanied by id or class. 
* iframe: Inline Frame. Usually used to embed a Google Map. iframe elements are accompanied with src, height, scrolling (XHTML and earlier), frameborder (XHTML and earlier), and seamless
* meta: lives inside head element. It's not visible to the user but tells the search engine information about your page. Also uses http-equiv. Author, pragma = prevents browser from caching the page, and expires = when page should expire. 
* See escape characters on page 194

[⬅ Back to README Home](README.md)