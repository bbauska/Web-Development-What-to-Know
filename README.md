Web development is the best job in the world. You build on a platform with nearly 5 billion daily 
active users. All connected together like the neurons of a global super intelligent brain. A system 
that can cure disease, eliminate poverty, advance science and stuff like that. But mostly it's used 
to share memes, create parasocial relationships, amplify drama, and, most importantly, make tons and 
tons of money. If you want to get into it you're going to need to know some stuff. Like a lot of stuff. 
In web development 101 we'll take a look at 101 different concepts that you'll need to know when 
building full stack web apps. This is the internet. It's a network of billions of machines connected 
together.

What do you write to it like mail. No, a lot of people use it and communicate. I guess they can 
communicate with NBC writers and producers. Allison can you explain what internet is. It was 
officially born on January 1st, 1983 thanks to the establishment of the Internet Protocol Suite 
which standardized the way these computers communicate. The Internet Protocol is used to identify 
different computers on the network by assigning each one of them a unique IP address. These 
computers can then send data back and forth with the transmission control protocol. It breaks data 
into a bunch of small packets. Kind of like puzzle pieces then sends them through a bunch of 
physical components like fiber optic cables and modems. 

Before they're put back together by the receiving computer you can think of the internet as 
hardware but the internet is not the same thing as the web. The world wide web is like software 
that sits on top of the internet. Where people can access web pages with the hypertext transfer 
protocol. What's special about it is that it gives every page of content a uniform resource locator 
or URL. Humans typically use a tool called a web browser to access a URL where it can be rendered 
visually on their screen. The browser is called the client because it's consuming information but 
on the other end of that URL there's another computer called a server. It received an HTTP request 
from the client, then sent a response containing the webpage content. These are called HTTP 
messages. But more on that later. What's interesting is that every web page has a unique domain 
name like fireship or example.com.

A domain name can be registered by anyone via a registar whose accredit by ICAN, a nonprofit 
responsible for overseeing name spaces on the internet. When you navigate to a domain in a 
browser it gets routed through the domain name system that maps these names to an actual IP address 
on a server somewhere. DNS is like the phone book of the internet. Now when you look at a web page 
the actual content you see is represented by hypertext markup language. Most browsers have "dev 
tools" where you can inspect the structure of the HTML at any time to build your own web page. 
You'll want a text editor like VS-Code. An HTML document is just a collection of elements, where 
an element is an opening and closing tag with some content in the middle. Like a paragraph and 
heading it also has elements that handle user input. Like the select and input Eeements which are 
used to build forms. 

In addition, elements can have one or more attributes to change their behavior. For example, an 
input can have a type like "text" or "number". Which the browser will render differently to collect 
the appropriate value. But the element that puts the hyper text in HTML is the "a" tag or "anchor". 
It's a link that allows one page to navigate to a different page based on its URL. These elements 
are nested together in a hierarchy to form the document object model or "DOM". From the root element 
a web page is split into two parts; the head contains invisible 
content like metadata and a title. 

Then we have the body for the main content that the end user actually sees. The reason we wrap 
everything in tags is to give browsers and bots hints about the semantic meaning of the web page. 
This allows search engines to display results properly and also helps with accessibility for 
devices. Like screen readers that allow anybody regardless of disability to enjoy the content. My 
computer reads me the text. Bro smash that like button and subscribe. One of the most common elements 
you'll come across is div or division to define a section of the web page on its own. A div might 
not seem to do anything and currently produces this plain black and white website that begs the 
question how do we make this website look cool. 

The second language you'll need to learn as a web developer is cascading stylesheets or css which 
allows you to change the appearance of the HTML elements one way to accomplish that is with an 
inline style using the style attribute. On an element, the style itself contains a collection of 
properties and values that change the appearance of the element. Like, we might make the background 
color black and the text color red. What we've created here is an inline style that will only be 
applied to this one element. However, CSS Cascades which means it can be applied to multiple elements 
at the same time. Providing better code reusability. 

Another option is to move our code into a 
style tag but to make the code work we'll first need to define a selector so it knows which 
elements to target a selector. For example, can target all of the paragraph elements on the page. But 
that's too broad. We can be more granular by defining a class that style can then be applied to one 
or more elements with the class attribute. What's interesting though is that we now have classes 
that apply different styles to the same element. CSS contains a bunch of specificity rules that 
determine which styles are relevant to an element in a way that's self-evident and elegant. Like a 
benevolent elephant. Most often, though, we don't use style tags. But instead, use an external style 
sheet which is linked to the web page in the head of the document. 

When it comes to CSS, by far the 
most difficult thing to learn is layout and positioning. Think of every element like a box. The 
outside of that box is wrapped with padding, border, and margin. The boxes then take up space on the 
page. From top to bottom, some elements like heading have a display of block, by default. Which means 
they take up all available horizontal space. Other elements like image are displayed in line which 
means they can line up horizontally side by side. The problem is that the default position is 
usually not desirable. It can be changed by customizing the position property on an element. Relative 
positioning allows an element to move a certain number of pixels from its normal position. Absolute 
positioning is similar, but the position values are relative to its nearest ancestor. And then we 
have fixed positioning which will keep an element on the screen even as the user scrolls away. From 
it because it's fixed to the entire viewport. Changing the position of an element is one thing. But 
one of the biggest challenges web developers face is creating responsive layouts. Users can access 
your web page from all kinds of different screens and it should look good on all of them. CSS 
provides a bunch of different tools to help make this happen. 

One of which is media queries. A media query allows you to get information about the device that's rendering
the web page. And apply different styles accordingly. But, more importantly, it provides layout tools 
like flexbox. Applying display flex allows the parent to control the flow of the children. To easily create rows and 
columns for more complex layouts. Display grid can be used to control multiple rows and columns at 
the same time. Now CSS is usually not considered a turing complete programming language. On its own 
however it does have mechanisms like cal to perform mathematical operations and custom properties. 
Which are like variables, that you can reuse in multiple places. Vanilla CSS is rarely enough though. 
And many developers choose to extend it with tools like SAS that add additional programmatic 
features. On top of it. 

And that brings us to the third language. You'll need to know as a web developer JavaScript. Technically, 
you don't need JavaScript to build a website. However, most developers choose to use it to make the 
user interface more interactive. To run JavaScript code on a web page; open up a script tag, then write 
some JavaScript code inside of it. The browser interprets the HTML from top to bottom and runs this code. 
When it encounters it in the DOM, in most cases, JavaScript is written in a separate file. Then referenced 

as the source on the script tag usually it's preferred that this code runs after the Dom content has loaded which can be accomplished with the defer attribute JS is a big complicated programming language which is more formally known as ecmascript and is standardized in all major browsers there are several different ways to declare a variable a variable that might be reassigned in the future uses the let keyword while a variable that can't be reassigned uses con it's a dynamically typed language which means no type annotations are necessary that's not always ideal so many developers choose typescript as an alternative to add static typing on top of JavaScript now one of the most common reasons you would use JavaScript in the first place is to handle events whenever the user does something on a web page the browser emits an event that you can listen to like a click Mouse move form input change and so on we can tap into these events using browser apis like document which in this case provides a method called query selector that allows us to grab an element El with a CSS selector once we have that element set as a variable we can then assign an event listener to it an event listener is a function that will be called or re-executed anytime the button is clicked the language has a variety of built-in data structures like an array to represent a collection of values but the most fundamental data structure is the object also commonly called a dictionary or hashmap anything that's not a primitive type like a string or number inherits its base functionality from the object class it relies on a technique called prototypal inheritance where an object can be cloned multiple times to create a chain of ancestors where the child inherits the properties and methods of its ancestors this is different from class-based inheritance which is kind of confusing because JavaScript also supports classes however these classes are just syntactic sugar for prototypal inheritance but now we're getting a little too low level most developers don't ever want to have to touch the word prototype so what we do instead is use a front-end framework like react view spelt angular and so on all of these Frameworks do the same thing in a slightly different way which is represent the UI as a tree of components a component can encapsulate HTML CSS and JavaScript into a format that looks like its own custom HTML element most importantly they produce declarative code that describes exactly what the UI does and that's much easier to work with than imperative code that you would normally get with just plain vanilla JavaScript at this point we've taken a look at the front end stack but now we need to switch gears to the back end starting with node.js which is a serers side runtime based on JavaScript you can run serers side code for web applications and all kinds of different languages but node is the most popular because it relies on the same language as the browser it's also based on the same V8 engine that powers the Chromium browser to run code in a single-threaded non-blocking event Loop this allows node to handle many simultaneous connections quickly and efficiently in addition it allows developers to share work remotely thanks to the node package manager a package is also called a module which is just a file that contains some code with an export statement so it can be used in another file the file can consume a module with an import statement but now we need to think about how to deliver the actual website from the server to the client the classic option is serers side rendering in this approach the client will make a get request for a certain URL every request has an HTTP method and git means you want to retrieve data from a server as opposed to methods like post and Patch where the intent is to modify data the server receives the request and then generates all the HTML on the server and sends it back to the client as a response the response contains a status code like 200 for success or levels 4 and 500 for errors for example if the web page doesn't exist the server will return a 404 status code which you've likely seen before as a web user SSR is extremely popular but in some cases it may not be fast enough another approach is the single page application with this approach the server only renders a shell for the root URL then JavaScript handles the rendering for all other pages on the website the HTML is generated almost entirely client side in the browser making the website feel more like a native iOS or Android app when the app needs more data it still makes an HTTP request but only requests a minimal amount of data as Json which is called a data interchange format that can be understood by any programming language this can result in a great user experience however it can be very difficult for Bots like search engines and social media link previews to understand content on the page this led to another rendering strategy called Static site generation in this case every web page on the site is uploaded to a server in advance allowing Bots to get the information they need a frontend JavaScript framework usually takes over to hydrate the HTML to make it fully interactive and behave like a single page application performance is extremely important and you'll want to use tools like Lighthouse to optimize metrics like first contentful paint and time to interactive now to implement one of these patterns most developers will use a full stack framework like nextjs Ruby on Rails laravel and so on they abstract away many of the more tedious things developers don't want to deal with one of which is module bundlers which are tools like webpack and that take all of your JavaScript CSS and HTML and package it in a way that can actually work in a browser they might also provide a linter like es lint to warn you when your code doesn't follow the proper Style Guidelines oh and I almost forgot you are definitely going to need a database to build a full stack web application because you need somewhere to store your data like data about your users but in order to get that data you'll need to give users a way to log in Via a process called user authentication now before you deploy your code you'll need to test it with a web server there are tools like engine X and A pchy to create an HTTP server but your framework will likely do this for you by serving the files on Local Host which makes your own IP address behave like a remote web server when it comes time to deploy you'll likely use a big cloud provider like AWS most apps are containerized with Docker making them easy to scale Up and Down based on the amount of traffic that they receive there are many tools out there that function as a platform as a service to manage this infrastructure for you in exchange for your money or if you don't want to get locked in with a giant Tech Corporation you might host your app on a decent calized blockchain with web 3 and that's about 1% of what you'll need to know to call yourself a full stack web developer if that seems overwhelming don't worry too much almost nobody knows what the hell they're doing and we all just use Google to figure things out on the Fly congratulations you just passed web development 101 thanks for watching and I will see you in the next one
