# RESTful Web App Project

This project is a simple RESTful web application built with Node.js and Express. It demonstrates basic CRUD (Create, Read, Update, Delete) operations using server-side rendering with EJS templates.

## Features
- List all items
- View details of a single item
- Create new items
- Edit existing items
- Delete items

## Project Structure
```
index.js           # Main server file
public/
  style.css        # Stylesheet
views/
  edit.ejs         # Edit item view
  index.ejs        # List view
  new.ejs          # New item form
  show.ejs         # Show item details
```

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gulshankumar143/Comm_Posts.git
   cd Comm_Posts
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the App
Start the development server:
```bash
node index.js
```

## Usage
- Access the home page to see a list of items.
- Use the navigation to create, edit, or delete items.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
