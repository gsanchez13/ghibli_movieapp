# Simple HTML webpage with API requests and CSS styling.

![wireframe](./wireframe.png)
## JS
1. Using [Studio Ghibli API](https://ghibliapi.herokuapp.com/#) create endpoints
   * /films - for all films (20 films)
   * /films/:id - for film by id
   * .title - for name
   * .release_date - for year released
   * .description - for description
2. Function with eventListener for a select option chosen that will clear HTML and reset to given class.
   * Might require an if statement for each individual option with HTTPRequest of info for each selected value.
3. Create a new selector option per movie before page loads to have all options ready.

## HTML
1. Image of studio Ghibli logo
2. Header that says "Ghibli Review App"
3. Select box that contains the titles of each movie availible in the API as well as a default blank section
    * Make sure the value/ class of the first select option is null/ nothing/ empty
4. An empty div that will hold an h3 title tag, release year p and description p
    * When users select an option, the div will be populated/ replaced with information 
5. A form that includes a text input and a submit input that allows users to submit their review to the page
6. A ul under the form that will list li all reviews submitted by users
7. Film title in bold and review not bold.

## CSS

**Body**
1. Monospace font
   * Header should have "Lucida Console", Monaco, monospace
   * Main Area will have "Courier New", Courier, monospace
2. "Lavender" background
3. In a column centered on the page width wise

**Header**
1. Header should contain (image) and (h1) tags
2. Width is 70% and height 150 px
3. Image and header text should be horizontally oriented
4. Totoro and title should be on opposite sides of each other with *center* positioning in relation to the height
5. Totoro image should be the same height as the header (150px)
6. Header should have 30px margin on the bottom and padding of 10px on all sides
7. Header background should be (skyblue)

**Main Area**
1. Contains all other content (select/ description div/ form/ reviews)
2. Width should be 60%
3. Content should be in a (column) with a (left orientation)

**Review Text Input**
1. Text(input) should have an explicit width of 400px
    
