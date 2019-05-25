## Eliminating Time

Solutions are nonsense without understanding the problems they solve. We'll take a trip down memory lane to shine a light on the stuff that led to all the bugs we've written in the past to prime us to see clearly how React is going to help.

Objectives:
- Understand the problems React solves
- Get people thinking about [the conceptual gap between the static program and the dynamic process][Dijkstra], and what it means to "eliminate time" in their apps
##Installation

Objectives:
 - Understand npm command line
 - Expo
 - 
## Rendering with React

We'll explore the lowest level of React: rendering UI. We'll take a look at what the "Virtual DOM" and JSX are, brush up on some JavaScript array methods, and do our first coding exercise.

Objectives:
- Render UI with React
- Transform and massage data into UI
- Become familiar with JSX
- Brush up on JavaScript expressions and scope


## Components

Components are the building blocks of UI in React. We'll discuss a few parts of a component's lifecycle, it's interface with the rest of the application, component state, encapsulation, and how to make components reusable.

Objectives:
- Define components
- Determine good values for component state
- Interface with the rest of the world (props)
- Use propTypes as "runnable documentation"
- Handle user interaction


## Props v. State

One of the first questions that comes up when you start using React is "when do I use state, and when do I use props?" We'll explore an app with changing requirements that lets us experience state moving to props and why. We'll discuss how data flows, or rather, how components communicate with each other. Finally, we'll explore how component composition helps answer the "props v. state" question.

Objectives:
- Understand the difference between props and state
- Know when to use props v. state
- Pass data up and down the view hierarchy
- Compose generic components into specialized components


## The Imperative to Declarative Shift

React is "declarative". What does that mean? What is imperative code?  We'll answer these questions, and show the power that comes from shifting your imperative code into declarative components using more of the React component lifecycle.

Objectives:
- Turn imperative code into declarative code
- Experience the benefits that come from declarative programming
- Learn to use existing JS libraries declaratively
- Use more of the React component lifecycle


## Compound Components

Some components get really, really big. Not only do their render methods get large, but as more people try to use the component, the props it takes grow as well. Eventually you end up with way too many properties and a really difficult component to work with that has to change with every new use-case you throw at it. There's a better way with compound components.

Objectives:
- Create reusable components by compounding related components together
- Dynamically flow data between components
