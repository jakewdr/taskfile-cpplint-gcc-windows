## Requirements

*GCC and other important C resources* = [link](https://www.mingw-w64.org/)

*Taskfile for command line scripts* = [link](https://taskfile.dev/installation/)

*Cpplint for linting* = [link](https://github.com/cpplint/cpplint?tab=readme-ov-file#installation)

*Ccache for recompile cache* = [link](https://ccache.dev/download.html)

*UPX for compressed binaries* = [link](https://upx.github.io/)

### From the command line

Note this requires [python 3](https://www.python.org/downloads/) and [chocolatey](https://chocolatey.org/install) to be installed, furthermore make sure you are in an elevated terminal

    choco install mingw

    choco install go-task

    choco install ccache

    choco install upx

    pip install cpplint

## Using the project

To compile the c file and run the executable simply enter the following into the command line:

    task run

This runs the compilation and linting automatically, you can check the separate scripts in the [taskfile.yml]("https://github.com/jakewdr/taskfile-cpplint-gcc-windows/blob/main/taskfile.yml") file
