# Recipe App AI

## What did we use in the project?
### 1- [Expo SDK 55](https://docs.expo.dev/get-started/create-a-project/)
### 2- [Google AI Studio](https://aistudio.google.com/apps)
### 3- [Expo/skills](https://github.com/expo/skills)
### 4 [](https://expo.dev/expo-skills)


## Getting Started Expo Applaction

- Open Cmd -> cd desktop
```
npx create-expo-app@latest --template default@sdk-55
```
- copy api from Google AI Studio -> Get Api Key
- open .env file paste API_KEY=
```
API_KEY=your_actual_api_key_here
```
- npx expo start
- npm run android
- npm run ios
- claude Opus 4.7
- gemini-2.5-flash

  
## Claude Code
### Expo Skills/Plugins

- Add the marketplace:
```
/plugin marketplace add expo/skills
```

- Install the plugin:
```
/plugin install expo
 ```

 
## Prerequisites

- [Node.js](https://nodejs.org/en) (LTS recommended)
- [Expo CLI](https://docs.expo.dev/get-started/set-up-your-environment/)
- iOS Simulator (macOS) or Android Emulator, or a physical device with [Expo Go](https://expo.dev/go)


### Prompt
```
1 > Set up three tabs for the app:
        * Home
        * Favorites
        * Settings  On the home screen, I want:
        * a text input where I can type what I want to cook
        * filter chips underneath for things like vegan, keto, gluten-free, dairy-free, and so on
        * below that, add a big green "Generate Recipe" button
        * two smaller buttons side by side
        * one of them will say "Surprise Me"
        * the "Scan Ingredients" button  Set up the types storage we will need for saving recipes and preferences later.

 2 > Hook up the Gemini API so I can actually generate recipes when I type something like "butter chicken" and tap "generate".
            It should call Gemini, get back the full recipe, and take me to the detailed screen showing:

           * the title
           * a description
           * all the ingredients with amounts
           * a step-by-step instruction in a nice timeline layout
           * stats like prep time, cook time, servings, and calories  It should do the same thing but with a random recipe idea.

3 > Add AI image generation for the recipe. When I open a recipe that doesn't have a photo yet, it should automatically generate one in the background using Gemini and show it as a big image on the top of the recipe screen. While it's generating, show a loading spinner, and when the image is ready, fade it in smoothly. Save the image so that it also shows up on the recipe cards elsewhere in the application.

```

## Preview Final Project

##### Page 1
<img src="" style="width:300px;" alt=" Page" />



#### Start Screen







# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### Other setup steps

- To set up ESLint for linting, run `npx expo lint`, or follow our guide on ["Using ESLint and Prettier"](https://docs.expo.dev/guides/using-eslint/)
- If you'd like to set up unit testing, follow our guide on ["Unit Testing with Jest"](https://docs.expo.dev/develop/unit-testing/)
- Learn more about the TypeScript setup in this template in our guide on ["Using TypeScript"](https://docs.expo.dev/guides/typescript/)

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
