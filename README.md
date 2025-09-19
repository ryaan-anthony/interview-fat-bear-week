# Fat Bear Week Take-Home Exercise

## Overview
Build a Ruby web application that simulates the popular Fat Bear Week voting competition, where users can view bear competitors, participate in bracket-style voting, and track tournament results. Focus on demonstrating your Ruby skills, code organization, and ability to build a functional web application.

## Project Background
[Fat Bear Week](https://explore.org/fat-bear-week) is an annual tournament celebrating the brown bears of Katmai National Park as they prepare for hibernation. Bears compete in head-to-head voting matchups based on their impressive weight gain throughout the salmon season.

## Core Requirements

### 1. Bear Management
- **Create bears** with the following attributes:
  - Unique ID/number (e.g., #747)
  - Name (e.g., "Otis")
  - Description/bio
  - Before weight (June)
  - After weight (September)
  - Photo(s) - can use placeholder images
- **View all bears** with their stats and transformation details
- **Individual bear profiles** showing detailed information

### 2. Voting System
- **Tournament bracket structure** with elimination rounds:
  - Round 1 (8 bears → 4 bears)
  - Quarterfinals (4 bears → 2 bears)
  - Semifinals (2 bears → 1 winner)
- **Head-to-head voting** in active matchups
- **Vote tracking** and real-time vote counts
- **Prevent duplicate voting** (one vote per user per matchup)

### 3. User Authentication
- **User registration** with email and username
- **Login/logout** functionality
- **Session management**
- Only authenticated users can vote

### 4. Results & Statistics
- **Real-time vote counts** for active matchups
- **Tournament bracket visualization** showing progression
- **Bear leaderboards** ranked by total votes received
- **Basic statistics** (total votes, active users, etc.)

### 5. Data Persistence
- Use any Ruby-compatible database (SQLite recommended for simplicity)
- Proper data models and relationships
- Basic data validation

## Technical Requirements

### Core Technology Stack
- **Ruby** (any version 2.7+)
- **Web framework** of your choice:
  - Sinatra (lightweight, recommended for time constraints)
  - Rails (if you're more comfortable with it)
  - Any other Ruby web framework
- **Database**: SQLite (or PostgreSQL if preferred)
- **Frontend**: HTML/CSS/JavaScript (keep it simple)

### Code Quality Expectations
- **Object-oriented design** with proper separation of concerns
- **Clean, readable code** with meaningful variable names
- **Basic error handling** for common scenarios
- **Some tests** demonstrating testing approach (don't need 100% coverage)
- **Git version control** with meaningful commit messages

## Application Features

### Homepage
- Welcome message and competition overview
- Current tournament status
- Links to view bears and participate in voting
- Basic statistics display

### Bears Listing Page
- Grid/list view of all competing bears
- Before/after photos showing transformation
- Key stats: weight gain, current vote count
- Link to individual bear detail pages
- Optional: sorting/filtering capabilities

### Bracket Voting Page
- Visual tournament bracket layout
- Current active matchups highlighted
- Click-to-vote functionality
- Real-time vote count updates
- Clear indication of completed vs. active rounds

### Individual Bear Pages
- Detailed bear profile with full stats
- Before/after photo comparison
- Bear's tournament journey/voting history
- Links back to voting and bear listing

### Results Dashboard
- Current tournament standings
- Bear leaderboards (by total votes, weight gain, etc.)
- Tournament progress indicator
- Summary statistics

### User Authentication
- Simple registration form
- Login/logout functionality
- Basic user profile (optional)

## Evaluation Criteria

### Code Quality (40%)
- Clean, well-organized Ruby code
- Proper use of OOP principles
- Meaningful variable and method names
- Basic error handling

### Functionality (30%)
- Core voting system works
- User authentication functions
- Data persistence works correctly
- Application runs without errors

### Architecture & Design (20%)
- Logical separation of concerns
- Good database design and relationships
- RESTful routing (if applicable)
- Scalable code structure

### Testing & Documentation (10%)
- Some tests demonstrating approach
- Clear README with setup instructions
- Code comments where helpful

## Getting Started

### Sample Data
Create at least 8 bears for a complete tournament bracket. You can use real Fat Bear Week contestants like:
- Bear #747 (Otis)
- Bear #856 (Divot)  
- Bear #128 (Grazer)
- Bear #480 (Otis Jr.)
- Bear #435 (Holly)
- Bear #284 (Elektra)
- Bear #909 (Bea)
- Bear #151 (Walker)

## Submission Guidelines

### What to Include
- Complete source code
- Database schema/migrations
- Basic test suite
- README with setup instructions
- Any additional documentation

### What We're Looking For
- **Working application** that demonstrates the core functionality
- **Clean Ruby code** following best practices
- **Thoughtful architecture** decisions
- **Problem-solving approach** and technical choices
- **Attention to detail** in user experience

## Mockup References
This repository includes HTML mockups showing the expected user interface:
- `index.html` - Homepage design
- `bears.html` - Bears listing page
- `bracket.html` - Tournament bracket voting
- `bear-detail.html` - Individual bear profiles
- `results.html` - Results dashboard
- `login.html` - User authentication

Use these as visual guides, but don't feel constrained to match them exactly.

## Notes
- **Focus on functionality over polish** - a working application is better than a beautiful but broken one
- **Make assumptions** where requirements are unclear and document them
- **Ask questions** if you're truly stuck, but try to solve problems independently first
- **Use libraries/gems** you're comfortable with - don't reinvent the wheel
- **Time management** is key - prioritize core features first

## Questions?
If you have any questions about the requirements or need clarification, please reach out. Good luck, and have fun building your Fat Bear Week application! 🐻
