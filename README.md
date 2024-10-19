# Practical work 1

Lisa Gorgerat et Alex Berberat

![Title card](/images/title_card.jpg)

## Table of content

- [Introduction](#introduction)
- [Application](#application)
    - [How to setup](#how-to-setup)
      - [Cloning our repository](#how-to-clone-our-repository)
      - [Build our application](#how-to-build-our-application)
    - [How it works](#how-it-works)
    - [Demo](#demo)

## Introduction
In this practical work, we needed to create a CLI using picocli to process files in any way we wanted, as well as git and github to manage our code, maven to build our application and using java as programming language and to run our application.

We have chosen to write an application that take a text file containing a text in UTF8 format that print every word(only one time, if the word is there multiple times) and allow the user to sort this dictionary in alphabetical order, reverse alphabetical order, by order of apparition or by number of appearance.

We don't consider two words distinct if the only thing that change are the case of certain letters. Numbers aren't considered words, if they are in digit form. 

## Application
### How to setup
#### How to clone our repository
To set up our application, you first need to go to our repository on github: [Our repo](https://github.com/AlexB-HEIG/DAI-Practical-work-1).

Then you need to clone our repository:
1. Go to the folder where you want our repository to be.
2. Open a terminal there
3. use the command git clone with the ssh<br>
`git clone git@github.com:AlexB-HEIG/DAI-Practical-work-1.git`

#### How to build our application
To build our application, you need to use the following command on your terminal:<br>
` java -jar target/DAI-Practical-work-1-1.0-SNAPSHOT.jar <your file> SORT <sort type>`

However, if you are a developer and if you have made some modifications, you need to repackage the application.
For that, we have made a maven configuration to package the application: <br>
![maven config](images/package.png)

### How it works



### Demo
We have given a file (`les_miserables.txt`) on which you can test our application.

