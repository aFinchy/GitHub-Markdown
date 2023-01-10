# GitHub-Markdown
Markdown for posting on GitHub


H E A D E R S
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag


 M A G E S
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

L I N K S
http://github.com - automatic!
[GitHub](http://github.com)

B L O C K Q U O T E S
As Kanye West said:
> We're living the future so
> the present is our past.

E M P H A S I S
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*

Username @ mentions
Typing an @ symbol, followed by a username, will
notify that person to come and view the comment.
This is called an “@mention”, because you’re
mentioning the individual. You can also @mention
teams within an organization

I S S U E R E F E R E N C E S
Any number that refers to an Issue or Pull Request
will be automatically converted into a link.
#1
defunkt#1
defunkt/github-flavored-markdown#1

TA S K L I S T S
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
@mentions, #refs, links, formaing,
and tags supported
list syntax required (any unordered
or ordered list supported)
this is a complete item
this is an incomplete item

F E N C E D C O D E B L O C K S
```javascript
function test() {
console.log("look ma`, no spaces");
}
```
Markdown coverts text with four leading spaces
into a code block; with GFM you can wrap your code
with ``` to create a code block without the
leading spaces. Add an optional language identifier
and your code with get syntax highlighting.

Tables
You can create tables by assembling a list of
words and dividing them with hyphens -
(for the first row), and then separating each
column with a pipe | 

First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

E M O J I
To see a list of every image we support, check out
www.emoji-cheat-sheet.com
I S S U E R E F E R E N C E S
Any number that refers to an Issue or Pull Request
will be automatically converted into a link.
#1
defunkt#1
defunkt/github-flavored-markdown#1
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:



Markdown Cheatsheet<a name="TOP"></a>
===================

- - - - 
# Heading 1 #

    Markup :  # Heading 1 #

    -OR-

    Markup :  ============= (below H1 text)

## Heading 2 ##

    Markup :  ## Heading 2 ##

    -OR-

    Markup: --------------- (below H2 text)

### Heading 3 ###

    Markup :  ### Heading 3 ###

#### Heading 4 ####

    Markup :  #### Heading 4 ####


Common text

    Markup :  Common text

_Emphasized text_

    Markup :  _Emphasized text_ or *Emphasized text*

~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

__Strong text__

    Markup :  __Strong text__ or **Strong text**

___Strong emphasized text___

    Markup :  ___Strong emphasized text___ or ***Strong emphasized text***

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

[heading-1](#heading-1 "Goto heading-1")
    
    Markup: [heading-1](#heading-1 "Goto heading-1")

Table, like this one :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2 
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task

~~~
 Markup : - [ ] An uncompleted task
          - [x] A completed task
~~~

- [ ] An uncompleted task
    - [ ] A subtask

~~~
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
~~~

> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Link to a specific part of the page:

[Go To TOP](#TOP)
   
    Markup : [text goes here](#section_name)
              section_title<a name="section_name"></a>    

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:


# Github Markdown Cheat Sheet

> Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by [John Gruber](https://daringfireball.net/projects/markdown/) in 2004, Markdown is now one of the world’s most popular markup languages.
> 
> - https://www.markdownguide.org/getting-started/#whats-markdown

## Headers 

```markdown
# This is an <h1> tag
  
## This is an <h2> tag 

### This is an <h3> tag   
  
#### This is an <h4> tag 
  
##### This is an <h5> tag
  
###### This is an <h6> tag
```

# This is an \<h1\> tag
  
## This is an \<h2\> tag 

### This is an \<h3\> tag   
  
#### This is an \<h4\> tag 
  
##### This is an \<h5\> tag
  
###### This is an \<h6\> tag
  
## Emphasis

```markdown
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

~~This text will be crossed out (strikethrough)~~ 

_You **can** combine them_

***All this text is bold and italic***
```

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

~~This text will be crossed out (strikethrough)~~ 

_You **can** combine them_

***All this text is bold and italic***

## Lists

### Unordered

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b


```markdown
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```

- Item 1
- Item 2
  - Item 2a
  - Item 2b

### Ordered

```markdown
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## Images 

```markdown
Format:  ![Alt Text](url)
Example: ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

## Links 

```markdown
http://github.com - automatic!
```

http://github.com - automatic!

```markdown
Format:  [Test](url)
Example: [GitHub](http://github.com)
```

[GitHub](http://github.com)

## Blockquotes

```markdown
As Kanye West said:

> We're living the future so
> the present is our past.
```

As Kanye West said:

> We're living the future so
> the present is our past.

Blockquotes can be nested.

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Horizontal Rules

Horizontal rules can be created using three or more asterisks (\*\*\*), dashes (\-\-\-), or underscores (\_\_\_) on a line by themselves.

```markdown 
*** 
----
______
```

*** 
----
______

## Inline code

```markdown
I think you should use an `<addr>` element here instead.
```

I think you should use an `<addr>` element here instead.

## Fenced Code Blocks 

### No highlighting 

````markdown
```
if (isAwesome){
  return true
}
```
````

```
if (isAwesome) {
  return true
}
```

### Highlighting 

````markdown
```javascript 
if (isAwesome){
  return true
}
```
````

```javascript
if (isAwesome) {
  return true
}
```

## Tabels 

```markdown
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

```markdown
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

Your Markdown does't have to be pretty. 

There must be at least 3 dashes separating each header cell. The outer pipes (`|`) are optional, and you don't need to make the table columns line up prettily.

```markdown
Less | Pretty | Markdown 
--- | --- | ---
1 | 2 | 3 
*Still* | `renders` | **as expected**
4 | 5 | 6
```

Less | Pretty | Markdown 
--- | --- | ---
1 | 2 | 3 
*Still* | `renders` | **as expected**
4 | 5 | 6

## Blackslash escape

Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formating syntax.

| Name                  | Markdown  | Result |
| --------------------- | --------- | ------ |
| backslash             | `\\`      | \\     |
| backtick              | `` \` ``  | \`     |
| asterisk              | `\*`      | \*     |
| underscore            | `\_`      | \_     |
| curly braces          | `\{\}`    | \{\}   |
| square brackets       | `\[\]`    | \[ \]  |
| parentheses           | `\(\)`    | \(\)   |
| hash mark             | `\#`      | \#     |
| plus sign             | `\+`      | \+     |
| minus sign (hyphen)   | `\-`      | \-     |
| dot                   | `\.`      | \.     |
| exclamation mark      | `\!`      | \!     |

## Task Lists

```
- [x] this is a complete item 
- [ ] this is an incomplete it
```

- [x] this is a complete item 
- [ ] this is an incomplete it

## Inline HTML

Markdown also supports raw HTML.

```html
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>

```html
<p>Markdown and HTML does *not* work **well**. Use <i>HTML</i> <b>tags</b> instead.</p>
```

<p>Markdown in HTML does *not* work **well**. Use <i>HTML</i> <b>tags</b> instead.</p>

## Emoji

```markdown
:+1: :sparkles: :camel: :tada: :rocket: :metal:
```

:+1: :sparkles: :camel: :tada: :rocket: :metal:
