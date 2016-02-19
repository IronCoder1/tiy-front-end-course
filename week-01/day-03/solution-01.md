# Day 3 Solutions

## Problem 1

### Tags also known as elements are used to structure HTML Documents this is also known as 'semantics'. The following tags are explained below.

There are different kinds of content and HTML organises all elements into different categories. 

* <strong> used to give text strong importance, usually rendered in bold. flow and phrasing content using a start and end tag.

* <em> used to markup text with stress emphasis. flow , phrasing and palpable content using starting and ending tag.

* <blockquote> used for long quotes (where <q> short quote) cannot be used. Flow, sectioning root, and palpable content using starting and ending tags.

* <q> short quote, flow phrasing and palpable content, using starting and ending tags dom interface HTMLQuoteElement

* <abbr> represents abbreviation optionally provides full description in title. example <p>I do <abbr title="Hypertext Markup Language">HTML</abbr></p>

* <cite> when you need to reference a creative work e.g essay. it must include url of ref.can be controlled by css example is More information can be found in <cite>[ISO-0000]</cite>.
* <dfn> to define a term. cannot be a descendant. must start and end tag. in HTML5 It should be given by <p> or <section> or <dt>,<dd> pair (definiton list).

* <address> used to supply contact info when used in <article> or for entire doc when used in <body> (ancestor). can be used in <footer> must start and end tag. e.g

<footer><address>
Visit us at:<br>
IronYard, London, UK.
</address> </footer>


* <ins> a range of text added to document. start and end tags a must, any phrasing or flow content e.g <p> My favorite color is <del> blue</del> <ins>red</ins>!</p>

* <del> represents deleted text and renders with a strike through. must start and end tags. e.g

<p> My favorite color is <del> blue</del> sorry i forgot :( </p>


* <s> strike through rendering used to notify temporary change. e.g 
<p> <s>Today's Special: Salmon</s> SOLD OUT </s>


##Problem 2

Explain why do we need <thead>, <tbody> and <tfoot>?
These are used to group attributes together for further styling, printers and readers also understand this semantic organization most effective when using a different style sheet (css)


