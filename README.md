Instagram UI Clone

A clone of the Instagram app made with React, React-native and Typescript.

Dependencies:
React Native (With Typescript)
Native Base
React Navigation
Others (See package.json at the root folder)

Clone the Repo
On the command prompt run the following commands

$ cd InstagramClone

$ npm install

$ grep -rl "s.dependency 'React/Core'" node_modules/ | xargs sed -i '' 's=React/Core=React-Core=g' // To replace React/Core with React-core for all dependencies that use it 

$ cd ios && pod install && cd..

$ react-native run-ios
