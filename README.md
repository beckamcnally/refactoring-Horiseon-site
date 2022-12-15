# Refactoring Horiseon Site

## Description

This repository is for the purposes of refactoring code to make it more accessible for the fictisious marking company, Horiseon. Horiseon would like their page to be more accessible to more poeple to again a larger reach. With this goal I have refactored the code to meet accesibilty standards.

[Visit the deployed Site](https://beckamcnally.github.io/refactoring-Horiseon-site/)

## Table of Contents

* [Technology Used](#technology-used)
* [Code Refactoring Example](code-refactoring-example)
* [Learning Points](learning-points)
* [Author Info](author-info)

## Tochnology Used

| Technoly Used     | Resource URL      |
| -------- |:---------:|
| HTML  | [https://www.w3schools.com/html/default.asp]
| CSS   | [https://www.w3schools.com/css/default.asp]
| Git   | [https://docs.github.com/en]

## Code Refactor Example

Original code
```html
 <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
```
Changed Code
```html
<img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="image of a computer work area with a note book, cup of coffee, cup of pens, and a magnifying glass on a laptop"/>
```


Origianl Code 
```html
<div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
```
Changed code
```html
<article class="benefits-info">
            <h3>Lead Generation</h3>
          <figure> 
            <img src="./assets/images/lead-generation.png" alt="Icon in the shape of a light buld. Starting at the top it has the top half of a sun, then narrows with an arrow pointing to a dallar sign." />
          </figure>  
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </article>
```

## Learning Points

* Semantic HTML 
* Markdown
* Accessibility Standards 
* Refactoring

## Author Info 

### Becka McNally

* [LinkedIn](linkedin.com/in/becka-mcnally-21520670)
* [Github](https://github.com/beckamcnally)
