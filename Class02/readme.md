# Class02

<sup> Code for superscript
<sub> Code for subscript

Superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning.

<abbr> Code for abbreviations.  this is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the <abbr> to mark up the abbreviation. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means.

## CSS Structure

3 types of stylesheets....external, internal, inline styles.

External: An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet. In the Getting started with CSS, we linked an external stylesheet to our web page.

Internal: An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a <style> element contained inside the HTML <head>.

Inline Styles: Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute. The implementation of an inline style in an HTML document might look like this:

CSS Selectors: h1
a:link
.manythings
#onething
*
.box p
.box p:first-child
h1, h2, .intro

CSS Declarations: When a property is paired with a value, this pairing is called a CSS declaration. Properties: These are human-readable identifiers that indicate which stylistic features you want to modify. For example, font-size, width, background-color.
Values: Each property is assigned a value. This value indicates how to style the property.

Javascript Statements

If...else: This code is pretty human-readable — it is saying "if the condition returns true, run code A, else run code B"

You should note that you don't have to include the else and the second curly brace block 

Else...if: The last example provided us with two choices, or outcomes — but what if we want more than two?

There is a way to chain on extra choices/outcomes to your if...else — using else if. Each extra choice requires an additional block to put in between if () { } and else { } — check out the following more involved example, which could be part of a simple weather forecast application.

Comparison Operators: Comparison operators are used to test the conditions inside our conditional statements. We first looked at comparison operators back in our Basic math in JavaScript — numbers and operators article. Our choices are:

=== and !== — test if one value is identical to, or not identical to, another.
< and > — test if one value is less than or greater than another.
<= and >= — test if one value is less than or equal to, or greater than or equal to, another.

Logical Operators

&& — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.

|| — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.