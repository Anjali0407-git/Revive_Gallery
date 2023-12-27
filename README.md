
# REVIVE GALLERY
## Overview of the application Revive_Gallery

Introducing ReviveGallery, an innovative online marketplace tailored for the buying and selling of second-hand goods. What sets this software apart is the groundbreaking inclusion of a unique trustworthiness scoring system. This system meticulously evaluates each user's credibility incorporating feedback and reviews from buyers. Sellers who attain high trustworthiness scores gain exclusive access to advanced features, such as online delivery services and the capability to accept online payments.

Our primary focus is on bridging the trust gap between buyers and sellers in the online marketplace. To foster customer confidence, we have developed a robust system that assesses user trustworthiness. ReviveGallery goes beyond conventional online marketplaces by revolutionizing user trust and ensuring the quality of second-hand items. This overview encapsulates the core features that make our application a secure and sophisticated platform for individuals seeking to buy or sell pre-owned goods.

## Instructions for setting up a development environment

**1. Frontend Development (React.js):**
   - Begin by ensuring you have Node.js installed on your system
   - Clone the project repository from the provided source
   - Navigate to the frontend directory within the project
   - Run `npm install` to install the necessary dependencies
   - Execute `npm start` to launch the React development server

**2. Backend Development (Node.js):**
   - Confirm that Node.js is installed on your machine
   - Move to the backend directory in the project
   - Utilize `npm install` to install essential Node.js packages
   - Initiate the backend server by running `npm start`

**3. Image Storage (Firebase):**
   - Set up a Firebase account if you don't have one
   - Create a new Firebase project and note down the configuration details
   - Replace the existing Firebase configuration in the project's codebase with your newly acquired credentials

**4. User Credentials Storage (MongoDB):**
   - Ensure access to an online MongoDB server or set up a new one
   - Replace the MongoDB connection string in the backend code with your server details

**5. Environment Variables:**
   - Create a `.env` file in both the frontend and backend directories
   - Configure environment variables such as API keys, database credentials, and Firebase configurations in these files

**6. Testing:**
   - Verify the setup by conducting test transactions and interactions with the application
   - Address any issues that may arise during testing

By following these instructions, we should have a functional development environment for ReviveGallery, incorporating React.js for the frontend, Node.js for the backend, Firebase for image storage, and an online MongoDB server for storing user credentials. This comprehensive setup will facilitate seamless collaboration and development for our innovative online marketplace.

## Steps to build and run the application
### Steps to build and run the frontend

**1. Clone the repository:**

   `git clone https://github.com/Anjali0407-git/Revive_Gallery.git`

**2. Navigate to the project directory:** 

   `cd frontend/revive-gallery-app`

**3. Install all dependencies:**

   `npm install`

**4. Running the Project:**

   `npm start`

   This command will start a development server, and will notice that the output indicating that the application is running.
   Open web browser and go to http://localhost:3000. You will see the "Login" page, which is the LoginForm component.

### Steps to build and run the backend 

**1. Navigate to the project directory:**

  `cd Backend_NodeJS`

**2. Install all dependencies:**

 `npm install`

**3. Running the project:**

   `npm start`

   This command will start a development server, and will notice that the output indicating that the application is running.

## Information for evaluators and future developers 

At present linear transformation formuale is used for getting trustwothiness score in this case which can be enchaced by implementing machine learning models to find the trustworthiness score. 

