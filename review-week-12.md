## answer 1
import React from "react";

const message = "Welcom to React!"

export function Welcome(props) {
return <div className="welcome">{message}
<h1>Welcome to React!</h1>
}

## answer 2

export function Welcome(props) {
  return <div className="welcome">{message}
  <p>Hello</p>
  <p>World</p>
  </div>;
}

## answer 3
export function Welcome(props) {
  return <div className="Picture">{ProfilePictue}
<img src='../assets/images/profile-picture.jpg' alt='The users profile picture'
/>
  </div>;
}

## answer 4
const name = "John Doe";
const age = "30";
export function Welcome(props) {
  return <div className="welcome">{message}
  <p>Welcome, {props.name}</p>
  <p>you are, {props.age}</p>
  </div>;
}

## answer 5
i think that the code example wont work because, both the const elements are not correct and under the <h1>tag the apple things have no tags to know what they are.

## answer 6

export function TableOfContents(props) {

}

## answer 7

import Profile from "profile";

## answer 8

yup i think the code will work, and i think that it should return a bullet pointed list of apples, bananas and oranges.

## answer 9

const Summary = () => {
  return (
      <div class="title">
        <h1>My Site!</h1>
      </div>
      <p class="description">
        You can find my thoughts here
        <br><br>
        And I have plenty of them!
      </p>
  );
}

## answer 10

export function Greeting(props) {
  return <div className="Greet">{message}
<p>Hello, {props.name}</p>
  </div>;
}

## answer 11

function App() {
    const name = "Horua!";
  return (
    <div className="app">
    <h1>Greetings</h1>
    <Greeting  name={name}/>
  )
}
export default App