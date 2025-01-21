
# [Google Books](https://LINK)

## Description
Google Books is a full-stack MERN application that lets users search for books through the Google Books API and save their favorite titles to a custom list. With account creation and login functionality, users can easily manage their saved books. The application utilizes GraphQL for streamlined and efficient API queries and mutations.

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Installation](#installation)
5. [Demonstration](#demonstration)
6. [Technologies Employed](#technologies-employed)
7. [Future Development](#future-development)
8. [Contributing](#contributing)
9. [Credits](#credits)
10. [Tests](#tests)
11. [Questions](#questions)
12. [License](#license)

## Usage
**Features**
- JWT user authentication
- Save and manage books
- Google Books API for book search
- Design using Bootstrap

**User Story:**
```md
AS AN avid reader  
I WANT to search for new books to read  
SO THAT I can keep a list of books to purchase
```

**Acceptance Criteria:**
```md
GIVEN a book search engine  
WHEN I load the search engine  
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
WHEN I click on the Search for Books menu option  
THEN I am presented with an input field to search for books and a submit button  
WHEN I am not logged in and enter a search term in the input field and click the submit button  
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site  
WHEN I click on the Login/Signup menu option  
THEN a modal appears on the screen with a toggle between the option to log in or sign up  
WHEN the toggle is set to Signup  
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button  
WHEN the toggle is set to Login  
THEN I am presented with two inputs for an email address and a password and login button  
WHEN I enter a valid email address and create a password and click on the signup button  
THEN my user account is created and I am logged in to the site  
WHEN I enter my account’s email address and password and click on the login button  
THEN the modal closes and I am logged in to the site  
WHEN I am logged in to the site  
THEN the menu options change to Search for Books, an option to see my saved books, and Logout  
WHEN I am logged in and enter a search term in the input field and click the submit button  
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account  
WHEN I click on the Save button on a book  
THEN that book’s information is saved to my account  
WHEN I click on the option to see my saved books  
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account  
WHEN I click on the Remove button on a book  
THEN that book is deleted from my saved books list  
WHEN I click on the Logout button  
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
```

## Installation
This application is deployed using [Render](https:FILL).

## Demonstration
   <div style="margin-left: 40px;">
   Demonstration of the application's desktop interface:<br/>
   <img src=".gif" alt="Desktop demonstration video" width="550"/>
   </div>
   <br/>

   <div style="margin-left: 40px;">
   Image of the application's desktop interface:<br/>
   <img src=".png" alt="Screenshot" width="550"/>
   </div>
   <br/>

## Technologies Employed
**Frontend:**  
   ![React](https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB) 
   ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)  
   ![Apollo Client](https://img.shields.io/badge/-Apollo%20Client-311C87?logo=apollographql&logoColor=white) 
   ![React Bootstrap](https://img.shields.io/badge/-React%20Bootstrap-563D7C?logo=bootstrap&logoColor=white)

**Backend:**  
   ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white) 
   ![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white)  
   ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white) 
   ![Mongoose](https://img.shields.io/badge/-Mongoose-880000?logo=mongodb&logoColor=white)   
   ![Apollo Server](https://img.shields.io/badge/-Apollo%20Server-311C87?logo=apollographql&logoColor=white) 
   ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?logo=graphql&logoColor=white)

**Authentication:**  
   ![JSON Web Tokens](https://img.shields.io/badge/-JSON%20Web%20Tokens-000000?logo=jsonwebtokens&logoColor=white)

**Build:**  
   ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white) 
   ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)

## Future Development
I do not plan to make any further developments on this project outside of using it as a learning and resource model.

## Contributing
Contributions are welcome and encouraged. To do so:
- Fork this repository.  
- Your pull request will need approval in order to merge to `main`.  
- Take a look at the [Future Development](#future-development) section to see what I am currently working on.

## Credits
This code was written as an exercise by the edX coding bootcamp and modified to function by me.

## Tests
No tests are needed beyond visiting the website.

## Questions
If you have any questions, please reach out to me at:
- Email: [skylarkline16@gmail.com](mailto:skylarkline16@gmail.com)
- GitHub: [skylark-shae](https://github.com/skylark-shae)

## License

This project is licensed under the MIT license.

The MIT License is a permissive software license originating at the Massachusetts Institute of Technology (MIT) in the late 1980s. As a permissive license, it puts very few restrictions on reuse and therefore has high license compatibility.

For more information, visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

---

© 2025 Sky-Shae Design. All Rights Reserved.
