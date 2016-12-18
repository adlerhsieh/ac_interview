# Interview

---

# Algorithm

Sum the array: 

    !ruby
    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
---

# Algorithm

Return the average age of the `persons`.

Return an array of names from the `persons`. # => ["John", "Daniel", "Mandy"]

    !ruby
    [
      {
        name: "John", 
        age: 30
      },
      {
        name: "Daniel", 
        age: 45
      },
      {
        name: "Mandy", 
        age: 28
      }
    ]

---

# Git

Describe the functions of the following commands:

- git commit --amend -m "this is a commit"
- git reset --soft HEAD~1
- git rebase -i HEAD~10

<!-- Answer: -->
<!--  -->
<!-- 1. What is GitHub flow? -->
<!-- 2. Why version control? -->

---

# API design - spec

Game: Mario
Device: iPhone iOS

The device should be able to:

1. retrieve the current user's profile
2. retrieve the score of a level from a user
3. create a score of a level for a user
4. update a score of a level for a user
5. retrieve the scores from the current user's friends in a level

For example:

- GET /profile?user_id=10
- POST /user

<!-- Also, explain how to use Chrome inspector for debugging a request. -->

---

# Portfolio

<!-- 1. Describe the purpose of the projects -->
<!-- 2. (Pick some features and) Describe how features are implemented -->
<!-- 3. How the deployment is done -->
<!-- 4. Is there any testing -->
<!-- 5. Is there any performance issue -->

---

# Front-End

<!-- 1. Experience in any JS framework -->
<!-- 2. Any knowledge in prototype -->
<!-- 3. Experience in CSS specificity -->
<!-- 4. Experience in jQuery or JS getElementByXXX -->
<!-- 5. Experience in AJAX -->

---

# Ruby Programming Language

What is the returned value?

    !ruby
    ['foo', 'bar', 'buz'].map(&:upcase)

---

# Ruby Programming Language

What is the returned value?

    !ruby
    class A
      def initialize
        @bar = 10
      end

      def foo
        @bar ||= 20
      end

      def bar
        @bar
      end
    end

    a = A.new
    a.foo
    a.bar

---

# Ruby Programming Language

What is the returned value?

    !ruby
    class Array
      def find(number, &block)
        target = select {|n| n == number }.first
        block.call(target)
      end
    end

    result = [1,2,3,4,5].find(4) do |n|
      n + 10
    end

    result

<!-- Also, what is the difference between class and module? -->

---

# Rails

<!-- &#45; What is Strong Parameter -->
<!-- &#45; What is Background Job -->
<!-- &#45; What is unit test and integration test -->
<!-- &#45; What is the idea of "fat model, skinny controller" -->
<!-- &#45; What is MVC and why -->
<!-- &#45; What is object oriented design -->
<!-- &#45; How cookie and session works -->
<!-- &#45; Why Rails is popular in the market -->
<!-- &#45; What is polymorphic association in Rails -->

--- 

# Database

<!-- &#45; Experience in use SQL query -->
<!-- &#45; What is n + 1 issue -->
<!-- &#45; What is transaction -->
<!-- &#45; Why can't we add index to all columns in all tables if index can improve query speed -->
<!-- &#45; What is INNER JOIN and OUTER JOIN -->
<!-- &#45; How to design a many&#45;to&#45;many association -->
<!-- &#45; Experience in checking slow query log -->

---

# Linux

<!-- &#45; Experience in setting up a server from scratch -->
<!-- &#45; Experience in automated deployment -->
<!-- &#45; Experience in checking log for nginx &#38; unicorn or passenger -->
<!-- &#45; Experience in configuration management -->
<!-- &#45; Experience in using eco&#45;system on AWS, Azure or GCP -->
