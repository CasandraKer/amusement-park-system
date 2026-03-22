# amusement-park-system
Simulation of an amusement park system with business logic and system interactions.
# Amusement Park System

## Overview
This project simulates an amusement park system focusing on business logic and system interactions.

The system models how visitors, rides, tickets, and employees interact in a real-world scenario.

## Key Features

- Ticket validation (ride-specific tickets, premium tickets)
- Ride capacity management
- Height restrictions
- Ride lifecycle (operational, maintenance, closed)
- Employee roles (operator, manager)
- Ride breakdown logic and repair system
- Visitor tracking and statistics

## Business Rules

- Visitors must have a valid ticket for a specific ride
- Premium tickets can bypass certain restrictions
- Underage visitors can trigger ride maintenance
- Ride closes after repeated rule violations
- Only authorized employees can repair rides
- Rides require operators to function

## Entities

- Visitor
- Ticket / PremiumTicket
- Ride
- Employee
- LinnanMaki (main system)

## Purpose

This project demonstrates system analysis and modeling skills, including:
- translating business rules into logic
- handling system state
- designing interactions between entities
