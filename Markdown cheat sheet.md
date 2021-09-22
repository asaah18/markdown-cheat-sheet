
# Introduction

Markdown is a way to write content for the web. It is written in what people like to call plaintext, which is exactly the sort of text you’re used to writing and seeing. Plaintext is just the regular alphabet, with a few familiar symbols, like asterisks ( * ) and backticks ( ` ).

[Reference](https://www.markdowntutorial.com)

- [Introduction](#introduction)
- [Demonstration](#demonstration)
  - [headers](#headers)
  - [Style text](#style-text)
  - [Links](#links)
    - [Inline link](#inline-link)
          - [Or even within a _header_](#or-even-within-a-header)
    - [Reference link](#reference-link)
  - [Images](#images)
    - [Inline image](#inline-image)
    - [Reference image](#reference-image)
  - [Embeded object*](#embeded-object)
  - [Blockquotes](#blockquotes)
    - [Single paragraph](#single-paragraph)
    - [Multiple paragraphs](#multiple-paragraphs)
  - [list](#list)
    - [Ordered list](#ordered-list)
    - [Unordered list](#unordered-list)
    - [Nested list](#nested-list)
      - [Example 1](#example-1)
      - [Example 2](#example-2)
      - [Example 3](#example-3)
  - [Paragraphs](#paragraphs)

# Demonstration

## headers

There are six levels of header with decreasing size, Which also can be styled with _italic_ *text*.

```markdown
# Header *one*
## Header *two*
### Header *three*
#### Header *four*
##### Header *five*
###### Header *six*
```

## Style text

You can style your text as an:

- italc text using a _single underscore_ or a *single asterisk*. (`*text*`), (`_text_`)
- bold text using a  __double underscore__ or a **double asterisk**. (`__text__`), (`**text**`)
- **_both at the same time_**. (`**_text_**`), (`__*text*__`)

## Links

Links are used to refer to a website or a header.
And there are two types of link:

- Inline link: refer to a website or header in directly in the tag.
- Reference link: refer to a website or header using a defind variable in the document.
  
### Inline link

You can make a link [**within** the sentence](www.google.com).
###### Or even within [a _header_](www.google.com)

[go to start of section](#demonstration)

### Reference link

Here's [a link to something][link].
Here's [yet another link][another-link].
And now back to [the first link][link].

[link]: www.github.com
[another-link]: www.google.com

## Images

Images are similar to links. with the only defference being that image are prefaced with an exclamation point ( ! ), and the **optional** text is used as an alternative text for the image when it is not accessible.

There are two types of images:

- Inline image
- Reference image
  
### Inline image

![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

Image from Internet

![A pretty tiger](images/Tiger.jpg)

Image from current folder

### Reference image

![Orange cat][Cat]

Image from Internet

![Orange tiger][Tiger]

Image from current folder

[Cat]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

[Tiger]: images/Tiger.jpg

## Embeded object*

**important notice:** It is possible to embed an image or html file into markdown file. But it is not recommended, because it is not supported everywhere.
Like:

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==" alt="Red dot" />

## Blockquotes

A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. Which also can be styled and contain IMG and LINK. For example:

### Single paragraph

>"The sin of __doing nothing__ is the **deadliest** of all the seven sins.  It has been said that for evil men to accomplish their purpose it is only necessary that good men should do nothing."

### Multiple paragraphs

>In order to group multiple paragraph into one quotes you can use the symbol ( > ):
>
>- in the blank lines between the paragraphs
>
>- and at the start of each paragraph
>
>       See, that was easy

## list

List are made using - or * interchangeably.

And can be styled with both italic and bold. It's also possible to use a link or even an image.

There are two types of lists (order list & unordered list).

You can nest a list as far as you want.

### Ordered list

1. Step one
2. Step two
3. Step three

### Unordered list

- Chicken
- Egg
- Bread
- Milk
- Dates

### Nested list

#### Example 1

1. Calculus
    - A professor
    - Has no hair
    - Often wears green
      1. Has a modern style in clothes
         - Wear a Jacket
2. Castafiore
    - An opera singer
    - Has white hair
    - Is possibly mentally unwell

#### Example 2

1. Crack three eggs over a bowl.

    Now, you're going to want to crack the eggs in such a way that you don't make a mess.

    If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

    Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

   By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:

   > Up and down and all around, that's how butter on salmon goes.

4. Drop the salmon into the egg-milk bowl.

   Here are some techniques on salmon-dropping:

   - Make sure no trout or children are present
   - Use both hands
   - Always have a towel nearby in case of messes

#### Example 3

- *Cat*
  - ![sample](images/cat.png)
  - [More pictures](https://www.google.com/search?q=cats)

## Paragraphs

You can add a new line in a paragraph  
by adding two spaces at the end of each line.

And here is a new paragraph wich is surrounded by blank spaces to seprate it from the other paragraphs.