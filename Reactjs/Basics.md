1) Components

A component is a function or class that returns JSX and represents a reusable part of the UI.

Real-life example:
A website is a building → buttons, navbar, footer are components.

👉 Today, function components are preferred because of Hooks.

2) JSX

JSX stands for JavaScript XML.
It looks like HTML but allows JavaScript expressions inside {}.

Browsers cannot read JSX directly, so it is compiled into JavaScript (using tools like Babel).

Example:

<h1>Hello, {username}</h1>

3) URL Routing

Routing allows navigation between different views in a Single Page Application without reloading the page.

React Router keeps the UI in sync with the URL.

Real-life example:
Different rooms in a house, but you’re still inside the same house.

4) Props

Props are used to pass data from a parent component to a child component.
Props are read-only.

Real-life example:
A parent giving instructions to a child — the child cannot change them.

👉 Passing props through many layers is called prop drilling.

5) State

State is data owned by a component that can change over time and causes the component to re-render.

Example:
Login status, counter value, form input data.

👉 When state changes → UI updates automatically.

6) Component Lifecycle

Every component goes through three phases:

Mounting – Component is added to the DOM

Updating – Component re-renders due to state/props change

Unmounting – Component is removed from the DOM

In functional components, useEffect is used to handle side effects related to these phases.

Real-life example:
Switching a light ON (mount), adjusting brightness (update), switching it OFF (unmount).

7) Hooks

Hooks allow functional components to use state, lifecycle logic, and other React features.

Hooks only work in functional components.

Common Hooks:

useState() → manage state

useEffect() → handle side effects (API calls, subscriptions)

👉 Before Hooks, functional components were stateless.

8) State Management

When multiple components need access to the same data, we use global state management.

This avoids prop drilling.

Common solutions:

Context API

Redux (third-party library)

Real-life example:
User login status available to navbar, profile, and settings page.

9) Virtual DOM

The Virtual DOM is a lightweight copy of the real DOM.

When state changes:

Virtual DOM updates

React compares old vs new Virtual DOM (diffing)

Only the required changes are applied to the real DOM

👉 This makes React fast and efficient.

10) Key Prop

Keys help React identify list items uniquely during re-rendering.

Rule:
Keys must be unique and stable.

Example:

{users.map(user => (
  <li key={user.id}>{user.name}</li>
))}

11) Handling Events

Events in React are handled using event handlers, not traditional event listeners.

React uses Synthetic Events for better performance and consistency.

Example:

<button onClick={handleClick}>Click</button>

12) Handling Forms

Forms in React are usually handled using controlled components.

Form input values are stored in state, making the UI and data always in sync.

Real-life example:
Typing in an input box updates state → state updates UI.

13) Conditional Rendering

Rendering UI based on conditions.

Example:
Show user name only if logged in, otherwise show Login button.

{isLoggedIn ? <Profile /> : <Login />}

14) Re-rendering (Important Concept) ⭐

A component re-renders when:

Its state changes

Its props change

Its parent re-renders

👉 Re-render ≠ DOM update (thanks to Virtual DOM).

15) Unidirectional Data Flow ⭐

Data in React flows one way:
Parent → Child

This makes the application:

Predictable

Easier to debug

Easier to scale