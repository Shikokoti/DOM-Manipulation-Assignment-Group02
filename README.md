# DOM Manipulation Assignment

## Description

This assignment aims to help you understand and practice fundamental Document Object Model (DOM) manipulation techniques using JavaScript. You will be working with an existing HTML file (`index.html`) and a JavaScript file (`main.js`) to perform the following tasks:

1.  **Selecting and Styling:** Learn how to select a specific HTML element using JavaScript and dynamically inject a CSS class to change its appearance.
2.  **Dynamic Element Addition:** Practice querying the DOM to identify elements with existing styles and then creating new elements that inherit the same styling.
3.  **Removing Child Elements:** Understand how to traverse the DOM to find parent elements and programmatically remove their child elements.

By completing these tasks, you will gain a solid foundation in manipulating the structure and styling of web pages using JavaScript.

## Cloning the Assignment

To get started, you will need to clone this assignment repository to your local machine. Follow these steps:

1.  **Ensure Git is Installed:** If you don't have Git installed on your computer, download and install it from [https://git-scm.com/downloads](https://git-scm.com/downloads).

2.  **Open Your Terminal or Command Prompt:** Navigate to the directory where you want to save the assignment files.

3.  **Clone the Repository:** Use the following command:

    ```bash
    git clone git@github.com:Moringa-SDF-PT10/git-dom.git
    ```

    This will create a new directory containing the assignment files (`index.html`, `styles.css`, `main.js`, `README.md`).

4.  **Navigate to the Assignment Directory:** Change your current directory to the newly created assignment folder:

    ```bash
    cd git-dom
    ```

## Creating and Checking Out Your Group Branch

For grading purposes, you will need to work on a specific branch named according to your group. Follow these steps:

1.  **Identify Your Group Name:** Determine your assigned group name. Examples include `groupAA`, `group01`, `group09`, `group10`, etc.

2.  **Create and Checkout Your Branch:** Use the following Git command, replacing `your_group_name` with your actual group name:

    ```bash
    git checkout -b your_group_name
    ```

    For example, if your group is `group03`, the command would be:

    ```bash
    git checkout -b group03
    ```

    This command does two things:
    * `-b`: Creates a new branch with the specified name.
    * `group03`: The name of your group's branch.
    After running this command, you will be automatically switched to your newly created branch.

## Completing the Assignment

Now you can open the `index.html` file in your web browser and the `main.js` file in a code editor. Follow the `TODO` comments in the `main.js` file to complete the assignment tasks. You might also need to refer to the `styles.css` file to understand the existing styles.

## Submitting Your Work

Once you have completed all the tasks in the `main.js` file:

1.  **Add Your Changes:** Stage all the changes you have made using the following command:

    ```bash
    git add .
    ```

2.  **Commit Your Changes:** Create a commit with a descriptive message:

    ```bash
    git commit -m "Completed DOM manipulation assignment for group [your_group_name]"
    ```

    Replace `[your_group_name]` with your actual group name (e.g., `group03`).

3.  **Push Your Branch to the Remote Repository:** Push your group's branch to the remote repository. Replace `your_group_name` with your actual group name:

    ```bash
    git push origin your_group_name
    ```

    For example:

    ```bash
    git push origin group03
    ```

Your work will then be available in your group's branch on the remote repository for grading (`DUE: 05-APR-2025 11:59PM EAT (GMT+3)`). Happy Coding!