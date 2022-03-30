# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|{username:'Jjones08', isActive:true;}| Welcome back, Jjones08!| 
|{username:'Holly92', isActive:false;}|Hey Holly92! Would you like to renew your subscription?| 
|{username:'Sam28', isActive:true;}|Welcome back, Sam28!| 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program gives a message to the login user based on whether they have an active account or not.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
