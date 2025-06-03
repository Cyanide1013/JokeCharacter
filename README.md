# JokeCharacter

This is a project submission demonstrating the following requirements:
Objective Create a simple project in Unreal Engine that: 
1. Implements WASD movement for a Simple capsule.
2. Integrates a public API call (like a joke or weather). 
3. Displays the API result on screen (UMG or debug). 
4. (Optional bonus) Trigger the API call via a key press (e.g., 'J' to fetch a joke). 
Task Breakdown 
1. Basic Character Movement- Create a Character class in C++ or Blueprint.- Set up WASD movement.- Handle jump via input bindings. 
2. API Call- On BeginPlay or key press (J), make an HTTP GET request.- Use the Joke API: https://official-joke-api.appspot.com/random_joke. 
3. UI or Screen Display- Display the joke (json response) on UI. 
Optional Enhancements- 
Add a UI button to request a new joke.
- Add a cooldown to prevent spamming.
- Implement error handling (invalid response, network fail).
- Allow the character to talk (e.g., display the joke as a speech bubble).

The project has been developed with blueprints, including character blueprint, input actions, widget blueprints and gamemode inside JokeCharacter Folder.

Most operations and handled directly in character blueprint, and widget blueprints.

Third party plugin VaRest is used to handle api calls.
