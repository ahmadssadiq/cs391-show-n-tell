# cs391-show-n-tell

Checklist App is an extra-credit project designed as part of the Show and Tell assignment. The project aims to demonstrate skills in React, TypeScript, and React Router, utilizing state management and component animations to create a dynamic and interactive checklist application. We used Transition components which are implemented in our checklist to add a item to list, to delete the item, to tick off the item.

Project Requirements

	1.	The project covers dynamic state management and routing in React using TypeScript, which wasn’t thoroughly covered in class.
	2.	Instructor approval was obtained before starting on the project.
	3.	The project is a Web App and satisfies the requirement of creating a small interactive application.
	4.	A presentation slideshow will be created to document the project implementation, challenges, solutions, and progress.

Challenges and Solutions

Challenge 1: Handling State and Data

Solution: We used React’s useState to manage the state of each checklist and task, making sure tasks are updated dynamically without page reloads.

Challenge 2: Smooth Transitions

Solution: The app uses TransitionGroup and Collapse components from React Transition Group and Material-UI to achieve smooth entry and exit animations for tasks, enhancing the user experience.

Challenge 3: Case-Sensitive File Issues

Solution: We ensured consistent casing for file imports in our codebase to avoid errors related to case-sensitive file systems in macOS.

Potential Pitfalls

	1.	Case Sensitivity: Ensure file names match import paths exactly, especially in macOS or Linux environments.
	2.	State Management: Complex state management can lead to unexpected bugs if not carefully handled. Properly track updates and use TypeScript’s type checking to catch errors early.

Future Improvements

	•	Persist Data: Integrate local storage or a backend to save user-created checklists.
	•	User Authentication: Allow multiple users to create and manage their own checklists.
	•	Advanced Transitions: Implement more advanced transitions and animations to enhance user experience.

This project showcases the implementation of advanced React features and animations while fulfilling all requirements of the Show and Tell extra-credit assignment. We aimed to demonstrate a comprehensive understanding of state management, routing, and component-based architecture in React with TypeScript.
