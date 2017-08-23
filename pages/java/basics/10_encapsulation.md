---
layout: page
title: Encapsulation in Java
permalink: /java/basics/lessons/encapsulation.html
description: "A look at Encapsulation in Java"
comments: true
signoff: true
---
[Course Home](../../course) \| [What is Encapsulation?](/programming/lessons/encapsulation) \| [Encapsulation Example(s)]() \| [Access Modifiers Example(s)]()

In our previous lesson on [Abstraction](../lessons/abstraction), we abstracted a few lines in to a new method on the same class. Now using the idea of Encapsulation we take this one step further. Instead of a method, we can create a new class and add the method there. That class would then be the place we'd put similar methods in the future.

Another way to think about Encapsulation is when you spot you have many similar methods, perhaps spread across many classes. To make the code more manageable we could use Encapsulation to create a single class and refactor all those methods on to that class. This would then group those similar methods into once place, into one well named class.

### Access Modifiers
In the programming basics course we have Public, Private, Protected and Internal. Java doesn't have the concept of Internal, but it does have the other three.

As mentioned they control access, which is something really important to consider when thinking about Encapsulation. As mentioned in the basics course, a part of encapsulation is data hiding. Something we achieve using Access Modifiers. Here are the basic rules in Java.

| | Containing Class | Extended Class / Same Package | Any Class 
|:-----:|:------:|:------:|:------:|
|private| &#10003; | 	&#10060; | 	&#10060;
|protected| &#10003; | 	&#10003; | 	&#10060;
|public| &#10003; | 	&#10003; | 	&#10003;

Please look at the links above for full code examples which are heavily documented. Too many classes and a lot of code to paste in to the post.

### [Next Lesson &#10132;](../lessons/inheritance)
