
import './App.css';
import React from 'react';
import {useState} from 'react';


function App() {
  const[name,setname]=useState('');
  const[email,setEmail]=useState('');

  const handleSubmit=(e) => {
    e.preventDefault();//Prevent page reload
    alert(`form Submitted with:\nname:${name} \nEmail:${email}`);
  }
  return (
    <div className="App">
      <h1>simple react form</h1>
      <form onSubmit={handleSubmit}>

        <div>
          <lable> name </lable>
          <input type = "text" value={name} onChange={(e) =>setname (e.target.value)}placeholder="enter user name"/>

      </div>
      <div>
      <lable>email</lable>
        <input type="email" value={email}onChange={(e)=>setEmail(e.target.value)}placeholder="enter user email"/>
      
          <button type="submit">submit</button>
        </div>
        </form>
        </div>
      
  );
}

export default App;
