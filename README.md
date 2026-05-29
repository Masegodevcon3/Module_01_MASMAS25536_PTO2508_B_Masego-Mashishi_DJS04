Book Connect - Web Components Edition
Overview
Book Connect is a web application that showcases a collection of books using reusable Web Components. This version encapsulates the book preview feature into a custom <book-preview> element, promoting modularity, reusability, and encapsulation in modern web development.
Features

Display book information (title, author, cover image, description) via a custom Web Component.
Fully encapsulated styles using Shadow DOM to prevent CSS conflicts.
Easy to add new books by simply inserting <book-preview> elements with attributes.
Demonstrates the power of Web Components for building modular UI elements.

Demo
You can see a live preview by opening the index.html file in your browser, or after deploying to GitHub Pages (see instructions below).
Usage
How to Use <book-preview> in Your HTML

          
            
            
          
          <book-preview
  title="The Great Gatsby"
  author="F. Scott Fitzgerald"
  cover="https://images.unsplash.com/photo-1544935724-4acf4d63b2f3"
  description="A classic novel about the American Dream."
></book-preview>
      How to Add More Books
Simply add more <book-preview> elements with different attribute values inside your HTML.

Setup Instructions
Local Development

Download or clone this repository.
Open index.html in your browser to view the demo.

Deployment to GitHub Pages

Push your code to GitHub (see previous instructions).
Enable GitHub Pages in your repository settings.
Access the live site via the provided URL.


Folder Structure

          
            
            
          
          /your-project-folder
│
├── index.html        # Main HTML file that uses the Web Components
├── book-preview.js   # JavaScript defining the <book-preview> Web Component
└── README.md         # This documentation file
      
Future Enhancements

Add event handling (e.g., clicking a book opens details).
Fetch book data dynamically from an API.
Style the component for responsiveness and better UI.

License
This project is for educational purposes and is provided under the MIT License.

Acknowledgments

Built as part of the DJS03 Web Development course.
Inspired by Web Components tutorials and best practices.
