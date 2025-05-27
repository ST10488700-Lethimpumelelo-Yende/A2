A2
Flashcard Quiz Study App - README
Overview
This Android Flashcard Quiz Study App is a simple educational app that allows users to test their knowledge with true/false questions. It consists of four screens: MainActivity, QuizScreen2, ScoreScreen3, and ReviewScreen4.
1. MainActivity
This is the entry point of the application. It displays a start button which launches the quiz screen (QuizScreen2).
2. QuizScreen2
This is the main quiz interface. It presents a series of true/false questions to the user. Users receive immediate feedback on whether their answer is correct or incorrect. After answering a question, the 'Next' button is enabled to proceed to the next one. Once all questions are answered, it navigates to the score screen (ScoreScreen3).
3. ScoreScreen3
This screen displays the user's total score out of 5 and provides motivational feedback based on performance. It includes buttons to review the quiz (go to ReviewScreen4) or exit the app.
4. ReviewScreen4
This screen allows users to review each question, displaying the question, the user's answer, the correct answer, and whether the user was correct. It supports reviewing both correct and incorrect answers.
Data Flow
Data such as questions, correct answers, and user answers are passed between activities using Intents. The ScoreScreen3 receives the score from QuizScreen2. The ReviewScreen4 receives the question array, correct answers array, and user answers array from ScoreScreen3.
Navigation
• MainActivity → QuizScreen2 (start quiz)
• QuizScreen2 → ScoreScreen3 (after quiz ends)
• ScoreScreen3 → ReviewScreen4 (review answers)
Final Notes
The app is designed with simplicity and ease of use in mind, making it suitable for educational purposes. The logic can be easily extended to include more question types or different feedback formats.


Images and Screenshots

![image](https://github.com/user-attachments/assets/305703c7-bfba-4d37-9c16-c7fd9efb310d)
![image](https://github.com/user-attachments/assets/1e2f097b-701f-4d5b-8745-bc3621c8d4f2)
![image](https://github.com/user-attachments/assets/c07799c5-a3a4-40da-9463-c9915b0b08c8)
![image](https://github.com/user-attachments/assets/eb629822-7042-4d81-acac-91ce647d1d1b)
![image](https://github.com/user-attachments/assets/dd8dae48-0f75-46cb-a440-d331de3b1259)
![image](https://github.com/user-attachments/assets/3797e405-4c1a-4180-9852-0b87232ad0c2)
![image](https://github.com/user-attachments/assets/8a78e039-17bc-4347-b610-7a1e73e1ecd0)
![image](https://github.com/user-attachments/assets/f71d00d8-808f-4a0f-ab20-a973d64a6456)
![image](https://github.com/user-attachments/assets/13c376b4-1c89-4996-8274-3861362f4457)
![image](https://github.com/user-attachments/assets/83e6206b-5e2c-4566-a6e4-d70f8b160572)
![image](https://github.com/user-attachments/assets/94e01759-689d-4a97-8a22-e87f733547b3)
![image](https://github.com/user-attachments/assets/8fee402b-dfb1-47eb-b257-a74754c34d3c)
![image](https://github.com/user-attachments/assets/2ec7e934-5134-4876-be84-95deb9ffddbe)
![image](https://github.com/user-attachments/assets/fc3c1515-d246-4b87-936f-d6246c08918e)
![image](https://github.com/user-attachments/assets/bd35c660-aa56-43c4-a82d-41cd2bcc44c4)
![image](https://github.com/user-attachments/assets/d08e8ad1-3eee-4618-adf1-f3685c40172a) 

https://github.com/ST10488700-Lethimpumelelo-Yende/A2.git ( repository link)

CODE ATTRIBUTIONS:

//CODE ATTRIBUTIONS
//THIS METHOD WAS TAKEN FROM
//Code assistance provided by [ChatGPT](https://chat.openai.com)
//AI CHATGPT


//CODE ATTRIBUTIONS
//THIS METHOD WAS TAKEN FROM
//https://www.geeksforgeeks.org/creating-multiple-screen-applications-in-android/
//GEEKSFORGEEKS

YOUTUBE VIDEO:

https://youtu.be/uU_3p2cwaOk
