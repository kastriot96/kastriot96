```javascript

class Person { 
    constructor(name, interest, learning) {
        this.name = name;
        this.interest = interest;
        this.learning = learning;
    }
    personDetails() {
        console.log(`Hello I'm ${this.name} , my interests are on ${this.interest} and I'm currently learning ${this.learing} :)`
    }
}

let personOne = new Person('Kastriot', 'Frontend', 'VueJS');
