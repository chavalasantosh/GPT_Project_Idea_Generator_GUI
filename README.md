# GPT_Project_Idea_Generator_GUI


GPT Project Idea Generator GUI
This application serves as an interface for users to effortlessly generate coding project ideas using OpenAI's GPT model. The GUI allows users to specify parameters such as the programming language, difficulty level, and additional features (like database or API usage) for the desired project. Upon entering these preferences, the user can tap the "Generate Ideas" button to fetch a list of project suggestions.

Features:
Language Selection: Choose your preferred programming language from options like Python, Java, C++, and JavaScript.

Difficulty Levels: Decide the complexity of the projects you want, choosing from Easy, Medium, or Hard.

Feature Inclusion: Specify if you'd like projects that involve databases or APIs.

OpenAI Integration: The tool uses the GPT model from OpenAI to dynamically produce project ideas based on user input.

Dark Mode UI: Uses customtkinter for an enhanced and modern-looking dark-themed GUI.

How to Use:
Launch the application.
Choose the desired programming language from the dropdown menu.
Specify the difficulty level of the project using the radio buttons.
Check the boxes if you want your project to include a database or an API.
Click the "Generate Ideas" button.
Review the proposed project ideas displayed in the textbox.
Prerequisites:
Ensure you have the openai and customtkinter libraries installed.
Add your OpenAI API key in the openai.api_key section of the script.
Notes:
Remember that using the OpenAI API may incur costs, depending on the amount of usage and your subscription plan. Make sure to monitor your usage.
Adjust the openai.ChatCompletion.create method as per any future updates or changes in the OpenAI library.
Disclaimer: Always ensure compliance with OpenAI's terms of service and usage limits. Make sure you handle API keys securely and not expose them in public repositories or insecure locations.
