# Development Strategy

> `acme-web-design`

write a short description of your project:
- who would want to use it?
- why would they want to use it?

---

This project has created in a public repo. So, it is accessable for everyone who wants to learn from this project, fork this repo, work on this project, merge his/her change to this project...

### In general!

Merge each branch when it is completely finished

## Wireframe

<!-- include a wireframe for your project in this repository, and display it here -->
<!-- wireframe.cc is a good site for getting started with wireframes -->
![wireframe](./images/wireframe.PNG)

## 0. Set-Up

__A User can see my initial repository and live demo__

### Repo

- Generated repo `acme-web-design` from Template `w3-validation-template`
- Write initial, basic README
- Turn on GitHub Pages

## 1. User Story branch `start-up` 

__full user story description__

As a visitor I want to know where this project started from and as a website owner or creator, I want to let the visitors or learners know how to start working with this project.

### Branch

* Created the branch `start-up`
* Created a new folder called `css`
* Created a new file `style.css`
* Created a new folder called `images` within a REAMDE file describing the folder


### HTML

1. Added title to index.html
1. Linked the `style.css` file to the `index.html`
1. Added `meta tag` for the webpage


### CSS

No change

## 2. User Story branch `header` 

__full user story description__

As a visitor, I want to know which website I am visiting and as a website owner or creator I want to give the website a good descriptive `header`.

### Branch

* Created the branch `header`

### HTML

* Created `header tag`
* Created `div tag` inside the header
* Created `nav tag` for HOME, ABOUt, SERVICES
* Created `span tag`

### CSS

* style for the body **Globally**
* style for the header(header text, nav)
* Styles such as: background-color, color, font size, padding, margin,...

## 3. User Story branch `main-sec1` 

__full user story description__

As a visitor, I want to know what the website is about and as a website owner or creator I want to describe the content of the website in a short showcase area.

### Branch

* Created a new branch `main-sec1` for the showcase in main part of the web page
* Uploaded images to the `images` folder


### HTML

* Added `section tag`
* Added `h1 tag`
* Added `div tag`
* Added `p tag`

### CSS

* Added `background picture`
* Added `font and color style`
* Added `margin and text-align`

## 4. User Story branch `main-sec2` 

__full user story description__

As a visitor, I want to subscribe for more news letters which keeps me up-to-date and as a website owner or creator I want to create subscribtion option for the website so that visitors happily subscribe for news letters.

### Branch

* Created a new branch `main-sec2` for the news letter **(second section of the webpage)**  in main part of the web page

### HTML

* Added `section tag`
* Added `h1 tag`
* Added `div tag`
* Added `form tag`
* Added `input tag`
* Added `button tag`

### CSS

* Added `font and color style`
* Added `margin, padding, height, width, background, float`

## 5. User Story branch `main-sec3`

__full user story description__

As a visitor, I want to read and understand the main content of the the website and as a website owner or creator I want that visitors are comfortable with the main content of the website by good explanation and visualisation with adding photos.

### Branch

* Created the branch `main-sec3` for the third section in the main part of the webpage


### HTML

* Added `section tag`
* Added `h3 tag`
* Added `div tag`
* Added `img tag`
* Added `p tag`

### CSS

* Added rules:
    * float
    * width
    * padding
    * margin
    * text-align

## 6. User Story branch `footer`

__full user story description__

As a visitor, I want to have enough information about the website I am visiting and as a website owner I want that visitors know about the copyright and etc...

### Branch

* Added a new branch called `footer` for the footer part of the webpage


### HTML

* Added `footer tag`
* Added `p tag`

### CSS

* Added rules:
    * text-align
    * color
    * background-color
    * padding
    * margin
      
## 7. User Story branch `about`

__full user story description__

As a visitor, I want to know about the website's owner or company and as a website owner I want to describe my company or myself so that visitors know who I am or what the company is.

### Branch

* Added a new branch called `about` for the footer part of the webpage
* Created a new file called `about.html`


### HTML

* copy-past the content of the file `index.html` inside the file `about`
* Changed some element's content:

    * Changed the title -->> Acme Web Design | about
      
    * Added the `class="current"` to the about page link
      
    * Removed Showcase or the `first section` of the webpage
      
    * Removed the box area or `third section`
      
    * Added new `section` with `id="main"`
      
    * Added `div tag` with `class="container`
      
    * Added `article tag` inside the above `div tag` with `id="main-col"`
      
    * Added `h1 tag` inside the above `article tag` with `class="page-title"`
     
    * Added `p tags` below the `h1 tag` , the last `p tag` has a `class="dark"`
      
    * Added `aside tag` below the `article tag` with `id="sidebar"`
      
    * Added `div tag` inside the `aside tag` with `class="dark"`
      
    * Added `h3 tag`inside the `div tag`
      
    * Added `p tag` below the `h3 tag`
      
      

### CSS

* Added rules for aside #sidebar:

    * float: right
      
    * width: 30%
      
    * margin-top: 10px
      
* Added rules for article #main-col:

    * float: left
      
    * width: 65%
      
* Added rules for .dark:

    * padding: 15px
      
    * background: #35424a
      
    * color: #fff
      
    * margin-top: 10px
      
    * margin-bottom: 10px
      
## 8. User Story branch `services`

__full user story description__

As a visitor, I want to know what services the website or company offers and have so that I can benefit from and as a website owner I want that people know about our services which is the main goal of the website and company.

### Branch

* Added a new branch called `services` for the footer part of the webpage
* Created a new file called `services.html`


### HTML

* copy-past the content of the file `about.html` inside the file `services.html`
* Changed some element's content:

    * Changed the title -->> Acme Web Design | services
      
    * Removed the `class="current"` from `about page link` and added it to the `services page link`  
    
    * Added `ul tag` with an `id="services"`
    
    * Added `li tags` 
    * Added `h3 tags` inside the `li tags`
    * Added `p tags` below `h3 tags`
    * Added `form tag` with `class="quote"`
    * Added `div tag` , `label tag`, `input tag` inside the above `form tag`
    * Added `button tag` with `class="buttoon_1"`
      

### CSS

* Added rules for `aside ul#services li`:

    * list-style:none;
      
    * padding: 20px;
      
    * border: #ccc solid 1px;
    
    * margin-bottom: 5px;
    * background: #e6e6e6;
      
* Added rules for `aside#sidebar .quote input`, `aside#sidebar .quote textarea`{
   * width: 90%;
   * padding: 5px;
     
## 9. User Story branch `media-queries` 

__full user story description__

As a visitor, I want to be comfortable with the layout of the website or webpage while I am reading, watching,... in the website and as a website's owner I have to create a responsive webpage so that visitors don't get bored while visiting my website.

### Branch

* Created the branch `media-queries`

### HTML

**No Change in HTML files**


### CSS

* Created `media queries` for responsive webpage:
   
   ```CSS
   
   @media (max-width: 768px) {
  header #branding, header nav, header nav li, #newsletter h1, 
  #newsletter form, #boxes .box, article#main-col, aside#sidebar {
    float: none;
    text-align: center;
    width: 100%;
  }
  
  header {
   padding-bottom: 20px; 
  }
  
  #showcase h1 {
   margin-top: 40px; 
  }
  
  #newsletter button, .quote button {
    display: block;
    width: 100%;
  }
  
  #newsletter form input[type="email"], .quote input, .quote textarea {
    width: 100%;
    margin-bottom: 5px;
    
    }
   }

   ```
      
## I really hope that this development strategy makes sense to you
   
      
## Finishing Touches

- Write final, complete README:
  - [makeareadme.com](https://www.makeareadme.com/)
  - [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  - [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Validate code to check for any last mistakes
