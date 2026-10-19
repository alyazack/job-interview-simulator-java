# Job Interview Simulator (Java)

A Java desktop application that lets users practise job interviews for 15 occupations and get instant feedback.

## Overview
Many candidates struggle in interviews because they lack realistic practice. This group project (MDA3044 Industrial Programming Language, Universiti Malaysia Terengganu) simulates an interview in a low-stress setting. The user picks an occupation, answers five randomly selected questions, and receives a scored summary.

## Features
- 15 occupations (Doctor, Teacher, Software Engineer, Lawyer, Chef, Pilot, Architect, Accountant, Nurse, Police Officer, Data Analyst, Journalist, Psychologist, Entrepreneur, Marketing Manager)
- Question bank of about 10 questions per occupation, with 5 chosen at random each session
- GUI dialogs built with Swing (`JOptionPane`)
- Scoring based on expected keywords found in each answer
- Result summary with each question, answer, score, and average score, plus feedback

## How scoring works
Each answer starts from a randomised baseline score between 50 and 80, plus 4 points for every expected keyword found in the answer, capped at 100. This is a simple heuristic for demonstration, not a validated assessment of answer quality.

## How to run
1. Install a JDK (Java 8 or later).
2. Compile: `javac -d out JobInterviewSimulator.java`
3. Run: `java -cp out finaljava.JobInterviewSimulator`

Or open the file in an IDE such as Eclipse and run it directly.

## Tools
Java, Swing (`javax.swing`), Eclipse

## Note
Group project for MDA3044 Industrial Programming Language, Universiti Malaysia Terengganu.
