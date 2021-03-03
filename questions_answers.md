# Javascript Questions

### What are Closures?
- A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). A closure gives you access to an outer function's scope from an inner function. 
- In JavaScript, closures are created every time a function is created, at function creation time. 

- The inner function has access to the variables and scope of the outer function. 
- JS provides access to variables outside of a function (above or below function)

### What are JS Promises
- The Promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting values
- A Promise is in one of these states:
- pending: initial state, neither fulfilled nor rejected
- fulfilled: menaing that the operation was completed successfully
- rejected: meaning that the operation failed 

```JS
let p = new Promise((resolve, reject) => {
  let a = 1 + 1
  if(a == 2){
    resolve('Success')
  }else{
    reject('Failed')
  }
})

p.then((message) => {
  console.log(`This is the '.then' ${message}`)
}).catch((message) => {
  console.log(`This is the '.catch' ${message}`)
})
```



### What is Object Oriented Programming?



### What is this keyword and how would you set it? 
- variable that is provided in the local class
- it is provided via the class props
- can access it with this.props or this.state
- can set it with setState()






# React Questions

### What is the difference between props and state
- props can be passed down to other components 
- state is local to the particular class and set with setState()

### Explain what the Virtual Dom is
- It's a layer that looks for changes to the view
- when setState() is updated a new view will be rendered
- saves time/expense because it is only called when needed, stopping the view from always updating

### What is Testing or Test Driven Development
      -**Why is it important**
    	-**What frameworks are available**



### What is version control
- type of version control is Git
- Provide branches of control to organize a project
- Ex. there can be a brance for testing, development. When project is complete all branches are merged. 






