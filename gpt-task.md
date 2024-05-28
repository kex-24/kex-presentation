# Spotify Playlist Manager

### Deadline
This work should be completed before the next exercise session.

### Instructions
Please see the assignments section of the course instructions for how to do and submit this assignment.

### Preparation

- Read and answer all questions in Module 2: Looking Inside Classes.
- Access the OLI material through Canvas or the provided webpage.

**Note:** The OLI material and tasks might not align perfectly this year, so feel free to explore upcoming sections if needed.

### Learning Goals

This week you will practice:
* Designing Java classes for a specific purpose
* Adding instance variables to a class
* Creating a constructor method
* Implementing *getters* and *setters* for class fields
* Object interaction using the dot operator
* Outputting data to the terminal
* Utilizing the `main` method effectively
* Understanding scope and variable shadowing

### Troubleshooting Guide

Follow this approach for any questions or problems:

1. Check this week's posted issues to see if other students have encountered the same problem.
2. If not, create a new issue with a descriptive title.
3. Ask a TA for help during the weekly lab session.

Collaboration is encouraged, but **do not share answers**.

### Assignment

Imagine you are creating a simple playlist manager for Spotify users. Users can create playlists, add songs, and display playlist contents.

#### Exercise 1: Create the Song Class

Create a new Java file named `Song.java` in the `src` folder. Define the `Song` class within it, and add the following fields:

- `String` title
- `String` artist
- `int` duration (in seconds)
- `String` album

#### Exercise 2: Define a Playlist Class

In another file, `Playlist.java`, define the `Playlist` class with the following:

- A name for the playlist
- A list (use an `ArrayList` for this) to store songs

#### Exercise 3: Constructors

Add constructors to both your `Song` and `Playlist` classes to initialize the objects with provided values. For the `Playlist`, initialize the list and set its name.

#### Exercise 4: Getters and Setters

For both classes, create *getters* and *setters* for all fields. Remember the boolean conventions for getters (`is` instead of `get`).

#### Exercise 5: Adding Songs to Playlists

In the `Playlist` class, implement a method `addSong()` that takes a `Song` object and adds it to the playlist's song list.

#### Exercise 6: Displaying Playlist Contents

Implement a method in the `Playlist` class that prints all the songs in the playlist, showing title, artist, and duration in a readable format.

#### Exercise 7: Main Method Testing

In a separate `Main.java` file, demonstrate the creation of a `Playlist`, add a few songs to it, and then display its contents.

#### Exercise 8: Enhancing Song Information

Add a method to the `Song` class that converts the duration from seconds into a more readable format (minutes and seconds) and include this in the playlist display output.

### Checklist
- Create the `Song` and `Playlist` classes with relevant fields.
- Implement constructors for instantiating your objects.
- Write getters and setters for managing field access.
- Add functionality for adding songs to a playlist.
- Implement playlist content display functionality.
- Convert song duration from seconds to minutes and seconds in display output.

### Bugs and Errors
If you find any inconsistencies or errors in this exercise, please open a new issue with the title "Error: summary of the error". Reported bugs will be acknowledged in the acknowledgments section.