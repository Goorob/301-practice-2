# 301-practice-2

**1. In a Handlebars template, what does {{city}} refer to?**
It's  handlebars expression When the template is executed, these expression are replaced with values from an input object which the key for it is city .



**2.Explain how the following code in a Node-express server is triggered to run, and what it's output is**
server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.send(200).json(animals);
});
   this server have a route "list" the output for it will be printing out the animals array 




   **3.write a Constructor function that can create an instance of a person, with a name and an age, given 2** **arguments**

function Person(name , age){
    this.name = name ;
    this.age = age ;
};
let student = new Person('yumen',7);