# Task
### Write a constructor which creates an object
### Add a method to the constructor getting two arguments: name of a property and value of a property. This method adds the property to the object.

function Users (name, age) {
    this.name = name
    this.sge = age 
}

Users.prototype.addNewprop = function (propName, propValue) {
        this [propName] = propValue
