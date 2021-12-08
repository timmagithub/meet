<h1>meet App</h1>

<h2>Goal</h2>
    <p>
    meet is a serverless progressive web application built with React in the test driven development technique. Combined with the Google Calendar API to fetch events.
    </p>

<h3>Features</h3>
    <li>Filter events by city</li>
    <li>Show/Hide event details</li>
    <li>Specify number of events</li>
    <li>Utilize app while offline</li>
    <li>Add app shortcut to home screen</li>
    <li>Chart showing the number of upcoming events by city</li>

<h4>User Stories</h4>
   
    Feature 1
        Sc 1. 
            --As a user, I should be able to see events from all cities so I can begin my search with all options available.
            --Given a user hasn't searched for a city-When the user opens the app-Then the user should see all upcoming events

        Sc 2. 
            --As a user, I should be able to see city suggestions once I start typing so that I am able to select one from the list.
            --Given the main page is open-When the user starts typing in the city textbox-Then user should see list of suggestions that match what they've typed

        Sc 3. 
            --As a user, I should be able to pick a city from a list so that I can save time and avoid spelling errors.
            --Given the user begins typing a city name-When they select the city they want-Then the user's city should be updated to the one selected

    Feature 2
        Sc 1. 
            --As a user, I should be able to login and see a clean screen so that I can decide how I want to use the app without clutter on screen.
            --Given the user hasn't expanded the event details-When they open the app-Then the event should be collapsed

        Sc 2. 
            --As a user, I should be able to expand an event's details so that I can gather further information on the event.
            --Given the app is open and details aren't expanded-When the event details are clicked-Then they should expand showing all the available details for the event.

        Sc 3. 
            --As a user, I should be able to collapse the event's details so that I can navigate the rest of the screen without clutter.
            --Given the app is open and the details are expanded-When the details buttons is clicked-Then the details should collapse

    Feature 3
        Sc 1. 
            --As a user, I should be able to access all of the events available, so that I can decide which ones I want to filter out.
            --Given no filter parameters are selected-When the user opens the app-Then the user should have access to all of the events.

        Sc 2. 
            --As a user, I should be able to change how many events I am shown, so that I can customize my experience to my device and intake ability.
            --Given all the events are available-When the user selects how many events they want to see-Then the app should display that number of events.

    Feature 4
        Sc 1. 
            --As a user, I should be able to access my data, so that I can continue to utilize it even if I'm not connected to the web.
            --Given the user is offline-When the app is opened-Then the user should be able to see the events that they had access to when online.

        Sc 2. 
            --As a user, I should not be able to change the settings on the events so that I do not misinform myself or others.
            --Given the user is not an administrator of the app or event-When the user tries to alter any details of the event-Then an error message appears alerting the user they are not allowed to do so.

    Feature 5
        Sc 1. 
            --As a user, I should be able to access a chart sorting the number of events by city so that I can find events I want to go to in cities I'll be in.
            --Given the user is trying to find out how many events are in each city-When they access the chart-Then a chart with the number of events per city. 

