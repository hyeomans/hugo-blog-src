+++
date = "2017-04-16T18:49:32-07:00"
title = "Go interfaces testing"
draft = true
+++


Go programs, once implemented correctly, are simple to test. Go includes a simple unit test library. This library forces you to be repetitive and that's perfect if you're in you're learning phase.

Testing is one way you can learn how to decouple your Go programs. Usually unit testing forces you to think about dependencies and how you can mock them. Think about retreiving data from a database, you don't care how data comes into your program -- in the case of integration testing you might want to setup/destroy a db each time--you only want to verify your bussines logic works.


