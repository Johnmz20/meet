<h1>Meet App</h1>

<h2>Feature 1: Filter Events By City</h2>

- Given: The user has launched the application and is on the events listing page.
- When: The user selects a city from the available city options in the filter menu.
- Then: The events listing page refreshes, showing only the events located in the selected city.

<h2>Feature 2: Show/Hide Event Details</h2>

- Given: The user is viewing the event details page.
- When: The user taps on a button for a specific gesture.
- Then: The event details section either expands or collapses, showing or hiding additional information about the events.

<h2>Feature 3: Specify Number of Events</h2>

- Given: The user is on the events listing page.
- When: The user inputs a specific option from a drop-down menu to see the number of events displayed.
- Then: The events listing page refreshes, displaying the specified number of event options.

<h2>Feature 4: Use the App When Offline</h2>

- Given: The user has accessed the event application and has an internet connection.
- When: The user loses the internet connection.
- Then: The event application displays a message that the user is offline and some features may be unavailable. Previously viewed events and cached data are still accessible.

<h2>Feature 5: Add an App Shortcut to the Home Screen</h2>

- Given: The user has installed the event application on their phone.
- When: The user long-presses the app icon or accesses the app settings.
- Then: The user is presented with an option to add a shortcut to the home screen. After confirming, the app icon appears on the home screen.

<h2>Feature 6: Display Charts Visualizing Event Details</h2>

- Given: The user is viewing the event details page.
- When: The user taps on a "View Charts" button.
- Then: The application retrieves relevant data and generates visually appealing charts about the event data.
