# Custom HTML Emails

## Description

This project focuses on creating custom HTML emails using the MJML framework, a responsive email framework that utilizes a markup language to streamline the process of developing responsive email templates. MJML’s objective is to simplify the way you design responsive emails by providing a set of components that automatically handle the complexity of responsive email layouts.

Custom HTML emails are designed to be compatible with a variety of email clients, ensuring a consistent and visually appealing experience across different platforms and devices. This is crucial for maintaining brand integrity and providing a reliable user experience to all recipients, regardless of their email client.

In addition to being compatible with various email clients, a web browser-based version is linked at the bottom of each email. This ensures that recipients who are unable to view the email in their client, or who prefer to view it in a web browser, can still access the content seamlessly.

In this repository an index.msg file is provided for each email template. This is an Outlook message that allows users to open the email directly in Microsoft Outlook, providing another layer of accessibility and convenience for recipients who use this email client.

Each email folder contains the following files:
- index.mjml (the editable MJML code)
- index.html (the exported HTML file)
- index.msg (the exported Outlook email message file) 

## Installation Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (Download and install from [Node.js official website](https://nodejs.org/))
- A code editor (e.g., Visual Studio Code, Sublime Text, or Atom)

## MJML Installation & Usage

To install MJML and set up the project, follow these steps:

1. Install MJML
    `npm install -g mjml`
    If using Visual Studio Code install the [MJML extension](https://marketplace.visualstudio.com/items?itemName=attilabuti.vscode-mjml)
    More MJML installation instructions can be found [here](https://youtu.be/Q1M4tKmBM7k?si=MK3xZYE4x9CHzJQw)

2. Clone this repository to your local machine:
   `git clone https://github.com/Dylan-Hedges/Custom-HTML-emails.git`

3. Open the index.mjml in a code editor & make changes

4. Compile your MJML to HTML:
    `mjml your-email-template.mjml -o index.html`

