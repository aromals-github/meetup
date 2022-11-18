PROJECT IDEA - to create an app with login auth funtionality to CREATE an meeting setup

 						# - logged in user can send friend requests and accepts request from other
						# - those who are friends create meetings - which can be virtual meeting or an non virutal
						
		
		HOW THE SITE WORK:
		
						* LOGIN SYSTEM TO CREATE - to create new users
						    	
						when autherized :
									
							* user can create send friend request to other users
										* user can create meeting and invite other users.
											1)those who are friends can only be invited to a meeting
											2)there are two type of meeting virtual and non virtual meet ups
																							
												meet up those are virtual:
														will contain info on how that is conducted...
															non virtual:
														contains the details on how that is conducted...
	
	
	APPS required :
							ACCOUNTS - App that create users .
							FRIENDS - App  that handles all the friends request logics
							MEETINGS - App that create meetings and handles the logics for each individual meeting.
							EMAIL - App contains the logics to send an automated mail to participants depending upon the logics by the 
											created meetings.
							LOCATION -(in mind)
													uses geo location funtionality - to track the users locations and sends 
													an automated mail if the user most likely not to attend the destination .
													where the non virtual meeting is set to happen.
							COMPANY_MEETUP - an expansion the above apps but with certain restrictions and dues.
													
																	
	Models Required for the projects:
				
				
				Accounts -  user login informations
				FriendsList - contians the list of friends of individual users.
				FriendRequest - model is used to main friend-requst pending acceptance etc..
				Meeting - where the data of each meeting details are stored when created.
				MeetingParticipants - the participants of the each individual meetings are stored over here
																													
													
