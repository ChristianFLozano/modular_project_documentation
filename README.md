# Overview

This was a project required for university program. We had to focus on create a project to innovate and help others.

Bookmatch born as an idea to share books and bring security between users...


<details>
    <summary>Login and Register</summary>

## Register

 > User can register his account with his real gmail, after adding the credentials manually or using google.

### Manually

![Register screenshot scene 1](Images/screenshots/Register1.png)

Once you are on Register page add your credentials manually then click on submit button

![Register screenshot scene 2](Images/screenshots/Register2.png)

A modal will pop up and introduce the code received via mail to verify the mail address

![Register screenshot scene 3](Images/screenshots/Register3.png)

You will be redirected to login page with a success message

![Register screenshot scene 4](Images/screenshots/Register4.png)

### Google

![Register google screenshot scene 1](Images/screenshots/Register1.png)

Then click on Google icon 

![Register google screenshot scene 2](Images/screenshots/RegisterGoogle2.png)

Select the account you want to register and let google do it

![Register google screenshot scene 3](Images/screenshots/RegisterGoogle3.png)

Once is done

![Register google screenshot scene 4](Images/screenshots/RegisterGoogle4.png)

## Login

> User can sing up his account with his real gmail, once has added the credentials manually or using google.

### Manually

Add credentials and click on submit button then you will be in home page

![Login screenshot scene 1](Images/screenshots/Login1.png)

### Google

Click on google icon in login page

![Login google screenshot scene 1](Images/screenshots/LoginGoogle1.png)

Then select the account and you will be in home page

![Login google screenshot scene 2](Images/screenshots/RegisterGoogle3.png)

</details>

<details>
    <summary>Homepage</summary>

As you can see in the home page there are book cards with essential information. Some important information is displayed.

Actions on this page:

- Liking books: This helps to train the k-means algorithm, once it is trained you can visualize recommendations in For You tab.
- View comments: This display a modal to see comments left on the book and post new comments
- Request a book to book's owner: This triggers a request that owner has to accept or deny.
- Move other books: There is a pagination that avoid get too much books from backend and keep the query fast

![Home page screenshot scene 1](Images/screenshots/Homepage.png)

</details>

<details>
    <summary>Profiles</summary>

## My profile

In my profile page you can see your own information, books you have added and buttons to add books or edit user information

![My profile page screenshot scene 1](Images/screenshots/MyProfile1.png)

### Edit profile

Once you click edit button it will show a new modal to edit your information

Actions:

- Add basic information,
- Add or update profile pic
- Add or delete book genres user likes

![Edit profile modal screenshot scene 1](Images/screenshots/EditProfile1.png)

If you want to add a new profile pic, to keep consistency between dimentions we have a function that rezise the image

![Edit profile modal screenshot scene 2](Images/screenshots/EditProfile2.png)

Once everything has been updated click the submit button and it will close the modal.

![Edit profile modal screenshot scene 3](Images/screenshots/EditProfile3.png)

![Edit profile modal screenshot scene 4](Images/screenshots/EditProfile4.png)

## Other profiles

A way to visit other users page is clicking on the name in book card

![Other profile page scene 1](Images/screenshots/OtherProfile1.png)

When you visit a user page you can see his information, books he has posted and request for them, and report the user

![Other profile page scene 2](Images/screenshots/OtherProfile2.png)

If you want to report it opens a report modal ready to fill it up

![Other profile page scene 3](Images/screenshots/OtherProfile3.png)

</details>

<details>
    <summary>Books</summary>

## Add book

To add a book you have go to your profile page and click on add button


![Add book scene 1](Images/screenshots/AddBook1.png)

Once you've pressed the button, a add book modal will be showed.

Title, author, ISBN, description, genre, language and cover image are required

![Add book scene 2](Images/screenshots/AddBook2.png)

If you filled up the information successfuly the book will be ready to shown in your profile pic and home page for other users

![Add book scene 3](Images/screenshots/AddBook3.png)

## Edit book

To edit a book you need to click on edit icon in book table in your profile

![Edit book scene 1](Images/screenshots/EditBooks1.png)

Once you have clicked on the edit icon, it will show edit book modal, edit any field you want

![Edit book scene 2](Images/screenshots/AddBook2.png)

## Delete book

To delete a book you need to click on delete icon in book table in your profile

![Delete book scene 1](Images/screenshots/DeleteBook.png)



</details>

<details>
    <summary> Request book </summary>

TO-DO

- Request book
- Accept cancel book


</details>

<details>
    <summary> Chat </summary>

TO-DO

- Chat interface


</details>

<details>
    <summary> Other </summary>

This helps to log out and change theme color

![Other](Images/screenshots/Other.png)


</details>

###  Note

In this repo we're adding documentation about Projecto modular and things we think are important to keep easy access

As a collaborator feel free to modify this markdown as long as you are following MD syntax rules

### Documentation links

[IEEE DOCUMENT](https://docs.google.com/document/d/1mLF7090NzrJhLA9YUJWiEZ7_enC_3GOSiRYUyXb64gI/edit?usp=sharing ) -
Requirement specification document

[Figma Desing](https://www.figma.com/design/34GIcbvp4FpIKh9K4uaaWb/Proyecto-Modular?node-id=0-1&p=f&t=4z8hYSzqaRw0p5lI-0) - Figma desing proyect **ask for authorization**

[Use Case Diagram](https://lucid.app/lucidchart/02368ea8-910c-4010-888d-e97c29fdd83d/edit?page=0_0&invitationId=inv_240a06a3-a8d8-4d62-a538-96affdf015ff#) - A brief overview of how users will interact with the app **ask for authorization**

[Activity diagram](https://lucid.app/lucidchart/9b235a27-fd11-43af-b4ad-9297f87cf67b/edit?viewport_loc=308%2C-290%2C3198%2C1590%2C0_0&invitationId=inv_4011781a-d61e-40c1-b9d6-5d5c387b038b). Activity Diagram 

### Important links

[Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/) - Best practices for markdown format

[Free File Converter](https://www.freeconvert.com/) - Used to convert any image format to webp

