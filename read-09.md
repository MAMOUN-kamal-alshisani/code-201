# read-09-Forms and Events.

### Forms :
***Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.
HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to 
your site.***

### Why Forms?
***The best known form on the web is probably the search box that sits right in the middle of Google's homepage
In addition to enabling users to search, forms also allow users to perform other functions online.***

### Form Controls
***There are several types of form controls that you can use to collect information from visitors to your site
1.ADDING TEXT:***
+ Text input (single-line)
- Password input
+ Text area (multi-line),massages and comments
2.Making Choices:__
- Radio buttons :For use when a user must select one of a number of options.
- Checkboxes :When a user can select and unselect one or more options.
-Drop-down boxes :When a user must pick one of a number of options from a list.

__3.Submitting Forms:__
+ Submit buttonsTo submit data from your form to another web page
- image buttonsSimilar to submit buttons but they allow you to use an image.

__4.Uploading Files:__
- File upload Allows users to upload files (e.g. images) to a website.

### Form Structure :
***Form controls live inside a <-form-> element. This element should always carry the action
attribute and will usually have a method and id attribute too.***

#### action :
***Every <-form-> element requires an action attribute. Its valueis the URL for the page on the server that will receive the 
information in the form when it is submitted***

#### method :
***Forms can be sent using one of two methods: get or post.With the get method, the values from the form are added to 
the end of the URL specified in the action attribute.***



# Lists : 1. list-style-type :
***The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 
It can be used on rules that apply to the <-ol->, <-ul->, and <-li->elements.***

2. Unordered Lists :
***For an unordered list you can use the following values:***
 + none
- disc
- circle
 + squar

3. ***Ordered Lists For an ordered (numbered) list you can use the following values:***
decimal
1 2 3
decimal-leading-zero
01 02 03
lower-alpha
a b c
upper-alpha
A B C
lower-roman
i. ii. iii.
upper-roman 
I II III

## Images for Bullets:list-style-image.
**You can specify an image to act as a bullet point using thelist-style-image property.
The value starts with the letters url and is followed by a pair of parentheses. Inside the 
parentheses, the path to the image is given inside double quotes.This property can be used on 
rules that apply to the <-ul-> and <-li-> elements.The example on this page also 
shows the use of the marginproperty to increase the vertical gap between each item in the list***

# events summary :
- ***Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).*** 
- ***Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.*** 
- ***When an event occurs on an element, it can trigger aJavaScript function. When this function then changes the web page in some way,***
***it feels interactive because it has responded to the user.*** 
- ***You can use event delegation to monitor for events that happen on all of the children of an element.*** 

