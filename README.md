# Custom HTML emails 
This repository contains the code for [Custom HTML emails](https://customhtmlemails.dylanhedges.com/).

# About
This project focuses on creating custom HTML emails using the MJML framework, a responsive email framework that streamlines the process of developing responsive email templates. 

Custom HTML emails are designed to be compatible with a variety of email clients, ensuring a consistent and visually appealing experience across different platforms and devices. 

A web browser version is also linked at the bottom of each email template. This ensures that recipients who are unable to view the email in their client, or who prefer to view it in a web browser, can still access the content.

This repository contains a number of templates with each one dedicated to a distinct custom HTML email. For instance, the directory named 'Periodic-Welcome-Light' encompasses all the necessary files for that particular email template.

## How to use
1. Click [here](https://customhtmlemails.dylanhedges.com/) to open the live project.
2. View and select an email template.
3. Click on the download icon to download the index.html file for that template.
4. Click on the envelope icon to open [PutsMail](https://putsmail.com/tests/new).  
5. Create a new account.
6. Enter recipient email addresses.
7. Enter a Subject Line for the email.
8. Copy the code from the downloaded index.html file.
9. Paste the code in the Body(HTML) section.
10. Click Send Email.

### index.mjml

The index.mjml file in each folder serves as the editable source code for an email template. This file provides a structured and semantic way to define the layout and content of an email. 

By using custom tags and clear syntax, MJML abstracts away much of the complexity associated with writing raw HTML and inline CSS for emails, ensuring consistent rendering across various email clients and devices.

Once the content and layout are defined in the .mjml file it needs to be compiled into HTML, resulting in a file that can be directly used in email campaigns or integrated into email sending platforms. The compilation process translates the high-level MJML code into standard HTML and inline CSS, applying best practices for email design to ensure responsiveness and cross-client compatibility. 

### index.html
The index.html file generated from the .mjml file serves as the final output of the email template development process. This HTML file is the result of compiling the MJML code into standard HTML and inline CSS. The compilation ensures that the email template adheres to best practices for email design, aiming for consistent rendering across various email clients and devices.

This file encapsulates responsive design, handling complexities such as table layouts, inline styling, and specific email client quirks. By generating this file from the .mjml source, developers and designers are provided with a streamlined and error-resistant workflow, as the MJML framework automates many of the tedious and error-prone aspects of email template creation. This allows for a ready-to-use, reliable, and cross-client compatible email template, ensuring that the end-users receive a well-rendered and responsive email, regardless of the device or email client they are using.




