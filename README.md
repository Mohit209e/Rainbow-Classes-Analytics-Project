# 📚 Rainbow Classes Analytics Project

## Overview
A comprehensive educational analytics dashboard tailored for Rainbow Classes, focusing on in-depth analysis of class and individual student performance.

## Table of Contents
- [Project Need](#project-need)
- [Solution](#solution)
  - [Database Design](#database-design)
  - [Dashboards](#dashboards)
- [Tools & Technologies](#tools--technologies)
- [Future Enhancements](#future-enhancements)
- [Acknowledgments](#acknowledgments)

## 🎯 Project Need
Rainbow Classes, an esteemed educational institution, was in search of a robust analytics solution for:
- Macro-level monitoring of class performance, understanding average scores, test topics, and spotlighting top and bottom performers.
- Micro-level insights into individual student performance across varied subjects and over time.

## 🌟 Solution

### Database Design
- **Star Schema Tables**: Crafted for optimized data storage and swift retrieval.
  - `students_table`: Details of each student.
  - `tests_table`: Information pertaining to different tests.
  - `subjects_table`: Data about distinct subjects.
  - `performance_table`: Scores of students across varying tests.
  - `chapters_table`: Data on chapters within each test.

### Dashboards
- **Class Overview Dashboard**:
  - **Average Scores by Subject**: An immediate overview of class performance per subject.
  - **Top and Bottom Performers**: Recognize students who excel or may require additional assistance.
  - **Test Topics Covered**: Insight into curriculum coverage.

- **Individual Student Analysis Dashboard**:
  - **Performance Breakdown by Subject**: Insightful data on each student's performance in subjects.
  - **Zoom In Feature**: A deep dive into a single test's metrics, highlighting strengths and areas of growth.

## 🛠️ Tools & Technologies
- **Database**: MySQL
  - Central to the creation and management of a structured database.
  - Ensures rapid data retrieval for dashboard updates.
  
- **Data Visualization**: Power BI
  - Expertly designed dashboards that are visually appealing and informative.
  - Interactive features, including the 'Zoom In' tool, add depth to the analysis.

## 📈 Future Enhancements
- Integrate with interactive learning metrics for richer insights.
- Utilize predictive analytics for identifying potential top performers and students who might be at risk.

## 🙏 Acknowledgments
Special thanks to Rainbow Classes for this golden opportunity and to the vast open-source community for the constant support and knowledge exchange.

