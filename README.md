![FlightPlan](static/images/screenshots/FlightPlanLogo.png)



<h1 align="center">FlightPlan</h1>

<h4 align="center">This version of FlightPlan has been deployed to AWS with static files served by S3 </h4>

> FlightPlan is an application I created to maintain a log of drone flights. I am a commercial drove pilot and fly for live television broadcasts, often in locations that require FAA approval. For this reason, I am required to keep a flight log. I also keep a flight log to keep track of flight time for each of my drones.

## Technology Stack:


> ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![NGINX](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)  

## My goal for this application is:
1. Single User Pilot record
2. Maintain FAA Pilot License Information
3. Maintain Flight records 

___


### Flight Information:
1. Total hours flown by pilot
2. Total hours flown by drone
3. Flight Information:
    * Location
    * Drone
    * Time
    * Approval required for flight
    * Notes  
            

###  Drone information
1. Serial Number
2. FAA Registration Number
3. FAA Renewal Date  


###  Pilot Information:
1. Total hours flown
2. Time flown, by Drone
3. FAA license information  

## My database includes:
-   User tables for login and authentication
-   Drones Table
-   Flights Table
-   Profiles Table  

### Relationships:
1. Flights - Profile: Foreignkey
2. Flights - Drones: Many To Many
3. User - Profile: One To One  

### CRUD Operations:
- Drones 
- Flights  

___


<h1 align="center">Links</h1>

* GitHub Local Version:  https://github.com/Tom-Stout325/flightplan-local.git

* GitHub AWS Version:  https://github.com/Tom-Stout325/flightplan-aws.git

* Docker Hub:  https://hub.docker.com/u/tomstout325  

___

<h1 align="center">Instructions</h1>


1. Create a PostgreSQL database:  
    - drones

2. A sample database is provided:
    - Flights-Drones.sql
    - Copy the SQL statments into PGAdmin and run

3. Create a virtual environment
    - python3 -m venv venv

4. Run virtual environment:
    - source venv/bin/activate

5. Install packages:    
    - pip install -r requirements.txt



<h1 align="center">Screenshots</h1>

> ![Home](static/images/Home.png)
![Login](static/images/Login.png)
![Profile](static/images/profile.png)
![Flights](static/images/flights.png)
![flight](static/images/flight.png)
![Drones](static/images/drones.png)
![drone](static/images/drone.png)
![Insomnia](static/images/FP_insomnia.png)
![S3 Feed](static/images/AWS_S3.png)
![AWS](static/images/FlightPlan-AWS.png)
