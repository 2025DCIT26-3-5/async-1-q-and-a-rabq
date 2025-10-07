# Hello World

## Question
#How to print Hello World in React?
## Answer
#Una ay gagawa muna tayo ng function na kailangan sa react
function App() {
  return <h1>Hello World</h1>;
}

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);



# Interactive Counter

## Question
#Paano gumawa ng button na nagdadagdag ng number sa React?
## Answer
#Gamitin ang useState hook para mag-store ng number at dagdagan ito gamit ang button.
ex;
function Counter() {
const [count, setCount] = React.useState(0);
return (
<div>
<p>Count: {count}</p>
<button onClick={() => setCount(count + 1)}>Add</button>
</div>
);
}



# Multiple Components

## Question
#Paano gumawa ng React app na may maraming components?
## Answer
#Gumawa ng hiwalay na functions para sa bawat component at gamitin sa main App.
ex;
function Header() {
return <h1>My Website</h1>;
}

function Footer() {
return <p>© 2025 All rights reserved</p>;
}

function App() {
return (
<div>
<Header />
<p>Welcome sa site!</p>
<Footer />
</div>
);
}


# Pure React (No JSX)

## Question
#Paano gumawa ng element sa React nang walang JSX?
## Answer
#Gamitin ang React.createElement() para gumawa ng element gamit JavaScript lang.
ex;
const element = React.createElement('h1', null, 'Hello World (No JSX)');
ReactDOM.render(element, document.getElementById('root'));