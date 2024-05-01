# How to Create Cloud Resume Using Bootstrap Template

This guide provides step-by-step instructions on how to use the StartBootstrap resume template to create a cloud resume.

## Prerequisites
- Git
- Node.js and npm installed on your machine

## Step 1: Clone the Project
Begin by cloning the repository to your local machine:
```bash
git clone https://github.com/heralddsb/cloud-resume.git
```

## Step 2: Install Dependencies
Navigate into the project directory and install the necessary dependencies:

```bash
cd cloud-resume
npm install
```

## Step 3: Run the Application
Start the application to see the initial template:

```bash
npm run start
```
After running the command, open your web browser and go to http://localhost:3000 to view the page.

##Step 4: Modify the Resume Information
Open the file located at ``/src/pug/index.pug`` in your text editor and modify the information to fit your resume:

- Update personal information
- Edit work experience and education sections
- Add skills and other relevant details

## Step 5: Build the Project
Once you have completed modifying the template, build the static pages by running:

```bash
npm run build
```
## Step 6: Access the Generated Files
Navigate to the dist folder in the project directory to access the generated HTML, CSS, images, and JavaScript files:

```bash
cd dist
```
You can now deploy these files to any static site hosting service to publish your cloud resume.

##Salut

Until next time, happy learning!