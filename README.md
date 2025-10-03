The application functions by prompting the user for input (a note title, note content, and a to-do item) and then processes the data.

Go Concepts Demonstrated:
Custom Structs: Uses dedicated structs (Note and Todo) to model real-world data entities.

Interfaces for Polymorphism: Implements saver and outputtable interfaces. This allows the core functions (outputData and saveData) to work uniformly with both the Note and Todo structs, highlighting Go's approach to polymorphism.

Modular Design: Code is organized into multiple packages (e.g., note, todo, and main) to ensure clean separation of concerns and enhance reusability.

Command Line I/O: Utilizes the standard bufio and fmt packages for robust handling of string-based user input from the terminal.

Basic Error Handling: Incorporates checks to gracefully handle errors during application execution and object creation.
