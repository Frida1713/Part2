# Part2
# Recipe App

This is a standalone command line application written in C# that allows users to manage and interact with recipes. It allows users to enter multiple recipes, each with its own set of ingredients and steps. The application provides features like displaying recipes, scaling recipe quantities, calculating total calories, and notifying the user when a recipe exceeds 300 calories.

## Instructions

To compile and run the software, follow these steps:

1. Ensure you have Visual Studio and .NET Framework installed on your machine.
2. Clone or download the repository from the GitHub link provided below.
3. Open the solution file (`RecipeApp.sln`) in Visual Studio.
4. Build the solution to compile the application.
5. Run the application by clicking the "Start" button or pressing `F5` on your keyboard.

Once the application starts, you can follow the menu prompts to interact with the software and perform various actions such as entering new recipes, displaying recipes, and selecting a recipe to view its details.

## GitHub Repository

[Recipe App GitHub Repository]( https://github.com/Frida1713?tab=repositories)

Please click the link above to access the GitHub repository for the Recipe App. You can clone or download the repository to your local machine and explore the source code, make modifications, or submit issues or suggestions.

## Description of Changes

Based on the feedback received, the following changes have been made to the part1 software:

1.	Implemented the use of generic collections (`List<T>`) instead of arrays for storing recipes, ingredients, and steps. This allows for dynamic resizing and improved flexibility.
2.	Introduced a delegate (`Action<string>`) and event (`RecipeExceedsCaloriesNotification`) in the `Recipe` class to notify the user when a recipe exceeds 300 calories.
3.	Added the ability to enter additional information for each ingredient, including the number of calories and the food group it belongs to. 
4.	Implemented a method (`CalculateTotalCalories`) in the `Recipe` class to calculate the total calories of all ingredients in a recipe, taking into account the quantity and calories of each ingredient.
5.	Included a unit test (`RecipeUnitTest`) to test the `CalculateTotalCalories` method and ensure its correctness.
6.	Updated the overall code structure and added comprehensive comments to improve readability and maintainability.

These changes enhance the functionality and user experience of the Recipe App, allowing users to manage multiple recipes, track ingredient details, and receive notifications for high-calorie recipes. The use of generic collections and a delegate-based event system improves code flexibility and extensibility. The addition of the unit test ensures the accuracy of the calorie calculation logic, providing increased reliability to the software.
