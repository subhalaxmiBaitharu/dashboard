Overview
This project is a dynamic dashboard that allows users to manage and customize widgets in various categories. The dashboard is built using React and utilizes a JSON configuration to define the structure of categories and widgets. Users can dynamically add, remove, and update widgets in different categories.

Features
Dynamic JSON Configuration: The dashboard structure is built based on a JSON configuration that contains categories and their respective widgets.
Add/Remove Widgets: Users can dynamically add new widgets to any category or remove existing ones.
Customizable Categories: Categories such as "CSPM Executive Dashboard" are configurable, and users can add or remove widgets from these categories.
Widget Content Management: Each widget contains random placeholder text that can be modified when new widgets are added.
Interactive User Interface: Users can manage widgets using intuitive UI controls like an "Add Widget" button, which prompts users to enter widget details, and a cross (X) icon to remove widgets.


Here’s a sample README file for your dynamic dashboard project:

Dynamic Dashboard Project
Overview
This project is a dynamic dashboard that allows users to manage and customize widgets in various categories. The dashboard is built using React and utilizes a JSON configuration to define the structure of categories and widgets. Users can dynamically add, remove, and update widgets in different categories.

Features
Dynamic JSON Configuration: The dashboard structure is built based on a JSON configuration that contains categories and their respective widgets.
Add/Remove Widgets: Users can dynamically add new widgets to any category or remove existing ones.
Customizable Categories: Categories such as "CSPM Executive Dashboard" are configurable, and users can add or remove widgets from these categories.
Widget Content Management: Each widget contains random placeholder text that can be modified when new widgets are added.
Interactive User Interface: Users can manage widgets using intuitive UI controls like an "Add Widget" button, which prompts users to enter widget details, and a cross (X) icon to remove widgets.
JSON Structure
The dashboard's categories and widgets are dynamically generated from a JSON file. Below is an example of the JSON structure:


Explanation
categories: An array of categories in the dashboard.
categoryName: The name of the category (e.g., "CSPM Executive Dashboard").
widgets: An array of widgets within each category.
widgetName: The name of the widget.
widgetText: Placeholder text that can be displayed within the widget.
User Interactions

Adding a Widget:
Users can click on the "+Add Widget" button to open a form.
The form allows the user to input:
Widget Name
Widget Text
The newly created widget is added to the selected category.

Removing a Widget:
Each widget has a cross (X) icon in the top-right corner.
Clicking this icon will remove the widget from its category.

Adding/Removing Widgets via Category Management:
Users can manage widgets in a category through an "Add Category" section.
This section allows users to check/uncheck widgets from a list to add or remove them from a category.


Here’s a sample README file for your dynamic dashboard project:

Dynamic Dashboard Project
Overview
This project is a dynamic dashboard that allows users to manage and customize widgets in various categories. The dashboard is built using React and utilizes a JSON configuration to define the structure of categories and widgets. Users can dynamically add, remove, and update widgets in different categories.

Features
Dynamic JSON Configuration: The dashboard structure is built based on a JSON configuration that contains categories and their respective widgets.
Add/Remove Widgets: Users can dynamically add new widgets to any category or remove existing ones.
Customizable Categories: Categories such as "CSPM Executive Dashboard" are configurable, and users can add or remove widgets from these categories.
Widget Content Management: Each widget contains random placeholder text that can be modified when new widgets are added.
Interactive User Interface: Users can manage widgets using intuitive UI controls like an "Add Widget" button, which prompts users to enter widget details, and a cross (X) icon to remove widgets.
JSON Structure
The dashboard's categories and widgets are dynamically generated from a JSON file. Below is an example of the JSON structure:

json
Copy code
{
  "categories": [
    {
      "categoryName": "CSPM Executive Dashboard",
      "widgets": [
        {
          "widgetName": "Widget 1",
          "widgetText": "Random text for Widget 1"
        },
        {
          "widgetName": "Widget 2",
          "widgetText": "Random text for Widget 2"
        }
      ]
    },
    {
      "categoryName": "Security Metrics",
      "widgets": [
        {
          "widgetName": "Security Widget 1",
          "widgetText": "Random text for Security Widget 1"
        }
      ]
    }
  ]
}
Explanation
categories: An array of categories in the dashboard.
categoryName: The name of the category (e.g., "CSPM Executive Dashboard").
widgets: An array of widgets within each category.
widgetName: The name of the widget.
widgetText: Placeholder text that can be displayed within the widget.
User Interactions
Adding a Widget:

Users can click on the "+Add Widget" button to open a form.
The form allows the user to input:
Widget Name
Widget Text
The newly created widget is added to the selected category.
Removing a Widget:

Each widget has a cross (X) icon in the top-right corner.
Clicking this icon will remove the widget from its category.
Adding/Removing Widgets via Category Management:

Users can manage widgets in a category through an "Add Category" section.
This section allows users to check/uncheck widgets from a list to add or remove them from a category.
