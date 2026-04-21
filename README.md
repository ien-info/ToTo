## ToTo Language v1.0: Official Release Description

ToTo is a lightweight, human-readable scripting language designed for beginners, educators, and hobbyists. It bridges the gap between simple logic and the powerful Windows PowerShell engine, wrapped in an easy-to-understand syntax.

### Core Concept

ToTo operates by translating intuitive keywords into optimized PowerShell commands. This allows developers to create interactive console games, automate tasks, and trigger Windows GUI elements without learning complex programming structures.

### Key Features

-   Intuitive Syntax: Replaces cryptic code with natural verbs like `Show`, `Ask`, and `Set`.
    
-   Dynamic Variables: Supports memory storage using the `Set` and `Ask` commands for real-time user interaction.
    
-   Visual Feedback: Built-in support for terminal colors (`Red`, `Green`, `Blue`, `Yellow`) and ASCII graphics (`DrawStar`, `DrawLine`).
    
-   Windows Integration: Native support for System Beeps and GUI Message Boxes (Popups) via the Presentation Framework.
    
-   IDE Support: Includes a dedicated VS Code Extension for custom syntax highlighting and `.tt` file association.
    

### Command Glossary (v1.0)

**Command**

**Description**

**Example**

`Show`

Outputs text to the console.

`Show "Hello ToTo" Green`

`Ask`

Captures user input into a variable.

`Ask PlayerName`

`Set`

Assigns a value to a variable.

`Set Score 100`

`Popup`

Displays a Windows Message Box.

`Popup "Game Over"`

`Wait`

Pauses execution for $n$ seconds.

`Wait 2`

`Clear`

Clears the terminal screen.

`Clear`

`Beep`

Plays a system notification sound.

`Beep`

### Technical Specifications

-   Backend: Rust (High-performance compiler)
    
-   Interpreter: PowerShell 5.1/7.x Core
    
-   File Extension: `.tt`
    
-   Platform: Windows 10/11
    
-   Developer: Thwin & Gemini Collaboration
    

> Developer Note: ToTo v1.0 focuses on the "Foundation of Interaction." It is designed to be portable, requiring only the `toto.exe` binary to interpret and run any `.tt` script.
