# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sports Day Event</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
      font-family: 'Arial', sans-serif;
      scroll-behavior: smooth;
      background: #f9f9f9;
    }

    section {
      height: 100vh;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    h1, h2 {
      text-align: center;
      margin-bottom: 1rem;
    }

    .btn {
      background: #222;
      color: #fff;
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      text-decoration: none;
      font-size: 1rem;
      margin-top: 1rem;
      transition: 0.3s;
    }

    .btn:hover {
      background: #555;
    }

    /* Section 1 - Welcome */
    #welcome {
      background: url('https://images.unsplash.com/photo-1601412436009-5fe9dc07e0ed?auto=format&fit=crop&w=1000&q=80') no-repeat center center/cover;
      color: white;
      text-shadow: 1px 1px 2px black;
    }

    /* Section 2 - Events */
    #events {
      background: #f0f0f0;
    }

    .event-list {
      list-style: none;
      text-align: center;
    }

    .event-list li {
      margin: 10px 0;
      font-size: 1.2rem;
    }

    .event-list li::before {
      content: "• ";
      color: #222;
      font-weight: bold;
    }

    /* Section 3 - Registration */
    #register {
      background: #fff;
    }

    form {
      width: 90%;
      max-width: 400px;
      display: flex;
      flex-direction: column;
    }

    input, select {
      margin-bottom: 1rem;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 10px;
      font-size: 1rem;
    }

    label {
      margin-bottom: 0.3rem;
      font-weight: bold;
    }

    /* Section 4 - Thank You */
    #thankyou {
      background: url('https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=1000&q=80') no-repeat center center/cover;
      color: white;
      text-align: center;
      text-shadow: 1px 1px 3px black;
    }

    address {
      margin-top: 1rem;
      font-style: normal;
      line-height: 1.5;
    }

    nav {
      position: fixed;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      background: rgba(0,0,0,0.6);
      padding: 10px 20px;
      border-radius: 20px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#welcome">Home</a>
    <a href="#events">Events</a>
    <a href="#register">Register</a>
    <a href="#thankyou">Contact</a>
  </nav>

  <!-- Section 1: Welcome -->
  <section id="welcome">
    <h1>SPORTS DAY</h1>
    <p>“Don’t just aspire to win. Aspire to make a difference.”</p>
    <a class="btn" href="#events">View Events</a>
  </section>

  <!-- Section 2: Events -->
  <section id="events">
    <h2>List of Events</h2>
    <ul class="event-list">
      <li>CRICKET</li>
      <li>BADMINTON</li>
      <li>RUNNING</li>
      <li>KABADDI</li>
      <li>CHESS</li>
    </ul>
    <a class="btn" href="#register">Register Now</a>
  </section>

  <!-- Section 3: Registration Form -->
  <section id="register">
    <h2>Register for Sports Day</h2>
    <form onsubmit="event.preventDefault(); window.location='#thankyou';">
      <label for="name">Full Name</label>
      <input type="text" id="name" required />

      <label for="email">Email</label>
      <input type="email" id="email" required />

      <label for="college">College Name</label>
      <input type="text" id="college" required />

      <label for="event">Choose Event</label>
      <select id="event" required>
        <option value="">-- Select --</option>
        <option value="cricket">Cricket</option>
        <option value="badminton">Badminton</option>
        <option value="running">Running</option>
        <option value="kabaddi">Kabaddi</option>
        <option value="chess">Chess</option>
      </select>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" required />

      <button type="submit" class="btn">Submit</button>
    </form>
  </section>

  <!-- Section 4: Thank You -->
  <section id="thankyou">
    <h2>Thank You!</h2>
    <p>We appreciate your interest. Get ready to show your spirit!</p>
    <address>
      Email: saveethaengineeringcollege@gmail.com<br />
      Phone: 6369183394 / 3669183394
    </address>
  </section>

</body>
</html>

## OUTPUT:

<img width="1917" height="1199" alt="image" src="https://github.com/user-attachments/assets/68f10845-0c52-4ca6-b55d-53e04f34834f" />

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/7f9536b3-41fc-4565-bc9e-2bbdd2d049c8" />

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/c9d4f5bf-78ca-418c-8212-90fe019abeb3" />

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/4bd1afc4-24a9-4e7d-9efc-8d6065bdffe7" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
