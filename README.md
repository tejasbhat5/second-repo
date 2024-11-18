Java Hello World Program

This is a basic Java program that demonstrates how to print "Hello, World!" to the console.
Prerequisites

Before running this program, ensure you have the following installed:

    Java Development Kit (JDK): You can download the JDK from Oracle's official website or use an open-source version such as OpenJDK.

    Text Editor or IDE: Any text editor (e.g., Visual Studio Code, Sublime Text) or an Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or NetBeans.

Steps to Run the Program

    Create a Java File
    Create a new file with the name HelloWorld.java.

    Write the Code
    Open the file in your text editor or IDE and add the following Java code:

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

Save the File
Make sure to save the file with the .java extension (i.e., HelloWorld.java).

Compile the Program
Open your command line or terminal and navigate to the directory where the HelloWorld.java file is saved. Run the following command to compile the Java program:

javac HelloWorld.java

This will create a file named HelloWorld.class in the same directory.

Run the Program
After compiling, run the program using the java command:

java HelloWorld

Output
You should see the following output in your terminal or command prompt:

    Hello, World!

Explanation

    public class HelloWorld: This is the declaration of the HelloWorld class. Every Java program must have at least one class.
    public static void main(String[] args): The main method is the entry point for any Java application. It’s where the program starts executing.
    System.out.println("Hello, World!");: This statement prints the text "Hello, World!" to the console.

Troubleshooting

    Error: javac: command not found
    Make sure Java is installed properly. Check the installation by running java -version and javac -version in your terminal. If these commands don't work, you may need to install or configure the JDK properly.

    Error: Could not find or load main class HelloWorld
    Ensure the filename matches the class name exactly (Java is case-sensitive). Also, ensure you’re in the correct directory where the .class file is located.

Additional Resources

    Official Java Documentation
    Java Tutorials by Oracle

This README provides the necessary steps and instructions to successfully write, compile, and run a simple "Hello, World!" program in Java.

 

