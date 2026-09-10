Class reflection – CSC360

Date: 8 September 2026

Introduction

In our last class, we continued learning Java Graphics and how a graphical application is interacted with a user. The topics we discussed in the class included events and their connection with graphics, event handling, view and wrapper, Grid Layout, sliders and dialogue boxes. These topics helped me understand that to create a graphical application is not only about showing objects on the screen. We also need to make sure that graphical application works fine when the user interacts with it.

Events and Graphics

We first discussed how events are connected with graphics. An event is an action that is taken place when the user or the system does something. In a graphical application, actions like clicking a button, moving the mouse, pressing a key or changing a value can be a source of event.

For example, if we create a game with a Start button, clicking the button starts the game. The click is an event and starting the game is the response it can elicit.

User Action Event Possible Response

Click a button Button event Perform a particular action

Move the mouse Mouse event Move or change an object

Press a key Keyboard event Perform a specific task

Change a value Value change event Update something on the screen

This helped me understand that graphics can be interactive. The objects shown on the screen can change or respond depending on what the user does.

Event Handling

We then discussed event handling. The event handling means deciding what the program should do when a particular event comes. Not only detecting an event but it is also needed that program has instructions of handling that event.

For example, when we click a button, the program knows what should happen after the click. It can open another part of the application, display a message or perform some other task.

A simple flow that I understood from this concept is:

User Action → Event → Event Handler → Response

A real-life example could be a lift. When we press the button for 3rd floor, pressing the button is the action, the button press turns into an event and the lift moves to the selected floor is the response.

Similarly, in a graphical application, event handling connects the user’s action with the required response from the program. I found this topic important as it explains how applications become interactive instead of just display information.

View and Wrapper

Another topic discussed in the class was view and wrapper. I understood that the view is related to what is shown to the user on the screen. A wrapper can be used to contain or manage another component.

For example, a graphical interface may contain different components like buttons, text fields, sliders and other controls. These components need to be placed and managed properly so that the interface works smoothly.

This topic helped me understand that while designing a graphical application, we also need to think about how different components are organized and how they are connected with the visible part of the application.

Grid Layout

We also learned about Grid Layout. Grid Layout is used to arrange different components in the form of rows and columns. It provides a simple and organized way to place multiple components on the screen.

For example, the buttons of a calculator can be arranged like this:

7 8 9

4 5 6

1 2 3

0 + =

Here, every component gets a proper position in the grid. This makes the interface easier for the user to understand.

I found this concept useful because if we have many components on the screen, placing them randomly can make the application confusing. With Grid Layout, it is possible to get a proper structure for the design.

Slider

Another component we discussed was the slider. A slider allows the user to select or change a value by moving a control from one position to another.

For example:

Low ───────── ● ───────── High

A slider can be used in many applications. Some examples are:

Example Use of Slider

Music player Adjust volume

Computer settings Adjust brightness

Editing application Change a particular value

Application settings Select a value from a range

I found the slider easy to understand as I have already seen it in many applications. For example, while watching a video or listening to music, we can use a slider to control the volume or move to a particular part of the video.

Dialogue Box and Its Use

We also discussed dialogue boxes and why we use them. A dialogue box is a small window that is used to communicate something to the user or take input or confirmation from them.

For example, when we try to delete something, an application may show a message such as:

Are you sure you want to delete this?

It can then give us options such as Yes and No.

Dialogue boxes can be useful in different situations:

Situation Purpose of Dialogue Box

Deleting something Ask for confirmation

An error occurs Display an error message

Information is required Take input from the user

An important action is performed Ask the user to confirm

I understood that dialogue boxes are useful when the program needs the user’s attention or needs a response before continuing. They can prevent accidental actions and make communication between the application and the user easier.

Connection Between the Topics

After discussing all these concepts, I understood that they are connected to each other while creating an interactive graphical application. First, we have different graphical components on the screen. The user interacts with these components, which creates events. Event handling decides what the program should do in response.

For example:

Component → User Interaction → Event → Event Handling → Response

A button can generate an event when it is clicked, a slider can generate an event when its value is changed and other graphical components can also respond to different user actions.

This made me understand that a good graphical application should not only look organized but should also respond correctly to the user.

My Learning from the Session

The most useful part of this session for me was understanding the connection between graphics and user interaction. Before learning about events, I mainly thought that graphics were related to drawing shapes and displaying things on the screen. Now I understand that interaction is also an important part of graphics programming.

The real-life examples of calculators, music players, computer settings and confirmation messages made these concepts easier to understand. I could relate the things discussed in class to the applications that I use in everyday life.

Overall Reflection

Overall, this session gave me a better understanding of how different components are used to create an interactive graphical application. I learned how events are generated, how event handling is used to respond them and how components such as Grid Layout, sliders and dialogue boxes are useful in an interface. I especially found event handling interesting as it explains how a program responds when the user performs an action. The session also made me realize that designing an application is not only about its appearance; we also need to think about how easily the user can interact with it.
