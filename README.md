# OS-Project
Objective: The goal of this project is to give students hands-on experience with the processes, methods, 
and system calls commonly used in modern operating systems. By the end of the project, students will 
have created a custom shell that can execute basic commands related to file systems management, 
handle I/O operations, and implement basic scheduling. 
Custom Shell Development 
In file systems management, command parsing is crucial for interpreting and executing file-related 
operations. Implement a shell that can parse and execute basic commands for the following: 
 File Operations: Develop the commands to: 
o create <file_name>: create a new file 
o delete <file_name>: delete an existing file 
o rename <old_name> <new_name>: Rename a file  
 Directory Management: Develop the commands to: 
o make <dir_name>: create a new directory 
o remove <dir_name>: delete a directory 
o change <dir_name>: change the current working directory 
 File Access and Permissions: Develop the commands to: 
o modify <permissions> <file_name>: modify file permissions  
o list -l: display file attributes 
You have full control over the naming of shell commands. 
Additional Requirements 
 Allow the shell to handle and manage environment variables and implement I/O redirection 
(e.g., >, <) and piping (|). The shell should also have built-in commands like help and exit.  
 Include error handling for invalid commands and arguments. Within a documentation document 
provide specific syntax and examples for each command. 
 Students should include a set of test cases demonstrating the shell's functionality. These should 
cover various scenarios, including edge cases, to validate that the shell works as intended under 
different conditions. 
 Use of version control systems like Git to document the contributions of each member. Include 
evidence of version control usage in the report, such as a link to the repository or a summary of 
commits. 
 Each group presents their shell and explains the design choices, challenges faced, and how they 
addressed them. 
Deliverables 
Your shell should interface with OS-level functionality by translating user commands into system calls 
that perform the actual work. It should manage process creation and execution, file system operations, 
and handles input/output redirection and piping. Through your scripting and environment management, 
the shell must provide a powerful interface for users to interact with the operating system and 
automate tasks. Deliverables required 
1. Group Submission: Submit the complete code for the shell. 
Page 1 of 3 
2. Report: A detailed report documenting the shell's features, architecture, design decisions, and 
how it interfaces with OS-level functionality. Include a user guide and system requirements. 
3. Live Demonstration: A live demonstration showcasing the shell's capabilities.  
The project should be done in groups with NO MORE than five (5) students per group. Failure to do so 
will result in a 5-point reduction. Late submission: 10% per day. After three days will not be accepted 
Assessment Criteria 
1. Functionality: How well the shell implements the required features (file operations, directory 
management, I/O redirection, piping, environment variables, and error handling). 
2. Code Quality: Code readability, structure, commenting, adherence to coding standards, and 
effective use of system calls. 
3. Team Collaboration: How effectively the team worked together, as evidenced by version control 
contributions and peer reviews. 
4. Documentation: Clarity, completeness, and organization of the report, including a user guide, 
system requirements, and evidence of testing.  
5. Team Collaboration: Effectiveness of team collaboration as evidenced by version control 
contributions, peer reviews, and group dynamics during the project. 
6. Presentation & Demo: Quality and clarity of the live demonstration, ability to answer questions, and 
the overall presentation of the project.
