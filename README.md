# REACT-REDUX Concepts

### 1. Why JSX?

#### Ans. React doesn't need to use JSX. Normally it is known to all seperation of technology like mark up (html) and logic (JavaScript) in seperate files. 

#### But JSX combines mark up with JavaScript in a Single file. It seperates functionalities by loosely coupling "Components". 

#### Embedding expression in JSX like:

#### const name = 'Fagley Ali';
#### const element = <h1>Hello, {name}</h1>;   

#### ReactDOM.render(
####    element,
####    document.getElementId('root')
#### )