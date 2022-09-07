---
title: Markdown Quick Syntax
date: 2022-09-07 12:00:00 +0530
categories: [technical]
tags: [code,syntax,reference,markdown,cheatsheet]
published: true
---

# Cheat Sheet for Markdown 

## Objective
___


Article aimed at quick glance for all the code syntax or act as a reference point for Markdown language!


## Heading
___
\# for Heading 1, ## for Heading 2, .. ###### for Heading 6

\== for Heading 1, -- for Heading 2
\
\
Eample:
```markdown
    Heading
    ==
```

>Heading
>--

## Paragraph
___
Blank line added before and after a paragraph 
\
\
Eample:
```markdown

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

```

>
>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
>

## Text Styling
___
1. Bold
Add 2 `**` before and after the word / character
2. Italics
Add 1 `*` before and after the word / character
3. Bold & Italics
Add 3 `***` before and after the word / character

## New Line
___
Add a `\` before and after a paragraph to insert line gap
\
\
Example:

```markdown
line 1 with \
\
line 2
```

line 1 with `\`
\
line 2
\
line 1 without `\`
line 2 will fall in same line

## Line Breaks
___
Creating line breaks before paragraph using `\`
\
\
Example:

```markdown
\
Lorem Ipsum is simply dummy text of the printing and typesetting industry.
```

>Output for line break start

\
Lorem Ipsum is simply dummy text of the printing and typesetting industry.
>Output for line break end

## Horizontal rules
___
Add any of these symbol after a empty line `***` or `---` or `___`

>
>___
>after ruler

## List
___
There are two types of list
#### Ordered lists
Add numbers in any order with a number, a dot and a space `1. `
\
\
Example:

```markdown    
1. item one
1. item two
```

>1. list one
>1. list two

#### Unordered lists
Add any of the following symbol `-` or `+` or `*`
\
\
Example:

```markdown
- list item 1
    - sub list item 1
+ list item 2
* list item 3
```

>- list item 1
>    - sub list item 1
>+ list item 2
>* list item 3

## Table
___
Add a pipe symbol before the start and end `| heading |`
\
\
Example:

```markdown
    | Header 1    | Header 2 |
    | ----------- | ---------- |
    | data row 1  | data row 1 |
    | data row 2  | data row 2 |
```

| Header 1    | Header 2 |
| ----------- | ---------- |
| data row 1  | data row 1 |
| data row 2  | data row 2 |

## Images
___
To add images add an `!` follwed by box brackets and image location hyperlink within paranthesis.
\
\
Example:

```markdown
![alt text](image.jpg)
```

## Blockquotes
___
To create a new blockquote add this symbol `>` on new line on first column
    1. Nested blockquotes
        Add the same symbol twice `>>` to create a nested block

>blocked quote
>>nested blockquote

    2. Code blocks
        An indent with 4 spaces or 1 tab creates a code block

>   tab / indented

    3. Fenced Code blocks
        Adding 3 ``` (backticks) or 3 `~~~` will create a fenced code blocks
        
        Example:
        
        ```
        {
            "firstname":"John",
            "lastname":"Doe"
        }
        ```

```
{
    "firstname":"John",
    "lastname":"Doe"
}
```

    4. Formating Code block languages
        Adding 3 ``` with language name will create a language formating
        
        Example:
        
        ```json
        {
            "firstname":"John",
            "lastname":"Doe"
        }
        ```

```json
{
    "firstname":"John",
    "lastname":"Doe"
}
```

## Links
___
Types of links

    1. Titles
        Put the text in box brackets immediately followed by url within Paranthesis
        To add onhover text, add a space and the description within double quotes next to hyperlink url
        
        Example:
         
        [Google](https://www.google.com)
        [Google](https://www.google.com "search engine for all needs")

>[Google](https://www.google.com "search engine for all needs")

    2. URL
        To display URL add the hyperlink within the arrow brackets 
        
        Example:
        
        <https://www.google.com>

><https://www.google.com>

    3. Reference
        To create reference links for any text or paragraph, add numbers within box brackets and after a line gap create hyperlink url reference to the numbers added above.
        
        Example:
        
        [Google Wiki][1]

        [1]: https://en.wikipedia.org/wiki/Google

>[Google-Wiki][1] 
>
>[1]: <https://en.wikipedia.org/wiki/Google> "Wikipedia"

    4. Email
        To create a mailto hyperlink, add the email within arrow brackets
        
        Example:
        
        <author@domain.com>

><author@domain.com>

    5. Images
        As we know adding `!` immediately followed by box brackets with text acting as ALT TEXT and image url within paranthesis
        Optionally description can be added for image onhover
        This image set in box brackets immediately followed by hyperlink url within paranthesis makes the image hyperlinked
        
        Example:
        
        ![alt-text](image.jpeg)
        ![alt-text](image.jpeg "image description")
        [![alt-text](image.jpeg "image description")](https://www.google.com)

[![image](https://images.pexels.com/photos/5012119/pexels-photo-5012119.jpeg?auto=compress&cs=tinysrgb&w=200&lazy=load "Images from Pexels.com")](https://www.pexels.com/)

## Additional Syntax
___
    1. Footnote
        Adding `^` to the reference link creates the foot note
        
        Example:
        
        Sample footnote created.[^1]

        [^1]: This is the footnote 

>Sample footnote created.[^1]
>
>[^1]: This is the footnote


    2. Strikethrough
        Adding 2 ~~ will create a strikethrough
        
        Example:
        
        This will ~~strikethrough~~ the word inbetween

>This will ~~strikethrough~~ the word inbetween

    3. Highlight
        To highlight a word or sentence, double equal `==` between the word or if application supports then add html supported tag <mark>
        
        Example:
        
        In this line, this word ==highlight== will be highlighted.
        In this line, this word <mark>highlight</mark> will be highlighted.

>In this line, this word <mark>highlight</mark> will be highlighted.

    4. Subscript
        To create subscript, Single tilde `~` between the word or if application supports then add the tag <sub> between the word
        
        Example:
        
        H~2~O
        H<sub>2</sub>O

>H<sub>2</sub>O

    5. Superscript
        Single backtick `^` between the word or if application supports then add the html supported tag <sup> 
        
        Example:
        
        X^2^
        X<sup>2</sup>

>X<sup>2</sup>

## Escaping characters
___
All the above character literals used can be escaped using the `\`
\
\    
Example:
        
    * Conditions Apply 

but output renders as bullet point

>* Conditions Apply
    
    to this escape this, add the backslash 

>\* Conditions Apply
    
    Different characters that can be escaped are
    \ ` * _ { } [ ] < > ( ) # + - . ! |