# Intro

# Paragraph

This is my first paragraph.

After hitting two <kbd>Enter</kbd>. This is my second paragraph.

Again after hitting two Enter, This is my third paragraph. so what will happen if I Just use one enter to write my next paragraph. Let's try.I am going to hit one Enter and write my next paragraph.
 I have hit one Enter and writing this paragraph and as you can see this paragraph is continuing in the same line. **So if we want to write in next paragraph then we need to hit enter twice**.

You'll ask, That's Ok Shivam. But what if we want to write on next line or take a break but stay in the same paragraph. I'll say No Problem. We can do that as well. Let's try. I am writing this line and taking a
break with one enter while writing it but as you can see even with taking a break
it is continuing on the same line. Ok, now let's try this ...I am going to hit space twice and then take a break.  
Now I have hit two space followed by a enter and you can see that this line is continuing in the same paragraph but on different line.

_**Key Points :**_

* Press Enter twice to write on next paragraph.
* Press Space twice followed by enter to take a break and write on next line without changing paragraph.

<br>

# Headers

One # creates a H1, ## creates a H2, ### creates a H3 and so on...

# Here I am writing with One # and space

## Here I am writing with Two ## and space.

### Here I am writing with Three ### and space. 

#### Here I am writing with Four #### and space.

##### Here I am writing with Five ##### and space.  
<br>

# Italics and Bold

' ** ' or ' __ ' : **Bold**  

' * ' or ' _ '   :  _Italics_

To convert text into italics all we need to do is to use single underscore(' _ ') or single Astrix (' * ') on start and end of the text that we want to emphasize. For example I will convert next word to _Italics_. It's just that simple and the same you can do with the multiple words or sentence. _So this sentence is going to be in italics_.

Let's try bold now. To make any word/sentence in Bold we need to just enclose it in double astrix ' ** ' or double underscore (' __ ') . **This sentence is going to be in Bold**.  

_**You can also use both to italicize and bold your sentence**_.

<br>

# Quotes

> ' > ' : Turn into quotes

Use the greater than symbol ' > ' followed by space and your text to turn your text/sentence into Quotes. Let's try...

> If you have a dream, don’t just sit there. Gather courage to believe that you can succeed and leave no stone unturned to make it a reality.

#####  -_Dr Roopleen_
<br>

# Codes

' ` '       : One line(inline) code

' ``` ' or Tab Indented : Multiple line code

We can either use ' \` ' (Back tilda: Present on keyboard before Number 1 key) or Indented by a tab(four space) to turn into Code. Let's try inline first, `var abc = 'hello'` and now try multiple code blocks...

```
ls -lart  
cat abc.txt
```

# List

Unordered : Astricks ( * ), Plus ( + ) or Dash ( - ) 

Ordered : Number ( 1. )

Lets try Unordered lists with indentatation(<kbd>Tab</kbd>) to change listing sign( Bulleted, Circle & Squared bullet)

* List 1
+ List 2
    * List 3
        * List 4
            * List 5


1. List a
2. List b
8. List c

Mixing Ordered and Unordered List

1. Orange
3. Apple
    * Banana
    * Guava
        * Mango
            1. Watermelon
            7. Carrots

<br>

# Horizontal Lines

Use three or more Astricks ( *** ), or Underscore ( ___ ) or Dashes ( --- ) for horizontal rules.

Let's try to put one horizontal line below this line we are writing.

--- 

<br>

# Links

The syntax for link is a square bracket with text to display followed by circular bracket with the corresponding link and an optional text for readability. 

    [Text] (http link "Optional text for readability)

Let's try..Here is my website [Shivam Srivastava](http://shivamsrivastava.co.in "Shivam's Website").

Markdown also automatically convert/renders raw links. For example...

Here is my website again http://shivamsrivastava.co.in

### Reference Links

Sometimes our source markdown file get crowded with multiple links at same place so we use Reference Links to maintain the readability. Here is how to use it. 

    [Text to display for link] [Reference Text]

    Then at the end of the Markdown file use that Reference Text with square bracket followed by a colon and then link and then the optional text.

    [Reference Text]: http link "Optional Text"

Let's try...here is my website [Shivam Srivastava][mywebsite] again.


[mywebsite]: http://shivamsrivastava.co.in "Shivam's Website"

<br>

# Image

Image syntax is in some way similar to Links starting with an exclamation mark !. Let's look the basic syntax...

### Inline Image
    ![Alt Text for Image](http link to image "optional title text")

Let's use Inlne image here 
![300x100 image](https://placehold.it/300x100 "300 by 100 image")

### Referenced Image
This is just like referenced links where we define an id for the image with link at the bottom of the markdown file and then use that id while creating image.

    ![Alt Text for Image][Image Id defined below]

    [Image Id]: http link "Optional Title/Alt text"

![demo 400 by 100 image][img1]

[img1]: https://placehold.it/400x100 "400 by 100 image"

<br>

# HTML

Sometimes markdown is not enough to meet our needs. In that case we may want to use HTML and to our rescue markdown supports HTML too.

Let's try breaking a line using `<br>` keyword. So I will break this line now <br> and we can see that it continues on the next line. We might also want to center our headers sometime or maybe center our image, we can do so by using HTML code snippet. Let's try...

<center> <h3> Hello world </h3> </center><br>

# Enhanced/Modified/Flavored Markdown

## Code Blocks (Enhanced with language highlight feature)

### Basic Code block

```
if True:
    print("YES")
else:
    print("FALSE")
```

### Using with Language highlight feature(python here)

```python
if True:
    print("YES")
else:
    print("FALSE")
```
<br>

## TABLE

<br> 

### Simple table (Default)

| COLUMN 1 | COLUMN 2 | COLUMN 3 |
|----------|----------|----------|
|text      |text      |text      |
|text      |text      |text      |

<br>

### Left, Centered, Right aligned Table

| COLUMN 1 | COLUMN 2 | COLUMN 3 |
|:----------|:----------:|----------:|
|text       |text        |text       |
|text       |text        |text       |


