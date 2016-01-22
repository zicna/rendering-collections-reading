## Objectives

 1. use the `collection` keyword with their partials
 2. use the just pass in the array of instances method `<%= render @products %>`
 3. Understand that the render method returns nil and do a `||`. `<%= render(@products) || "There are no products available." %>`
 
## Instructions

1. Refactor the list of blog posts to use the collections. Take them from the most explicit: `collection` to the most implicit
2. When there are no blog posts have them use the `||` to give an error message
3. Make blog posts have many categories. So now you need to show a list of categories in the blog show page. 
4. Show that the implicit doesn't work. Still need to do the explicit one


<a href='https://learn.co/lessons/rendering-collections-reading' data-visibility='hidden'>View this lesson on Learn.co</a>
