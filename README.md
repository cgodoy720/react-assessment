# React Assessment: Building a Simple Application

## Objective
The goal of this assessment is to test your React skills, including:
- Creating and managing **stateful components**.
- Passing state as **props** to child components.
- Building and handling a **controlled form**.
- Using the **useEffect** hook to fetch data from an API.

## Instructions
1. **Fork & Clone this repository** to start working on your assessment.
2. This repo contains a React project using Vite.
    - after forking & cloning, `npm i`
    - then run `npm run dev` to open it in the browser
3. The pages/components you need are already created for you in the `src/components/` folder.
4. Complete the tasks below to build the required application.
5. Submit your completed app via `pull request` on the original repo.

## Requirements

### 1. Stateful Component
- Your **PokemonList** component should hold state for a **list of pokemon**  
- Initialize the state as an empty array.

### 2. Passing State as Props
- Create a **child component** to display the list of items from the parent's state.
- Pass the state and any necessary handlers as **props** from the parent to the child component.
- In the child component, use **props** to render the list dynamically.

### 3. Controlled Form
- Add a **form** in the parent component to allow the user to add a new item to the list.
- The form should include:
  - A text input field.
  - A submit button.
- Manage the form's input using **controlled components** (state-driven inputs).
- On submission, update the parent component's state to include the new item.

### 4. Fetching Data with useEffect
- Use the **useEffect** hook in the parent component to fetch a list of sample items from an API and populate the state.
- Example API: [JSONPlaceholder Todos](https://jsonplaceholder.typicode.com/todos) or any other public API.
- Display the fetched items in the list along with the items added via the form.

### 5. Styling (Optional)
- Add some basic CSS or use a library like **Tailwind CSS** to make the app visually appealing.

## Bonus (Optional)
- Add a delete button next to each item in the list to remove it from the state.
- Use conditional rendering to display a loading indicator while fetching data.
- Validate the form to ensure the input is not empty before adding a new item.

## Example App Structure




## Submission
Submit your completed project by sharing:
1. A link to your **GitHub repository**.
2. A brief explanation (in the README of your project) describing your implementation and any additional features.

Good luck!
