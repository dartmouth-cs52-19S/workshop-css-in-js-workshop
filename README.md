# CS52 Workshops:  TITLE OF YOUR WORKSHOP

![](http://i.giphy.com/eUh8NINbZf9Ys.gif)

Brief motivation here as well as in presentation

## Overview

Summary of what we're about to do.

### Intro about "What are Styled Components?"

### Pros
- Load time: styled-components keeps track of which components are rendered on a page and only uses their styles and nothing else. This means users load the least amount of code necessary.
- Ease of maintenance: Ever have the problem of naming too many things similarly, and then running into trouble when rendering? styled-components generates unique class names for your styles, so you never have to worry about duplication, overlap or misspellings. All the styling is also tied to a specific component, which makes it easier to find, modify, or delete the styles that go along with it. 

### Cons
- something

## Setup

Any necessary setup steps

## Step by Step

* Explanations of the what **and** the why behind each step. Try to include:
  * higher level concepts
  * best practices

Remember to explain any notation you are using.

```javascript
/* and use code blocks for any code! */
```

![screen shots are helpful](img/screenshot.png)

:sunglasses: GitHub markdown files [support emoji notation](http://www.emoji-cheat-sheet.com/)

Here's a resource for [github markdown](https://guides.github.com/features/mastering-markdown/).

## Creating a Nav Bar
We're going to create a Navigation Bar from scratch and add some nice styled-components to it!
Create a new file in your /src folder called ```nav-bar.js```. We're going to start with the bare bones of a navigation bar and see how we'd style it. 
```
/* eslint-disable jsx-a11y/anchor-is-valid */
/* eslint-disable react/prefer-stateless-function */

import React, { Component } from 'react';

class Navbar extends Component {
  render() {
    return (
      <div>
        <ul id="nav">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">FAQ</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    );
  }
}

export default Navbar;
```
Now let's import Navbar to your ```index.js``` file:

```
import Navbar from './components/nav_bar';
```

## Summary / What you Learned

* [ ] can be checkboxes

## Reflection

*2 questions for the workshop participants to answer (very short answer) when they submit the workshop. These should try to get at something core to the workshop, the what and the why.*

* [ ] 2 reflection questions
* [ ] 2 reflection questions


## Resources

* cite any resources
