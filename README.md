### Hi there 👋 this is Partho

<!--
**partho5/partho5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



- 💼 Software Engineer
- 🎓 Electrical and Electronic Engineering, University of Dhaka
- 🧰 Pro skill: React.js · Next.js · Typescript · Node.js · Express.js · PHP · Laravel · MySQL · NoSQL(e.g. managed MongoAtlas, DynamoDB) · AWS(Ec2, S3, Lambda etc.) · Firebase · HTML, CSS, Bootstrap · Tailwind · jQuery · Android · API development & Integration
- 🔨 Also worked with: Java · Spring Boot · PostgreSQL · Linux · Apache, NGINX · C# · Python · IOT · Arduino · NodeMCU


## Let's talk about some of my projects

# YouTube Video to Article Writer

A powerful AI-driven tool that transforms YouTube videos into SEO-optimized, long-form articles with featured images in just one click.

### Overview

This software streamlines content creation for businesses, agencies, and creators by generating high-quality, engaging, and thought-provoking articles directly from YouTube transcripts. It also produces stunning featured images and metadata to maximize SEO performance.

### Features

- **Input Simplification:** Input only a YouTube URL to generate content.
- **AI-Powered Prompt Engineering:** Utilizes advanced prompts to extract insights and produce high-quality articles.
- **SEO Optimization:** Ensures green scores for SEO, readability, and inclusivity.
- **Dynamic Article Expansion:** Recursive AI-driven enrichment for long-form content.
- **AI-Generated Images:** Creates visually appealing featured images tailored to the topic.
- **External Link Integration:** Adds authoritative external links using Google Custom Search Engine (CSE).
- **Publishing Workflow:** Direct upload to WordPress with SEO metadata.
- **Cloud Storage:** Scalable image storage using AWS S3.

### Technologies Used

- Next.js
- Typescript
- AWS Lambda
- DynamoDB
- Python
- Express.js
- Socket.io
- WordPress REST API

### Business Impact

- **Time-Saving:** Completes tasks in 1 minute that typically require 7-8 hours.
- **Cost-Efficient:** Reduces reliance on manual content creation.
- **Scalable:** Designed for bulk content generation and publishing.


# Google Drive Merge

A web application that virtually merges multiple google drive accounts into one, providing a seamless user experience.

### Overview

If a user possesses 10 Gmail accounts, they have a total of 15 * 10 = 150 GB of free cloud storage. However, managing 10 different accounts can be overwhelming! This web application introduces a technique that virtually merges all accounts into one single account.

### Features

- **Account Merging:** Seamlessly merge multiple Gmail accounts into a single account.
  
### Usage

You can clone and deploy to your own server. Even it's possible to run it under localhost if you configure. Everything will work, but you can only access from your PC.

### Technologies Used

- Spring Boot
- React.js
- PostgreSQL
- Google API

Source code will be shared in github soon


# Payment Verification

A free alternative to the bKash payment verification API developed in Java and Android.

### Overview

This app provides a free alternative to the bKash payment verification API. It efficiently verifies payments by reading and parsing bKash payment confirmation SMS messages on the user's phone. The app is designed to work seamlessly with Java code, ensuring prompt processing of payment information.

#### How It Works

1. **SMS Reading:** The app immediately reads bKash payment confirmation SMS messages as soon as they arrive on the user's phone.

2. **SMS Parsing:** The received SMS is parsed to extract key information, including the mobile number, arrival time, and Transaction ID.

3. **Server Communication:** The parsed information is promptly sent to the server for verification. If the internet connection is not already ON, the app activates it.

### Technologies Used

- Java
- Javascript (for the development of the app's UI)
- HTML, CSS (for UI design)

[Github repository link](https://github.com/partho5/payment-verification)

# Vocabulary Preparation App
Feature-rich web application for processing vocabulary data. Developed in Java for Android, available on the Play Store. Paid app, no free version yet. Not much downloads. But all the downloads are paid users. I am afraid that I can't share the source code, because it's my business.


# Visualize your users on geographical map

This project is to show your website/channel visitors in (Bangladesh) map. Number of visitors from all the districts will be taken from server. Then in the front end SVG map will be drawn and manupulated using Javascript. require.js and svg-path-properties.js libraries are required. Jquery, Bootstrap are also used.
[Github repository link](https://github.com/partho5/visitor-map)


# Convert any website into android app !
This is a very simple but useful & valuable project. Any website can be converted into an android app, just by changing a variable value, the url of desired website. [Github repository link](https://github.com/partho5/convert-any-website-into-android-app)


# Boolean Expression Comparator

Takes two boolean expressions of any number of variables, compares them, and indicates whether the expressions are the same or not. This tool is useful when verifying the reduction of boolean expressions. Users can compare expressions to ensure the correctness of the reduced form.

### Overview

For example, if the original expression is A + A!B + B!C + !AB!C and it is reduced to A + B!C, the tool can be used to verify the reduction. If someone ends up with an incorrect solution like A + B!CA, the output will indicate the disparity.

Additionally, the tool generates a truth table for any number of variables.

### How It Works

1. **Expression Comparison:** Compares two boolean expressions to determine if they are the same or different.

2. **Verification Output:** Provides clear output indicating the result of the expression comparison, helping users identify errors in their reductions.

3. **Truth Table Generation:** Generates a truth table for any number of variables in the boolean expressions.

### Usage

1. Enter the two boolean expressions for comparison.

2. Click on the compare button to initiate the comparison process.

3. Review the output to verify the correctness of the reduction.

[Github repository link](https://github.com/partho5/boolean-expression-comparetor)


# FindBook E-commerce

An E-commerce platform designed for selling books. This project incorporates basic e-commerce functionality and is built using Laravel and Vue.js. Mailgun is used as the email service provider for seamless communication. Also pdf file of a book can be downloaded for free if available. All basic features of a ecommerce. Once I myself run this business.
[Github repository link](https://github.com/partho5/findbook)

# Blood Donor Database for Badhan (Dhaka University JN hall unit)

A database collection for a non-profit organization managing volunteer blood donors. This project allows volunteer donors to register, add, and edit their personal information. Users can search for donors by their blood group, filtering those who donated blood more than 3 months ago.

### Key Features

- **Volunteer Donor Registration:** Users can register as volunteer donors, providing and managing their personal information.

- **Personal Information Editing:** Donors have the ability to add and edit their personal details as needed.

- **Search by Blood Group:** The system enables searching for donors based on their blood group.

- **Time-Based Filtering:** Donors who have donated blood more than 3 months ago can be filtered for better organization and outreach.

[Github repository link](https://github.com/partho5/blood_donors)


# 2D graph plotter
### Features

- **Data Persistence:** Save any dataset used for plotting, allowing for easy re-plotting without re-entering data.

- **Re-Plotting:** Graphs can be re-plotted using previously saved datasets, providing convenience for users.

- **Image Saving:** Save the plotted graph as an image file for sharing or further analysis.

- **Direct Printing:** Print the graph directly from the right-click menu for quick and easy hard copies.

- **Zoom-In and Zoom-Out:** Zoom in and out options available for both X and Y axes, providing a detailed or holistic view of the plotted data.

[Github repository link](https://github.com/partho5/line-graph-plotter)



# Weather forecasting service for farmers

'Enlightened Farmer' is a weather forecasting system designed for village farmers, enabling them to take precautionary steps against forthcoming adverse weather conditions. The system retrieves weather data from the wUnderground API, scraps additional weather data from a website, and then parses and sends weather forecasting messages to registered farmers' mobile numbers using an SMS API.

### Key Features

- **Weather Data Integration:** Utilizes wUnderground API for comprehensive weather data.

- **Web Scraping:** Gathers additional weather data from a website and parses the information.

- **SMS Notifications:** Sends weather forecasting messages to registered farmers' mobile numbers using an SMS API.

[Github repository link](https://github.com/partho5/enlightenedFarmer)


# University Course Management

A web-based application designed for university teachers to manage courses, student attendance, and exam marks seamlessly. The system allows teachers to register, create courses, and enables students to register and join courses using a link provided by the teacher. Additionally, there's an Android application for teachers to take attendance, with automatic synchronization of student details between the website and the mobile application.

### Key Features

- **Teacher Registration:** Teachers can register themselves on the platform.

- **Course Creation:** Teachers can create and manage courses.

- **Student Registration:** Students can register and join courses using links provided by teachers.

- **Mobile Attendance Application:** Android application for teachers to take attendance, with automatic syncing of student details.

- **Attendance Calculation:** Automatic calculation of attendance marks at the end of the semester/year.

- **Exam Mark Entry:** Teachers can enter exam marks for students.

- **Printable Marksheet:** Generate a handy and printable marksheet in PDF format, saving time and reducing the hassle for teachers.

[Github repository link](https://github.com/partho5/courseMan)




# Education-Based Social Media

An education-focused social media platform developed using the Laravel (PHP) framework, jQuery, and MySQL database. This platform allows users to search for existing communities or create new ones using the name of their institute or department. Users can add members by sharing links similar to Google Classroom. The system notifies all members via email when posts are made.

### Key Features

- **Community Creation:**
  - Users can search or create communities using the name of their institute or department.
  - Members can be added by sharing links, similar to Google Classroom.

- **Notification System:**
  - Members receive email notifications for posts and updates.

- **File Management:**
  - Members can create directories, upload files, and share file links similar to Google Drive.
  - A desktop application (written in C#) syncs all files on the user's computer, mirroring files and folders.

- **Teacher/Admin Privileges:**
  - Teachers can join communities, taking on the role of a teacher/admin with enhanced privileges for community control.

- **Amazon S3 Integration:**
  - Files are stored in Amazon S3 for efficient and scalable storage.

- **Android App:**
  - An Android app mirrors files and folders, displaying posts from the website.

- **Course Management System:**
  - Dedicated course management system for teachers.

- **Question Answer Forum:**
  - Platform includes a question and answer forum for community interaction.

[Github repository link](https://github.com/partho5/letsOrgan)


# Clipboard Manager

A Clipboard Manager written in Python for Linux running PCs. This software runs at startup with the help of bash programming and efficiently saves anything that is copied, allowing users to reuse copied content later. The project utilizes PyQT for GUI building and SQLite for storing data.

### Key Features

- **Startup Integration:** The software is designed to run at startup using bash programming, ensuring continuous clipboard management.

- **Clipboard History:** Anything copied is saved, creating a history of the clipboard content for later reuse.

- **PyQT GUI:** The Graphical User Interface (GUI) is built using PyQT, providing a user-friendly experience.

- **SQLite Database:** Utilizes SQLite for data storage, ensuring efficient and lightweight management of clipboard data.

[Github repository link](https://github.com/partho5/clipboard-manager)




# Live cricket score updating website

Admin panel to add, edit, publish live cricket match. Shows in live update page. Developed using laravel, nodejs, mysql.
    
[Github repository link](https://github.com/partho5/crickbd)



# Facebook Fun App - Character Certificate

A fun Facebook app that utilizes the Facebook Graph API to retrieve user information such as name, email, date of birth, etc. The app then employs some logic to generate random and humorous results along with the user's profile image, creating a light-hearted and entertaining experience.

### How It Works

1. **Facebook Graph API Integration:** The app interacts with the Facebook Graph API to fetch user details from their profile.

2. **Logic and Random Results:** Employing a creative algorithm or logic, the app generates funny and random character certificate results based on the user's information.

3. **Profile Image Integration:** The results are presented along with the user's profile image for a personalized touch.

[Github repository link](https://github.com/partho5/facebook-fun-app-character-certificate)


# Newspaper headlines crawler
Collects all the headlines from Daily Star, Jugantar, Ittefaq, Kaler Kantho - these newspapers. A HTML page is created as showing in the screenshot attached below. That page is just a list of headlines. So that user can skim through all the headlines and read only desired news. Reading this way s/he can read all important news of the day from 4 newspapers in significantly less amount of time. [Github repository link](https://github.com/partho5/newspaper-headlines-crawler)


# Yoga Practice App

### Overview

The Yoga Practice App is designed to facilitate the practice of six crucial yoga asanas, providing users with guidance through images of each stance along with proper timing. This app aims to enhance the yoga practicing experience by incorporating structured sessions with visual cues and auditory notifications.

### Features

- **Six Crucial Asanas:** The app focuses on guiding users through six fundamental yoga asanas, promoting a holistic approach to yoga practice.

- **Stance Visualization:** Each yoga stance is accompanied by an image, providing users with a visual reference to ensure proper form during practice.

- **Timed Sessions:** The app displays each yoga stance for a specific period, allowing users to focus on the posture and transition between poses seamlessly.

- **Auditory Cues:** A beep tone is played at the end of each stance to notify users to transition to the next pose, creating a rhythmic and meditative experience.

- **Completion Tone:** Upon completing all the asanas in the session, a distinct completion tone is played, signaling the end of the practice.

[Github repository link](https://github.com/partho5/Yoga)


# IP Location

The simplest way to get a user's location using their IP address. This application takes an IP address as input and retrieves information such as country, city, region, ISP name (org), geolocation (latitude, longitude), postal code, timezone, response_time, etc. The project demonstrates how to achieve this using PHP, but you can implement it in any language using cURL.
[Github repository link](https://github.com/partho5/ip-location)



# Funny sum game
Simple number summing game, but it's funny to play. This project is one of my earliest works when I was a beginner coder. 
[Github repository link](https://github.com/partho5/funny-sum-game)


# Send SMS
Takes a .txt file containing mobile number list and sends sms. It's a bulk sms sender having some customization.
[Github repository link](https://github.com/partho5/SendSMS)



# Online News Portal

A fully-fledged online news portal developed in PHP using the Laravel framework. This platform allows administrators to add, edit, and delete news articles, categorized under different categories. Users can explore detailed articles by clicking on headlines, and administrators have the ability to manage news categories. The portal also features a tabbed panel showcasing the most viewed news, and visitors can engage by commenting after registering or logging in.

### Key Features

- **Admin Panel:**
  - Add, edit, and delete news articles.
  - Create, edit, and delete news categories.

- **News Categories:**
  - Categorizes news articles for organized presentation.

- **Detailed Articles:**
  - Clicking on headlines opens detailed articles in a new tab.

- **Most Viewed News:**
  - Displays the most viewed news in a tabbed panel.

- **User Interaction:**
  - Visitors can comment by registering or logging in.

[Github repository link](https://github.com/partho5/news-portal) 




## Thank You

Thanks for visiting my GitHub homepage! Feel free to explore my repositories and get in touch if you have any questions or collaboration opportunities.
