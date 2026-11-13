# React-Lab-Exercise-3-State-in-React
## Name: Madhan Kumar J
## Roll no: 2305001016
## Department: CSE

## AIM
### To create a simple React application that demonstrates the use of State using the useState() Hook. 

## PROGRAM
### App.jsx 
```py
import { useState } from "react"; function App() { const [name, setName] = useState("Aravindan T"); const [newName, setNewName] = useState(""); 
return ( 
<div> 
<h1>Student Name Example</h1> 
<h2>Student Name: {name}</h2> 
<input type="text" placeholder="Enter new name" value={newName} 
onChange={(e) => setNewName(e.target.value)} 
/> 
<button onClick={() => setName(newName)}> 
Change Name 
</button> 
</div> 
);
}
export default App;

```
## OUTPUT
<img width="905" height="715" alt="image" src="https://github.com/user-attachments/assets/7122a142-19a0-415c-8ef5-02cc0796eca5" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
