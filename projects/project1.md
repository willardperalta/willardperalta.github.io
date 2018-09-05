---
layout: project
type: project
image: images/clang.png
title: Bank Database
permalink: projects/bankdatabase
# All dates must be YYYY-MM-DD format!
date: 2018-03-05
labels:
  - C
  - List
  - Database
  - Pointers
summary: I created a bank database program for my ICS212 class at UH Manoa in C using a linked list.
---

<img class="ui medium right floated rounded image" src="../images/linkedlist.gif">

In my Program Structure class (ICS212) at UH Manoa, we were putting everything we learned about C together by creating a final project that involved using a linked list to implement a database program. The program allowed the user to add, remove, and print a list of records. Each record included an account number, name, address, and a pointer. By using pointers, I was able to create a linked list by referencing the next record using the previous record's pointer. The end of the list's pointer would point to NULL. 

Creating this program was a little frustrating because I didn't have any experience with C before I took this class. I learned about memory leaks and dangling pointers the hard way because of this project, but I am glad that I went through it.

<img class="ui medium right floated rounded image" src="../images/ccode1.png">
<img class="ui medium right floated rounded image" src="../images/ccode2.png">

<a href ="https://github.com/willardperalta/bankdatabase">Here's a link to my source code</a>
