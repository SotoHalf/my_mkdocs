# **Welcome to the C# Notes**
---
These notes are designed to be direct and practical, serving as a quick reference guide. At the same time, I can use them to document, expand and organize my knowledge.

On this website, we will cover all the basic and major aspects of the C# language.

## **Getting Started with C#**
---
Set up your environment to start developing with C#.

### **Installing C**#

To write and run C# code, you'll need to install .NET SDK, which includes everything required to develop and run C# applications.

#### 1. Install the .NET SDK

The .NET SDK provides the runtime and libraries necessary to build and run C# applications. Follow these steps to install the SDK:

1. Go to the official [.NET download page](https://dotnet.microsoft.com/download).
2. Select the version of .NET that is compatible with your system and click **Download**.
3. Run the downloaded installer and follow the on-screen instructions.
4. Once the installation is complete, open a terminal or command prompt and run the following command to verify the installation:

    ```
    dotnet --version
    ```

   This should return the version number of the installed SDK, confirming that the installation was successful.

#### 2. Install Visual Studio Code (Optional)

While you can write C# code in any text editor, Visual Studio Code (VS Code) is a lightweight, free, and highly popular option among developers. To install VS Code:

1. Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. Download the version that corresponds to your operating system.
3. Install the editor by following the instructions provided.

#### 3. Install the C# Extension in Visual Studio Code

If you choose to use Visual Studio Code, you'll also need to install the C# extension for full C# support:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
3. Search for "C#" and install the **C# extension** by Microsoft.

### **Verifying the Installation**

To confirm that everything is set up correctly, follow these steps:

1. Open a terminal or command prompt.
2. Create a new C# console application by running the following command:

    ```
    dotnet new console -n HelloWorld
    ```

   This command will generate a simple "Hello World" program in a new folder named `HelloWorld`.

3. Navigate to the new project directory:

    ```
    cd HelloWorld
    ```

4. Run the application:

    ```
    dotnet run
    ```

   You should see the output:

    ```
    Hello World!
    ```

This confirms that your C# development environment is set up correctly.