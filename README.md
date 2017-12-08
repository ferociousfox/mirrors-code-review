# Mirrors

#### A look into another world, _2017_

#### by **Shane Ryan**

## Description
_week 3 of CSS code review_

##Two day thoughts and feedback.
 _Learning and styling process/what worked and what didn't_ This week has been great overall. Sass seemed complex when first looking at it, but its logical structure and nature have been wonderful to work with. Mostly, like many other weeks, I have been learning by tackling problems as they arise. I found the tutorial given on Monday confusing and counter-intuitive. The work of writing functions and loops to calculate color schemes however, I found most gratifying. I am also enjoying more freedom of creativity in choosing layout and topic for our two day project. This week, working with sass, has reinforced styling from broad to granular(outside-in) as a work flow. This feels more natural and logical. Setting global variables and functions initially, saves a ton of work in the long run, again, reinforcing a more logical and thoughtful work flow. I have a tendency to want to just jump and start coding, fixing problems as they arise. With the complexity increasing with sass file structure, I have been forced to stop and plan out what needs to happen for the best outcome. Now, on the other side of this I see the merit in these initial planning and envisioning steps. The challenges that arose mostly stemmed from making things more complicated than necessary. Example: the 7:1 file structure seems like overkill with single page layouts, spreading work out a little too much. Also, I still have some lack of clarity on where certain rules go in the file structure. Wether all the main(input).scss file just compiles my partial files or if i actually include some granular tweaks to the broad rules in said file.

| Term | Description | Implementation |
| -- |:--:| -- |
| variables | Variables are names used to store information that can be called and used as a value in any key/value pair or interpolation in the Sass files. The value can be changed where the variable is declared and thus the value will change wherever the variable is called. | We use variables whenever possible to manage colors, margins, and other style values throughout the page. All of the variables are declared in one location which makes it easier to make global style changes. |
| extend | Using extend shares all of the properties from one CSS selector to another as a way to avoid repeating the same block of code, similar to using a variable. | If one selector uses the same set of properties as another existing selector, using extend allows you to call all of the properties of the selector being extended. |
| mixins | Mixins are a way to write a block of code to be reused throughout the page. Like a JavaScript function, a mixin can use a parameter to pass data to set a value in each instance the mixin is called. | We would use mixins when we need to change the same parameter(s) in multiple classes with different values. |
| functions | Sass functions are a way to repeat a block of code that accepts arguments and returns a specific value. | Functions are similar to mixins and are sometimes confused with one another, although we use functions are used where one specific value is expected to be returned. |
| nesting | Nesting is the practice of calling selectors inside another selector. This is used to affect descendants of the original parent element selected. | We use nesting to write rules for specific elements or groups of elements inside a specific container. |
| partials | Partials are files with blocks of code for a specific element, function, category, or role that will be compiled with other partials to make a complete stylesheet. | We use partials to create and organize separate files for variables, colors, layout, mixins, functions, reset/normalize, third-party libraries, and any other unique categories. |
| import | Import is a way to compile partials together. Common practice is to write a file specifically dedicated to call partials to be imported and compiled by Sass | We use an import file in each directory to compile all of the partials from that location, then import each of those files into the main Sass file to be compiled into a complete CSS stylesheet. |

## Approach for today
_how I will change my approach_. Today I will mostly approach this project in much the same manner to how Adam and I did things over the last two days. That said, I will be stripping it down a bit in complexity. The 7:1 file structure feels a bit large for a single page where a framework isn't used. I'll set up a 4:1 structure with fewer files to simplify things a bit. One piece I picked up that I will implement was setting a rather large number of variables for sizes and colors. Setting an almost excessive number of variables was incredibly helpful once we had moved to the final stages of polishing the page, when something needed tweaking we could do it all on the variable page and changes were applied across the entire document. This helped to standardize the look of the page and saved time, double-bonus. Another piece I picked up from Adam was that I tended to want to move on before he did on particular parts of the project, often I liked the outcome, but he seemed to make extra work for himself. We often could have fixed the problem with less code or less work. Overall the outcome was good, but given a limited amount of time, many of the sidebars we took could have been avoided. Again, mostly the workflow will be done in the same manner of mobile first/ outside-in/ broad to granular.
### Setup

Visit the webpage [here]().

Alternately you may [Clone this repository]().
  1. Click on the link above.
  2. Click the green button marked **Clone or download**.
  3. Click **Download ZIP**.
  4. Unzip file.
  5. Open index.html in Chrome or another web browser.

## License

Copyright (c) 2017, Shane Ryan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
