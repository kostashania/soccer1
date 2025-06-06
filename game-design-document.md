Gdevelop soccer
Game Design Document: Interactive Soccer Manager
Core Gameplay Concept
A soccer management game where players make real-time tactical decisions during matches that influence the outcome, combined with team management features.
Match Gameplay Interactions
In-Match Decisions
Formation changes during play
Player substitutions
Tactical adjustments (attacking/defensive stance)
Set piece decisions (corners, free kicks)
Player instructions (mark specific opponent, play aggressive/conservative)
Event-Based Decision System
Critical moments pop up requiring player input
Injury situations
Red/yellow card responses
When team is losing/winning
Derby matches special events
Weather condition adaptations
Morale/Energy System
Players get tired during matches
Team morale fluctuates based on performance
Individual player confidence affects performance
Visual Presentation
2D top-down view of the field
Simple player representations (dots or basic sprites)
UI overlay for:
Score
Time
Player stats
Tactical options
Event popups
Basic Technical Implementation
Match Engine
Simple physics for ball movement
AI for player positioning
Event trigger system
Stats-based outcome calculation
Decision Interface
Pop-up windows for choices
Quick-access tactical buttons
Substitution interface
Formation adjustment screen
Team Management Features
Squad Management
23-player roster
Player Stats:
Speed
Shooting
Passing
Defense
Stamina
Morale
Form
Injury status
Training System
Weekly training focus
Individual player development
Team tactics practice
Recovery management
Season Structure
League matches (38 games)
Cup competitions
Friendly matches
Transfer windows (2 per season)
Progression System
Team Development
Club facilities improvement
Youth academy
Staff hiring
Stadium upgrades
Manager Experience
Reputation system
Achievement unlocks
Career statistics
Performance bonuses
Economy System
Budget Management
Transfer budget
Wage budget
Match income
Facility maintenance costs
Sponsorship deals
Revenue Streams
Ticket sales
TV rights
Merchandise
Player sales
Technical Implementation in GDevelop
Match Engine Core Systems
code

A. Main Game Loop - 90-minute match timer (scaled time) - Ball physics and movement - Player AI movement patterns - Possession changes - Score tracking B. Event System - Random event generator based on: - Match time - Score - Team stats - Player conditions - Match importance
User Interface Layout
code

A. Match Screen - Top: Score, time, match stats - Bottom: Quick tactics, substitution button - Side: Player status bars - Center: Playing field - Pop-up: Decision events B. Team Management Screen - Squad overview - Formation editor - Player stats - Team tactics
Save System
code

- Auto-save after matches - Multiple save slots - Save data includes: - Team information - Player stats - Season progress - Financial status - Achievement records
First Development Phase (MVP)
code

Priority Features: 1. Basic match simulation 2. 3-4 types of in-match decisions 3. Simple team management 4. One season structure 5. Basic save system

