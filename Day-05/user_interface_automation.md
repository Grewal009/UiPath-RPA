## User Interface (UI) Automation with Modern Design in Studio

In today's digital world, user interfaces play a crucial role in delivering seamless user experiences. However, manually interacting with UIs can be tedious and time-consuming. This is where UI automation comes in.

As an automation explorer, it's essential to have knowledge of the core components of UI automation, such as UI Automation activities, Activity properties, Targeting methods, Input and Output methods, as well as Recorders and Scraping Wizards in UiPath Studio.

## Overview of UI Automation

### What's UI automation?

UI automation automates interactions with graphical user interface elements in software apps, saving time and minimizing errors. This is done by using robots that perform tasks in the same way as a human user, making it easier to automate complex business processes and repetitive tasks.

### How should I get started with UI automation? 

Automation developers need to design actions logically to ensure robots perform actions through application user interfaces (UIs) just like humans would. This is similar to building a house, where each action must be taken in order, and the result is dependent on all of those actions being done correctly and in the correct order.

The first step is to lay out the human path and ensure the automation replicates the user experience accurately. This approach guarantees that the automation process is efficient and effective, while also identifying errors that might be missed during development.

For example: to automate the task of entering a value in the input field of the 'Double UI' application, we must first open the application and type the desired value into the 'Cash In' field.

### The key concepts of UI Automation are:

1.  UI Automation activities
2.  Activity properties
3.  Targeting methods
4.  Input and output methods
5.  Recorders
6.  Extraction Wizard
7.  The object repository
8.  AI Computer Vision

#### Activities (What to do):

Activities tell the Robot what to do. You can find them in the Activities panel and they are of four types:

- **Containers** - Select a specific app or browser
- **Input** - Send input to an app interface
- **Output** - Get output from an app interface
- **Synchronization** - Control your process flow based on the states of UI Elements (e.g. do something when an UI Element appears)

#### Properties (How to do it):

Properties control how the Robot executes an activity. Here you can control if you want the Robot to wait before or after executing the activity, what element to execute the activity on, how much to wait if it cannot find the element and so on.

#### Targeting Methods:

The targeting methods help the robot to identify the correct UI element to perform the action.

#### Input and Output Methods:

Input and output methods tell the Robot what technology to use to send input to or get output from an interface. They can make a huge difference in terms of how reliable your UI Automation is, how fast it works, and most importantly, if it can run only on a foreground window or a background window too.

**Recorders**

The Recorders will help you develop UI Automation much faster by following your manual interaction with a GUI step by step and translating it into a sequence of Studio activities.

**Extraction Wizards**

Scraping wizards help you extract structured data automatically.

**The Object Repository**

The Object Repository is a more advanced feature, but it's useful to know about it early. It allows developers to store UI Element identifiers in a repository, fine-tune them and share them with colleagues for much faster UI Automation development and project update.

**AI Computer Vision**

AI Computer Vision is an AI skill that enables all UiPath Robots to see every element on a computer screen. This is a more advanced feature.

### Interaction between key concepts in UI automation: 

An application's interface requires coordination between these key concepts to execute an action. The diagram below provides a brief overview.
[diagram]()

- **Targeting methods**: determine which elements in the UI to interact with.

- **UI Automation activities**: perform the required actions on the targeted UI elements.

- **Activity properties**: configure the behavior of the UI Automation activities.

- **Input and output methods**: provide data to and receive data from the UI elements.

### Summary

**UI automation** in UiPath involves using a combination of key concepts including UI automation activities, activity properties, targeting methods, input and output methods, recorders and wizards, the object repository, and AI Computer Vision.

**UI automation activities** can be containers, input, output, or synchronization activities, and activity properties determine how the Robot performs an action.

**Targeting methods** provide several ways to identify the UI element the Robot will be interacting with.

**ßInput and output methods** define the type of technology used in interacting with UI elements, with output methods used to extract data from a UI element.

**Recorders and wizards** allow easy capturing and translation of user actions on the screen into sequences.

**The Object Repository** provides management, reusability, and reliability of UI elements by capturing them as objects in a repository.

Finally, **AI Computer Vision** uses artificial intelligence to identify and interact with UI elements that may be difficult to target with traditional methods.
