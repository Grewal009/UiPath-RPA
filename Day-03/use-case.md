### Use-case

Create a project that asks for the user’s full name, store it and display only the first letter of the full name. Ask for the year of birth as well and calculate the age. Display the name and age in a window. At the same time, write the result of the execution to the Output Panel.

[Solution: outline](https://github.com/Grewal009/UiPath-RPA/blob/main/Day-03/outline2.jpg)
[Main Sequence](https://github.com/Grewal009/UiPath-RPA/blob/main/Day-03/outline-sequence.jpg)

hint - `Username.Split(" "c)(0) +" you are "+ (DateTime.Now.Year - BirthYear).ToString()+ " years old.`
