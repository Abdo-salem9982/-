#  Collection

### The advantage of using a collection is :
 - indicates that multiple pieces of data are related

Collection : مجموعه معلومات 

## - list

list: simple collection that groups pieces of data together in a certain order and assigns the collection a name


### Create a list and work with it
```python
# Office locations
# city1 = 'Tokyo'
# city2 = 'Dakar'
# city3 = 'Mumbai'
# city4 = 'Buenos Aires'

cities = [
    'Tokyo', 
    'Dakar', 
    'Mumbai', 
    'Buenos Aires',
]

print(cities[1])

```
Here the output will be the second item on the list. ( Dakar )

###  note 1 : 
Index number : start at zero 
###  note 2 : 
The ( list ) is a name of groups of pieces of data in ( python ), but in ( JavaScript ), it's called ( Array )


## - Dictionary 

Dictionary : Lets you store related information


### Create a dictionary and work with it


```python
# California state symbols
# state_bird = 'California quail'
# state_animal = 'Grizzly bear'
# state_flower = 'California poppy'
# state_fruit = 'Avocado'

california_symbols = {
    'bird': 'California quail',
    'animal': 'Grizzly bear',
    'flower': 'California poppy',
    'fruit': 'Avocado',
}
print(california_symbols['flower'])

```
Here the output will be the value of the flower key. ( California poppy )

## First Challenge
1. Replace variable with list " stars " .
2. Create statement that prints fourth nearest star.
3. Create dictionary " peaks " that stores all values.
4. Create statement that prints name of highest peak on pacific plate.

```python
# Nearest stars to Earth
star1 = 'Sol'
star2 = 'Alpha Centauri'
star3 = 'Barnard'
star4 = 'Wolf 359'

# Highest peak on each tectonic plate
African = 'Kilimanjaro'
Antarctic = 'Vinson'
Australian = 'Puncak Jaya'
Eurasian = 'Everest'
North_American = 'Denali'
Pacific = 'Mauna Kea'
South_American = 'Aconcagua'

```
## First Challenge ' Solve '
```python
stars  = ['Sol' ,'Alpha Centauri' , 'Barnard' , 'Wolf 359']
peaks = {
    'African' : 'Kilimanjaro',
    'Antarctic' : 'Vinson',
    'Australian' : 'Puncak Jaya',
    'Eurasian' : 'Everest',
    'North_American' : 'Denali',
    'Pacific' : 'Mauna Kea',
    'South_American' : 'Aconcagua',
}
print(stars [3] + ' & ' + peaks['Pacific'])

```
Here the output will be the value of the flower key. ( Wolf 359 & Kilimanjaro )

***





