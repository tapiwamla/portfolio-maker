# portfolio-maker

Developed by [Chidochashe Gerald Zhou](https://github.com/chidozhou) and [Tapiwanashe Mlambo](https://github.com/tapiwamla)

portfolio-maker is a dynamic web application designed for crafting personalized portfolio websites. This full-stack project empowers users to create accounts, customize content, upload images, and share their professional profiles with the world. Built with React, MongoDB, Node, and Express, portfolio-maker provides a seamless platform for showcasing your skills and experiences.

## Key Features

- _User Accounts:_ Create and manage your account to curate a unique portfolio.
- _Customization:_ Tailor your portfolio by modifying data, links, pictures, and uploading your resume.
- _Live Sharing:_ Share your finished portfolio website with a global audience.

## How to Run the Project

1. _Download Repository:_

   - Clone or download this repository to your local machine.

2. _Install Dependencies:_

   - Run npm install in the root directory.
   - Navigate to both the client and server folders and run npm install.

3. _Configure MongoDB:_

   - Ensure you have MongoDB installed on your local machine or set up an account in the cloud [MongoDB Website](https://www.mongodb.com/).

4. _Set Up Third-Party Accounts:_

- Create accounts for third-party technologies: [Sendgrid](https://sendgrid.com) and [Cloudinary](https://cloudinary.com).
   - Inside the server folder, create a `.env` file and update it with your credentials:

   ```
   NODE_ENV=development
    DB_STRING=your_local_link_to_MongoDB
    DB_STRING_PROD=your_link_to_MongoDB_in_cloud
    SENDGRID_API_KEY=your_Sendgrid_API_key
    CLOUD_NAME=your_Cloudinary_cloud_name
    API_KEY=your_Cloudinary_API_key
    API_SECRET=your_Cloudinary_API_SECRET_key
   ```

5. _Generate RSA Key:_

   - Run node `generateKeypair.js` in the server folder to create your own RSA key for encryption.

6. _Run the Project:_

   - After setup, execute `npm start:dev` from the root directory.

7. _Enjoy Your Portfolio Maker App!_
   - Your portfolio-maker app is now up and running. Explore the features and showcase your professional journey.

We welcome your feedback and contributions to make portfolio-maker even better!
