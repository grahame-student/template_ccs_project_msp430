# template_ccs_project_msp430
The following is a summary of the template project structure

```text
+-- .project
+-- .cproject
+-- .ccsproject
+-- .clang-format
+-- version.h.template
+-- build.bat
+-- format_code.bat
+-- lnk_msp430xxxxxx.cmd
+-- project.log
+-- <documentation>
|   +-- changelog.txt
|   +-- doxyfile
|   +-- HowToProgramDevice
|   +-- <Doxygen_Report>
|   +-- <Feature Documentation>
+-- <scripts>
|   +-- <setup_git_hooks>
+-- <src>
|   +-- main.c
|   +-- main.h
|   +-- module_1.c
|   +-- module_1.h
|   +-- <tests>
|       +-- main_test_runner.cpp
|       +-- module_1_feature_1_test.cpp
|       +-- module_1_feature_2_test.cpp
|       +-- module_1_wrapper.cpp
|       +-- module_1.wrapper.h
+-- <libs>
    +-- <lib1>
    |   +-- <tests>
    +-- <lib2>
    |   +-- <tests>
    +-- <libN>
        +-- <tests>
```

## Getting Started
* Use GitHub to create a new project from this template
* Clone the created project
* Run the setup script to configure git hooks (TODO)

## Populate the Project
The following is a summary of how to populate the project

### Copy project files to the root of the project
These should include
* .project
* .cproject
* .ccsproject
* lnk*.cmd

### Copy / add project source code to the `src` directory
This should include all `*.c` / `*.h` files

### Copy / add unit test code to the `src/tests` directory
This should include all test related `*.cpp` / `*.h` files

