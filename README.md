# Fundamentals of Python - Quiz

We recommend you **do not** use Python to answer these questions. Instead, based on what you have learned in this section, _reason_ the code to choose an expected answer. 

???

# Lists, dictionaries, conditionals, and loops

?: Question 1    


Horatio owns a zoo and is keeping track of the next animals he wants to purchase in a list.    


```python
animals = ['ocelot', 'capybara', 'narwhal', 'koala', 'king cobra']
```   

Which animals will be returned if we used the index `[2:4]` to subset the list?    


( ) `['capybara', 'narwhal', 'koala']`      
( ) `['narwhal', 'koala', 'king cobra']`       
(X) `['narwhal', 'koala']`       
( ) `['capybara', 'narwhal']`       



?: Question 2     


Sadly, he realizes that narwhals cannot be kept in captivity, so Horatio opts to get another Arctic animal, a penguin. What is/are the way(s) to change the value of `'narwhal'` to `'penguin'`?      


[X] `animals[-3] = 'penguin'`    
[ ] `animals.insert(2, 'penguin')`     
[X] `animals[2] = 'penguin'`      
[ ] `animals.append(2, 'penguin', replace = True)`     



?: Question 3      


Horatio creates a dictionary with these animals, categorizing them based on their class.      


```python
animal_dict = {'mammal': ['ocelot', 'capybara', 'koala'],
               'bird' : 'penguin',
               'reptile': 'king cobra'} 
```       


What is the output of `animal_dict['mammal']`?        

( ) `'ocelot'`    
( ) `'capybara'`    
( ) `'koala'`     
(X) `['ocelot', 'capybara', 'koala']`     
( ) None of the above     
( ) An error     


?: Question 4     


What is the output of:       

```python
for i in animal_dict:
    print(i)
```         


( ) ['ocelot','capybara','koala'] , 'penguin', 'king cobra'     
( ) There would be a ValueError: too many values to unpack      
( ) ('mammal', ['ocelot','capybara','koala']) , ('bird','penguin'), ('reptile', 'king cobra')     
(X) 'mammal' , 'bird', 'reptile'         



?: Question 5       


What is the output of:       


```python
var = 1
var -= 1

if var:
    print('cat')
else:
    print('dog')
```        


( ) `'cat'`     
(X) `'dog'`     
( ) An error      



???
