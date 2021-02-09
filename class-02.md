### HTML Chapter Two: Text

Discusses the headings, paragraphs, bold and italics tags.

**Superscript** \<sup\> is used for things like date suffixes and exponents

**Subscript** \<sub\> is used for footnotes, chemical formulas, etc.

When two or more line breaks in code are created, the browser only recognizes one space. This is **white space collapsing**. Developers can use this make their code easier to read.

**Line breaks** \<br \/\> separates a line into a separate one.

**Horizontal rules** \<hr \/> can be used to separate into different themes.

**Semantic markup** is used to add extra information to a web page, such as adding emphasis to particular text and marking a block of text as a quotation.
Examples inclde the strong, emphasis, blockquote and q elements.

The abbreviation element \<abbv> is used for both abreviations and acroyms.

### HTML Chapter Ten: Introducing CSS

CSS is what makes the web page pretty! It associates rules with HTML elements that tell the HTML how it should look.

A CSS rule is made of two part: a selector and a declaration.

A **selector labels which element the rule applies to.

A **declaration tells the element how it will be styled.

Within the declaration, **properties indicate what characteristic of the element to change (color, font, margin, etc.)

**Values** are the characteristics being assigned (blue, Arial, 30px, etc.)

CSS can either be placed within the HTML document itself with the \<style> tag, or it can be a separate file which is linked \<link\ to the HTML document.

If two selectors created in CSS are identical, the second selector takes precedence. 

If one selector is more specific than the other, it will take precedence. 

!important can be added after a value to indicate that it should take precedence on others that apply to the same element.

Child elements **inherit** some properties from their parent elements (font, color, etc.) Others do not (background color, border.)

Using an external style sheet is more efficient when creating multiple pages on a website, and it makes reading the HTML easier.


### JS Chapter Two: Basic JavaScript Instructions

Each instruction of a script is called a **statement** and ends with a semicolon.

Each statement starts on a new line.

**Code blocks** help organize statements and are contained within curly braces.

**Variables** stores data andcan change each time a script runs.

Variables are **declared** with the **var** keyword.

If the variable is more than one word camelcase is used.

**Values** are **assigned** to a variable with the assignment operator (\=).

Stored values can be changes by assigning the variable the new value with the assignment operator.

Rules for naming variables:

1. It must begin with a letter, dollar sign or underscore. 
2. 3It can contain letters, numbers, dollar signs or underscores.
3. Keywords cannot be used (ex: var).
4. Variables are case sensitive.
5. Use a relevant, descriptive name.
6. Use camelcase.

**Arrays** store lists of values that are related to one another.

Variables act as though they are in a numbered list. The numbers starts at zero. The numbers are called an **index**.

An **expression** can either be just a single value assigned to an operator, or it can be two or more values that return a single value (var num = 4*4).

Operations within an expression follow the oder of execution (PEMDAS).


### JS Chapter Four: Decisions and Loops

**Comparison operators** compare values and determine whether a condition is met or not.

There are two parts to a decision: first, an expression is evaluated. Then a conditional statement says what to do based on the value.

Comparion operators compare one value to what it is expected to be. The reesult is a **Boolean**.

**Logical operators** compare the results of more than one comparison operator.

**If statements** evaluates a condition.

**If/else** statemtns checks a condition.









