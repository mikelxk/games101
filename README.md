# Games101 Homework
Games101 Homework setup with VSCode , vcpkg and CMake.
## Environment Setup
1. Install [vcpkg](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started-vscode)
2. Install [CMake](https://cmake.org/install/) and add to PATH
3. Install [C++ extension in VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
4. Install [CMake Tools extension in VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
5. Select corresponding CMake config using `Ctrl+Shift+P` -> `CMake: Configure`
7. Go to `CMake: PROJECT OUTLINE` to debug the project
6. For mac user, add `"miDebuggerPath": "${extensionInstallFolder:ms-vscode.cpptools}/debugAdapters/lldb-mi/bin/lldb-mi"`
in `"cmake.debugConfig"` in `settings.json` to make lldb work.