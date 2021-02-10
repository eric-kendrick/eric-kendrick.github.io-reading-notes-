### HTML Chapter 3: Lists

Ordered list \<or> : numbered.
Unordered \<ul : bulleted.

Both use the \<li> tag for each item in the list.
CSS should be used to style the numbers or bullets if necessary.

Definition lists \<dl> : a series of terms and their definitions.
Definition term \<dt> tags the item being defined in the dl.
Definition definition \<dd> defines the \<dt>.

Lists can be nested inside parent lists.

###HTML Chapter 13: Boxes

A box's default size is just large enough to contain its contents. These dimensions can be changed by styling them with height: and width: 

Pixels are units that can be used to alter these dimensions and have traditionally been popular because designers can control their size.

Percentages and ems allow for more flexibility across different screens and devices. 

**Min-width** specifies the smallest size a box can be when a browser window is narrow.
**Max-width** specifies the max size when the browser is wide.

**Min-** and **max-** width perform the same functions as min- and max- width in relation to box height.

The overflow property tells browser what to do if contents are larger than the box and consists of two values:
**Hidden** hides content that doesn't fit.
**Scroll** adds a scrollbar to the box.

The **border** property allows the designer to specify the width, style and color in one property (in that order).

**Padding** specifies the amount of space between the contents of an element and its border. 

**Margin** controls the gap between boxes.
If one box sits on top of another the margins collapse, and the larger of the two margins will be used.

A box can be centered on a page by setting the left- and right- margins to auto.

The **display** property assigns whether a box will be an inline or block level element.

**Inline-block** flows like an inline element while retaining other block-level features.

**Border-radius** creates rounded corners on a box.

### JS Chapter 2 Review

**Arrays** store lists of values that are related to one another.

Arrays are helpful when you don't know how many items a list will contain. Instead of creating many variables you can just create an array and add them as necessary.

The structure of an array is referred to as an **array literal** and is arranged in square brackets with a comma separating each item. 

Another structure is the **array constructor** in which the new keyword is followed by Array() with each items listed in parenthesis.

Each array value has a corresponding **index** number, in which the first value is assigned [0].

### Chapter Four: Decisions and Loops

**Conditional statements** allow your code to make decisions about what to do next.

Two operands can be compared by using the (===, ==, !=, <, >, <=, >=) comparison operators.

**Logical operators** are used to combine more than one set of comparison operators. 

**Switch** statements compare a value against possible outcomes.

The **for, while, and do... while** loops repeat a set of statements.

