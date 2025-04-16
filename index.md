# Sync'd Study

## Table of Contents
* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Meet the Team](#meet-the-team)

## Overview
*The Problem:* UHM students often spend more time than they need on their homework and don’t learn the material as effectively as they could, because they study alone and do not leverage the power of face-to-face study groups with peer mentors.

*The Solution:* Sync’d Study is a web application designed to help students at the University of Hawai‘i at Manoā optimize their study time through peer-organized, in-person study sessions. It enables students to easily propose and join study sessions in many different subjects. Students are categorized as “<ins>sensei</ins>” (helpers) and “<ins>grasshoppers</ins>” (learners) depending on the course.

### Key Features

Here's how it works: 

- **User Profiles:** Students must log in and set up their profile that includes a headshot and two course lists:
    - Courses they’ve taken and can help with. (Sensei)
    - Courses they’re currently taking and need help with. (Grasshopper)
    - Every student can be both a sensei and a grasshopper, depending on the course.

- **Course Directory:** All courses are listed on the site. Within each course, students can view the senseis and grasshoppers associated with it. 

- **Study Session Scheduling:** Grasshoppers can propose face-to-face study sessions focused on a specific topic (e.g. “Write my essay on configuration management” and a time to meet in Campus Center (i.e. 10:30-11:30 AM morning)).
    - *Plan Ahead:* Schedule a study session in advance for later in the day or week.
    - *Right Now:* Create a session instantly, notifying others that help is needed now in Campus Center.

- **Notifications:** When a session is proposed, senseis and grasshoppers for that course will receive a notification.

- **Calendar View:** A shared calendar displays all upcoming and ongoing study sessions, along with the list of attendees.

- **Gamification:** To encourage participation, the app includes:
    - A point system, levels, and a leaderboard.
    - Incentives such as gift cards for top-performing senseis and grasshoppers.
    - Anti-cheating measures to ensure points are earned through meaningful interaction. *(Feature under discussion)*

- **Admin Tools:** Admins can monitor user activity, resolve issues, and ensure the space remains safe and supportive. Users can also contact admins to report inappropriate behavior.

### Goals

- Foster in-person collaboration on campus.
- Encourage student interaction and peer mentoring.
- Promote safe, structured real-world study support.

## Deployment

Sync'd Study will be deployed at https://syncdstudy.github.io. This site provides public documentation and walkthroughs for the application.

## User Guide

This section provides a walkthrough of the Sync'd Study user interface and its capabilities.

### Landing Page

Public entry point to explain the app and link to login.

### User Home Page

Displays personal dashboard and calendar. Includes quick links to profile and study sessions.

### Admin Home Page

Displays a personal dashboard and calendar, with additional tools to monitor users, manage sessions, and oversee platform activity.

### User Profile Setup

Users declare their courses (past and present) and upload a headshot.

### Calendar Page

Visual display of all upcoming and active sessions.

### Create Study Sesh Page

Propose a new session by selecting course, topic, and time. Sessions can be scheduled in advance or "Right Now!".

### Course Pages

Each course shows sensei and grasshopper members, and active/proposed study sessions.

### Notifications

Members of the course receive alerts and can respond to confirm attendance.

### Game Mechanics

Earn points by participating in sessions, organizing events, or helping others. Weekly/monthly leaderboard available.

## Community Feedback

Have suggestions or comments? Submit your feedback through our Sync'd Study Feedback Form.

## Developer Guide

### Admin Tools

Admins can:
- Review user reports
- Moderate sessions
- Manage reward programs

## Development History

Development follows an issue-driven project management process. Tasks are managed using GitHub Projects, with branches per issue and milestones.

[Milestone 1](https://github.com/orgs/syncdstudy/projects/1):

- Initial project setup & planning completed (e.g., GitHub repository creation, mock-up sketches, deploy to Vercel).
- Created the following pages:
    - Landing Page
    - User Home Page
    - Admin Page
    - User Profile Set-up

Milestone 2: 

- No development tasks completed for this milestone yet.

Milestone 3: 

- No development tasks completed for this milestone yet.

Milestone 4: 

- No development tasks completed for this milestone yet.


## Meet the Team

Sync'd Study is developed by a team of ICS students at UH Mānoa: [Angela Joy Almeron](https://angelaalmeron.github.io/), [Silvia Arjona](https://silviaarjonag.github.io/), [Arisa Nakai](https://arisa-1208.github.io/), and [Jaimee Yokoyama](https://jamiee-tech.github.io/). For more information or contributions, visit our [GitHub repo](https://github.com/syncdstudy/syncdstudy.github.io).

Our [Team Contract](https://docs.google.com/document/d/1zECIUP7hNx_SDHHqtqRzjvWOJxT7PPx1KGY5Zllg55c/edit?usp=sharing)
