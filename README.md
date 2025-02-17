# Games101 Homework
Games101 Homework super easy setup with VSCode , vcpkg and CMake. Use this template or dire ctly on in Codespace to get started!
## Environment Setup
1. Install [vcpkg](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started-vscode)
2. Install [CMake](https://cmake.org/install/) and add to PATH (Optional?)
3. Install [Ninja](https://ninja-build.org) if you are using Mac or Linux
4. Install [C++ extension in VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
5. Install [CMake Tools extension in VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
6. Make sure `"VCPKG_ROOT"` is added to your path
7. Select corresponding CMake config using `Ctrl+Shift+P` -> `CMake: Configure`, for mac and linux use ninja, for windows use vs
8. Go to `CMake: PROJECT OUTLINE` to debug the project
9. For Mac users, add `"miDebuggerPath": "${extensionInstallFolder:ms-vscode.cpptools}/debugAdapters/lldb-mi/bin/lldb-mi"`
 in `"cmake.debugConfig"` in `settings.json` to make lldb work.

## Thanks
Thank @endingly for the port for cgl