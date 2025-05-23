# Pye PyCharm Theme

**A Visual Studio Code theme inspired by the classic PyCharm Darcula aesthetic.**

This theme, "Pye PyCharm Theme", brings the familiar dark, comfortable, and productive PyCharm color experience into your VS Code editor. It's particularly tuned for developers working with Python and Jupyter Notebooks, aiming for clarity and reduced eye strain during long coding sessions.

## Features

*   **PyCharm Inspired:** Colors and syntax highlighting are carefully chosen to emulate the well-loved PyCharm Darcula theme.
*   **Enhanced RTL Support in Notebooks:** Improved readability for Right-to-Left languages (like Arabic) in Jupyter Notebook cells, including better margins for a more comfortable note-taking and study experience. This is particularly helpful when mixing RTL and LTR languages.
*   **Optimized for Python & Jupyter Study:** Specifically designed to enhance the experience of learning, coding in Python, and taking notes within Jupyter Notebooks.
*   **Dark & Consistent:** Provides a cohesive dark interface across the editor, terminal, sidebar, and other VS Code UI elements.
*   **Optimized for Readability:** Focus on clear differentiation for keywords, strings, comments, and other code tokens.
*   **Notebook Friendly:** Specific styles for Jupyter Notebook cells, borders, and status elements.

## Installation

1.  Open Visual Studio Code.
2.  Launch the **Extensions** view by clicking on the square icon on the sidebar or by pressing `Ctrl+Shift+X` (Windows/Linux) or `Cmd+ShiftX` (macOS).
3.  In the Extensions view search box, type `Pye PyCharm Theme`.
4.  Find "Pye PyCharm Theme" by **med-mhamdi** in the search results and click the **Install** button.
5.  Once installed, activate the theme:
    *   Open the Command Palette with `Ctrl+Shift+P` (Windows/Linux) or `Cmd+ShiftP` (macOS).
    *   Type `Preferences: Color Theme` and press Enter.
    *   Select **"Pye PyCharm"** from the dropdown list.

## Screenshots

Here's a glimpse of the "Pye PyCharm Theme" in action:

**Jupyter Notebook Example 1 :**

![Pye PyCharm Theme in a Jupyter Notebook showing Markdown and Python code structure](screenshots/pye-notebook%201.png)

**Jupyter Notebook Example 2 :**

![Pye PyCharm Theme displaying Python function definitions in a Jupyter Notebook](screenshots/pye-notebook%202.png)

**Jupyter Notebook Example 3 :**

![Description de pye-notebook 3](screenshots/pye-notebook%203.png)

## Feedback and Contributions

If you encounter any issues or have suggestions for improvement, please feel free to share them! (If you plan to host this project on a platform like GitHub, you can add a link to your repository here later for issues and contributions.)

---

## Advanced Customizations (Optional) - Enhanced Notebook Experience & RTL Support! - Get the Full Look!

For those who want to replicate even more of the specific PyCharm notebook styling seen in some screenshots (like rounded corners on cells, specific margins, or hidden UI elements), you can apply custom CSS to your VS Code.

**Please Note:** This method requires an additional extension and involves modifying VS Code in a way that is not officially supported. These customizations might be affected by VS Code updates. Proceed at your own discretion.

1.  **Install the "Custom CSS and JS Loader" Extension:**
    Search for `Custom CSS and JS Loader` in the VS Code Extensions view (by `beautify-web.beautify-vscode`) and install it.
    (Marketplace Link: [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=beautify-web.beautify-vscode))

2.  **Get the Custom CSS:**
    The custom CSS file for these advanced tweaks is available in this theme's GitHub repository:
    [**custom.css**](https://github.com/medjazz79/pye-pycharm-vscode-theme/blob/main/custom.css)
    *(If you placed it in `extras/custom.css`, the link would be `.../blob/main/extras/custom.css`)*

3.  **Configure "Custom CSS and JS Loader":**
    *   Open your VS Code `settings.json` file (Ctrl+Shift+P or Cmd+Shift+P, then type "Preferences: Open User Settings (JSON)").
    *   Add or update the following settings:
        ```json
        "vscode_custom_css.imports": [
            "file:///C:/Path/To/Your/Saved/custom.css" // IMPORTANT: Replace with the ACTUAL path where YOU save the custom.css file on YOUR computer
        ],
        "vscode_custom_css.policy": true, // Enable stylesheet injection without prompting
        "vscode_custom_css.statusbar": false // Optional: hide the status bar indicator
        ```
    *   **Important for users:** They will need to download the `custom.css` from your GitHub link and save it somewhere on THEIR computer, then update the path in `vscode_custom_css.imports` to point to where *they* saved it.
    *   After configuring, run the command "Enable Custom CSS and JS" from the Command Palette (Ctrl+Shift+P or Cmd+Shift+P). You might need to restart VS Code.

This custom CSS provides tweaks for:
*   Notebook cell appearance (borders, radius, status indicators)
*   **Improved margins and layout for RTL languages (e.g., Arabic) in rendered notebook cells, making note-taking much more comfortable.**
*   Comment colors (though the theme aims to cover this)
*   Other minor UI adjustments.

---

Enjoy the Pye PyCharm experience in VS Code!