# Data-Structures-and-Algorithms-with-Python by Lee Kent and Hubbard Steve 

#### Calling Methods on Objects
There are two types of methods in an object-orientated language: 
  - **mutator** methods
  - **accessor** methods 

*Accessor* methods *access* the current state of of an object without changing the object. Accessor methods return new object *references* when called.

                                    x = "hello, goodbye!"
                                    y = x.upper()
                                    print(y)
                                    
**Note** x is not changed when calling the *upper* method 

*Mutator* methods change the existing object. The *revserse* method on the list type, for example, changes the order of the elements within a list. 

                                    myList = [1,2,3]
                                    myList.reverse()
                                    print(MyList) # this prints [3,2,1] on the screen
                                    
                                    
**Note** : a mutator method cannot be undone once called. The change is therfore permanent until mutated again by some other mutator object.
