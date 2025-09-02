# React Class-Based Profile Component

## Description
This project demonstrates how to create a class-based React component with state management and lifecycle methods. It showcases a simple profile of a person that can be shown or hidden with a button and includes a timer displaying the time since the component was mounted.

## Features
- Class-based `App` component.
- State containing:
  - `person` object with:
    - `fullName`
    - `bio`
    - `imgSrc` (profile image)
    - `profession`
  - `shows` boolean to toggle profile visibility.
- Button to toggle the display of the person's profile.
- Timer showing seconds elapsed since the component was mounted, updated using `setInterval`.

