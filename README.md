# Mastering Markdown

Hello there - welcome to _mastering markdown_!

I'm **super excited** to have you along for the ride.

Examples:

```javascript
const name = 'Wes Bos is cool';
let age = 100;
```

### TODO:
* [x] Sign up for Mastering Markdown Course
* [x] Install Tooling
* [x] Learn Markdown!

#   Paragraphs
## The Best Pups Around
*this* is the same as _this_

and **this** is the same as __this__

line ~~through~~ you do like that 

#   Headers:

# h1
## h2
### h3
#### h4
###### h5 

h1 other posibility
=
h2 other posibility
-

---
---
---

# Links:

<http://wesbos.com> link

[other way to make a link](http://github.com)

[hackeryou.com](hackeryou.com "This is where wes teaches") this gives title to link

lorem [text][1] that way you [can][1] link you link to variables 

[1]: http://hackeryou.com


# IMAGES
![Great pic](http://unplash.it/500/500?random "This is the title tooltip")

![Alternative text](http://unplash.it/500/500?random "This is the title tooltip")

![Cute pup][pup]

[A link](http://unplash.it/500/500?random)

[![](http://unplash.it/500/500?random)](http://unplash.it/500/500?random)

[<img src="http://unplash.it/500/500?random" height="200">](http://unplash.it/500/500?random)

<style>
    img {
        width: 200px;
    }
</style>

[pup]: http://unplash.it/500/500?random

# Lists:

#### Ingredients - _Unordered lists_
* milk
* eggs
* bread
+ milk
+ eggs
+ bread
- milk
- eggs
- bread

#### Steps - _ordered lists_
1. Combine Ingredients
    * Sift the flower
        * Do it again
1. Gently Stir Together
    1. test
        this is inline
        
        this is not inline
        ```javascript
        codeblock inside list
        const test = testString => testString; 
        ```
    1. ordered inside ordered list
1. Bake at 350 for 20 minutes
    * test 2
        
        This is img in a list
        
        ![](http://unplash.it/500/500?random)

# Line Breaks

Wes is cool.<br>
He really is.

I love you.

## Horizontal Rules
Something

---

Another Thing

===


# Black Quotes

> You miss 100% of the shots you don't take. -<br> 
>  **Wayne Gretzky**
>
> Another line here
>
>
Hello

>Quote here

#   Block codes

Here is my code:

    var x = 100;
    const dog = 'snickers';

And here is the same with lang name - _this is prefered_
```javascript
    var x = 100;
    const dog = 'snickers';
```

Example with php:
```php
$age = 50;
$name = "wes";
echo strtoupper($name);
```

Example without adding language name
```
echo "hello"
```

Inline code example `const x = 100;` you do like that.

Showing diff - _great for github_
```diff
var x = 100;
- var y = 200;
+ var y = 300;
``` 

#   Tables

|Dog's Name| Dogs' Age| Dogs City|
|:---------|:--------:|---------:|
|Left aligned|Centeret|Right aligned|
|Snickers|2|Toronto|
|Prudence|8|New York|

# Github Treats

* [ ] Get Milk - checkbox
* [x] Crack Eggs - **checked** checkbox
* [ ] Cook Bacon- checkbox

In github you can make reverences:<br>
* to issues by hash '#'
* to people by '@'.