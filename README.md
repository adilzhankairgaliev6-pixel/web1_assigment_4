# Assignment #4. Forms and Validation

## Student Information
- Name: Adilzhan Kairgaliyev
- Group: SE-2540

---

## Project Overview
In this lab assignment, I added forms to my StrideHouse web application. I practiced working with HTML forms, HTML5 validation, Bootstrap form classes and Bootstrap validation styles. All forms are made as real pages of the shop: Contact Us, Feedback, Customer Support, Request a Return and Sign Up.

---

## Tasks & Assignments

### Part 1. Basic HTML Forms

- Task 0. Simple Contact Form
- What I did: Created a contact form with Name, Email, Message and a Send button. Every field has a `<label>`. The page is `contact.html`.
<img width="1915" height="987" alt="image" src="https://github.com/user-attachments/assets/91f3a960-9c0d-4952-b158-109550e0bffd" />


- Task 1. Form with HTML5 Validation
- What I did: Made a feedback form and added validation attributes: `required`, `type="email"`, `minlength` and `maxlength`. The browser shows an error if a field is empty or the email is wrong. The page is `feedback.html`.
<img width="1919" height="936" alt="image" src="https://github.com/user-attachments/assets/3fbfdc53-bc19-45ee-aea9-d52894ee3651" />
<img width="1915" height="1001" alt="image" src="https://github.com/user-attachments/assets/4a4ff509-421e-4d64-851f-a65b7a6f2e60" />



### Part 2. Bootstrap Forms

- Task 2. Bootstrap Form Styling
- What I did: Made the contact form with Bootstrap classes (`form-control`, `form-label`, `btn`). Used the Bootstrap grid (`row`, `col-md-6`) to put Name and Email in one row. Added placeholders and helper text (`form-text`). The page is `support.html`.
<img width="1787" height="812" alt="image" src="https://github.com/user-attachments/assets/19df4058-0c0e-4e2f-9b60-d08e04e516a6" />
<img width="392" height="933" alt="image" src="https://github.com/user-attachments/assets/88c144cb-c490-433d-9801-c87f0ac45272" />



- Task 3. Bootstrap Validation Styles
- What I did: Used `is-valid` and `is-invalid` classes with feedback messages under the inputs, like "Looks good!" and "Email is required". A small JavaScript checks the fields and adds these classes. I tested it with correct and wrong data. The page is `returns.html`.
<img width="1681" height="787" alt="image" src="https://github.com/user-attachments/assets/42b93553-a3e2-4a72-b30c-eb81071f0042" />
<img width="1627" height="828" alt="image" src="https://github.com/user-attachments/assets/2dcb1b95-a6f1-4997-aea9-3ae9825c5a39" />


### Part 3. Advanced Form Project

- Task 4. Registration Form
- What I did: Made a registration form with First Name, Last Name, Email, Password, Confirm Password, Gender (radio buttons), Hobbies (checkboxes), Country (select), Submit and Reset buttons. The form is responsive because of the Bootstrap grid. Added HTML5 validation (password minimum 6 characters) and Bootstrap feedback messages. JavaScript checks that both passwords are the same. The page is `register.html`.
<img width="1544" height="986" alt="image" src="https://github.com/user-attachments/assets/725bbe28-889d-4e47-973b-ea1da9a31a74" />
<img width="1444" height="1028" alt="image" src="https://github.com/user-attachments/assets/309400ab-37df-4be5-b361-150f56566a28" />
<img width="1005" height="973" alt="image" src="https://github.com/user-attachments/assets/c5091654-e9be-4084-8caa-b034d1a29bbc" />
<img width="517" height="888" alt="image" src="https://github.com/user-attachments/assets/327b9bfa-a250-4bec-b6e7-44b5aab62038" />


---

## Workflow Process

- Step 1. Preparing the project
- I used my StrideHouse project from the previous assignment. Created new pages and a `forms.css` file for the form styles. Linked Bootstrap from CDN.

- Step 2. Basic forms (Tasks 0 & 1)
- First I made a simple contact form with labels. Then I added HTML5 validation attributes and checked how the browser shows errors.

- Step 3. Bootstrap forms (Tasks 2 & 3)
- Rebuilt the form with Bootstrap classes and grid. After that I added `is-valid` and `is-invalid` classes with messages and tested the form with correct and wrong data.

- Step 4. Registration form (Task 4)
- Made the registration form with all required fields and added validation for password length and password match.

- Step 5. Connecting and testing
- Added the new pages to the menu and the footer of the main page. Tested all forms in the browser and on different screen sizes (F12). Finished up the README and pushed the code to GitHub.
