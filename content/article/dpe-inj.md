---
title: "Dependency injection Inj"
date: 2021-12-09T01:00:32+01:00


categories: [Java,Software engineering]
tags: [java,depedency injec,spring]
toc: false
author: "amine abdelmoumen"
---

Firstly dependency means that something rely on an another thing ,in another world when a class **A** uses a functionality of class **B** . so here **A** depends on **A** this is what we mean by dependency.as you know in java usually (but not alwayse) before we use a method of a class we need first to create object from that class.
Dependency injection is the princile of deligating this class instanciation to a third party. 

Why we need dependency injection?
without dependency injection we used to create an objects like this
```
Classb classaObject=new ClassB();
```
this makes our application stringlyCoupled and difficult to maintain regardless of memory problems 
![demo](/depi.png)
as you see here 3 classes are involved 

**1.Client Class** :which is the class the depends on a service class b \
**1.Service Class**: is the class with functionnalities nedded by class A  \
**1.Injector Class**: is the class which will creating an object of the Service class and inject it to the client class.


