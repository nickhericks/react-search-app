# React Exercise - Full Stack JavaScript Techdegree

### Search application
This project was a way for me to learn about create-react-app and React-Bootstrap.

***
<!-- <img src="https://res.cloudinary.com/dtqevfsxh/image/upload/v1554485395/portfolio/expressDoubler.png" width="700px"> -->

## View project
:mag: Live version available at [nickhericks.github.io/react-search-app/](https://nickhericks.github.io/react-search-app/)

<!-- ## Project objective -->
<!-- To complete this project I created JavaScript classes (Game, Board, Space, Player, Token) to organize the code. Each class, with its constructor function, methods, getters and setters is in its own .js file, and the app.js file handles the interaction with DOM elements. -->
<!-- 
## Techniques and concepts
- Express web framework -->

## Code example
```javascript
import React from 'react';
import { Container, Jumbotron } from "react-bootstrap";
import SearchForm from './components/SearchForm';
import Results from './components/Results';

function App() {
  return (
    <div>
      <Jumbotron>
        <Container>
          <h1>Search App</h1>
          <p>This is a simple search app</p>
					<SearchForm />
        </Container>
      </Jumbotron>

			<Results />
    </div>
  );
}

export default App;
```

## Acknowledgements
This project was built as part of the [Full Stack JavaScript Techdegree](https://join.teamtreehouse.com/techdegree/) offered by [Treehouse](https://teamtreehouse.com) :raised_hands:

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).