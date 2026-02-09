# Ex09 Event Registration Web Application
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
HOME PAGE:
~~~
<style>
.auth-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(0, 0, 0, 1);
  white-space: nowrap;
  text-align: center;
  margin: 0 auto;
  padding: 57px 8px 141px 24px;
  font: 800 36px Inter, sans-serif;
}

.hero-image {
  aspect-ratio: 3.53;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 225px;
  margin-top: 74px;
  max-width: 100%;
}

.auth-button {
  background-color: rgba(204, 146, 216, 1);
  width: 281px;
  max-width: 100%;
  padding: 21px;
  cursor: pointer;
}

.login-button {
  margin-top: 128px;
}

.register-button {
  margin-top: 53px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="auth-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/67936953a9dca9ef0a7c92fa3ae634fc7822616a3aa54a5437eb44296fe4c2b5?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="hero-image"
    alt="Hero banner"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/05b18098531f1679fb9a0bc705adc0060c4a612ab24aea08502bff0465167705?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="logo-image"
    alt="Company logo"
  />
  <button class="auth-button login-button" tabindex="0">LOGIN</button>
  <button class="auth-button register-button" tabindex="0">REGISTER</button>
</div>
~~~

PAGE 2

~~~
<style>
.auth-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(0, 0, 0, 1);
  white-space: nowrap;
  text-align: center;
  margin: 0 auto;
  padding: 57px 8px 141px 24px;
  font: 800 36px Inter, sans-serif;
}

.hero-image {
  aspect-ratio: 3.53;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 225px;
  margin-top: 74px;
  max-width: 100%;
}

.auth-button {
  background-color: rgba(204, 146, 216, 1);
  width: 281px;
  max-width: 100%;
  padding: 21px;
  cursor: pointer;
}

.login-button {
  margin-top: 128px;
}

.register-button {
  margin-top: 53px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="auth-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/67936953a9dca9ef0a7c92fa3ae634fc7822616a3aa54a5437eb44296fe4c2b5?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="hero-image"
    alt="Hero banner"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/05b18098531f1679fb9a0bc705adc0060c4a612ab24aea08502bff0465167705?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="logo-image"
    alt="Company logo"
  />
  <button class="auth-button login-button" tabindex="0">LOGIN</button>
  <button class="auth-button register-button" tabindex="0">REGISTER</button>
</div>
~~~

PAGE 3:

~~~
<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 45px 12px 135px;
}

.registration-title {
  font: 800 36px Inter, sans-serif;
  text-align: center;
  color: #000;
}

.form-group {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 367px;
  margin: 0 auto;
}

.input-field {
  background-color: #F5F5F5;
  padding: 20px;
  margin-top: 19px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.input-row {
  display: flex;
  gap: 7px;
  margin-top: 19px;
}

.input-field-half {
  background-color: #F5F5F5;
  padding: 18px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.submit-button {
  background-color: #CC92D8;
  padding: 20px 16px;
  border: none;
  font: 800 36px Inter, sans-serif;
  color: #000;
  width: 206px;
  margin: 68px auto 0;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <h1 class="registration-title">EVENT REGISTRATION<br />FORM</h1>
  
  <form class="form-group">
    <label for="fullName" class="visually-hidden">Full Name</label>
    <input type="text" id="fullName" class="input-field" placeholder="FULL NAME" required>

    <div class="input-row">
      <div>
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" class="input-field-half" required>
          <option value="">GENDER</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>
      
      <div>
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" class="input-field-half" placeholder="AGE" required>
      </div>
    </div>

    <label for="regNumber" class="visually-hidden">Register Number</label>
    <input type="text" id="regNumber" class="input-field" placeholder="REGISTER NUMBER" required>

    <label for="department" class="visually-hidden">Department and Branch</label>
    <input type="text" id="department" class="input-field" placeholder="DEPT & BRANCH" required>

    <label for="email" class="visually-hidden">Email ID</label>
    <input type="email" id="email" class="input-field" placeholder="EMAIL ID" required>

    <label for="event" class="visually-hidden">Event to Register</label>
    <select id="event" class="input-field" required>
      <option value="">EVENT TO BE REGISTER</option>
    </select>

    <button type="submit" class="submit-button">REGISTER</button>
  </form>
</div>
~~~

PAGE 4:

~~~
<style>
.thank-you-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 37px 26px 191px;
}

.header-logo {
  aspect-ratio: 4.31;
  object-fit: contain;
  object-position: center;
  width: 375px;
}

.thank-you-title {
  color: rgba(0, 0, 0, 1);
  text-align: center;
  align-self: center;
  margin-top: 170px;
  width: 286px;
  font: 800 36px Inter, sans-serif;
}

.title-small {
  font-size: 24px;
}

.contact-info {
  color: rgba(0, 0, 0, 1);
  align-self: start;
  margin: 74px 0 0 21px;
  font: 800 24px Inter, sans-serif;
}

.contact-text {
  font-weight: 500;
  font-size: 16px;
}

.social-icons {
  align-self: center;
  display: flex;
  margin-top: 53px;
  width: 100%;
  max-width: 335px;
  gap: 20px;
  justify-content: space-between;
}

.social-icon {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 92px;
}

.social-icon-medium {
  aspect-ratio: 1.02;
  width: 95px;
}

.social-icon-large {
  aspect-ratio: 1.17;
  width: 98px;
  align-self: start;
}
</style>

<div class="thank-you-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/09e074d1a119ed32c1adab028880a86b57f34be20c2630059aa71a4cdd628766?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="header-logo"
    alt="Company Logo"
  />
  <div class="thank-you-title">
    THANK YOU
    <br />
    <span class="title-small">FOR REGISTERING EVENT</span>
  </div>
  <div class="contact-info">
    CONTACT US:
    <br />
    EMAIL ID:
    <span class="contact-text">
      SAVEETHAENGCLG@GMAIL.COM
    </span>
    <br />
    ADDRESS:
    <br />
    <span class="contact-text">
      SAVEETHAENGINEERINGCOLLEGE,
    </span>
    <br />
    <span class="contact-text">
      THADALAM,SRIPREMBATHUR
    </span>
    <br />
    <br />
  </div>
  <div class="social-icons">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/6c7c84a2d120cae548d9fa5189dcbe9b55ab11affe03c068e34cb8f129511237?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="social-icon"
      alt="Social Media Icon"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/d99089f2ca3aba8b902cfb3d44c7916280e262fee8a2f39c47ce1adc4bbe0fc7?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="social-icon social-icon-medium"
      alt="Social Media Icon"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/469e9b99608b334e03e54e1694affbc9bc2908d5a5c813f1e512a0e74c42c09d?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="social-icon social-icon-large"
      alt="Social Media Icon"
    />
  </div>
</div>
~~~
 
# OUTPUT:
<img width="1223" height="562" alt="Screenshot 2026-02-09 052854" src="https://github.com/user-attachments/assets/3e274484-66b6-436e-b669-866e93028cd3" />


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
