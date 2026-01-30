# Core IDE - Native C++ Visual Development Environment

**Pure IDE** is a lightweight, high-performance Integrated Development Environment (IDE) built entirely from scratch using the native Windows API (Win32). It is designed to provide a Delphi/Visual Basic-like visual design experience for modern C++ development, without the bloat of heavy frameworks.

## 🚀 Key Features

*   **Native & Lightweight**: Built with pure C++ and Win32 API. No Electron, no .NET, no heavy runtime dependencies. Fast startup and low memory usage.
*   **Visual Form Designer**: Drag-and-drop interface for building Windows GUI applications. Support for standard controls:
    *   Buttons, Labels, Edit Boxes, Checkboxes, Radio Buttons
    *   ComboBoxes, ListBoxes, ListViews, TreeViews
    *   Progress Bars, Sliders, GroupBoxes
    *   Menus, TabControls, StatusBars, and more.
*   **Integrated Code Editor**: Powered by **Scintilla**, featuring:
    *   Syntax highlighting for C++.
    *   Line numbers and indentation guides.
    *   Real-time synchronization between the Visual Designer and generated C++ code.
*   **Live Property Inspector**: Inspect and modify component properties (Position, Size, Caption, Colors, Fonts) in real-time.
*   **Smart State Management**: Robust Undo/Redo system preserving project history (implemented with `std::deque` for efficiency).
*   **Compiler Support**:
    *   Seamless integration with **MinGW (g++)**.
    *   Support for **MSVC (Microsoft Visual C++ compiler)** via auto-detection.
    *   One-click Build & Run.
*   **Project Management**: Solution explorer-style file tree for managing project files and forms.
*   **IntelliSense-like Features**: Basic code completion and parsing improvements (ongoing).

## 🛠️ Built With

*   **C++17**: Core language.
*   **Win32 API**: Native GUI framework.
*   **Scintilla**: Code editing component.
*   **GDI+**: Advanced graphics rendering.

## 🎯 Goal

To demonstrate that powerful, modern, and user-friendly development tools can be created using pure, native technologies, offering maximum performance and control.
