# Login-Authenticator
This project is based on creating an application that handles the login and signing up functions of a certain service that requires the user to create an account for using its services. The designed application's main page has the option to **sign up, sign in, delete the account or exit** the portal.

The user can choose to create a new account on the portal where he needs to enter a desired username, a password, answer a **security question** and verify that they're not a bot by answering the captcha correctly. The user can use the security answer entered while signing up to reset their password later in case they forget it. 

We have used the **Caesar Cipher** technique for encrypting the password before saving it to the server to have better security. The **CAPTCHA technology** has been used, which authenticates that a real person is accessing the application and blocks automated systems. These automated systems fail to read the distorted characters in the graphic that the user has to read and enter to validate.

## Technologies Used:
- MySQL
- Tkinter
- Captcha Generator

## Screenshots of the application
### The main page 
<img src="https://user-images.githubusercontent.com/75370975/146645515-a68537bb-b625-4d44-8efb-6d7745c8ca58.png" width="600"/>
                                    
### The Signup page
<img src="https://user-images.githubusercontent.com/75370975/146645623-f1bb1822-aad5-4265-9f80-a639dec652ae.png" width="600"/>

In case the user fails to fill one field and clicks on submit, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645695-991725e1-57a0-4d1a-ad92-e7e9b7c339e1.png" width="300"/>

In case the captcha fails to match, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645752-fa448808-222d-4b0f-ad3e-993607d63ae0.png" width="300"/>

In case the password entered in the 'desired password' field and the confirmation password field do not match, the message that the user receives is:

<img src="https://user-images.githubusercontent.com/75370975/146645841-9254a3e5-e651-433a-b781-190b61825ebc.png" width="300"/>

In case all the entered information meets the requirements, the message that the user receives is:

<img src="https://user-images.githubusercontent.com/75370975/146645863-311271a4-3dcb-4361-bb9d-475a6a6760ac.png" width="300"/>

In case the email entered already exists on the server, then, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645912-d8bd1710-4386-4423-9451-3f0e02e5939e.png" width="300"/>

### The Login page
<img src="https://user-images.githubusercontent.com/75370975/146645952-4c23ff0d-f38e-4ece-994b-f7e3bdf71492.png" width="600"/>

In case the user fails to fill one field and clicks on submit, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645993-a766d69c-7aa0-4628-86e8-cd643ca77096.png" width="300"/>

If the user succeeds to enter all the details correctly, the login is successful:

<img src="https://user-images.githubusercontent.com/75370975/146646016-42c0453b-7418-40e7-8dcb-fa1d3547a2c6.png" width="300"/>

In case the user fails to enter their credentials correctly, the login becomes unsuccessful:

<img src="https://user-images.githubusercontent.com/75370975/146646024-1b0f1d6a-2526-409f-9c35-c61723c0715d.png" width="300"/>

### The forgot password page
<img src="https://user-images.githubusercontent.com/75370975/146646086-ed5dc3df-8670-4441-aa00-f6fbb4abf18f.png" width="600"/>

In case the user fails to fill one field and clicks on submit, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645993-a766d69c-7aa0-4628-86e8-cd643ca77096.png" width="300"/>

Let's say that the user fails to enter the right security answer, then they will not be able to change their password and the message box that pops on validating the security answer will be the following:

<img src="https://user-images.githubusercontent.com/75370975/146646117-eeedb9bb-4a82-43a1-abd0-12d90a4066a7.png" width="300"/>

Let's say that the user enters the right security answer, Then the following message pops up:

<img src="https://user-images.githubusercontent.com/75370975/146646149-a1a29004-2b2a-4113-8e52-330c1d38cfcb.png" width="300"/>

In case the password entered in the 'desired password' field and the confirmation password field do not match, the message that the user receives is:

<img src="https://user-images.githubusercontent.com/75370975/146645841-9254a3e5-e651-433a-b781-190b61825ebc.png" width="300"/>

In case the captcha fails to match, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645752-fa448808-222d-4b0f-ad3e-993607d63ae0.png" width="300"/>

When the user enters all the required details correctly and clicks submit, the following message pops up:

<img src="https://user-images.githubusercontent.com/75370975/146646166-6c5934df-7156-4111-8c8e-324fedc27e25.png" width="300"/>

### Delete Account page
<img src="https://user-images.githubusercontent.com/75370975/146646179-2202161b-42c3-4b9b-a58d-25493f4e4e98.png" width="600"/>

In case the user fails to fill one field and clicks on submit, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645993-a766d69c-7aa0-4628-86e8-cd643ca77096.png" width="300"/>

In case the captcha fails to match, the following message box pops up:

<img src="https://user-images.githubusercontent.com/75370975/146645752-fa448808-222d-4b0f-ad3e-993607d63ae0.png" width="300"/>

In case the user gives an incorrect prompt in place of 'CONFIRM', the user will not be able to delete their account and the following message pops up: 

<img src="https://user-images.githubusercontent.com/75370975/146646232-c9d39c35-cacc-4b20-9916-cb8a7d32492e.png" width="300"/>

If everything entered matches the details on the server, and the user clicks on submit, the account gets deleted successfully:

<img src="https://user-images.githubusercontent.com/75370975/146646236-c34d61da-cd96-482c-ab5f-c457fee4f08c.png" width="300"/>




