Senior Design Project

1220 ~ The Puzzle Sequence



Written/Developed By Rahman Hridhoy(Nobody) in 2017







ACKNOWLEDGMENT

OUT OF FUN,


DONE IN A Capstone to bridge the gap between the theoretical knowledge and our existing practical knowledge as part of the BACHELOR OF SCIENCE IN COMPUTER SCIENCE AND ENGINEERING (BSCSE) program in 2017. 




                                                                                            




ABSTRACT


This report represents the design choice and the implementation of an online multiplayer game. It can be categorised as a game which tests the players' mathematical skills to ‘foresee the sequence to victory’. For visualisation, imagine a ladder where whoever among the players reaches the top wins. Players can move according to the pre-established number of steps they are allowed while respecting the ‘last location’ of the player before them. The rules will vary depending on the size of the player count as well as the level of difficulty they are at. While the game concept is simple, the system is designed in a manner that is enjoyable and induces the yearning to keep playing. Single players can also enjoy the game as the AI is designed to become progressively more challenging. Every player must also make their move within five second interval.




Introduction

Project Definition:

Consider asking your children to sit down and do math homework, what happens? Many kids will complain. Others might start but then stew in frustration, especially if they have trouble with math. Adults are also not an exception to this problem. But there are ways to have fun and build math skills at the same time. One way is by playing games. A lot of people agree with the idea that learning should be fun. It’s a bit surprising, but in some ways, video games can teach valuable lessons and may even help improve your mental faculties. Video games, like many popular, entertaining and addicting kid activities are looked down upon by many parents as time-wasters, and worse, parents think that these games rot the brain. But many scientists and psychologists found that video games actually have many benefits and teach people high-level thinking skills while providing the brain real workout. 

As the process of thinking happens constantly player are almost engaged almost every second of the game giving the brain real workout. According to researchers at the University of Rochester, led by Daphne Bavelier, a cognitive scientist, games simulating constant engagement develops the brain to make quick decisions and adapt to future scenarios. 

A fun math game typically has set rules, goals, and competition—either against other players or an individual score. Clear rules and goals are important, because they let kids know exactly what to do. Competition matters because it gives a sense of challenge.

The best math games have just the right level of challenge. Players have to choose and use strategies as they play. They have to count/think ahead and make an informed decision. Players have a chance to win, but it’s not guaranteed. That makes things fun and exciting.

A good example is the popular card game Uno or Snakes & Ladders, which are easy to learn—but not always easy to win. Lots of kids (and adults) love those game, including us. The game helps them learn how to count and identify numbers.

![Home Screen](home%20screen%201220.png)


Motivation:


The idea was to create a mathematical sequence puzzle game that will make the player/players ponder if their decision to move forward is right or wrong.  Although the starting few steps you can rush forward, depending on the level of difficulty, the later half of the steps are crucial to dictate the winner as success requires proper strategy and understanding number sequence. The whole purpose of this project is to make something that players of all ages, irrespective of their individual background, can enjoy. Mathematics or rather the number system introduced  in the field of maths is universal. The project idea came from my fellow group-member Rifat Rahman Hridhoy which was inspired from the classic game of Snakes & Ladders. He wanted to make something similar in essence and hence pitched the idea. We wanted to make the game exist in the realm of something which starts of easy but gets harder progressively. Thereby, making the players adapt if they wanted to win. As we both enjoy playing video games, rather then coming forth with a basic game itself; we were more invested in figuring out different rules that will govern our game. Most of our 499B course’s run-time involved coming with an idea, then debating and finding the flaws of it and re-creating a newer idea. The process was fun and greatly motivated us as we wanted other people to experience playing the game as well.




Project Goal:

i. Skill-set development:
   Help develop basic understanding and implementation of math skills such as addition and   
   multiplication. Since our game did not incorporated any form of descent functionality. Thus  
  assisting numeral recognition as game has a number written and updating which makes it ideal 
  for learning to recognize numbers.

ii. Leader-board System: 
A global leader-board which will help motivate players who play with friends or just queue online and fights off against random stranger to achieve the higher spot in the ranking chart.
We believe such competition is quite compelling.

iii. Simple User Interface: 
The ultimate objective of the proposed system is to provide real-time, display & delivery of consecutive information. As an avid gamer ourselves, we pondered whether to go for a modern approach or something befitting the simple concept behind our game. We decided to go with a simple approach or rather a 'retro-gaming', old school gaming approach. We emphasized a lesser visual distraction so more focus is directed towards thinking the next step.

iv. Family Friendly System: 
We envisioned our game in the scenario that a parent playing with their son or daughter of a young age group and teach them the basics as they play along and have an enjoyable learning experience. Playing math games together can also help you get a better sense of your child’s strengths and challenges. And if your child wins (or just has fun) playing a math game, it can boost confidence.








Target Market:

Age Group:  8+
Audience:

  People who are at-least over 8 years old and beyond will be targeted who at- least have minimum  skills of handling smart-phones and applications. 

Based on a survey we conducted, we have seen that people within an age group of 8 – 35 years are most interested in using our “1220 ~ The Puzzle Sequence”. People over 35 years old gave mixed opinions. While some said they preferred usual methods of teaching when we prompted the notion of playing with someone of an younger age and teaching them. But a lot of the elderly citizens approved and were looking forward for an app like this.



Vision:


   “1220 ~ The Puzzle Sequence” is a unique app and the idea of an enjoyable teaching digital platform service is yet to be popular in Bangladesh. Through the survey we conducted, it is safe to say that some Bangladeshi appreciated the idea and will love an app like this which makes it market feasible as well. We personally hope it to alleviate the process of learning maths while enjoying.







Rules & Regulation

The basic rules are as follows:

. Players are given the option to move either 1 or 2 steps.

. The decision must be made within 5 seconds.

. Your decided step(position) will unlock the next two steps for your opponent.

. Whoever reaches the end first is the winner.




Summary:


This chapter introduces our project’s base idea and gives you an insight to what the app is and it’s target audience. It also provides an ideology regarding how the app can help people of various ages improve their mathematical and decision making skills. How something harder in nature can we converted into a fun play time activity for  a younger audience, which in turn would minimize their stress and therefore maximize their individual growth. Our game is also just a nice change from the math schoolwork your child does. As a parent you can use our game to help review it.




MODEL / METHODOLOGY/ DESGIN VISUALIZATION





Model Description:

Overview of the total system:

“1220 ~ The Puzzle Sequence” is a android that will let you a mathematical sequential game. The entire app in built on Android Studio using Java as the main language (with help of JDK). There is no such thing as user-authentication, but after you log in the application you can provide you name and save in on your android device. The system only allows one user per device. We implemented this system so that every user will have their android device’s identifier number as their own unique identity. Of course you can further add a profile picture of yourself.

After laughing the app, you will see the option to play either ‘single player’ or ‘multiplayer’. For single player you will play against an AI designed to become harder with increasing levels. Multiplayer level involves first searching for another player who has queued likewise, we still haven't implement multiplayer for over two people as of now.

When the game start, you will see three set of numbers, starting from ‘0-zero’ and by our default rules the next two consecutive number ‘1-one’ & ‘2-two’. After picking any of the other two consecutive number the game will progress and move in similar pattern until it reaches the end of Level-1 which is the number ‘30-thirty’.







Software Implementation With Reasons:

Android Studio: Android Studio is the official integrated  development  environment (IDE) for Google's Android operating system, built on JetBrains' IntelliJ IDEA software  and designed specifically for Android development. Android is the world's most prevalent operating system for developers to build various applications for mobile devices and tablets. It is an open source operating system which is created by Google, and is available to everyone, both developers and non-developers with any level of expertise to try out building their first android application.
Both the back-end and the front-end of our app is built using Android Studio. The main User Interfaces (UI) are built using XML language. And for the back-end connection with the front-end, Java language is used.

Adobe Photoshop: Adobe Photoshop is a very popular software that is extensively used for creating and editing images, graphics designing and digital artworks and illustrations, which can then be saved into one of the many formats  as  per requirements. For designing our Application background and Logo we have used Adobe Photoshop. Adobe Photoshop, developed by Adobe Inc. is an important tool adopted by designers, web developers, graphic artists, photographers, and creative professionals.











Languages Used:

JAVA: 
Java is a general-purpose computer-programming language that is concurrent, class-based, object-oriented, and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation. The official language for Android development is Java. Large parts of Android are written in Java and its APIs are designed to be called primarily from Java.


XML: 
Extensible Markup Language (XML) is a markup language, much like HTML, that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable. In our project, we have used XML to design the layout of the user interfaces. The UI in android is made with a collection of View and ViewGroup objects.

The View is a base class for all UI components in android such as EditText, TextView, Button, RadioButton etc. For example, the EditText class is used to accept the input from users in androids app, which is a subclass of View. The ViewGroup is a subclass of View and it acts as a base class for layouts and layout parameters such as LinearLayout, RelativeLayout etc. The ViewGroup provides an invisible container to hold other Views or ViewGroups.



JSON: JSON stands for JavaScript Object Notation. Since JSON has a lightweight format, this is convenient for storing and transporting data which is very easy to understand. JSON can be used for multiple purposes. In our project, we have used JSON for styling the Google map to make it more eye catchy by changing the visual display of roads, locations and overall built-up areas in accordance to the theme of our app.








