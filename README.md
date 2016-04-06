# ios-decal-proj4

## Check-in

### Authors
 *	Sai Yerraguntla

### Purpose 
 *	Check-in is an app that allows users to check-in to an event and allows the 
   host of the event to see who attended the event. 

###	Features
  *		User profiles (Name and Picture)
  *		Ability to create groups
  *	 Host an event option with ability to invite individual users or a group
  *	 Ability for a user to indicate intention of attending
  *		Ability for host to generate a random word or specify a random word used for check-in
  *		Ability for user to enter word and see confirmation of check-in or share their location as confirmation of attendance
  *		List of user profiles attending/attended for host to see
  *		Event will show under “events attended” for user profile
  *		Ability for host to manually check-in users invited to the event
  *		Option for host to confirm attendance

###	Control Flow
  *	When a user opens the app, they will be given a choice to enter as either a host or a guest to an event. Then, they will select the event (or if they are hosting, they will have the ability to create a new event or choose from events they have previously created). Then, the host can either activate the event check-in or view the list of people checked-in.

###	Implementation
####  Model
      - Event.swift, User.swift
####  View
  		- OpeningScreenView, EventSelectionView, CheckInView, UsersCheckedInTableView
####  Controller
  		- OpeningScreenViewController, EventSelectionViewController, CheckInViewController, UsersCheckedInTableViewController
