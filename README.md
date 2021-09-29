# 11-NoteTaker_Heroku_Express.js-FrontEndandBackEndApp

## Task
Modify starter code to create an application called 'Note Taker' that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.  The application’s front end has already been created. It's our job to build the back end, connect the two, and then deploy the entire application to Heroku.

## SOLUTION:

🗂️ [Github Repository](https://github.com/cakspri/Note-Taker)

📑[Heroku Git Repository](https://note-taker1100.herokuapp.com/)

## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Acceptance Criteria

```
GIVEN a note-taking application
✓ WHEN I open the Note Taker THEN I am presented with a landing page with a link to a notes page
✓ WHEN I click on the link to the notes page THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
✓ WHEN I enter a new note title and the note’s text THEN a Save icon appears in the navigation at the top of the page
✓ WHEN I click on the Save icon THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
✓ WHEN I click on an existing note in the list in the left-hand column THEN that note appears in the right-hand column
✓ WHEN I click on the Add icon in the navigation at the top of the page THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

## Application Functionality Screenshots

The following images show the web application's appearance and functionality:
Landing Page/Getting Started Page: 
![Landing/Getting Started Page](./Assets/LandingPage.png)
Notes Page
![Notes Page](./Assets/NotesPage.png)
Rerouting to Landing Page/Getting Started Page no matter which path apart from /notes is entered: 
!(./Assets/RerouteHome.png)
Note Added
![Note Added](./Assets/NoteAdded.png)
Note Deleted
![Note Deleted](./Assets/NoteDeleted.png)
Saved Notes View
![Saved Notes View (ReadOnly)](./Assets/ViewingSavedNotes.png)
Note Deletion
!(./Assets/NoteDeletion.png)
No Console Errors
![No Console Errors](./Assets/NoErrors.png)
