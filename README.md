# Module 3 Solution - Narrow Down Your Menu Choice

## Overview
This is a simple AngularJS application that allows users to search through a list of menu items from a restaurant's API and filter down to only the items they are interested in. Users can enter a search term, view the results, and remove items they don’t want to see.
<img width="896" alt="0" src="https://github.com/user-attachments/assets/319e46d9-9931-4c1e-88f3-5c114a54c72c">
<img width="884" alt="3" src="https://github.com/user-attachments/assets/d8bd70aa-a4f9-403f-85be-2dfdccd3d92a">
<img width="890" alt="1" src="https://github.com/user-attachments/assets/d8f67873-9ff2-4fdb-9f53-538fc04eeae6">

## Technologies Used
- **HTML5**
- **CSS3**
- **AngularJS (1.8.2)**
- **JavaScript**

## Feature
 - **Search Menu Items**: Allows users to search through menu item descriptions using a search term.
 - **Remove Unwanted Items**: Provides an option to remove items from the search results.
 - **Scrollable List**: Displays search results in a scrollable area when there are many items.
 - **Responsive Design**: Adjusts to various screen sizes and ensures a user-friendly experience.
 
## Usage
**Enter a Search Term**:
 - Type a search term in the input field (e.g., "soup", "appetizer").
 - Click the "Narrow It Down For Me!" button to filter menu items by the entered term.
   
**View Results**:
 - The results will appear in a scrollable list on the right side of the screen.
 - Each item displays the name, short name, and description of the menu item.
   
**Remove Unwanted Items**:
 - Click the "I Don't Want This" button next to an item to remove it from the list.
   
**Clear Results**:
 - If no items match the search term, a message saying "Nothing found" will appear.

## API Endpoint
This application uses a publicly available API endpoint to fetch menu items:
 - URL: https://coursera-jhu-default-rtdb.firebaseio.com/menu_items.json

## AngularJS Components
**Controller**: NarrowItDownController manages the user input, invokes the search service, and handles the list of found items.

**Service**: MenuSearchService interacts with the API to fetch menu items and filter them based on the search term.

**Directive**: foundItems directive displays the filtered list of items and provides functionality to remove items.

## Author
Created by Quang Bui.

