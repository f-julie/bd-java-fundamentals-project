# Sprint 2 Module 1

### AppSettings Update
Go to `AppSettings` and update the `story` to `S2M1_TestDirections`.

## Properties
A property is a place to store a value. For example, the property `age` can store a value like `30`. Then you can reference that value by simply stating `aga`. If you need to change the `age` because it's the person's birthday, you can simply assign a new value (`31`) to the property.

## Working Classes
We will be working with the following class:
- Player

## Player
Player is a class that has been built out considerably, but there are some new properties that we want to add as well as some methods to access the properties. 

### Name

The first property to add is `name`. This property will hold a `String` and we don't want outside classes to have direct access to it, so make it `private`. 

With that property in place, we can now write the getter and setter methods for `name`. They are called `getName` and `setName`. The methods are already defined, but they don't do anything (at the moment). Read the comments above each method to see what the requirements are and write the code to complete the requirements. 

### Arithmetic in Code
The last thing you'll need to do is calculate if the player can open a door (the doors are heavy). Find the method `canOpenDoor` and read the comments to find out how to validate if the player can open doors. 

##Testing
To run the tests for this assignment, run the following:

`./gradlew test --tests com.adventure.sprint2.S2M1Test`

or by right-clicking the `S2M1Test` file and selecting "Run 'S2M1Test'"

You can run the game by going to the `Main` class and clicking on the run icon to the left of the `main()` method.