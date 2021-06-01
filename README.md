# tech-task

Prerequisites

You are expected to have access to the Internet during the course of the development of this task, it is expected that you will have a suitable professional environment in which to complete the test.

If you feel you do not meet these requirements, please contact the person who directed you to this test, and they can make arrangements for such things to be arranged.

## Instructions

The purpose of this test is to produce a small working application for review by your prospective employer, the details of the application have been provided below.

The aim for the test is to understand how you structure your solution, and how you turn that solution into a working application.

You need to:
* Produce working, object orientated, unit-tested code
* Describe the setup of your project, and how to resolve any external dependencies
* Deliver the working application in some form to your prospective employer
* If you want to use a framework you're more than welcome to do so! (Preferably Laravel/Lumen)

You are expected to:
* Work on this task alone without help from anyone else
* Ask questions if you do not understand anything you are being asked to do

## Task
* download https://shadowapi-public.s3.eu-west-2.amazonaws.com/books.csv
* download https://shadowapi-public.s3.eu-west-2.amazonaws.com/book-meta.csv
* write a command line tool to merge and import the data from both csv files into a database either using raw PHP or Laravel
* create an endpoint to query this data by author, publication date and book title.
* create an endpoint to query this data to return the amount books by each author i.e. Helen Fielding,  1
