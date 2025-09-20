# thepdfwebsite 

A very simple website whose main page is programmed to look just like a PDF document, however all of the links on the website lead to actual PDF documents, and if you would like to navigate between pages, just like on a website, you would navigate through the links on each PDF page. 

## Overview
This project contains only a single file, `index.html` that looks and behaves like a PDF viewer:

The aim of this project is to perfect my basic web development skills of creating a Web 2.0 website using a simple `index.html` file with all the CSS and JavaScript functionality being a part of the respective `<style>` and `<script>` tags. The idea of this project came about when I took a course in Software Engineering and my professor said that he and his team would create demo sites for clients to gauge an understanding of what they wanted to develop. His team developed a whole "website" using MicroSoft PowerPoint. All the clients thought it was a legitimate website, however it was all just a demo. In that same light, I intend this project to be a "demo website", composed of LaTeX developed PDF documents and hosted on a singular `index.html` file. 

## Features
- Light macOS-style gray backdrop, centered “page” with outline & soft shadow
- LaTeX-style typography (Times/LM/CM stacks)
- Smooth zoom (buttons, slider, keyboard, trackpad pinch)
- The entire first page can be seen without peeking page 2 
- Floating HUD (zoom − / zoom + / print / download) that appears briefly on load & on interaction
- Multi-page layout (stacked pages)

## Technologies Used
- **HTML5**: For the basic structure of the website.
- **LaTeX**: For the development of PDFs in the website. 

## Project structure

```
├── README.md 
├── ThePDFWebsite.pdf 
└── index.html        
```

## Future Enhancements
- More PDF documents with links to each other
- A "navigation bar" on each PDF document for easy navigation between the most important links
- A "sign up" and "login page" where the user can feel like they are navigating through pages only accessible to them
