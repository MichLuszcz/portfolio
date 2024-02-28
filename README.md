# Michał Łuszczek

## Tools and languages
- **git** and **Github** for group projects, making use of issues, code reviews, automatic testing
- C++
- Python
- Java, Springboot REST API design
- Typescript (basic knowledge)
- SQL and PLSQL
- Assembly (basic knowledge)

## Things I'd like to learn
- UX design
- the software design process

## Education
- 2022-currently | Computer Science, Warsaw University of Technology

### Projects
- ### [Web application for rating language courses on WUT](https://pap.mgarbowski.pl) (will be opened as open-source soon)
	 Our faculty had a website for rating different courses and professors, but our university had been lacking something similar for the language courses. This application is meant to solve that problem by allowing users to (having first created an account) rate different language classes and their teachers, so the next students can choose knowing how others felt about the class. The app features a secure registration and login procedure requiring an email confirmation and using JWTs for user verification. The users are able to engage in discussions under each course review, as well as report any content they deem hurtful, false or otherwise harmful to the administrators, which review the reports in a special admin panel and decide what to do next.
	 The backend of the app is written in Java using Springboot. The frontend uses React and Typescript. 
	 
	 I was responsible for:
	 - modeling much of the Java classes representing objects in the database such as Courses, reviews, comments, etc. using Object-Relational Mapping
	 - Designing and writing API endpoints. 
	What I learned:
	- Designing and writing REST APIs
	- Dealing with HTTP requests
	- Object-Relational Mapping
	- Using Postman
- ## [Guide Dog app](https://github.com/Faculty-guide-dog-app-team/Faculty-guide-dog-app)
	A mobile application written in React meant to help mainly those hard of seeing find their way around universities, government buildings and other similar places. Useful to anyone wanting to quickly find their way around a building. Utilises BLE signals from transmitters (ESP-32 mikrocontrollers) placed around the building to accurately determine the users location by trilateration. The user may enter the number of the room they are looking for either by normal means or a voice command. The app uses the Dijkstra algorithm to find the shortest path to said room, and gives the user a series of detailed instructions on how to get there. 
	The app is a prototype, but could easily be expanded upon and improved. The main issue is the use of BLE instead of other, more accurate forms of determining the user's distance from the transmitters, but that's the only thing we were provided with
	I was responsible for:
	- The navigation system, using typescript and dijkstra's algorithm
	- Designing a map format for representing the building, rooms and corridors to be used by the navigation system
	- Determining the optimal placement of the BLE transmitters for maximum area coverage
	- (group meeting) Consulting with a blind person about the difficulties they faced in day-to-day life to determine the theme of the project and the functionalities needed 
- #### [Chess written in C++ using QT for the GUI](https://github.com/threescomplement/proi-chess)
	 I was responsible for the graphical interface that used the backend developed by my the other team members as well as helping out in the design process of the class hierarchy and functionalities needed in it. 
- #### [Database for a hotel with a cli app for operating the hotel](https://github.com/threescomplement/bd1-hotel-app) 
	I'm responsible for PLSQL procedures used in the database
- [AI algorithms](https://github.com/MichLuszcz/basic-AI-algorithms)
	 I know how most basic AI algorithms such as Q-Learning, Neural nets, Evolutionary algorithms, Support Vector Machines and Bayesian networks work and how to implement and use them.
- [Dijkstra algorithm](https://github.com/MichLuszcz/dijkstra-algorithm-practice)
	 A separate, smaller project focused solely on the Dijkstra algorithm

- Text game in 3 languages using different programming paradigms:
  - [Prolog](https://github.com/MichLuszcz/space-text-game-prolog)
  - [Haskell](https://github.com/MichLuszcz/space-text-game-haskell)
  - [Smalltalk](https://github.com/MichLuszcz/space-text-game-smalltalk)