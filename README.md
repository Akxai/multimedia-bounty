# Multimedia App

This is a file manager app that allows you to manage and view various types of files. It provides search and filter functionalities to help you easily find and organize your files.

## Features

## Added functionalities (Search and Filter)

### Search: 
You can search for files by their names or types. The search functionality dynamically updates the file list as you type.

The search functionality allows you to search for files based on their names or types. Here's how it works:

   - In the app's user interface, you'll find a search input box where you can enter your search query.

   - As you type in the search input, the app dynamically filters the file list based on the search query.

   - The filtering process compares the lowercase versions of the file names and types with the lowercase version of the search query. If a file's name or type contains the search query, it will be included in the filtered file list.

   - The filtered file list is updated in real-time, displaying only the files that match the search query.

### Filter: 
You can filter files by their types. Choose from options like video, audio, document, or image to view files of a specific type.

The filter functionality allows you to filter files based on their types. Here's how it works:

   - In the app's user interface, you'll find a filter dropdown menu that lists different file types such as video, audio, document, and image.

   - To apply a filter, you can select a specific file type from the filter dropdown menu.

   - When you select a file type, the app filters the file list to display only the files that match the selected type.

   - The filtered file list is updated accordingly, showing only files of the selected type.

   - If you want to view all files again, you can choose the "All" or "None" option in the filter dropdown menu. The "All" option displays all available file types, while the "None" option removes any applied filters, showing all files.


By combining the search and filter functionalities, you can easily search for specific files by name or type and further narrow down the file list by filtering based on file types. This provides a convenient way to find and manage your files within the file manager app.


### Previous functionalities


- Rename: You can rename a selected file by clicking the "Rename" button and entering a new name.
- Delete: You can delete a selected file by clicking the "Delete" button. The file will be permanently removed from the app.
- Files Breakdown: Clicking the "Files Breakdown" button displays a modal window showing a breakdown of file types using pie and bar charts.
- Download: You can download a selected file by clicking the "Download" button. The file will be opened in a new tab for downloading.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Akxai/multimedia-bounty.git

2. Install dependencies:
   ```bash
   cd multimedia-bounty
   npm install

3. Start the app:
   ```
   npm start
   ```
   The app will be running at http://localhost:3000.

4. Use the search bar to search for files by name or type. The file list will update dynamically as you type.

5. Use the filter dropdown to filter files by type. Selecting a specific file type will update the file list to display only files of that type.

6. Perform file management actions using the buttons provided:

    - Rename: Click the "Rename" button and enter a new name for the selected file.
    - Delete: Click the "Delete" button to permanently delete the selected file.
    - Files Breakdown: Click the "Files Breakdown" button to view a modal window with pie and bar charts showing the breakdown of file types.
    - Download: Click the "Download" button to open the selected file in a new tab for downloading.
  
## Technologies Used

  - React: A JavaScript library for building user interfaces.
  - Chart.js: A flexible JavaScript charting library for visualizing data.
