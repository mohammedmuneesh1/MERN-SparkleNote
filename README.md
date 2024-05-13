#Running MERN-SparkleNote: A Step-by-Step Guide
Welcome to MERN-SparkleNote, a user-friendly note-taking website designed to streamline your note-taking experience. With a host of features including note creation, editing, deletion, note completion tracking, and categorization options, MERN-SparkleNote is your go-to platform for organizing your thoughts and tasks effortlessly.
Features:
Note Creation, Editing, and Deletion:
Easily create, edit, and delete notes to keep track of your ideas, tasks, and reminders.

Task Completion Tracking:
Track your task completion progress within your notes, helping you stay organized and productive.

Categorization Options:
Categorize your notes for better organization and quick access to relevant information.

Visually Appealing Design:
Enjoy a visually appealing and intuitive design that enhances your note-taking experience.

Seamless Navigation:
Navigate through the website seamlessly, ensuring a smooth and hassle-free user experience.

Email Verification:
Ensure the security of your account with email verification, providing an additional layer of protection for your data.


Get Started:
To get started with MERN-SparkleNote, follow these simple steps:

Clone the Repository:
Clone the MERN-SparkleNote repository to your local machine using the following command:

git clone [https://github.com/your-username/mern-sparkle-note.git](https://github.com/mohammedmuneesh1/MERN-SparkleNote.git)


Navigate to the Project Directory:
Open the MERN-SparkleNote Folder in VsCode and open two terminal for running frontend and backend 
use cd command for setting the terminal path 
example: cd client  ,  cd Server

Install Dependencies:
Install the project dependencies by running the following command:

npm install

Set Up Environment Variables:

Create a .env file inside both folder 

on client side 
create .env 
REACT_APP_BASE_URL = "http://localhost:4000/"

on Server side 
create another .env file 
create following fields
PORT = 4000
DB_URL =  your mongodb url 
USER_SECRET_KEY = create a user scret key with crypto.randomBytes(32).toString("hex")
NODEMAILER_EMAIL = your nodemail
NODEMAILER_PASS = your google account pass
APP_URL = give the url of react app  example http:/localhost:3000


Start the Development Server:
Start the development server by running the following command:

npm start

Access MERN-SparkleNote:
Once the development server is running, open a web browser and navigate to the following URL:

http://localhost:3000
You should now be able to access MERN-SparkleNote and start using its features.

#Thank you for Reading. All the best
