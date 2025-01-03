## Variable

A variable is an element that holds data or values of a certain type. It serves the essential purpose of storing data and passing it between activities.

Variables in Studio are configured through four main properties. They are as follows:

- Name (mandatory)
- Variable-type (mandatory)
- Scope (mandatory)
- Default-value (optional)

### Best practices when working with variables:

- **Assign meaningful names**
  Meaningful names should be assigned to variables in order to accurately describe their usage in a project.
- **Follow a naming convention**
  To improve readability, variable names should also align to a naming convention. We recommend using the PascalCase naming convention. In this convention, the first letter of each word in a variable is capitalized.
  `Eg: First1Name2, First1Name`
- **Keep variables in the innermost scope**
- **Automatically generate variables from activity outputs**
  If the Auto-generate Activity Outputs design setting is enabled, Studio automatically populates each Output field of activities that generate an output with a variable. You can then use the generated variable in other activities by selecting the Plus button on the right side of the activity input fields and then Use Variable.

### There are four ways of creating variables in Studio:

- From the Data Manager
- From the Body of an Activity
- From the Properties Panel
- From the Variables Panel
