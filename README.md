# 📝 **TechSnap** 📚 

## Overview
TechSnap is an innovative, fully animated, and responsive web application designed to streamline the process of managing classroom attendance. The platform enables teachers to create classrooms, and students can easily enroll using a class code. TechSnap supports both manual and online attendance tracking, with an advanced feature that tracks the location of students during attendance submission to ensure authenticity.

## Features

- 📚 **Classroom Creation:** Teachers can create virtual classrooms where students can enroll using a unique class code.
  
- 🏫 **Student Enrollment:** Students join classrooms by entering the provided class code.

- 📝 **Manual Attendance:** Teachers have the option to take attendance manually within the platform.

- 🌍 **Online Attendance with Location Tracking:** Teachers can initiate an online attendance session where students submit their attendance. The system tracks the student's location at the time of submission. If a student's location is not within the expected vicinity of the classroom, the teacher can discard that submission.

- 📊 **Attendance Visualization:** Both teachers and students have access to visual representations of attendance records, making it easier to analyze attendance patterns.

## Problem Solved

- ✂️ **Reduces Paperwork:** TechSnap digitizes the attendance process, significantly reducing the need for physical paperwork.

- 🚫 **Prevents Proxy Attendance:** By tracking the location of students during online attendance submission, TechSnap helps prevent proxy attendance.

- 📈 **Attendance Analysis:** The platform provides tools for both students and teachers to analyze attendance data, helping in identifying patterns and irregularities.

## How it Works

1. 👨‍🏫 **Teacher:** Create a classroom and share the class code with your students.
2. 👩‍🎓 **Student:** Enroll in the classroom using the provided class code.
3. 👨‍🏫 **Teacher:** Start a manual attendance session or initiate an online attendance session.
4. 👩‍🎓 **Student:** Submit your attendance during the online session.
5. 👨‍🏫 **Teacher:** Review and finalize attendance, with the ability to discard submissions that do not meet location criteria.
6. 👩‍🏫 **Both Teacher and Student:** View and analyze attendance records through visual dashboards.

## Technologies Used

- 💻 **Bootstrap:** Frontend framework for creating responsive and mobile-first web applications.
- 🌍 **Geolocation API:** Used for tracking student locations during online attendance submission.
- 🚀 **Node.js:** Backend runtime environment.
- 🖥️ **Express.js:** Web framework for Node.js.
- 🔑 **Passport:** Authentication middleware for Node.js to manage user login and security.
- 🗄️ **MongoDB:** Database for storing user and attendance data.

## Demo

Check out the live demo of TechSnap at [TechSnap Live Demo](https://teachsnap.onrender.com).

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install the required dependencies for TechSnap.

```bash
npm install
