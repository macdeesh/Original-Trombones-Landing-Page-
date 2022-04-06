#Product Landing Page for FreeCodeCamp
Responsive Web Design Project for freeCodeCamp

## FreeCodeCamp - Product Landing Page

This is a solution to the [Build a Product Landing Page](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-product-landing-page). 

### Links

- Solution URL: [https://github.com/macdeesh/Original-Trombones-Landing-Page-]
- Live Site URL: [https://macdeesh.github.io/Original-Trombones-Landing-Page-/]

#### What I learned

I learned in this project how to insert a Youtube video in my html. I insert the code, which i get from the Embed option in Youtube, inside a div in my html :

```
<iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/y8Yv4pnO7qc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```  

To align the Features and the icones, I learned how to use the Grid display : 

  ```css
 .features-grid {
   display: grid;
   justify-content: space-around;
   align-content: center;
   align-items: center;
  } 
  ```
  -  ```grid-template-columns: auto auto;``` to make 2 colums of grid.
  -  ```gap: 2rem;``` to make a space between the colums.


  For the navigation bar to make it always be at the top of the viewport, I learned how to use the Fixed position. The navigation bar was inside the Header so i positioned the all the header div:
  
  ```css
  header {
   display: flex;
   position: fixed;
   overflow: hidden;
   width: 100%;
   top: 0;
   margin: auto;
   padding-top: 1rem;
   background-color: #FAF3F3;
  }
  ```
  
##### Author

- Github - [Macdeesh](https://github.com/macdeesh)
- Twitter - [@Macdiish](https://twitter.com/Macdiish)
