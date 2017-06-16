# Python Learning Resources
Below is a list of the resources I used to learn programming in Python. Maybe they will come in handy for you as well. :)

All entries include a link to the resource, the approximate time I spent on completing it, price info and a short description.

## Python Basics
Beginner-level tutorials (no previous programming knowledge needed), that I used as a first step to learn the basics of Python syntax.
  - [Codecademy's Python tutorial](https://www.codecademy.com/learn/python) Time: ca. 20h Price: Free
  A simple introduction to Python's basics. It involved a lot of hand holding and very little information on programming beyond writing code in Python, but it was perfect for me to get a first grasp of the absolute basic building blocks in Python (in-build data types, control flow etc.)

  - [Learn Python the Hard Way](https://learnpythonthehardway.org/book/) Time: ca. 25h Price: Free
  A great book for complete beginners. The learning method might seem a bit blunt at first (you basically write the very same code that is presented to you in the chapter line-by-line and make it run), but it allowed me to get more and more familiar with writing Python code and  correcting my errors. Zed E. Shaw, the author, has scattered some pretty useful advice on learning here and there and in general I am a bit of a sucker for the tone in which the book is written (straight to the point and yet still encouraging). I particularly liked Zed's [note on practice and persistence](https://learnpythonthehardway.org/book/intro.html) from the book's intro. Although the book is in Python 2.7, at this level I didn't find the differences between Python 2 and 3 relevant.

  - [Google's Python Class](https://developers.google.com/edu/python/) Time: 18h Price: Free
  A tutorial based on a two-day workshop that Prof. Nick Parlante from Stanford gave at Google a couple of years ago. It includes class notes, exercise files and video recordings of the workshop posted on YouTube. Being equipped with a solid knowledge of the basic Python syntax, it still took me much more than two days to cover the tutorial (I would spend maybe 2 hours daily on it), but it was really fun! Finally, the exercises resembled something like a real-world use of Python to manipulate data. I recall exercises where I wrote a program for calculating a wordcount from a text file, with options to show how many times each word appeared in the text and what were the most common words. Another one involved extracting data from a US administration website with statistics on baby names to analyse popularity of certain names across years. As the workshop was held 7 years ago, it also uses Python 2 and in the latter part I run into some issues with deprecated modules being used. But despite that, the exercises were fun, and finally I got to write some simple but useful Python programs.

## Programming Basics
Having grasped the fundamental syntax of Python, I was ready to combine it with broader knowledge of programming and computing principles. This involved getting more familiar with concepts such as functional and object-oriented programming, understanding more about basic data structures and algorithms, principles of clean code, debugging or error and exception handling.
  - [MITx: 6.00.1x Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-10) Time: 80h Price: Free
  This is the single resource I have spent the most time on. A MOOC MIT course hosted on edX, first of two in a series (I only took the first one). As the creators say on the course homepage: "They are challenging and rigorous courses in which the students spend a lot of time and effort learning to bend the computer to their will." And it was that indeed. I have spent may hours and used additional resources to understand the lectures and solve the problem sets. As the material for each week was rolled out, I would usually start by not having the faintest idea about what the professor was talking about and gradually building my way up to finally breaking through and understanding the concepts. And the break-through would always finally come. It gave me immense satisfaction to persist, do the work and see it's effects in the end. And at the end of the course I got a 95% mark (based on problem sets, mid-term and final exams). It was difficult but it was worth it.

  - [Harvard: CS50 Introduction to Computer Science](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x) Time: ca. 20h Price: Free
  This one is just so awesome. Don't mind that the code itself is in C for the most part. I only watched the lectures (w/out doing the problem sets) and treated them like my new favourite TV series. To some extent it covered the same fundamental programming concepts as the MIT one and I used it to just get a better grasp of the foundations. I love the energy of prof. David Malan and the team. And the physical 'stagings' of data structures and algorithms really helped me to understand their underlying implementations. I never thought I would find a lecture on searching and sorting algorithms to be such a pleasure.

## Intermediate Python
  - [Python Beyond the Basics: Object Oriented Programming](https://www.udemy.com/python-beyond-the-basics-object-oriented-programming/) Time: ca. 20h Price: 10 EUR on Udemy
  This one helped me to get a better grasp of OOP. I felt a little lost when the paradigm, along with classes, attributes, encapsulation, polymorphism and inheritance, was introduced both in in the MIT course and in Learn Python the Hard Way, and this course helped me to get a properly clear vision of how it all works. Apart from the core of OOP, the final chapters also throw in topics such as serialisation (including json) and efficiency and testing (eg. using pytest).

  - [Intermediate Python](http://shop.oreilly.com/product/0636920049852.do) Time ca: 15h Price: $60 (but I watched it as part of a free trial)
  I didn't find this course to be absolutely essential, but it provided me with opportunity to practice Python a bit more beyond the basics. It was similar to the Google Python course in that the exercises were closer to real-life and their application more practical. Plus, Jessica McKellar is an inspiration to me.

## Django
 As I started to apply for internships, it usually was the case that the recruitment process consisted of a task to build a simple web app in Django. Also, after months spent on learning pure Python, I felt it was time to start working on some more real-life projects and start building a portfolio on github to be able to present my skills during job interviews. So I ventured into Django.
  - [Try Django](https://www.codeschool.com/courses/try-django) [Digging into Django](https://www.codeschool.com/courses/digging-into-django) Time: 5+6h Price: 9EUR/for the 1st month (I got it with a promo code)
  As I started to apply for the summer internships, it turned out I had to learn Django fast. I stated with the [tutorial form Django's documentation website](https://docs.djangoproject.com/en/1.11/intro/tutorial01/), but found myself lost. So I decided to reach for Codeschool's paid subscription and try out their two Django courses. And they were right up my alley - I followed the videos along and built a sample app and finally understood the relation between the models, templates, views and the url controller in Django.

  - [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) Time: 25h Price: Free
  For me, this was the best beginner's resource in the web to get familiar with the framework. I actually got to participate in a live Django Girls workshop where we used the tutorial, but it is well written enough to serve as a stand-alone guide for you to follow at home. As I finished the basic tutorial, I kept extending the blog, looking for extra features to add and thus learning more and more while building an actual, real-life website deployed on the web. My blog is still just a shell without any proper content, and I focused more on the back-end (this it looks quite plain), but the point was to stop learning just from the tutorials and try myself out by creating something in a less hand-held way.

## Tools and utilities
  - [Atom](https://atom.io/) My source code editor of choice. It's open source, includes syntax highlighting and can be customised with a lot of useful plug-ins. My favourites are: minimap and minimap-highlight-selected (for side preview of the whole source code), linter-pylint and linter-pycodestyle (for static code quality linting and pep-8 compliance) and autocomplete (for suggesting completions).

  - [Command line](https://learnpythonthehardway.org/book/appendixa.html) Time: 5h Price: Free I felt that if I was thinking seriously about programming, I should get comfortable with the command line. And of course at the very beginning it was a bit intimidating. I wanted to share that appendix from Learn Python the Hard Way as it helped me to break the ice quickly, but gently. :)

  - [How to use Git and Github](https://www.udacity.com/course/how-to-use-git-and-github--ud775) Time: 12h Price: Free
  I started to use version control early on and pushed my solutions to exercises and assignments form the courses I was covering onto Github. I knew that the skill would be necessary in future work and it allowed me to neatly document my learning. This course got me up and running with Git and Github in a couple of days.

  - [Toogle](https://www.toggl.com) Free time tracking on projects. I basically used it to track how much time I've spent on a given resource. So, anytime I would sit down to learn, I would start off the timer saving each course/tutorial as a separate project. Thanks to this, after months I could see what I had spent most time on or compare how much work I had done in given weeks or months. It not essential to the programming process itself, but it helped me to keep track of my learning path.

## Programming challenges
More fun and practice. Never mind that sometimes I will put some serious time into solving tasks marked as 'painless' or 'elementary'. ;)
  - [Codility](https://codility.com/programmers/lessons) I came across Codility as I was applying for an internship. A test of several programming challenges was the first step of their recruitment process. What I'd learned then was that I could solve the basic challenges in reasonable time, and the code was correct, but it was usually quite poor in terms of memory and time performance. So I started to work on refractoring my code and do the lessons on Codility. What is nice is that each lesson has a reading material attached, discussing the main concepts around which the challenges in the lesson are based. The key thing I have learned was how to pay attention and test my code against different test cases (empty input, small, medium, large input and edge cases), before I would submit the final solution.

  - [Checkio](https://checkio.org/) Checkio adds an element of gamification to the programming challenges. You explore the different space bases, collect points and unlock new missions, all while exercising your coding skills.

## Final notes and disclaimer

As you might have noticed, I took full advantage of all the high quality, yet mostly free learning resources on the web. All of the major providers are there: edX, Udacity, Udemy, Codecademy, Codeschool. I am not saying these are the only good ones out there. I just wanted to share what was right for me and how it allowed me to progress in a structured way. Don't treat it as some ultimate truth. Find what's right for you. Maybe my collected experience will come in handy.

After almost 6 months covering these materials, I have one more thing to add: There is a point where you know the basics well enough to let go of the ready-made courses and move onto trying out your skills building your own stuff. I actually think, I overdone it a bit with the structured, hand-held learning. This is my preferred learning method, but it won't make me really ready for a programming job. Pushing myself to build things on my own and learn from all the errors I make will. Time to move on!

Good luck!!!
