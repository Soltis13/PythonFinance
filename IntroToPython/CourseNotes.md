This notebook will just go through the basic topics in order:

    Data types
        Numbers 
            (+, -, *, /, **, % )
        Strings 
            ('single quotes' "double quotes")
        Printing 
            print('My number is: {one}, and my name is: {two}'.format(one=num,two=name))
        Lists 
            [,]
        Dictionaries 
            d = {'key1':'item1','key2':'item2'}
        Booleans 
            True and False
        Tuples  (can not be reasigned)
            t = (1,2,3)
        Sets (unordered collection fo unique items)
            {1,2,3}

    Comparison Operators

    if,elif, else Statements
        if 1 == 2:
            print('first')
        elif 3 == 3:
            print('middle')
        else:
            print('Last')

    for Loops
        for item in seq:

        or 

        [item**2 for item in x]

    while Loops
        i = 1
            while i < 5:
                print('i is: {}'.format(i))
                i = i+1

    range()
        range(5)
        for i in range(5):
            print(i)

    list comprehension

    functions
        def my_func(param1='default'):
            """
            Docstring goes here.
            """
            print(param1)

    lambda expressions
        def times_two(var):
            return var*2
        
        lambda var: var*2

    map and filter
        (Python built in function)
        map(times_two, seq)

    methods
        .upper()
        .split()
        