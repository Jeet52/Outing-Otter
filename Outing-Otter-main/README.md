Outing Otters

The Outing Otters social media app is a way for people to connect with others and build connections. As introverts we wanted to create an app inspired by CampusGroups, Instagram, and Tinder to encourage people to interact with one another. It allows users to create and join events that fit their needs. After attending an event the friends feature will be enabled, as a result fostering connections. 

### CHECK OUR FIGMA BELOW (PROTOTYPE FIRST)
Figma Prototype: https://www.figma.com/proto/rXMnmbnQlLYvxJe7RvdFR0/Sparkhacks-2025-Outing-Otter?node-id=0-1&t=LPcirPL4V3qeqw7c-1
Figma Backend: https://www.figma.com/design/rXMnmbnQlLYvxJe7RvdFR0/Sparkhacks-2025-Outing-Otter?node-id=0-1&t=8nit64Ecq5ja0Dkp-1

Outline
The application requires swift to run. There are twelve files:
1)ContentView.swift
	>The foundation of the entire progam (the base/core)
2)Custom Corner Shapers
	>Sets up the design of the app
	>Includes corners and radius
3)EventPage
	>Idea: where people make events in order to hang out with other introverts identical to CampusGroups
	>Utilizes a struct called Event with multiple data members including name, time, location, ect.
	>Utilizes a struct to sign up for events via a checkbox
4)FriendsPage
	>Idea: a directory that lists all the user’s friends names similar to a contact list
	>Feature: to add a friend -> click the button
			  to block a friend -> swipe 
	>Utilizes a struct called Friend with the data members id and name
	>Includes formatting features like font, padding,background color, and a button
	>There are two functions called addFriend() and deleteFriend() that adds/deletes a new friend to the original list
5)Home
	>Idea: the default home page like Instagram 
	>Includes a homepage, post, event, friends, games, and account component
6)LaunchPage
	>Idea: generic front page
7)MainView
	>The foundation of the entire programs where Home is an extension of MainView 
	>Consists of all the formatting and therefore is the menu logic (back-end development) 
	>Utilizes modifiers like .offset, .shadow, .padding, 
		.fill, and.frame
8)Other_OtterApp
	>A swift debug protection tool
9)PostPage	
	>Idea: the formatting and layout of the post page
	>Utilizes modifiers like .frame, .cornerRadius, .sheet
	>Implements design functions like images and buttons
10)SideMenu
	>Idea: all the feature icons to switch pages
	>Includes a home, news, and info button with the built in swift function TabFunction
	>Utilizes modifiers like .font and .padding
11)TabButton
	>Idea: the design of the tab button in the SideMenu
	>Utilizes modifiers like .foregroundColor, .padding, and .background
12)GamePage
	>Goal: Allow users to make bonds with others through playing simple mini-games 

