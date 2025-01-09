## Control flow

Control flow is one of the fundamental concepts in programming that governs how activities are executed in a process or workflow.

For an Automation Explorer, it's recommended to have a solid understanding of the different types of control flow statements available in UiPath Studio, including If, While, Do While, For Each, and Switch.

Control flow is the order in which activities are executed or evaluated in a software project. 
In UiPath Studio, there are two concepts through which the control flow is carried out: the workflow layouts and the control flow statements.

### Control Flow are used in two ways:

- Workflow layouts
- Control flow statements

### Workflow layouts

**Workflow layouts** there are four predefined workflow layouts: Sequence, Flowchart, State Machine, and Global Handler.

In **Sequences**, the steps of a process execute in a clear sequential succession. Decision trees are rarely used. Activities in sequences are easier to read and maintain, and thus they're highly recommended for simple, linear workflows.
For example, you can create a sequence to type into a browser search, click search, click on the first result, and scrape any data from that webpage. As another example, you can create a sequence that automates repetitive tasks such as copying files from one folder to another, sending emails, or creating reports.

In **Flowcharts**, the individual activities are a bit more difficult to read and edit, but the execution flow between them is much clearer. For scenarios and decision mechanisms that require complex decision points and branches, it's best to use flowcharts.

Onboarding new employees is one example of how a flowchart could be used. The flowchart can include activities such as creating new user accounts, assigning roles and permissions, setting up email accounts, and providing training resources. It might involve some decision-making activities, such as verifying the new employee's information or determining the appropriate roles and permissions to assign to them.

### Control flow statements

**Control flow statements** these are activities and methods that determine the decisions made during the execution of a workflow.

The conditional, also known as decision-making activities, such as If, Else If, and Switch.

Loops such as While, Do While, and For Each.
