### W3C DOM
- organization that maintains the standard for HTML

### WHATWG DOM
- HTML specific
- web pages couldn't be rendered between different browsers

https://html.spec.whatwg.org/multipage/

### IANA
- DNS and IP registry organization
- DNS - giant list of IP address and domain names associated with them

Browser - read the page (translates to readable name, uses HTTP)
WebServer - serve the page (uses HTTP)
DNS - way to access WebServer
ISP (Internet Service Provider) - central hub that connects all 3 blocks together
Browser caches to save time 

### TCP/IP
- lower level packet-oriented
- everything goes through TCP/IP
- communication protocol of the webserver

### HTTP
- sends post/get requests as packages/messages
- gets stuff from certain pages or REST APIs
- browser makes HTTP request to load page details/visuals
- communication protocol of the internet

### Element
- global/specific attributes
- check MDN for global attributes

### Character Encoding
- Typeset vs UTF8 vs ASCII vs ANSI
- charset is an attribute of the META element described in the header 

### Semantic tag
- explicit vs implicit tags
- "what is the purpose of the element?"
- "why do we need the element/tag?"

### Search Engine Optimization (SEO)
- interpret the page faster and more efficiently for search engines; search engines

### Browser Inspector
- for reading source code on the front-end/HTML page

### Viewport
- the way you view an element (screen)

### Media Query

### DOM
- representation of the page using a tree concept
- nodes - data structure
- objects - basically the node interpreted as an object
	- properties/attributes/states/values
	- functions/methods/behaviors
	- contains general document and window objects
- how to manipulate the tree?
	- manipulate by reading and writing
	- add elements, update elements, delete nodes, read nodes

### Box Model
- change the size of the content with width and height
- block-level and inline-level elements
	- inline-level elements can contain block-level elements but not vice-versa
	- span is an example of an in-line element
	- div is an example of a block element
### CSS
-inline css - written in the element tag itself (is not normally used, but has special cases)
-internal styling - including CSS file itself in style tag of head
-selector - identifies the element you want to style
-property - the attribute within the element you want to style
-the browser will build the DOM then render the page in that order

### Selectors
- simple selectors - one or more elements based on the element's name, class, or id
- attribute selectors - one or more elements based on their attribute/attribute values
	- ID selectors - # before name (selects elements of the same ID)
	- class selectors - . before name (selects elements of the same class)
- pseudo-classes - 
	- nth-child(n)
- pseudo-elements
	- dashed property names (border-top, text-align)
	- CSS shorthand
	- have specific order of property values
- combinators - + immediately after (single) ~ immediately after (multiple)
- multiple selectors
- combinators dont have a particular order

### Lengths and Percentages
- px - pixels
- em - font size (inherits size of font)
- % - percentages (inherits size of container)
- pt - points
- rem - responsive font size

### Div containers
- div containers are naturally responsive

### Syntax
- syntax is 6 categories

### Class & ID
- used to identify your elements
- html elements can take more than one class value
- Precedence
	- inline style (will persist on top of all of them)
	- ID
	- child to parent
	- class and pseudo classes
	- elements and pseudo elements

- path is a URI
- URL is a URI
- URI is not always a URL
- shorthand
- float - moves element contents over while maintaining flow of the page
- object-fit - fits content within container borders

### Transitions
- pseudo-classes are for transitions/events

### CSS Rules
- dont style anything on their own, but edit other styles
- @keyframes
- opacity
- extension: external file source

### Viewport
- media query - set of rules for viewports or devices