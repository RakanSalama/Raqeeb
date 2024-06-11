# Raqeeb: Employee and Customer Activity Tracking System

<p align="center">
  <img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/bb913a0d-dd71-4fea-a4d6-18f320c77c26" alt="ProjectLogo" width="300">
</p>

## Overview

Raqeeb is an advanced surveillance and monitoring system designed to improve business environments by closely tracking the activities of employees and customers. Raqeeb captures activities and stores the data in a robust database. Managers can access this data through interactive dashboards and detailed reports, providing a clear overview of performance and progress. This helps them make better decisions and improve efficiency. Easy to integrate with existing systems, Raqeeb enhances transparency, accountability, productivity, and customer satisfaction, making it a reliable partner for business success.

## Features
### Detailed Reports
Comprehensive Analytics generates detailed reports on employee attendance, productivity, and customer engagement, featuring visual representations with charts and graphs for easy data understanding. It also provides access to historical data, allowing you to review past reports to identify trends and make better decisions.

<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/45ccc271-5bd4-4b7b-b5ae-c165dd834cdc" alt="Report Image 1" height="300"></td>
      <td><img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/e63f49b1-b9a2-43bd-bf7f-36bb223ca743" alt="Report Image 2" height="300"></td>
    </tr>
  </table>
</div>

### Activity Tracking
Activity Tracking encompasses various metrics such as attendance tracking, which records employee check-in and check-out times, productivity monitoring which tracks the number of cups served by each employee, and customer interaction metrics which measure both the wait times and the duration of customer visits in the café.

<div align="center">
  <img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/b2d35adb-5ac0-4745-9e4c-e0499002eb93" alt="Activity Tracking" width="950" height="400">
</div>


### Facial Recognition
Customer Satisfaction Analysis evaluates customer satisfaction by analyzing facial expressions during interactions with employees, while Employee Identification ensures accurate tracking of activities by recognizing employees through facial recognition.
<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/48b6cd45-bbb1-4ddd-b8ae-225cb2536904" alt="Image 1" height="300"></td>
      <td><img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/51548ebe-5190-4bb3-b45a-cd650ab5be88" alt="Image 2" height="300"></td>
      <td><img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/21ad05e7-cef9-4b6d-9ea9-838c7316d5f4" alt="Image 3" height="300"></td>
    </tr>
  </table>
</div>

### Automated Emails
Automatically sends email updates to managers to keep them informed with the latest insights.

<div align="center">
  <img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/0e651f95-66d3-476a-b5cc-1cc189d3ddc0" alt="Automated Emails" width="950" height="400">
</div>

### Interactive Dashboards
Interactive Dashboards feature a user-friendly interface with simple designs built using Microsoft Power BI. It offers customizable views, allowing managers to display the most important data for their needs. Additionally, the dashboards provide real-time updates, ensuring the latest data is always available.

<div align="center">
  <img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/19f5a592-9ea3-4463-91e1-99188a37b327" alt="Interactive Dashboards" width="950" height="400">
</div>

### Real-Time Monitoring
Managers can access these cameras integrated into the system to view the environment and ensure everything is running smoothly.

### Data Storage and Management
All captured activities are securely stored in a SQL Server Express database, providing efficient data retrieval for quick and reliable access to stored information.

## System Architecture
The system architecture integrates multiple components to provide comprehensive monitoring and analysis. Inputs are captured via high-quality cameras and video feeds, which are processed using OpenCV for computer vision and YOLOv8 for image analysis through machine learning techniques. The processed data and analyzed videos are then managed and stored in a secure SQL Server Express database. The Python programming language is utilized for data processing tasks. Data storage is seamlessly integrated with Power BI, a data visualization tool, to create interactive dashboards and detailed reports. Authorized users, such as stakeholders and managers, can access these insights through a React web application or receive automated email reports. Additionally, robotic process automation (RPA) tools enhance the system by automating repetitive tasks, ensuring efficient and real-time data management and visualization.
<div align="center">
  <img src="https://github.com/RakanSalama/Raqeeb/assets/98660298/a228b679-d89b-495f-9ca7-e946fc913781" alt="System Architecture" width="950" height="500">
</div>

## Project Results
Watch the video below to see the results of our project in action:

<div align="center">
  <a href="https://www.youtube.com/watch?v=jnhRd7ksrjk" target="_blank">
    <img src="https://img.youtube.com/vi/jnhRd7ksrjk/0.jpg" alt="Project Demo Video" width="560" height="315">
  </a>
</div>
