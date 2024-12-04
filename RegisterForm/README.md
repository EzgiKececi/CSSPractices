# Survey Form Project

This is a basic survey form created as part of a web development project. It includes various form elements such as input fields, radio buttons, checkboxes, a dropdown, a textarea, and a submit button. The form uses HTML5 validation features and is structured according to the specifications provided.

## Project Structure

- **HTML5 Form**: The form includes necessary fields for user information input, with HTML5 validation and IDs for easy identification.
- **Form Elements**:
  - **Title**: A header (`<h1>`) element with the ID `title`.
  - **Description**: A paragraph (`<p>`) element with the ID `description`.
  - **Form**: A form (`<form>`) element with the ID `survey-form`.
  - **Input Fields**:
    - **Name**: A text input with the ID `name` and type `text`.
    - **Email**: A text input with the ID `email` and type `email`. The input field includes HTML5 email validation.
    - **Number**: A number input with the ID `number` and type `number`, including validation for a range of valid numbers.
  - **Labels**: Each input field is properly labeled with the corresponding `id` for accessibility:
    - **Name Label**: ID `name-label`
    - **Email Label**: ID `email-label`
    - **Number Label**: ID `number-label`
  - **Select Dropdown**: A dropdown (`<select>`) element with the ID `dropdown`, containing at least two options.
  - **Radio Buttons**: At least two radio buttons grouped together using the `name` attribute.
  - **Checkboxes**: At least two checkboxes with `value` attributes.
  - **Textarea**: A textarea element for additional comments.
  - **Submit Button**: An input of type `submit` with the ID `submit`.

## Features

- **HTML5 Validation**: 
  - The email input field uses HTML5 validation to ensure a valid email format.
  - The number input field includes a validation range to accept only numbers within a specified range.
  
- **User-Friendly Interface**:
  - The form elements are designed with placeholders to guide the user in filling out the form.
  
- **Accessibility**:
  - Each input field is properly labeled with corresponding labels and IDs for better accessibility.

