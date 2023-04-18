# Solution Architecture

The solution architecture is an essential part of our project, in it our team promptly thought of a solution that will make the development of our project as fluid, beautiful and organized as possible.

Our solution relies on the following technologies:

- `HTML`: It is a technology whose code is used to structure a web page and its content.

- `CSS`: It is a technology whose code is used to style a web page and its content.

- `Javascript`: It is an interpreted programming language with weak dynamic typing and multiparadigm. Along with HTML and CSS, JavaScript is one of the three main technologies on the World Wide Web.

- `Vercel`: It is a static website hosting service that uses HTML, CSS and JavaScript files directly from a repository on GitHub.

- `IMDb API`: It is a web service to receive movie, series and cast information, and it includes things like movie specifications, images, posters, trailers, rating and much more.
Component diagram

   Below are the components that are part of our solution:


![Architecture diagram drawio](https://user-images.githubusercontent.com/69819769/199082976-3a7d1548-a9d7-478d-8731-7afcb11612e6.png)



## Component diagram

  Implemented solution has the following modules:
 
  - `Browser` - Basic interface of the system.
 
  - `Web Pages` - Set of HTML, CSS, JavaScript and images files that implement the system functionalities.

+ `Local Storage` - storage kept in the Browser, where databases based on JSON are implemented. Are they:
- `Registration` - User login and password
 
- `Comments` - Registration of user opinions about movies.

- `Profile` - Information from the user's profile page.

- `Indications` - Films selected by the site for the user.

- `IMDb API` - platform that allows access to films shown on the site.

- `Hosting` - location on the Internet where the pages are kept and accessed by the browser.
  

## Web Hosting

Our website uses the Vercel platform as a hosting environment. O
site is maintained in the environment of the URL:

https://vercel.com/

Publishing the site on Vercel is done through a project submission on the Github site.
