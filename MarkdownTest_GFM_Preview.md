# Part I: Standard Markdown

## Headings

### The 3rd largest heading (an <h3> tag)

#### The 4th largest heading (an <h4> tag)
##### The 5th largest heading (an <h5> tag)
###### The 6th largest heading (an <h6> tag)

## Block Quote

In the words of Abraham Lincoln:

> Pardon my French

## Bold and Italics

*This text will be italic*

**This text will be bold**

**Everyone _must_ attend the meeting at 5 o'clock today.**

## Lists
### Unordered Lists
* Item 1
* Item 2
  * Item 2.1
  * Item 2.2
* Item 3

### Ordered Lists
1. Item 1
1. Item 2
  1. Item 2.1
  1. Item 2.2
1. Item 3

## Source code
### Inline
Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.
### Indented Block
Check out this neat program I wrote:

    x = 0
    x = 2 + 2
    what is x


## Links
[Visit GitHub!](www.github.com).

# Part II: GitHub Flavored Markdown (GFM)

## Auto Linking (URLs)
http://www.google.com

## Strikethrough
~~Mistaken text.~~

## Fenced Source Blocks
```
function test() {
  console.log("notice the blank line before this function?");
}
```
## Syntax Highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
## Tables
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |
### Table Alignment
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
