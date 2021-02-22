# HTML Summaries
#### Html (hypertext markup language) is a code language that can make the website structure and it markup the browser and tell him about the website.

* ## Old HTML VS New HTML
#### Web page authors used <div> elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar).
#### But today with HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already

* ##  The <header> and <footer> elements can be used for:
* #### 	The main header or footer that appears at the top or bottom of every page on the site.
* #### A header or footer for an individual <article> or section> within the page

* ## The <nav> element
#### Is used to contain the major navigational blocks on the site such as the primary site navigation.
* ## The <article> element
#### Acts as a container for any section of a page that could stand alone and potentially be syndicated.
#### This could be an individual article or blog entry, a comment or forum post, or any other independent piece of content.

* ## The <aside> element
#### Has two purposes, depending on whether it is inside an <article> element or not:
* #### When the <aside> element is used inside an <article> element, it should contain information that is related to the article but not essential to its overall meaning. For example, a pull quote or glossary might be considered as an aside to the article it relates to.
* #### When the <aside> element is used outside of an <article> element, it acts as a container for content that is related to the entire page. For example, it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.

* ## The <section> element
#### Groups related content together, and typically each section would have its own heading.
  
 * ## <hgroup> element (<h1>-<h6>)
#### Use to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.
  
  * ## <figure> elements
 #### It should only be used when the content simply references the element (and not for something that is absolutely integral to the flow of a page).
#### Examples of usage include:
#### -	 Images
#### -	 Videos
#### -	 Graphs
#### -	 Diagrams
#### -	 Code samples
#### -	Text that supports the main
#### -	body of an article
#### The <figure> element should also contain a <figcaption> element which provides a text description for the content of the <figure> element. In this example, you can see a<figure> has been added inside the <article> element However, the <div> element.

* ## 	The <div> element
#### It’s an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.

#### Where there is no suitable element to group a set of elements, the <div> element will still be used.
  * ## Help old browser to understand HTML 5 
 #### Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of #### CSS on the left which states which new elements should be rendered as block-level elements. 

#### Also, IE9 was the first version of Internet Explorer to allow CSS rules to be associated with these new HTML5 layout elements. 

#### In order to style these elements using earlier versions of IE, you need to use a simple JavaScript known as the HTML5 shiv or HTML5 shim.


