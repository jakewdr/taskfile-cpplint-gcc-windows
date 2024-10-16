## Requirements

*GCC and other important C resources* = [link](https://installc.org/)

*Taskfile for command line scripts* = [link](https://taskfile.dev/installation/)

*Cpplint for linting* = [link](https://github.com/cpplint/cpplint?tab=readme-ov-file#installation)

### From the command line

Note this requires [python 3](https://www.python.org/downloads/) and [chocolatey](https://chocolatey.org/install) to be installed

    start https://tinyurl.com/install-c

    choco install go-task

    pip install cpplint

## Using the project

To compile the c file and run the executable simply enter the following into the command line:

    task run

This runs the compilation and linting automatically, you can check the separate scripts in the [taskfile.yml]("https://github.com/jakewdr/taskfile-cpplint-gcc-windows/blob/main/taskfile.yml") file
