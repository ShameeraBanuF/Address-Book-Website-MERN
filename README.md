Hello
I am Shameera
Welcome to Coding with Shameera
In this video we are going to create [website name]
With 
•	Frontend – React js
•	Backend – Express js, Node js
•	Database- MongoDB
Before that make sure you have
•	Visual Studio Code (VS Code)
•	MongoDB 
•	Node js
Installed on your device.
For Complete Coding used in this project, visit my GitHub profile: https://github.com/ShameeraBanuF
For Output Video, visit my YouTube channel @CodingwithShameera1
Let us start…

BACKEND
First we create Backend with following steps:-
Step 1: Create a Folder in your project name and Create a folder for Backend into it, Open it in VS code and also open terminal in it.
Step 2: Type npm init -y in terminal.
Step 3: Install required packages
	npm install express nodemon mongoose cors body-parser
Step 4: Create a file named app.js and type the code as shown.
Step 5: Create Folder models , Create file address.js inside it Type the codings into it


FRONTEND
Its time to create Frontend with below steps:-
Step 1: In terminal, type
	cd .. [to exit from backend folder]
	npx create-react-app address-book
	again change back to backend folder by
		cd address-book
Step 2: Open new terminal and install required packages for frontend
	npm install axios react-bootstrap-icons react-router-dom 
Step 3: Next navigate to src folder where you can see App.css file & App.js file. Open those two files and delete the default code & type the code as shown.
Step 4 : For bootstrap get CDN links of bootstrap and jquery and paste it inside index.html file in public folder as below.
<link href=”https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css” rel=”stylesheet” integrity=”sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC” crossorigin=”anonymous”>
<script src=”https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js” integrity=”sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM” crossorigin=”anonymous”></script>
<script src=”https://code.jquery.com/jquery-3.7.1.min.js” integrity=”sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=” crossorigin=”anonymous”></script> 
Step 5: Create a folder called components in src directory and create files AddAddress.js, AddressList.js, Navigation.js inside it. Copy the code as shown


EXECUTION
Frontend: npm start
Backend: node server.js
