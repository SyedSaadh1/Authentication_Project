## Authentication System

### 1. Overview:

The authentication system is a comprehensive solution encompassing user sign up, sign in, sign out, password reset, and Google login/signup functionalities.

### 2. Setup:

- Begin by installing any necessary dependencies.
- Configure the database connection to ensure seamless operation.

### 3. Encryption:

User passwords are securely stored in the database utilizing encryption techniques such as bcrypt, prioritizing user data security.

### 4. Sign Up:

- Navigate to the `signup.ejs` page.
- Provide a valid email address along with matching passwords.
- Ensure notifications are displayed promptly for unmatched passwords, enhancing user experience and security.

### 5. Sign In:

- Access the `signin.ejs` page.
- Input a registered email and the corresponding correct password.
- Successful sign-in redirects users to the `home.ejs` page, maintaining a smooth user journey.
- Notifications are prominently displayed in cases of incorrect passwords, aiding users in troubleshooting.

### 6. Home:

- Present user information in a clear and concise manner on the `home.ejs` page.
- Include intuitive buttons for signing out and resetting passwords, facilitating user actions.

### 7. Reset Password:

- Navigate to the `reset.ejs` page to initiate the password reset process.
- Input the current password, the desired new password, and confirm the new password.
- Provide clear notifications upon successful password reset, ensuring users are informed of the action's completion.

### 8. Google Login/Signup:

- Utilize the `google-login.ejs` page to implement Google OAuth for streamlined authentication.
- Enhance user convenience and security by offering the option for Google login/signup alongside traditional methods.

## Deployment

Experience the fully functional Authentication app by visiting the [Deployment Link](https://authentication-project-jd2s.onrender.com/). Explore the application to appreciate its capabilities firsthand.

## Support

For any assistance or issues encountered, please feel free to contact Saadh via email: [saadhsyed1@gmail.com](mailto:saadhsyed1@gmail.com). Your feedback is invaluable in improving the application and ensuring a seamless user experience.
