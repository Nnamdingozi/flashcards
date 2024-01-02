## FlashCard (Quiz App) Project built as part of CodeCademy Full-Stack Engineer Course requirement

### Description
 The flasCard is a Quiz application that emables users to create their own topics, quizzes for those topics as well as flash Cards for the quizzes.
 Users will also be able to interact with their quizzes by flipping flashcards over. 
 The app was built with React library. The project mainly tested knowlege of core Redux toolkit features

 ### prerequisite skills
 
 To work on this project, knowlege of the following skills is prerequisite

 * React
 * React-Redux
 * React-routers
 * Redux toolkit
 * uuidv4


### Skills implementation

* Created Slices for topics, quizzes and cards, using createSlice from Redux toolkit.
* Generated unique Ids for topics, quizzes and cards using uuidv4
* Defined initial state, actions, reducers and extraReducers within the slices
* Created and exported  selectors for topics, quizzes and cards states, to make them accessible within the components using useSelector from React-redux.
* Added the topics, quizzes and card reducers to the store, using configureStore from redux toolkit.
* Displayed the components on the UI using react routers


### Run Application

To run this application, make sure that you have node installed in your computer
* in Your terminal, run npm install
* finally run npm start


### lICENCE
MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

   
