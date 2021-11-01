
## Usage

```python
class Person:
    def __init__(self, name, interest, learning):
        self.name  = name
        self.interest = interest
        self.learning = learning
        
    def show(self):
        print(f"Hello , i am {self.name} with interests in {self.interest} and also learning {self.learning}")
        
person_1 = Person('Kastriot',
                  'Python/Django',
                  'React')
                  
print(person_1.show())


