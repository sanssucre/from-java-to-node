# from-java-to-node
A java enthusiasts view on how best to structure code when doing node based web services

I’ve been writing code for the internet one way or another since it’s early days.  I started out as the Javascript guy.  Roll overs, form validations and such.  Then came asp and Jscript which got me hooked on backend programming. So, i learned Java and moved on to full time server side code without looking back.  I happily wrote code in one fashion or another using Java and even Ruby for many years.  Along the way i got passionate about clean code, XP, TDD and things like solid principles and domain driven design.  So as you can guess order is paramount in my code base. 

Recently my place of employment standardize the entire software practice to a single technology.  Node.  At first i was annoyed.  Javascript as i remembered it, in the browser, is messy and the code base is hard to maintain.  But hey one has to make a living and i’ve always been kind of curious so why not.

Turns out i love it.  Initially i missed my compiler.  Actually what i missed is autocompletion and strict code inspection that comes with a strongly typed language.  However, in time, my unit test became my compiler.  I started being more attentive to the tests that i wrote to ensure call backs where called and that my variables are all spelled and declared properly.   Then i got a revelation and I actually fell in love with modules.  More then a class and less then library.  It’s the perfect thing; scope wise.  I never really liked the way Java manages encapsulation with private and package and such.  With node and modules if you export it’s public, if you don’t it’s private.  Simple and efficient.  I tend to think of module as a business object and all related functionalities.  

The ORM patterns in Java lead too often to anemic domain model with value objects and service classes (https://martinfowler.com/bliki/AnemicDomainModel.html) In node, with modules and Object stores you can actually create proper code if you put your mind to it.

This project is my view on pattern that could serve you well when doing restful micro services in Node.  This is not a framework.  It’s just a simple example of how i do things.  

If you know DDD then you can think of a micro-service as you would an aggregate root unless you tend to make your aggregate root very large; i don’t.  The added bonus of micro-service is that since the cost of a of rewrite isn’t as high you can afford to be a little sloppier but not too much.
