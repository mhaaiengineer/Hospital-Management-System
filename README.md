# Hospital Management System (C++)

A console-based Hospital Management System developed in C++ that manages patient information, stores date of birth records using a linked list, and schedules appointments through a menu-driven interface.

## Overview

This project was developed as a Data Structures & Algorithms lab/group project. It demonstrates the use of object-oriented programming and basic data structures in a healthcare-related management system.

The system allows users to:
- Enter new patient information
- Store and display patient date of birth records
- Schedule patient appointments
- View scheduled appointments
- Interact with the system through a simple console menu

## Features

- Patient information entry
- Date of birth management using a linked list
- Appointment scheduling
- Display of patient details
- Display of scheduled appointments
- Menu-driven console interface

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Linked List
- Vector
- Console-based UI

## Project Structure

- `main.cpp` – Main source code for the Hospital Management System
- `README.md` – Project documentation

## Classes Used

### Address
Stores patient address information such as:
- House number
- Street
- City
- State
- Country

### Age
Represents the patient's age information.

### PatientInfo
Stores complete patient details including:
- Name
- Address
- Age
- Marital status
- Registration number
- Blood group
- Sex

### Node
Represents a node in the linked list for storing date of birth records.

### DOBLinkedList
Manages date of birth records using a linked list.

### Appointment
Stores appointment details such as:
- Patient name
- Appointment date

### AppointmentScheduler
Handles appointment scheduling and displays all scheduled appointments.

### HospitalManagementSystem
Main system controller that integrates all functionalities.

## How It Works

When the program starts, the user is shown a menu with the following options:

1. Enter a new patient information
2. View details of existing patients
3. Schedule an appointment
4. View scheduled appointments
5. Exit the program

The program continues running until the user selects the exit option.

## How to Run
./hospital_management
### Using g++
Compile the program:

```bash
g++ main.cpp -o hospital_management
