---
layout: essay
type: essay
title: "Reflect on Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-12-05
published: true
labels:
  - Design Patterns
  - Reflection
---

## Building Blocks of Software: Design Patterns ##
  
#### What are Design Patterns? ####
<img src="https://github.com/user-attachments/assets/42dfb267-6ad1-46dc-9a24-6271d3fde4fb" alt="LEGO-recycled-bricks" style="width:50%; height:auto;">

Imagine you’re building with LEGO bricks. Over time, you discover the best ways to create certain structures, like sturdy bridges or tall towers, that can be reused in many models. These reusable methods save time and ensure that your designs are solid. 

In software development, design patterns work the same way as they’re like blueprints/references for solving common coding challenges. While they aren’t specific pieces of code, they provide general ideas that guide how you structure your program. For instance, if you need a way to manage how different parts of your program communicate, there’s a pattern for that. If you want to ensure that an object is created only once, there’s another pattern for that. Recognizing patterns is essential for programmers in order to be efficient and consistent enough in the workspace.  

These patterns are grouped into three main types. One group helps with creating objects in organized ways, another focuses on how those objects are structured, and the last one deals with how objects interact with each other. Together, they offer a toolkit for writing clear and maintainable code.

<img src="https://github.com/user-attachments/assets/f3fc5df5-c1ba-4ab9-81f9-a69b06c538b8" alt="Design-Patterns-A-Key-to-High-Performance-Software-Development" style="width:50%; height:auto;">

#### How I’ve Used Design Patterns ####
When building a student management system, I encountered challenges in both creating and processing objects. Design patterns provided helpful solutions to these challenges. 

One example is the Instructor pattern, which I used to dynamically create student objects. I created a system that generated student objects with attributes like name, grade, school, and GPA. This approach allowed me to add students with different attributes efficiently while keeping the code flexible. For instance, if a new attribute like “enrollment date” needed to be added, this method could easily accommodate this without disrupting the rest of the system.

Another design pattern I used was the Iterator, which simplified processing collections of student objects. For example, when calculating the average GPA of students, I used an iterator to loop through the list of student objects without manually handling indexes. This made the code cleaner and more intuitive. If additional filters, like finding students from a specific school or grade level, were needed, the iterator could be extended to handle those seamlessly.

Together, these patterns improved the system significantly. Recognizing the patterns that accomodate this challenge and the implementation of these patterns ensured that student objects were created consistently and dynamically, while the Iterator pattern streamlined data processing, making the system more readable and maintainable.

#### Why Design Patterns Are Useful ####
Design patterns are essential because they solve problems in ways that are proven to work. In the student management system, they made the code easier to understand, extend, and debug. By using patterns like instructors, iterators, etc. I didn’t just solve immediate problems, I also built a system that could grow and adapt without requiring a complete rewrite.

Beyond the technical benefits, design patterns also make it easier to communicate in a cooperative environment with other developers. For instance, instead of explaining every detail, I could simply say, “This part uses the Iterator pattern to process students,” and anyone familiar with design patterns would understand.

#### Conclusion ####
  Design patterns are a powerful tool for writing better code. They save time, prevent mistakes, and make your programs easier to understand and maintain. Whether it’s managing resources, organizing updates, or switching between behaviors, patterns offer solutions that work. Learning to use them has been one of the most valuable parts of my coding journey, and I’m glad to have them as part of my toolkit.
  
