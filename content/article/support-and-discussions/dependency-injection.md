---
title: "Dependency Injection"
date: 2021-12-08T22:12:49+01:00
draft: true

categories: [programming concepts,]
tags: [Java,spring boot,dependency injection]
toc: false
author: "amine abdelmoumen"
---
brievely dependency injection is design pattern which makes our code lesscoupled so we can maintain and test them erasily
so let's see how it works

 The Dependency Injection pattern involves 3 types of classes.

    Client Class: The client class (dependent class) is a class which depends on the service class
    Service Class: The service class (dependency) is a class that provides service to the client class.
    Injector Class: The injector class injects the service class object into the client class.
    
            ![Yellow Duck](/DI.png 'Yellow Duck')

