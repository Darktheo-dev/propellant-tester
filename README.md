# propellant-tester



Propellant Testing Record System

Project Purpose

This system helps aerospace engineers test rocket propellant performance and record the results securely.

It allows users to:
	•	Start a new rocket engine test session
	•	Input or collect real-time data such as thrust, temperature, and pressure
	•	Automatically calculate performance metrics like Specific Impulse (ISP), Burn Rate, and Thrust Coefficient using C++
	•	Store all test data in a local SQLite database
	•	Securely log in using Firebase Authentication
	•	Review and analyze previous tests
	•	Optionally simulate or supplement sensor data using external APIs

⸻

Key Features
	•	Secure login with Firebase Authentication
	•	Start and configure new test sessions
	•	Real-time or manual entry of measurement data
	•	C++ module for accurate performance calculations
	•	SQLite database for storing and retrieving test records
	•	Web-based dashboard for managing and reviewing tests
	•	Optional integration of external APIs (e.g., weather or sensor data)

⸻
Tech Stack

Component   Technology
Frontend    HTML, CSS, JavaScript
Backend     Python (FastAPI)
Calculation Logic  C++
Database     SQLite
Authentication  Firebase Authentication
External APIs Weather API, sensor APIs (optional)
