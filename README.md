 **Overview**
This project uses Python to automate the process of updating an IP address allow list. The program reads IP addresses from a text file, checks them against a list of IP addresses that should be removed, and updates the file by removing any matching addresses.

This project demonstrates basic Python programming concepts along with file handling techniques that can be useful in cybersecurity and system administration.

**What the Project Does**
The program:

Opens the allow_list.txt file.

Reads the IP addresses from the file.

Converts the file contents into a list.

Loops through a list of IP addresses that need to be removed.

Checks whether each IP address is in the allow list.

Removes matching IP addresses.

Converts the updated list back into a string.

Writes the updated list back to the file.

**Python Concepts Used**
Variables

Functions

Lists

for loops

if statements

with statements

File reading and writing

.read()

.split()

.remove()

.join()

open()

**Purpose**
This project demonstrates how Python can be used to automate a simple cybersecurity-related task. Maintaining an accurate allow list can help ensure that only approved IP addresses remain in the list.

**Skills Demonstrated**
Through this project, I practice using Python to work with files, lists, loops, conditional statements, and functions. I also demonstrate how automation can be used to manage and update data efficiently.
