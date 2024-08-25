# F_Assignment
his is a frontend spreadsheet application built using Next.js, Zustand for state management, and Tailwind CSS for styling. The app mimics the functionality of a traditional spreadsheet and includes advanced features like pagination, infinite scrolling, undo/redo, and basic cell formatting.


Features
Editable Cells: 1000 editable cells that allow dynamic data entry and update.
Cell Formatting: Align cell content (left, center, or right).
Undo/Redo: Revert or redo changes made to cells.
Pagination: Navigate through the grid with previous and next buttons.
Infinite Scrolling: Load more rows dynamically as you scroll.
Responsive Design: Fully responsive UI for various screen sizes.
Installation and Setup
Follow these steps to get the project running locally:

Prerequisites
Ensure you have the following installed:

Node.js (version 12.x or higher)
npm (or yarn)
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/spreadsheet-app.git
cd spreadsheet-app
Install Dependencies

bash
Copy code
npm install
Run the Development Server

bash
Copy code
npm run dev
The application will run locally at http://localhost:3000.

Build for Production
To build the project for production, use:

bash
Copy code
npm run build
npm start
The production build will be optimized for performance and can be served in production environments.

Features Overview
1. Editable Grid
The grid is composed of 1000 cells, all editable.
Enter text or numbers by selecting any cell.
2. Cell Formatting
Format the text within a cell (align left, center, or right) using small buttons displayed in each cell's top-right corner.
3. Undo/Redo
Undo your recent changes or redo previously undone changes with the Undo and Redo buttons.
4. Pagination
Navigate between different sets of rows using Previous and Next buttons at the bottom of the grid.
5. Infinite Scrolling
Automatically load more rows as you scroll through the grid.
6. Responsive Design
The app is responsive and adapts to various screen sizes, from desktop to mobile.
Project Structure
/pages: Contains Next.js pages (main app is located in pages/index.js).
/components: Contains reusable components (e.g., the Grid.js component).
/store: Zustand store that handles application state, including grid data, undo/redo functionality, and pagination.
Contributing
We welcome contributions! Here's how you can contribute:

Fork the repository.
Create a new feature branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
