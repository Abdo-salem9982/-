#  Programming Foundations: Beyond the Fundamentals

##  - **_Collections_**

   * ### Definitions
     1. **Collection** : containers used for storing data and are commonly known as data structures, such as lists, tuples, arrays, dictionaries, etc. 
     2. **list** : simple collection that groups pieces of data together in a certain order and assigns the collection a name.
     3. **Dictionary** : Lets you store related information.
   ___
    
   * ###  list ( Array )

     **Create a list and work with it**
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

   ###  Notes : 
   1. **Index number** : start at zero 
   2. The **list**  is a name of groups of pieces of data in ***python***, but in ***JavaScript*** , it's called **Array**

   ***

   * ###  Dictionary 

     **Create a dictionary and work with it**

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
    ***

  * ### 1st Challenge
   1. Replace variable with list " **stars** " .
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
   * ### 1st Challenge ' **Solve** '
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
   
   
   *  ### Section Question
        1. what is the advantage of using a collection is?
           * Ans : Indicates that multiple pieces of data are related


***
***

## - **_Iteration_**
  * ### Definitions
    1.  **Iteration** : Repeats the same procedure multiple times until it reaches a specified endpoint .
    2.  **Loop** : Code that iterates , moving from beginning to end of the process , then starting over . 
    3.  **Infinite** Loop : bug that occur when the ending condition is omitted or specified incorrectly .
  ---
   ### Iteration Tools ( looping Tools )

   * **_For loop_**

     ```python
     spices = [
         'salt',
         'pepper',
         'cumin',
         'turmeric',
     ]
     for spice in spices:
         print(spice)
     print('No more boring omelettes!')

     ```
  Here the output will be the values of the spices and will be printed one after the other.

  ###  Notes : 
   1. **For** : Specifies a variable name that we can use in each iteration of the loop to reference the current value .
   2. **in ( __python keyword__ )** : Indicates that what follows in the set of values that we want to iterate through
   
   ***

   * **_While loop_**

  ```python
  print('Counting to 100 by fives:')
  i = 5
  while i <= 100:
      print(i)
      i += 5
  print('List complete!')

  ```
  Here the output will be list of numbers starting with 5 and counting ny 5 to 100.
  ###  Notes : 
  1. **While** : Specifies a variable name that we can use in loops through a block of code as long as a specified condition is true .
  2. **i** : start condition

   ***

  * ### 2nd Challenge
   1. Print the name of all the fruits in the Terminal.
   2. Print each name on a separate line.
   3. Above list , print " Our fruit selection ".

  ```python
  fruits = [
      'apples',
      'bananas',
      'dragon fruit',
      'mangos',
      'nectarines',
      'pears',
  ]
  ```

  * ### 2nd Challenge ' **Solve** '

  ```python
  fruits = [
      'apples',
      'bananas',
      'dragon fruit',
      'mangos',
      'nectarines',
      'pears',
  ]
  print('Our fruit selection:')
  for fruit in fruits:
      print(fruit)
  ```

  Here the output will be "**Our fruit selection :**" title followed by each fruit name.
  
   *  ### Section Question
       1. What is another term for code that iterates?
          * Ans : **a loop** ( Code that iterates is often described as a loop, because the process moves from beginning to end and then starts over again at the beginning )


   ***
   ***

##  - **_External Code_**


   * ### Definitions
    1. **Module** : Pythone file that contains code, like variables or functions. set of tools that you can use as you wish.
    2. **Package or Library** : Using multiple modules together so they are distributed and used in a group. how you should accomplish a task.
    3. **framework** : when a set of code is not just used together but used in a specific way.
    
   ***
   
  * **_Create Module & use it_**

       1. Create Module  ( testCode.py )
            ``` python
            def mult(x, y):
              print(f'{x} * {y} = {x * y}')
            ```

      2. Using Module in other Code ( app.py )
            ``` python
            import testmodule
            testmodule.mult(10, 5)
            ```

      Here the **app.py** will access the function in **testCode.py** and can pass parametars to **mult** function in **testCode.py** . Here the output will be (**10*5 =50**).

    ***


  * **_Examples for Packages or Librarys_**

    1. **pandas** in python
    2. **jQuery** in JavaScript

  * **_Examples for frameworks_**

    1. **Django** in python
    2. **React** in JavaScript

 *** 
   *  ### Section Question
       1. Why do developers sometimes use shared code in their programs?
          * Ans : **It can become tedious to have to rewrite code to solve the same problem over and over.**
       2. How is a framework different from a library?
           * Ans : **A framework essentially defines how you should accomplish a task. And gives you a structure to use as a starting point and customize.**

  ***
  ***
  
  
  
##  - **_Working with strings_**

  * **_Combining Strings_**

    * Can combining string by using ' **+** ' operator
      ``` python

      value = input('Enter a number: ') # 50 as input
      print(value + ' is my favorite number!')
      ```
      Here the output will be " **50 is my favorite number** ".
      ---
        ###  Notes : 
         ' **Value** ' is a string not a **number**

  * **_Methods help with strings_**
    1. **Capitalize()**
       * used to capitalize the first **letter** of string
          ``` python
            irst_name = 'malala'

            first_name_cap = first_name.capitalize()
            last_name_cap = last_name.capitalize()
            print(first_name_cap)
           ```
           
            Here the output will be " **Malala** ".
       ---
       
     2. **Find()**
       * Return the index of what i looking for
          ``` python
            note = 'award: Nobel Peace Prize'
            
            award_location = note.find('award: ')
            print(award_location)
           ```
           
            Here the output will be " **0** ".
       ---
              
     2. **Slicing**
       * Getting part of a string value
          ``` python
            note = 'award: Nobel Peace Prize'
            
            award_text = note[7:10]
            print(award_text)
           ```
           
            Here the output will be " **Nob** ".
            
     ###  Notes : 
       ' **7** ' is a **Start**
       ' **10** ' is a **End**
       ---
       

  * ###  _Regular expression_ , Also known as **regex**_

      - allows you to create a description of a pattern that you want to match
      
   * **Made up of**
      1. Letters
      2. Numbers
      3.  Special character

  * Creating regular expressions
    ``` python
       import re

      five_digit_zip = '98101'
      nine_digit_zip = '98101-0003'
      phone_number = '234-567-8901'

      five_digit_expression = r'\d{5}'

      print(re.search(five_digit_expression, five_digit_zip))
      print(re.search(five_digit_expression, nine_digit_zip))
      print(re.search(five_digit_expression, phone_number))
    ```

  ***
  
 * ### 3rd Challenge
   1. Take the value entered by a user.
   2. Convert it to a value in Kilometers.
   3. print the result to the terminal.

  ```python
    miles = input('Enter a distance in miles: ')
    # kilometers_value = miles_value * 1.609344
  ]
  ```
  
  
 * ### 3rd Challenge ' **Solve** '

     ```python
            miles = input('Enter a distance in miles: ')
            miles_float = float(miles)
            # kilometers_value = miles_value * 1.609344
            kilometers = miles_float * 1.609344
            print('That value in kilometers is')
            print(kilometers)
     ```
     
      Here the output will be input ' value * 1.609344 '
     

***
***


##  - **_Input and Output_**

 * ###  _Read and write txt files_

     ```python
      infile = open('values.txt', 'rt')
      outfile = open('values-totaled.txt', 'wt')
      print('Processing input')
      sum = 0
      for line in infile:
          sum += int(line)
          print(line.rstrip(), file=outfile)
      print('\nTotal: ' + str(sum), file=outfile)
      outfile.close()
      print('Output complete')
    ```
    
    ### What does this code do? 
    * Write the values from **values.txt** in **values-totaled.txt** and calculate the sum of all values, then write the result in **values-totaled.txt**.

___
 *  ### Section Question
    * Why might you display statements for the user indicating when processing starts and when output is complete?
      * Ans : **if you want to let the user know where in the process the program is when a program takes a long time to run.**


***
***




