Markdown Syntax
====

    Markdown Syntax
    ====

### Text

    ### Text

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com).

    It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com).


*This text will be italic*

    *This text will be italic*

_This will also be italic_

    _This will also be italic_

**This text will be bold**

    **This text will be bold**

__This will also be bold__

    __This will also be bold__

*You **can** combine them*

    *You **can** combine them*

### Lists

    ### Lists


Sometimes you want numbered lists:

1. One
2. Two
3. Three

```
1. One
2. Two
3. Three
```

Sometimes you want bullet points:

* Start a line with a star
* Profit!

```
* Start a line with a star
* Profit!
```

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

```
- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
```

### Images & Links

If you want to embed images, this is how you do it:

![Image Aleph5](../images/aleph5.jpg)

    ![Image of Yaktocat](../images/aleph5.jpg)
Format: `![Alt Text](url)`

http://github.com - automatic!

[GitHub](http://github.com)

    [GitHub](http://github.com)

### Headers & Quotes

## Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

    Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

#### This is a fourth-tier heading

You can use  one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

```
> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway
```

### Code

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

    ```
    if (isAwesome){
      return true
    }
    ```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

    ```javascript
    if (isAwesome){
      return true
    }
    ```

Currently the following languages are supported:

Language    |Keyword
------------|-------
Bash        |bash
C#          |csharp
Clojure     |clojure
C++         |cpp
CSS         |css
CoffeeScript|coffeescript
CMake       |cmake
HTML        |html
HTTP        |http
Java        |java
JavaScript  |javascript
JSON        |json
Markdown    |markdown
Objective C |objectivec
Perl        |perl
PHP         |php
Python      |python
Ruby        |ruby
R           |r
SQL         |sql
Scala       |scala
Vala        |vala
XML         |xml

### Extras

GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

```
- [x] This is a complete item
- [ ] This is an incomplete item
```


### Tables

Tables        | Are           | Cool  
------------- |:-------------:| -----:
col 3 is      | right-aligned | $1600 
col 2 is      | centered      |   $12 
zebra stripes | are neat      |    $1 

    Tables        | Are           | Cool  
    ------------- |:-------------:| -----:
    col 3 is      | right-aligned | $1600 
    col 2 is      | centered      |   $12 
    zebra stripes | are neat      |    $1 
