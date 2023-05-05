# COMP SCI 506

## Description
<p> Projects I did in COMP SCI 506: Software Engineering
  <li> <b>Project Frontend: <a href="https://github.com/arunike/CS506-Frontend" target="blank">Five Course Bird Feeder Frontend</a> </b> </li> 
  <li> <b>Project API: <a href="https://github.com/arunike/CS506-API" target="blank">Five Course Bird Feeder API</a> </b> </li>
</p>

## About
<p>
    <ol type="1">
        <li>Login/Sign up Page</li>
            <ul>
                <li>The website will give the option to log in to an existing account for returning users or create a new account for new users.</li>
                <li>Returning users can sign into their accounts with their username and password.</li>
                <li>The data collected for new accounts:</li>
                    <ul>
                        <li>Username</li>
                        <li>Password</li>
                        <li>First Name</li>
                        <li>Last Name</li>
                    </ul>
            </ul>
        <li>Home Page – Live View of User’s Birdfeeder</li>
            <ul>
                <li>View live and recorded video streams of user’s birdfeeder</li>
                    <ul>
                        <li>If the bird feeder camera is currently streaming video, display it on the home page.</li>
                        <li>Recorded video Otherwise, display previously recorded video from the user’s bird feeder camera.</li>
                    </ul>
                    <li>Next to the video stream display will be a short summary of the bird observations since the user’s last login.</li>
                    <li>The home page sidebar will contain navigation buttons  to all the other  features offered by the application.</li>
            </ul>
        <li>Profile Page</li>
            <ul>
                <li>Display user profile data:</li>
                    <ul>
                        <li>Display username, full name, any any other personal information</li>
                        <li>Allow user to change any of this information, including their password</li>
                    </ul>
            </ul>
        <li>Settings Page</li>
            <ul>
                <li>Users can change feeding schedules to:</li>
                    <ul>
                        <li>DAttract specific bird species at certain times of the day</li>
                        <li>Keep certain animals/birds from feeding at their feeder</li>
                    </ul>
                <li>Users can change settings related to the default statistics shown</li>
            </ul>
        <li>Statistics Page</li>
            <ul>
                <li>Graphic and tabular displays of:</li>
                    <ul>
                        <li>what birds are visiting</li>
                        <li>how frequently they are visiting</li>
                        <li>what time of day they are visiting</li>
                        <li>total birds visited</li>
                    </ul>
                <li>Users can change settings related to the default statistics shown</li>
            </ul>
        <li>ML + Image Labeling Page</li>
            <ul>
                <li>Working in progress</li>
            </ul>
    </ol>
</p>

## How to Run
<ol type="1">
<li>Clone the repository</li>

```
git clone https://github.com/arunike/CS506-Frontend.git
```

<li> <a href="https://github.com/arunike/CS506-API" target="blank">Run the API</a> </li>
<li>Have Docker on your machine</li>
    <ul>
        <li> <a href="https://www.docker.com/" target="blank">Install Docker</a> </li>
        <li>Open Docker</li>
    </ul>
<li>Install dependencies</li>

```
npm install
```

<li>Enable CORS Unblock Extension</a> </li>
    <ul>
        <li> <a href="https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino" target="blank">Install CORS Unblock Extension</a> </li>
        <li>Activate CORS Unblock Extension</li>
    </ul>

<li>Run the application</li>

```
npm run dev
```
</ol>
