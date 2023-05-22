### State Transition Diagram:
**Write down the different states:**
<br>Sign-up page
<br>Login page
<br>Home page
<br>Profile page
<br>Settings page
<br>Logout

**Write down the different events:**
<br>User signs up
<br>User logs in
<br>User logs out
<br>User accesses profile
<br>User accesses settings

**Determine which events cause a transition between states:**
<br>User signs up: Sign-up page → Login page
<br>User logs in: Login page → Home page
<br>User logs out: Any state → Login page
<br>User accesses profile: Home page → Profile page
<br>User accesses settings: Home page → Settings page

**Summaries States and Events**

>**State: Sign-up Page**
<br>**Events:**
<br>User fills out sign-up form
<br>User clicks "Submit"
<br>Transition: Successful sign-up leads to the next state.

>**State: Login Page**
<br>**Events:**
<br>User enters username and password
<br>User clicks "Login"
<br>Transition: Successful login leads to the Home Page.

>**State: Home Page**
<br>**Events:**
<br>User clicks on a profile link.
<br>Transition: Redirects to the Profile Page.

>**State: Profile Page**
<br>**Events:**
<br>User updates profile information
<br>User clicks "Save"
<br>Transition: Saved changes lead to the updated Profile Page.

>**State: Settings Page**
<br>**Events:**
<br>User clicks on Settings Page
<br>Transition: Redirects to the Settings Page. 

>**State: Any Page/ State**
<br>**Events:**
<br>User clicks on Log Out Link
<br>Transition: Redirects to the Login Page.

**State Transition Table:**
<<<<<<< HEAD
<br><br> ![](Screenshot%202023-05-22%20at%2012.38.04.png)

| State         | Event                                       | Next State    |
|---------------|---------------------------------------------|---------------|
| Sign-up Page  | User fills out sign-up form                 | Login Page    |
| Login Page    | User enters username and password           | Home Page     |
| Home Page     | User clicks on the Profile link             | Profile Page  |
| Home Page     | User clicks on settings link                | Settings Page |
| Profile Page  | User clicks on the Home link                | Home Page     |
| Profile Page  | User updates profile information            | Profile Page  |
| Profile Page  | User clicks on settings link                | Settings Page |
| Settings Page | User clicks on Profile link                 | Profile Page  |
| Settings Page | User clicks on Home link                    | Home Page     |
| Settings Page | User logs out                               | Login Page    |
| Profile Page  | User logs out                               | Login Page    |
| Home Page     | User logs out                               | Login Page    |
| Sign-up Page  | User fills out sign-up form (invalid)       | Sign-up Page  |
| Login Page    | User enters username and password (invalid) | Login Page    |
=======
<br> ![](Screenshot%202023-05-22%20at%2011.58.30.png)
>>>>>>> fe660c22b99beb06ee6dabef47f2a0ffdcddcb22


#### **Hypothetical Test Case:**
**Starting State: Sign-up Page**
<br>**Test Steps:**
<br>Fill out the sign-up form with valid information.
<br>Click "Submit" to attempt sign-up.
<br>Verify if the transition occurs to the Login Page.
<br>Enter valid login credentials on the Login Page.
<br>Click "Login" to attempt login.
<br>Verify if the transition occurs to the Home Page.
<br>Click on the profile link on the Home Page.
<br>Verify if the transition occurs to the Profile Page.
<br>Update profile information on the Profile Page.
<br>Click "Save" to save the changes.
<br>Verify if the transition occurs to the updated Profile Page.
<br>Click "Settings" to see Settings page.
<br>Verify if the transition occurs to the Settings Page.
<br>Click on the "Log Out" link to log out.
<br>Verify if the transition occurs to the Login Page.

**Test Steps:**
<br>Fill out the sign-up form with invalid information.
<br>Click "Submit" to attempt sign-up.
<br>Verify that no transition occurs from sign-up page.

**Test Steps:**
<br>Enter invalid login credentials on the Login Page.
<br>Click "Login" to attempt login.
<br>Verify that no transition occurs from login page.