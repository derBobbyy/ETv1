
# ETv1

A library with many possibilities that, among other things, allow you to develop applications faster

[last release](https://github.com/derBobbyy/ETv1/releases/latest)
## Features

- Various predefined variables
- All variables can be saved with the `Save` function
- Simplified console commands
- Lots of storage options
- Lots of simplified MessageBox options
- Simple Open and SaveFileDialogs


## 

The commands listed below are not all commands that are available.

Simple console commands
```csharp
  C_Clear()                  // Clears the console
  C_DateTime()               // Writes the current date and time to the console
  C_Void()                   // Writes an empty line to the console
  C_WriteLine(string Text)   // Writes a line to the console
  C_Write(string Text)       // Write something to the console
```

Simple save commands
```csharp
  Save_String1(string String)// Stores a string so that it is retained after the program is closed and restarted
  Save_String2(string String)// Stores a string so that it is retained after the program is closed and restarted
  Save_String3(string String)// Stores a string so that it is retained after the program is closed and restarted
  Save_String4(string String)// Stores a string so that it is retained after the program is closed and restarted
  Save_Int1(int Int)         // Stores a int so that it is retained after the program is closed and restarted
  Save_Int2(int Int)         // Stores a int so that it is retained after the program is closed and restarted
  Save_Int3(int Int)         // Stores a int so that it is retained after the program is closed and restarted
  Save_Int4(int Int)         // Stores a int so that it is retained after the program is closed and restarted
```

Simple MessageBox command
```csharp
  // Shows a MessageBox with the given information
  MSGBox(string msgbText, string msgbTitle, int msgbType) 
```

Simple dialogues
```csharp
  // Shows a MessageBox with the given information
  D_OpenFile(OpenFileDialog openFileDialog, string Title)
  D_SaveFile(SaveFileDialog saveFileDialog, string Title)
```


## Authors

- [@derBobbyy](https://github.com/derBobbyy)
- [EXUDUS Studio]( )

