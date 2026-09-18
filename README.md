# Smart India Hackathon Workshop
# Date:18/09/26
## Register Number: 212224040323
## Name: M.SREYAS
______________________________________________
## PROBLEM TITLE
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## PROBLEM DESCRIPTION
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## PROBLEM CREATERS ORGANIZATION
Ministry of Railway

## IDEA
RailNav – Smart Railway Station Navigation

RailNav is an indoor passenger assistance system that converts the railway station layout into an interactive digital map.

Instead of manually searching for a facility or asking railway staff for directions, passengers can select their destination from the application.

For example:

"Where is Platform 7?"
          ↓
Select Platform 7
          ↓
Choose current location
          ↓

Route calculation
          ↓
Step-by-step navigation

The system can guide passengers to:

Railway platforms
Ticket counters
Restrooms
Waiting halls
Food courts
Information counters
Lifts
Escalators
Entrances and exits
Emergency locations

## OBJECTIVES
The major objectives of RailNav are:
Simplify navigation inside large railway stations.
Help passengers locate facilities quickly.
Provide interactive indoor maps.
Generate suitable walking routes.
Support passengers with accessibility requirements.
Provide voice-based instructions.
Make navigation available through public kiosks.
Allow passengers to continue kiosk navigation on their smartphones.
Keep station facility information updateable.

 ## SYSTEM ARCHITECTURE
                 PASSENGER
                     |
          +----------+----------+
          |                     |
          v                     v
      MOBILE APP             KIOSK
          |                     |
          +----------+----------+
                     |
                     v
              BACKEND API
                     |
          +----------+----------+
          |          |          |
          v          v          v
      STATION     FACILITY    USER
       DATA        DATA       OPTIONS
          |          |          |
          +----------+----------+
                     |
                     v
              NAVIGATION ENGINE
                     |
             +-------+-------+
             |               |
             v               v
        ROUTE PLANNER    ACCESSIBILITY
             |               |
             +-------+-------+
                     |
                     v
             NAVIGATION OUTPUT
                /          \
               /            \
              v              v
        VISUAL MAP      VOICE GUIDANCE

## USE CASES
1. Platform Navigation

Passengers can search for a specific platform and receive directions from their current location.

Current Location
       ↓
Main Concourse
       ↓
Foot Over Bridge
       ↓
Platform 6
2. Facility Discovery

Users can search for nearby facilities including:

Restrooms
Food courts
Ticket counters
Waiting areas
ATMs
Information desks

The system can display the location and route to the selected facility.

3. Accessibility Navigation

Passengers can select an accessibility preference before starting navigation.

Wheelchair Mode
       ↓
Avoid Stairs
       ↓
Use Lift
       ↓
Use Ramp
       ↓
Reach Platform
4. Voice-Based Navigation

The system can provide audio instructions during navigation.

Example:

"Continue straight."
"Turn left near the ticket counter."
"Take the lift to the next level."
"Your destination is ahead."
5. Kiosk Assistance

Passengers can use touchscreen kiosks installed at important areas of the station.

The kiosk can display the route and generate a QR code that allows the passenger to transfer the route to their smartphone.

6. Emergency Location

The system can help passengers locate emergency exits and other important safety facilities.

## SYSTEM WORKFLOW
Open RailNav
      ↓
Select Railway Station
      ↓
Set / Detect Starting Location
      ↓
Search Destination
      ↓
Select Facility or Platform
      ↓
Choose Route Preference
      ↓
Calculate Route
      ↓
Display Navigation
      ↓
Follow Directions
      ↓
      
## TECHNOLOGY STACK
Frontend
React.js
Vite
JavaScript
HTML5
CSS3
Three.js
React Three Fiber
Backend
Node.js
Express.js
REST APIs
Database
MongoDB
MongoDB Atlas
Navigation Engine
Python
NetworkX
A* Search
Dijkstra's Algorithm
Voice & Accessibility
Web Speech API
Text-to-Speech
Speech Recognition
Development Tools
Visual Studio Code
Git
GitHub
Postman

## DEPENDENCIES
Frontend
react
react-dom
react-router-dom
three
@react-three/fiber
@react-three/drei
axios
## BACKEND
express
mongoose
cors
dotenv
## NAVIGATION ENGINE
python
networkx
numpy
## DEVELOPEMENT DEPENDENCIES
vite
nodemon
## VOICE AND BROWSER APIS
Web Speech API
Speech Recognition API
Text-to-Speech API



