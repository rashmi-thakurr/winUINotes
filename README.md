# WinUINotes

A simple note-taking application built with .NET 8 and WinUI. WinUINotes allows you to create, view, save, and delete notes with a modern Windows user interface.

## Features

- **Create Notes:** Write and save new notes easily.
- **View All Notes:** Browse all your saved notes in a clean, organized layout.
- **Edit Notes:** Update the content of existing notes.
- **Delete Notes:** Remove notes you no longer need.
- **Persistent Storage:** Notes are saved locally using the Windows Storage API.
- **Modern UI:** Built with WinUI for a native Windows 11 look and feel.

## Getting Started

### Prerequisites

- Windows 10 version 19041 (20H1) or later
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with the **Universal Windows Platform development** workload

### Installation

1. **Clone the repository:**
  
2. **Open the solution in Visual Studio 2022.**

3. **Restore NuGet packages** (Visual Studio will usually do this automatically).

4. **Build and run the project** (F5 or Ctrl+F5).

## Project Structure

- `WinUINotes/Models/Note.cs`  
Represents a single note, with methods for saving and deleting notes from local storage.

- `WinUINotes/Models/AllNotes.cs`  
Manages a collection of notes and loads them from storage.

- `WinUINotes/Views/NotePage.xaml` & `NotePage.xaml.cs` 
The UI and logic for creating, editing, and deleting a single note.

- `WinUINotes/Views/AllNotesPage.xaml` & `AllNotesPage.xaml.cs` 
The UI and logic for displaying all notes.

- `WinUINotes/MainWindow.xaml` & `MainWindow.xaml.cs`  
The main application window and navigation host.

- `WinUINotes/App.xaml`  
Application entry point and configuration.

## Usage

- **Add a Note:** Click the "New note" button, enter your text, and click "Save."
- **View Notes:** All saved notes are displayed in the main view.
- **Edit a Note:** Select a note, modify its content, and click "Save."
- **Delete a Note:** Select a note and click "Delete."

## Technologies Used

- [WinUI 3](https://learn.microsoft.com/en-us/windows/apps/winui/winui3/)
- C#
- XAML

*Created with ❤️ using WinUI.*
