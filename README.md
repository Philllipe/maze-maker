<h1 align="center">Maze Maker ✏️</h1>

## About The Project

This was a university project for CAB302 Software Development. The project was to create an application to assist designers in creating mazes for publication in digital or print media. Creating mazes was done by a user drawing walls on a grid, with support for other functionalities and solving mazes was done by the application using a depth-first search algorithm. The project is old and the code is most definitely a mess with many bugs and errors as was done in my early days of programming. The project was built using Java and Swing for the GUI. The project also used MariaDB for storing mazes and their solutions.

## Technologies Used

- Java
- Swing
- JUnit
- [MariaDB](https://mariadb.org/)

## Getting Started

The project was built using IntelliJ IDEA. As this project is quite old and I am not the most experienced with Java, I only know how to run it through IntelliJ IDEA. The project was built with Maven. To run the project, you will need to have [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) and [MariaDB](https://mariadb.org/download) installed on your machine. The project may not work with newer or older versions of Java.

1. Clone the repository

```bash
git clone https://github.com/Philllipe/maze-maker.git
```

2. Edit the `src/MazeMaker/db.props` file to match your MariaDB configuration.
3. Make sure the MariaDB server is running and make a new database called `mazeco`.
4. Open the project in IntelliJ IDEA.
5. In the Project Structure, add the `mariaDB-java-client-3.0.5.jar` file to the Module Dependencies.
6. Run the `Main` class.

## Demonstration
https://github.com/user-attachments/assets/bf99cd26-5936-4757-a84e-d2c61665160a

