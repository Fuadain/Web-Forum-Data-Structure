# Web-Forum-Data-Structure
A web forum data structure library I created in C++ to help in a group project in college.

The goal was to use the knowledge I gained from my data structures class to create a data structure for a internet discussion forum like that of Reddit and Tumblr, 
where in which discussion threads are created that nest data an indeterminate amount of times. So, I focused on using C++ to create structure based on vectors that 
were fast to access and pull information from. I used vectors full of pointers to other vectors due to the requirement of resizing vectors as forums constantly add 
data, so a vector of pointers is more lightweight than a vector directly full of text data, especially when nesting information that could be parsed through 
recursively with a sort of coordinate system in order to add, delete, or simply read data.

The library was made to be modular, with just a focus on the data structure itself, with the idea that when coding a web server backend the library could then be incorperated along with custom manners by which to handle multithreading or asyncronous programming.

![image](https://github.com/Fuadain/Web-Forum-Data-Structure/blob/main/Forum%20Data%20Structure.png?raw=true)
