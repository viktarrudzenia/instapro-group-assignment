# Assignment for Instapro Group - Trello

## Link to application

[Link to the deployed application](https://instapro-group-assignment.vercel.app/)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.

### Node version

v20.11.1

## Evaluation Criteria Details

## App Functionality Criteria

### 1. A user should be able to add and label columns

> Yes. I implemented a feature that allows users to create and label columns. Users can click the "Create new Column" button to generate a new column, input the desired label, and then click the "Add Column" button to add the labeled column to the interface.

### 2. A user should be able to add and edit cards

> Yes, I implemented this functionality. Each column has an "Add new card" button at the bottom. When the user clicks it, they can input a label for the card. Clicking the "Add Card" button will add the new card to the current column.

> Once a card is created, it is possible to delete or move it between columns.

### 3. A user should be able to move cards between columns (UX is up to you, does not need to be drag-and-drop)

> Yes, I implemented it. Once a card is created, it is possible to move it to another column (if other columns exist). Press the "Move Card" button, and below, you'll see all available columns. Select the column where you want to move the card, and the card will be moved accordingly.

### 4. Do make sure the available interactions are intuitive. In other words, we will be considering usability

> Yes, I made it intuitive for any user to understand how to use the system. I added clear styles and followed best UI/UX practices to ensure the user experience is smooth and interactions are straightforward.

### 5. Some kind of persistency (LocalStorage or SessionStorage) is encouraged, though not required

> Yes, I implemented persistence through LocalStorage. This allows the user to refresh the page without losing any information, as all data is preserved during the session.

### 6. Any additional features you find important (feel free to elaborate in your README file about why you made certain choices)

> I added the ability to remove columns and cards, allowing users to clear unnecessary data easily.

> I implemented "no data" status messages for both cards and columns to enhance the UI and improve clarity when no content is present.

> I enhanced the UI with well-organized layouts to provide a better user experience (UX).

> I followed best practices in project architecture to ensure clean, maintainable, and scalable code.

## Technology constraints Criteria

### 7. Do not use any third-party React components (not even UI only ones). All React components must be yours. Create React App is encouraged as a starting point, but you should not use any other React npm packages for the app. We want to see how you work with core JavaScript/Typescript and React features and CSS/CSS-inJS, not necessarily what libraries or packages you know

> I didn't use any React component UI libraries. I added all the styles myself to create a better UI. I created a `TrButton` component as a `shared component` to maintain consistency across the application. I used Create React App as a starting point as recommended, although I believe that using modern React frameworks like Next.js or Remix would be a better approach for building applications. I styled the application using the SCSS module approach for better modularity and maintainability.

### 8. Don't worry too much about the presentation. This means no particular CSS, fonts, or images are required.This is a coding activity and not a design activity. That's not to say we don't appreciate great design or that we don't value those skills if you have them! It's just that we won't be considering design when scoring this particular project

> I didn’t focus on presentation too much, but as a Lead Frontend Developer, I added some styles to ensure a good visual representation. While the current design is good and functional enough, I would improve it if that was the goal of the assignment.

## Other Criteria

### 9. Feel free to use any utility libraries like Lodash, Ramda, Moment.js, etc.

> I added only `Prettier` for code formatting, `Sass` for styling with SCSS, and `classnames` for class concatenation. All other functionalities are implemented using core React, JavaScript, and TypeScript capabilities.

### 10. Please do not use Redux or similar state management libraries. We want to see how you handle the application state yourself

> I didn't use Redux, Redux Toolkit, or Zustand for state management. Instead, I utilized React’s native capabilities, such as Context API and useState, to handle the application state effectively.

### 11. Your project should have a package.json with all dependencies listed so that we can install it with npm

> Yes, the project includes a package.json file with all dependencies listed. You can easily install and run the project locally using npm. More details you can find inside `Available Scripts` paragraph above.

### 12. We expect to receive a Git repository with a React application. Please provide instructions on how to get your application running locally

> Yes, I have included all the instructions for running the project in the "Available Scripts" section above.

## Improvements

### 13. let me know what else you would've added to the project if this were a real app

> In a real-world scenario, I would consider the following enhancements:

> 1. React Framework: I would transition from Create React App (CRA) to a more modern React framework like Next.js, Remix, Astro, Gatsby, or Vite. These frameworks offer better performance, built-in features, and improved development workflows.

> 2. UI Component Libraries: I would integrate UI component libraries such as Ant Design (antd) or Material-UI. These libraries provide pre-built, customizable components that enhance the user experience (UX) and allow more focus on functionality rather than design.

> 3. State Management: I would implement a robust state management tool using Redux ( Redux Toolkit) or Zustand. These tools provide better solutions for managing complex application state and make state handling more efficient and scalable.

> 4. Drag-and-Drop Functionality: I would incorporate a drag-and-drop library to enable users to easily reorder cards or move them between columns, enhancing interactivity and usability.

> 5. Enhanced Card and Column Details: I would add more detailed information and customization options within columns and cards to provide a richer user experience.

> 6. Error Handling: I would implement an Error Boundary to handle and display errors gracefully, improving the application's robustness and user experience.

> 7. Bundler Configuration: I would refine bundler settings according to project requirements and best practices to optimize build performance and manage dependencies more effectively.

> 8. Extended Functionality: I would add more features to address edge cases and specific user needs, ensuring comprehensive functionality.

> 9. API Integration: I would integrate APIs to make the application dynamic and capable of interacting with external data sources, enhancing its utility and versatility.

> 10. Additional Pages: I would include additional pages such as a 404 error page, contact information, and other relevant sections to provide a complete and user-friendly experience.

These enhancements would significantly improve the functionality, usability, and maintainability of the application.