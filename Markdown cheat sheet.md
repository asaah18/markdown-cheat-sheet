
# Introduction

Markdown is a way to write content for the web. It is written in what people like to call plaintext, which is exactly the sort of text you’re used to writing and seeing. Plaintext is just the regular alphabet, with a few familiar symbols, like asterisks ( * ) and backticks ( ` ).

[Reference](https://www.markdowntutorial.com)

# Demonstration

## headers

There are six levels of header with decreasing size, Which also can be styled with _italic_ *text*.

###### Header *six*
##### Header *five*
#### Header *four*
### Header *three*
## Header *two*
# Header *one*

## Style text

You can style your text as :

- italc text using a _single underscore_ or a *single asterisk*
- bold text using a  __double underscore__ or a **double asterisk**
- **_both_** __*at*__ *__the__* _**same time**_

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

![A pretty tiger](Tiger.jpg)

Image from current folder

### Reference image

![Orange cat][Cat]

Image from Internet

![Orange tiger][Tiger]

Image from current folder

[Cat]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

[Tiger]: Tiger.jpg

## Embeded object*

**important notice:** It is possible to embed an image or html file into markdown file. But it is not recommended, because it is not supported everywhere.
Like:

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==" alt="Red dot" />

## Blockquotes

A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. Which also can be styled and contain IMG and LINK. For example:

### Single paragraph

>"The sin of __doing nothing__ is the **deadliest** of all the seven sins. It has been said that for evil men to accomplish their purpose it is only necessary that good men should do nothing."

### Multiple paragraphs

>In order to group multiple paragraph into one quotes you can use the symbol ( > ):
>
> - in the blank lines between the paragraphs
>
>- and at the start of each paragraph
