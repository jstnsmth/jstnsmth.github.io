---
layout: project
type: project
image: img/bankdb/bank.jpg
title: "Bank Database"
date: 2023
published: true
labels:
  - File-Based Database
  - Backend Development
  - C
summary: "Banking database system written in C that mangages customer records and maintains data persistence using text files."
---

<div class="text-center p-4">
  <img width="700px" src="../img/bankdb/bankinterface.PNG" class="img-thumbnail">
</div>

This is a banking system that keeps track of customer records using a text file for storage. The program lets users add, delete, print, and find records with each record containing the customer's name, address, and account number. The records are stored using a linked list and are saved to a text file when the program ends which allows the data to be loaded back in the next time the program is ran. The system is designed to handle duplicate records and other common issues. The project is split into multiple C files, one is for handling the database and another for the user interface, this helps keep the code organized and easy to work with.

This project was created for my ICS 212 class, where we were given simple guidelines on the program requirements, but all the coding and implementation had to be done individually. This program was developed using Vim in a terminal by connecting to the UHUNIX server through SSH. We were also required to create a Makefile to automate the compilation process. The Makefile would compile and link the necessary files into one executable.

Through this project, I gained a deeper understanding of C by compiling multiple files, implementing linked lists, and managing file I/O. Also, Working without the conveniences of modern IDEs taught me valuable debugging skills, relying only on manual error tracing without line-by-line error indications. This hands-on experience expanded my knowledge of C greatly and I found the challenge both rewarding and enjoyable.

You can view the source code [here](https://github.com/jstnsmth/ICS212/tree/main/project1).
