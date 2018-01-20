---
layout: project
type: project
image: images/
title: First Intro to Data Structures
permalink: projects/firsttimejava
# All dates must be YYYY-MM-DD format!
date: 2015-03-19
labels:
  - Java
  - Data Structures
summary: First Java Projects
---

<div class="ui small rounded images">
</div>

  ICS 111 was my intro to Java and usage of data structures in a practical way.  Since my first major
  exposure to coding was with C and some C++, using Java started as somewhat tedious.  The course started
  fairly easy but due to the simple nature of the programs I started with in EE150 working with multi-file
  programs was a bit of a struggle.

The requirements of some the assignments and my inexperience with java lead to some fairly large programs
that lack elegence.

An overly large while loop from a Book Store Catalog assigment
-----------------------------------------------------------------------------------------------------------
```C
while (bValid){
         try{
            System.out.print("Enter title:");
            title = scan.nextLine();
            if(title != null && !title.isEmpty()){
               check++;
            }
            
            scan = new Scanner(System.in);
            System.out.println();
            System.out.print("Enter ISBN:");
            sIsbn = scan.nextLine();
            if(sIsbn != null && !sIsbn.isEmpty()){
               check++;
            }
            
            scan = new Scanner(System.in);
            System.out.println();
            System.out.print("Enter quantity:");
            sQuantity = scan.nextLine();
            if(sQuantity != null && !sQuantity.isEmpty()){
               check++;
            }

            scan = new Scanner(System.in);
            System.out.println();
            
            if(check == 3){
               isbn = Integer.parseInt(sIsbn);
               quantity = Integer.parseInt(sQuantity);
               bookArray[count] = new Book(title, isbn, quantity);
               //System.out.println(bookArray[count].toString( ));
               count++;
               count2 = count;
               System.out.print("Book added to list.\n\n");
               check = 0;
            }
            if((title.trim().isEmpty()) && (sIsbn.trim().isEmpty()) && (sQuantity.trim().isEmpty())){
               bValid = false;
               break;
            }
         }
```
