# Custom HTML Emails

## Description

This project focuses on creating custom HTML emails using the MJML framework, a responsive email framework that utilizes a markup language to streamline the process of developing responsive email templates. MJML’s objective is to simplify the way you design responsive emails by providing a set of components that automatically handle the complexity of responsive email layouts.

Custom HTML emails are designed to be compatible with a variety of email clients, ensuring a consistent and visually appealing experience across different platforms and devices. This is crucial for maintaining brand integrity and providing a reliable user experience to all recipients, regardless of their email client.

In addition to being compatible with various email clients, a web browser-based version is linked at the bottom of each email. This ensures that recipients who are unable to view the email in their client, or who prefer to view it in a web browser, can still access the content seamlessly.

This repository contains a number of folders with each one dedicated to a distinct custom HTML email. For instance, the directory named 'Periodic-Welcome-Light' encompasses all the necessary files pertinent to that particular email template.

Each email folder contains the following files :

## index.mjml

The index.mjml file in each folder serves as the editable source code for an email template. This file provides a structured and semantic way to define the layout and content of an email. This file is crucial as it contains the MJML markup language, which is specifically designed to simplify the creation of responsive email templates. 

By using a series of custom tags and a clear syntax, MJML abstracts away much of the complexity associated with writing raw HTML and inline CSS for emails, ensuring consistent rendering across various email clients and devices.

Once the content and layout are defined in the .mjml file, it needs to be compiled into HTML, resulting in a file that can be directly used in email campaigns or integrated into email sending platforms. The compilation process translates the high-level MJML code into standard HTML and inline CSS, applying best practices for email design to ensure responsiveness and cross-client compatibility. 

## index.html
The index.html file generated from the .mjml file serves as the final output of the email template development process, ready to be used in email campaigns or integrated into email sending platforms. This HTML file is the result of compiling the MJML code, where the custom tags and semantic syntax of MJML are translated into standard HTML and inline CSS. The compilation ensures that the email template adheres to best practices for email design, aiming for consistent rendering across various email clients and devices.

The index.html file encapsulates the responsive design and intricate details required for email templates, handling complexities such as table layouts, inline styling, and specific email client quirks. By generating this file from the .mjml source, developers and designers are provided with a streamlined and error-resistant workflow, as the MJML framework automates many of the tedious and error-prone aspects of email template creation. This allows for a ready-to-use, reliable, and cross-client compatible email template, ensuring that the end-users receive a well-rendered and responsive email, regardless of the device or email client they are using.

## Outlook message file (.msg)
This file is a Microsoft Outlook email message file created from the index.html file, enabling users to open, modify, and dispatch the email directly through their Outlook client. The .msg file is a proprietary format used by Microsoft Outlook to store email messages, and creating a .msg file from an index.html email template involves a few specific actions. The .html file, generated from a .mjml file, contains the HTML and CSS code necessary for rendering the email template. To transform this HTML content into a .msg file, you can open the HTML file in Outlook, copy the HTML and CSS code, and save the email as a .msg file.