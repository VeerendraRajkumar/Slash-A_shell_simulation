# Slash: A Shell Simulation
By
  	-Bobbili Veerendra Raj Kumar
	-Naga Teja Mariyala
	-Aakash Sahu
	
This shell was developed as a coursework project while pursuing my Bachelor of Science (Honours) in Mathematics at SSSIHL.
----------------------------------------------------------------------------------------------
This is a basic shell simulation that includes additional features (given below) that we wanted to add. It is a coursework project written in C.

The available features are:
1. Users can create an account in Slash by providing their user-id, password, and birthdate to the admin. The admin can only create users if the user is signed in to Bash. The admin can also view all users and delete any user.
1. Users can log in to Slash using their user-id and the current password provided by the admin. They can also change their password using ->(password)<- command. The user can see their last logged-in time while logging in.
1. The Slash shell includes an On-The-Go calculator that users can use directly in the shell. Users can perform basic operations such as +, -, *, ^, %, and /, and the calculator evaluates numerical expressions with or without parentheses.
1.Users can send mails to other users in Slash using the command ->(smail <receiver>)<-. Users can write the contents of the mail and then press ctrl-d to send it.
1. Users can view their received mails and the status of their mails using the command ->(smail)<-. This command shows mails in the inbox only when there are unread mails for the user. After reading mails, the user can delete the status of the mails that have been read so that they will no longer be shown as unread mails.
1. Users can send fast mails using the ->(flashmail <receiver>)<-command. This command works similar to the smail command but notifies the receiver that the received mail is urgent. Users can open their inbox to see mails using the ->(smail open)<- command.
1. Users can see the history of commands used in the slash shell by using the ->(shist)<- command and can clear their command history using the ->(shist clear)<- command.
1. Users can find their age using the ->(myage)<- command.
1. Users can see other users in the slash shell by using the ->(susers)<- command.
1. Users can read witty statements using the ->(wit)<- command, or read quotes using the ->(quote)<- command.
1. Users can chat with other users in Slash using the ->(chatter)<- or ->(slashchat)<- command. To use this feature, users can enter the receiver's name and then send messages by typing the message and pressing the 'enter' key. This sends a notification to the receiver. Users can refresh their received messages by pressing the 'enter' key. To exit from the chatter, users must type 'exit'.
1. Users can convert between scientific units for different quantities using a menu-based program by typing ->(cnvrt)<- in the shell.
1. Users can find the volume of regular 3-dimensional shapes by using the ->(volume [argument])<- command in the shell. This program uses command-line arguments, so users can enter the shape when they call the volume functionality. For example, ->(volume cube)<- will prompt the user to enter the edge of the cube and display the result. Other shapes that can be used include sphere, hemisphere, cuboid, cone, etc.

Note : The main audience for this project were users that were working through workstations on a Ubutu Server. Therefore the complete application of this project outside this setting is very limited.