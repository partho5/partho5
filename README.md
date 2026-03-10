### Hi there, I am Full-stack Devloper and AI Engineer who works at System Level

I am a 𝘀𝗲𝗹𝗳-𝗱𝗶𝗿𝗲𝗰𝘁𝗲𝗱, 𝗽𝗿𝗼𝗱𝘂𝗰𝘁-𝗱𝗿𝗶𝘃𝗲𝗻 𝗯𝘂𝗶𝗹𝗱𝗲𝗿 who owns the projects end to end → from idea to delivery, no handholding required.<br>
I 𝘀𝗽𝗼𝘁 𝗽𝗿𝗼𝗯𝗹𝗲𝗺𝘀 𝗲𝗮𝗿𝗹𝘆, fill gaps before they're asked. I think in 𝘃𝗮𝗹𝘂𝗲, 𝗻𝗼𝘁 𝗷𝘂𝘀𝘁 𝗰𝗼𝗱𝗲 : connecting user pain, business goals, and technical execution.

<br>

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



- Dev skills: React.js · Next.js · Typescript · Node.js · Express.js · PHP · Laravel · MySQL · NoSQL · PostgreSQL · DynamoDB · AWS(EC2, S3, Lambda, DynamoDB etc.) · Firebase · HTML, CSS, Bootstrap · Tailwind · Python · FastAPI · Android · API development & Integration · Chrome Extension
   
- AI Skills: Claude API · OpenAI API · Grok (xAI) · LangChain · AI Agents & Automation · Prompt Engineering · LLM Integration · RAG (Retrieval-Augmented Generation) · MCP (Model Context Protocol) · AI-powered content pipelines
  
-  Also worked with: Java · Spring Boot · Linux · Apache, NGINX · C# · Flask · IOT · Arduino · NodeMCU
<br>

## Let's talk about some of my projects

# SEO Article Writer - OpenAI, AI Agent

An advanced AI tool that can  **mimic Human-Writing style** in a degree that you can't tell the difference. generates **SEO-friendly, long-form articles** with **featured image** and **in-article images**—instantly. It performs complete On-page SEO along with the article.  It writes all the articles complying **Google's E-E-A-T** guideline.

### Features  

- **Simple Input:** Just enter a **keyword** to create a full article.  
- **AI-Optimized Writing:** Uses smart prompts to ensure **quality and relevance**.  
- **SEO-Ready Content:** Achieves top **SEO and readability scores**.  
- **Extended Content Generation:** Expands articles **dynamically** using AI.  
- **Auto-Generated Images:** Creates **featured and contextual images**.  
- **External Link Automation:** Adds **relevant authority links** via Google CSE.  
- **Internal Linking:** Automatically Adds internal links in article if match found in your wordpress blog.  
- **One-Click Publishing:** Direct posting to **WordPress with metadata**.  
- **Cloud Storage:** Secure image hosting with **AWS S3 integration**.

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

---


# AI Hardware Diagnostics Software - RAG & Computer Vision

An advanced AI orchestration layer designed to serve as the "intelligence engine" for a specialized maintenance and diagnostics mobile ecosystem. It bridges high-level user symptoms with technical precision by enriching raw data with historical context, asset specifications, and real-time visual analysis.

### Features

* **Context-Aware Enrichment:** Dynamically injects asset service history, available toolsets, and specific model metadata into AI prompts to eliminate generic advice.
* **Multi-Modal Diagnostics:** Integrates Gemini Vision to analyze photos of mechanical components, extracting structured findings like part condition and damage severity.
* **Intelligent RAG (Retrieval-Augmented Generation):** Utilizes a vectorized document system (ChromaDB) to ground AI responses in specific technical manuals and PDFs, filtered strictly by asset ID to prevent data leakage.
* **Automated Confidence Scoring:** Implements a multi-factor scoring algorithm (Symptom Match, History Alignment, Specificity) that triggers self-critique loops if reliability falls below a 50% threshold.
* **Dynamic Persona Mapping:** A 5-level "Temperature Slider" that transforms response complexity from "Simple/Non-Technical" to "Expert/Professional" terminology based on user preference.
* **Dual-Pass Validation:** Low-confidence diagnoses automatically trigger an AI self-reflection cycle to check for hallucinations and missed variables before returning results.

### Technologies Used

* FastAPI (Python)
* Grok API (X.AI)
* Gemini Vision API
* ChromaDB (Vector Storage)
* LangChain (Document Processing)
* OpenAI Embeddings
* Pydantic (Data Validation)

### Business Impact

* **Increased Reliability:** Reduces AI hallucinations by grounding responses in verified technical documents and specific asset history.
* **Safety-First Architecture:** Automatically flags high-risk repairs (electrical, fuel, structural) to prioritize user safety and liability management.
* **Operational Efficiency:** Offloads complex AI logic from the primary backend, creating a clean separation between data storage and cognitive processing.
* **Scalable Expertise:** Allows a standard mobile app to function as a "mechanic in your pocket," providing expert-level guidance instantly without manual oversight.

---


# Glass Installation Workflow System – ERP & Field Service Automation

A production-ready enterprise resource planning (ERP) and field operations platform specifically engineered for glass installation businesses. This system digitizes the entire lifecycle of a project—from automated pricing and inventory checks to mobile-first field execution and automated billing.

### Features

* **Automated Pricing Engine:** Implements a sophisticated 3-way match logic (Client + Truck Model + Glass Position) to generate real-time price previews and instant inventory status via Notion.
* **Dynamic Order Workflow:** Manages project lifecycles through a specialized status pipeline (Pending → In Stock → Scheduled → Completed → Invoiced).
* **Mobile Field Wizard:** A specialized dashboard for technicians featuring step-by-step job execution, GPS-verified timestamps, and touch-supported digital signature collection.
* **Evidence-Based Documentation:** Integrated photo capture system requiring 3 "before" and 1 "after" photo, with real-time progress saving and secure Cloudinary storage.
* **Automated Billing Pipeline:** Generates professional PDF invoices using React components and automates delivery via the WhatsApp Business API (Twilio).
* **Multi-Tenant & Multilingual:** Full internationalization (Spanish/English) support with secure user authentication and role-based access control.

### Technologies Used

* Next.js 16 (App Router)
* TypeScript
* Notion API v5 (Database)
* Clerk (Authentication)
* Cloudinary (Media & PDF Hosting)
* Twilio (WhatsApp Business API)
* Tailwind CSS 4
* @react-pdf/renderer

### Business Impact

* **Operational Accuracy:** Eliminates pricing errors by automating complex calculations that previously relied on manual lookups.
* **Field Accountability:** Ensures service quality and proof-of-work through mandatory photo evidence and GPS-stamped job completion.
* **Accelerated Cash Flow:** Reduces the billing cycle from days to seconds with bulk invoice generation and instant WhatsApp delivery.
* **Zero Infrastructure Overhead:** Leverages Notion as a headless CMS/Database, drastically reducing backend maintenance costs and providing an intuitive interface for non-technical admins.

---


# Automated Facebook Brand Growth Bot

A fully autonomous content engine that manages an English-to-Bengali vocabulary page. The system handles the entire creative pipeline—from linguistic storytelling and image generation to automated publishing—ensuring a consistent social media presence with zero manual intervention.

### Features

* **Contextual Storytelling:** Uses GPT-4o / Claude to draft natural Bengali narratives featuring a recurring character, "Toma," weaving target IELTS/GRE words into relatable contexts.
* **Dynamic Image Compositing:** Automatically generates scene-specific artwork via Replicate (SDXL) and composites it onto a custom 1080×1350 canvas with branded headers and labels.
* **Cross-Platform Formatting:** Converts standard Markdown bolding into Unicode Mathematical Bold ($𝐰𝐨𝐫𝐝$), ensuring key vocabulary stands out on Facebook despite the platform's lack of native Markdown support.
* **Self-Healing Token Management:** Features an automated OAuth flow that converts short-lived access tokens into permanent Page tokens, eliminating the need for manual re-authentication.
* **Smart Scheduling & Persistance:** Powered by APScheduler to post at high-traffic intervals (08:00, 12:00, 18:00, 20:00) while maintaining a persistent state of the word list across system restarts.
* **Automated Field Execution:** Includes a "Single-Command Deploy" script and a FastAPI webhook for manual overrides or external triggers.

### Technologies Used

* Python (FastAPI)
* OpenAI GPT-4o / Anthropic Claude
* Replicate (SDXL-Lightning)
* Pillow (PIL) for Image Processing
* Facebook Graph API
* APScheduler
* Bash Scripting

### Business Impact

* **Zero Manual Input:** Replaces the need for a full-time content creator and graphic designer, managing 4–5 high-quality posts per day automatically.
* **Rapid Deployment:** Entire automation architecture built and deployed in under 8 hours.
* **Consistent Engagement:** Maintains a strict posting schedule that optimizes for the Asia/Dhaka timezone, driving steady follower growth and brand authority in the Ed-Tech space.
* **Scalable Education:** Easily adaptable to other languages or niche subjects by simply swapping the prompt engineering and word lists.

---


# Trading Data Hub – Financial API & Data Aggregator

A high-performance financial data ecosystem built with FastAPI, designed to aggregate real-time market insights from multiple premium sources into a single, unified API. It features a robust asynchronous architecture, secure multi-tier authentication, and a plugin-based system for seamless data source expansion.

### Features

* **Unified Data Aggregator:** A specialized plugin architecture that fetches and normalizes data from Yahoo Finance, Finviz, Alpha Vantage, and Benzinga via a single endpoint.
* **Advanced Market Insights:** Access to real-time quotes, historical OHLCV charts, pre/post-market data, analyst ratings, and insider trading activity.
* **Smart Caching Layer:** Integrated Redis caching with configurable TTL (Time-To-Live) to minimize API latency and reduce external service costs.
* **Enterprise Auth & Security:** Implements JWT-based authentication with 60-minute access tokens and persistent refresh tokens, including role-based access for Administrative and Superuser tiers.
* **Automated Data Ops:** Built on `FastCRUD` and SQLAlchemy for rapid, typed database interactions with built-in support for Soft Deletes, Pagination, and UUID primary keys.
* **Production-Ready Deployment:** Full support for containerized deployment via Docker Compose or high-performance VPS setup using Systemd and Nginx reverse proxying.

### Technologies Used

* FastAPI (Python 3.12+)
* Neon (Serverless PostgreSQL)
* Redis (Caching & Task Management)
* SQLAlchemy & Alembic (Migrations)
* Docker & Docker Compose
* Pydantic (Data Validation)
* uv (Next-gen Python Package Manager)

### Business Impact

* **Consolidated Intelligence:** Replaces multiple expensive financial subscriptions with a single, custom-tailored API hub.
* **Performance at Scale:** Asynchronous design ensures the system can handle concurrent market data requests without blocking, critical for high-frequency trading dashboards.
* **Developer Productivity:** Drastically reduces feature development time through a standardized "Model-Schema-CRUD-Router" workflow.
* **Market Edge:** Provides specialized market indicators like the VIX Fear Index, unusual volume alerts, and economic calendars to drive informed trading decisions.

---




# Tweeter Auto Posting Bot - Browser Automation, Chrome Extension

A lightweight Chrome extension for automated tweeting without the need for the Twitter API, designed to emulate normal user behavior to avoid bot detection.

## About

The Tweeter Auto Posting Bot eliminates the need for costly Twitter API plans (up to $5000/month). Instead, it utilizes a browser-based approach to emulate user interactions, making it a cost-effective solution for automated tweeting.

## Features

- **Random Time Gaps**: Posts are made with a random delay (1 to 20 seconds) between them to minimize the risk of detection as a bot.
- **Quota Tracking**: The bot tracks Twitter's posting quotas (300 tweets every 3 hours and a maximum of 2400 tweets per day) and automatically pauses after every 3-hour cycle.
- **Content Management**: Save a list of text; the bot will post each line sequentially.
- **Content Variation**: To avoid posting identical content, the bot adds random characters (e.g., 🙂 👍 ⚡ ✅) to the posts without changing their meaning.
- **Detailed Logging**: Provides log messages to show the current activity of the bot.




# LinkedIn Content Automation API - Professional Brand Building
**Transform Your LinkedIn Presence**

## About
A comprehensive LinkedIn automation platform that revolutionizes professional social media management by combining AI-powered content creation, intelligent image generation, and strategic posting automation. Built for professionals who understand the power of consistent LinkedIn presence but lack the time for daily content creation.

### Business Impact & Features
**Transform Your LinkedIn Presence**
* **10x Content Output**: Generate and post professional LinkedIn content automatically
* **Zero Creative Block**: AI-powered content ideas that resonate with your audience  
* **Consistent Brand Voice**: Maintain professional, engaging tone across all posts
* **Time Savings**: Reduce content creation time from hours to minutes

**Complete Content Pipeline**
* **🎯 Smart Idea Generation**: AI identifies trending topics and industry-relevant content ideas
* **✍️ Professional Content Creation**: Generate engaging LinkedIn posts with proper formatting
* **🖼️ Custom Image Generation**: Create relevant, professional images for each post
* **📱 Automated Posting**: Schedule and publish content directly to LinkedIn
* **📊 Performance Tracking**: Monitor post engagement and pipeline success

### Business Benefits
* **Increased Engagement**: Professional, consistent content drives higher LinkedIn engagement
* **Brand Authority**: Regular posting establishes thought leadership in your industry
* **Lead Generation**: Quality content attracts potential clients and business opportunities
* **Time Efficiency**: Focus on core business while maintaining active social presence
* **Scalable Growth**: Automate content creation to support business expansion

### Perfect For
* **Entrepreneurs & Business Owners**: Maintain professional LinkedIn presence
* **Marketing Teams**: Scale content creation without additional resources
* **Consultants & Freelancers**: Showcase expertise and attract new clients
* **Sales Professionals**: Generate leads through consistent, valuable content
* **Startups**: Build brand awareness and credibility cost-effectively

---

# X-Post Replicator - AI-Enhanced Content Migration
An intelligent content replication system that automatically copies, enhances, and reposts content between X (Twitter) accounts using AI-powered content optimization.

## About
This tool bridges the gap between content inspiration and original posting by intelligently replicating high-performing tweets while adding unique value through AI enhancement. Perfect for content creators who want to leverage successful content patterns while maintaining authenticity.

### Features  
- **Smart Content Fetching:** Automatically pulls high-performing tweets from source accounts
- **AI Content Enhancement:** Polishes and improves original content while preserving core message
- **Authenticity Preservation:** Maintains natural voice while avoiding direct copying
- **Performance-Based Selection:** Identifies and replicates only high-engagement content
- **Automated Scheduling:** Strategic timing for maximum reach and engagement
- **Duplicate Prevention:** Ensures no repetitive content across your timeline

### Business Impact
- **Content Velocity:** Accelerates content production without sacrificing quality
- **Engagement Growth:** Leverages proven content patterns for better performance  
- **Brand Consistency:** Maintains your unique voice while expanding content variety
- **Resource Optimization:** Reduces content research and ideation time by 80%

---

# Twitter Automation FastAPI Platform - Complete Content Pipeline
A comprehensive automation platform that creates an end-to-end Twitter content pipeline, from sourcing and enhancing tweets to automated publishing with intelligent content management.

## About
This enterprise-grade Twitter automation solution provides a complete content workflow system. It transforms how businesses and content creators manage their Twitter presence by automating the entire content lifecycle—from discovery to publication.

### Features
* **Tweet Scraping**: Download recent tweets from any source account with media URLs
* **Media Management**: Download and store all associated media locally
* **AI Content Polishing**: Enhance tweet content using OpenAI API
* **Type-based Organization**: Classify and manage tweets by type (General, Promotional, News, etc.)
* **Duplicate Prevention**: Avoid posting duplicate content
* **SQLite Database**: Track all tweet metadata and status
* **RESTful API**: Complete FastAPI interface for all operations
* **Two-Account Architecture**: Scrape from source accounts, post to destination account (API keys)
* **Automated Workflow**: Complete end-to-end automation with step-by-step execution
* **Cron/Systemd Integration**: Ready for automated scheduling
* **Robust Error Handling**: Comprehensive error handling and logging

### Business Impact
- **Operational Efficiency:** Replaces 20+ hours of weekly manual work with automated workflows
- **Content Quality:** AI enhancement ensures every post meets professional standards
- **Growth Acceleration:** Consistent, high-quality posting drives 3x faster follower growth
- **Risk Mitigation:** Advanced duplicate prevention and content classification prevent brand issues
- **Scalability:** Handles multiple accounts and unlimited content volume without additional overhead
- **ROI Optimization:** Reduces content team overhead while improving engagement metrics

---

# YouTube-to-X Auto-Posting Pipeline - Video Content Repurposing
An intelligent content transformation system that automatically converts YouTube video concepts into engaging X (Twitter) posts, maximizing content reach across platforms.

## About
This automation bridges the gap between long-form YouTube content and social media engagement by intelligently extracting key insights from videos and transforming them into Twitter-optimized posts. Perfect for content creators who want to maximize their content investment across multiple platforms.

### Features
* **YouTube Integration**: Automatically scan channels for new videos
* **Transcript Extraction**: Extract video transcripts using Supadata API
* **AI-Powered Tweet Generation**: Convert transcripts to engaging tweets using OpenAI
* **X (Twitter) Posting**: Automatically post generated tweets
* **SQLite Database**: Local database for tracking videos and posts
* **FastAPI REST API**: Secure endpoints for manual triggering and monitoring
* **Bearer Token Authentication**: Secure API access
* **Clear Workflow Instructions**: Complete endpoint usage and workflow documentation

### Business Impact
- **Content ROI Maximization:** Transforms single YouTube videos into multiple social media touchpoints
- **Audience Expansion:** Reaches Twitter audiences who may not discover YouTube content organically  
- **Engagement Amplification:** Drives traffic back to YouTube while building Twitter following
- **Time Efficiency:** Eliminates manual video-to-social content adaptation (saves 5+ hours weekly)
- **Cross-Platform Synergy:** Creates cohesive content strategy across video and microblogging platforms
- **Lead Generation:** Twitter posts act as traffic drivers to monetized YouTube content



# 🔗 URL shortener for Affiliate Marketing

## 🧠 Overview
A custom short URL generation tool built to streamline the sharing of long-form article links, specifically designed for SEO and affiliate marketing workflows. This project addresses the need for cleaner, more manageable URLs for campaigns across social media, email, and blog platforms.

---

## 💡 Problem Statement
Long URLs from CMS or AI-generated article platforms often contain unnecessary parameters and poor readability. These links:
- Reduce trust and click-through rates (CTR)
- Are hard to manage in bulk
- Offer limited flexibility for campaign tracking

---

## 🛠️ Solution
I built a lightweight, domain-restricted **Short Link Generator** that allows users to:
- Convert long URLs into short, trackable links
- Handle affiliate parameters safely
- Auto-tag internal links for better analytics
- Share links without relying on third-party services like Bitly

---

## 🔍 Features
- ✅ **Short URL Generation**: Clean, simple links for any long-form URL  
- 🔐 **Domain Restriction**: Only allows shortening links from approved domains  
- 📊 **Affiliate-Ready**: Preserves UTM and referral tags for campaign tracking  
- 🧩 **Simple UI**: One-click link creation for non-technical users  
- 🛡️ **Privacy-Safe**: No external API calls—self-hosted logic  
- ⏱️ **Fast Performance**: Lightweight backend with real-time redirects



# Crypto News → X Poster | Twitter API

CryptoXPoster is an automated Python tool that **scrapes the latest cryptocurrency news** from websites and **posts updates directly to X (formerly Twitter)** few times an hour. It ensures timely and relevant crypto news sharing with minimal manual effort.

### Features

- **Automated News Scraping:** Uses BeautifulSoup to extract the most recent crypto news.  
- **Secure API Access:** FastAPI endpoint with URL parameter authentication to prevent unauthorized use.  
- **Seamless Posting:** Automatically posts top news entries to X via the official API.  
- **JSON-Based Queue:** Maintains a JSON file as a queue for news items to be posted, ensuring ordered processing.  
- **Modular & Reusable:** Designed with clean, modular code adhering to the Single Responsibility Principle.  
- **Robust Error Handling:** Implements comprehensive try-except blocks for reliable operation.  
- **Environment Configuration:** Uses environment variables for sensitive data like API keys and auth codes.

### Tech Info

- Python  
- FastAPI  
- BeautifulSoup4  
- X API v2 (Twitter API)  
- JSON  
- Environment Variables (.env)
- Cron Job

### Business Impact

- **Fully Autonomous:** Creates a complete, hands-free social media presence on X.com by automatically posting the latest crypto news.  
- **Audience Engagement:** Reaches and informs a targeted audience interested in cryptocurrency in real-time.  
- **Time-Saving:** Eliminates manual effort in curating and posting crypto updates, freeing up valuable time.  
- **Consistent Posting:** Ensures regular and timely content delivery, boosting follower engagement and retention.  
- **Cost-Effective:** Reduces the need for dedicated social media managers or content creators.  
- **Scalable:** Easily adaptable to include more news sources or other social platforms in the future.  
- **Reliable & Secure:** Uses authentication and robust error handling to maintain secure and uninterrupted operation.




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
