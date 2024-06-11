# Expo Web Bug

Earlier today, I began working on an Expo project I started recently. When running the application using "npx expo start", the terminal gave me a message stating:

"The following packages should be updated for best compatibility with the installed expo version:
expo@51.0.11 - expected version: ~51.0.12
expo-router@3.5.15 - expected version: ~3.5.16
Your project may not work correctly until you install the expected versions of the packages."

Naturally, I reinstalled the correct versions of expo and expo-router. After I made this change, I ran the application again and typed 'w' to open the app on web. I was then met with this error:

"Static Rendering Error (Node.js)
Unable to resolve module .\node_modules\expo-router\entry from C:\Users\liamb\OneDrive\Desktop\comp sci personal\Lifting App\Project\Fitness-Tracker/.: .\node_modules\expo-router\entry could not be found within the project or in these directories:
node_modules
Call Stack
<unknown>
."

The application opened on web just fine before installing the newer version of expo and expo router. I noticed this problem also occurs when creating a new expo project.

This repository was generated using "npx create-expo-app@latest" and I have only changed the readme file.
