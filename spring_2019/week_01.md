## Last Week's Accomplishments

This past week, I was able to fix the Login interface on the frontend to shift the UI in order to account for keyboard coming up and covering much of the interface. Additionally, I implemented the tooling for the login authorization flow.

## This Week's Plan

I plan to do proper error reporting on the login page to account for incorrect username/password, or if the request simply failed. I won't be able to separate whether username or password are wrong, since SIS does not show that information, but I can show a simple dialog for that. Additionally, I'd like to set up react-native-keychain to preserve login once previously authenticated. This will involve re-logging into SIS, gathering data, and logging out when the user closes the app.

## Anything Blocking?

No blockers currently.

## Notes
