# VideoZip

In this project, you'll speed up video compression tool. This tool receives a folder with uncompressed image files (".ppm" extension) and creates a single zip file with all images after compression. The images in the input folder will have the frame number in their file name, and the output zip file follows lexicographical order.

This is a group project. Each group must have at least 3 members and at most 3 members. If you cannot find a group by Oct 28th, you will be randomly assigned to a random group after that.

To make a group, go to People on Canvas and click the Project 2 tab. You can drag students in any of the groups. Make sure that you are in the correct group. Pick a leader in your group.

FAQs:
- I wanna work by myself, is this allowed? Answer: No
- My group has only two people, is this allowed? Answer: No
- My group has more than three people, is this allowed? Answer: No
- I want to work with students from the other section, is that allowed? Answer: No

Task description
1) Download the starting package here Download here.

2) Unzip, build, and run the tool. You might have to install the zlibLinks to an external site. library.

$ unzip project2.zip
$ cd project2
$ make
$ make test
3) Change the code to make it faster using threads. You are only allowed to use the pthread library to this end, nothing else. Using other libraries, changing compiler flags, and other tricks are not allowed. If, at any point in time, your program has more than 20 threads (including the main thread) in execution, your submission will be deemed invalid. In other words, you cannot have more than 20 threads running simultaneously.

Submission
The submission is divided in two parts.

PART #1: The correctness of your submissions will be automatically evaluated by Gradescope. You must prepare a file named vzip.zip containing a folder named src. This folder must contain your source code in C language (other languages are not allowed) and a Makefile to build the executable named vzip. This code must be buildable and runnable in a Linux environment with a recent version gcc (more precisely, gcc version 11.4.0 with Ubuntu 11.4.0-1ubuntu1 22.04). Your code will be tested in a machine with 4.0 CPU cores and 6.0GB of RAM.

PART #2: Your group must create a video presenting your approach to speed up the tool (at least 5 minutes, at most 10 minutes). The video must be submitted through Canvas. All group members must participate in the presentation, and a person's face and name must be visible while this person is talking. Consider using a video conferencing tool (e.g. MS Teams) to record your presentation. The contributions of each group member must be explicitly stated in the presentation. Just showing your final solution is not enough. Groups are expected to show all the work that was needed to come up with their best submission.

Rubrics
Speeding factor: 50%
Code style: 10%
Presentation: 40%

Getting the code three times faster than the original code will guarantee a C for the speeding factor criterion. 

Code style will have deductions for bad indentation and organization, and for the lack of meaningful comments.
