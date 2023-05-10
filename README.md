```javascript

class Person {
    constructor(name) {
      this.personName = name;
    }
    present() {
      return 'I am ' + this.personName;
    }
  }
  
  class Engineer extends Person {
    constructor(name, interest, learning) {
      super(name);
      this.interest = interest;
      this.learning = learning;
    }
    show() {
      return this.present() + ', my interests are on ' + this.interest + ' and I am currently learning' + this.learning; 
    }
  }
  
  let me = new Engineer("Kastriot", "Frontend", "VueJS");
