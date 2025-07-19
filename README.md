# Outing Otters

Outing Otters is a social media app designed to help introverts connect meaningfully by creating and joining events tailored to their interests. Inspired by platforms like CampusGroups, Instagram, and Tinder, the app encourages interaction by enabling users to meet new people through events. After attending an event, users unlock the ability to add friends, fostering lasting connections.

---

## Figma Prototype & Design

- **Interactive Prototype:**  
  [View on Figma](https://www.figma.com/proto/rXMnmbnQlLYvxJe7RvdFR0/Sparkhacks-2025-Outing-Otter?node-id=0-1&t=LPcirPL4V3qeqw7c-1)  
- **Backend Design Files:**  
  [View Backend on Figma](https://www.figma.com/design/rXMnmbnQlLYvxJe7RvdFR0/Sparkhacks-2025-Outing-Otter?node-id=0-1&t=8nit64Ecq5ja0Dkp-1)

---

## App Overview

Built using Swift, the app contains 12 core files, each responsible for different features and UI components:

| File Name           | Description |
|---------------------|-------------|
| ContentView.swift | The app’s foundation and main entry point. |
| Custom Corner Shapers | Design elements for corner shapes and radii across the UI. |
| EventPage | Allows users to create and join events — modeled after CampusGroups. Uses an Event struct with attributes like name, time, and location. Includes sign-up functionality with checkboxes. |
| FriendsPage | Displays the user’s friend list similar to a contacts app. Supports adding friends (via button) and blocking (via swipe). Includes Friend struct and functions addFriend() & deleteFriend(). |
| Home | The default landing page with tabs for home, posts, events, friends, games, and account, inspired by Instagram. |
| LaunchPage | A generic welcome/front page for the app. |
| MainView | Core menu and navigation logic. Handles formatting and layout with modifiers like .offset, .shadow, .padding, .fill, and .frame. |
| Other_OtterApp | Swift debug protection tool. |
| PostPage | Layout and design of the post creation/viewing page. Uses modifiers such as .frame, .cornerRadius, .sheet. |
| SideMenu | Sidebar navigation with icons for home, news, info. Implements built-in Swift tab functions. |
| TabButton | Custom design for tab buttons in the SideMenu. Uses .foregroundColor, .padding, and .background. |
| GamePage | Mini-games to help users bond and socialize through fun interactions. |

---

## Getting Started

- Requires Swift and an appropriate iOS environment to run.  
- Clone the repository and open the Xcode project.  
- Build and run on your device or simulator.

---

## Why Outing Otters?

We created this app because, as introverts, we wanted a gentle and structured way to meet new people without the pressure of typical social media. By focusing on shared events and experiences, Outing Otters aims to build genuine friendships in a supportive community.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/outing-otters.git
   cd outing-otters
Open the project:
Open OutingOtters.xcodeproj or the workspace file in Xcode.
Build and run:
Select your target device or simulator.
Click the Run button (▶️) in Xcode.
Requirements:
Xcode 14 or higher
Swift 5+
iOS 15+ (or specify your minimum deployment target)
Contribution

We welcome contributions from the community! Here’s how you can help:

Fork the repository.
Create a new branch for your feature or bugfix:
git checkout -b feature/your-feature-name
Make your changes with clear, descriptive commits.
Push your branch to your fork:
git push origin feature/your-feature-name
Open a Pull Request to the main repository.
