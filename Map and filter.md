The idea of a map function is to apply a function to an iterable data.

Formatting:

map(function_name, sequence)

-- function_name: any function (built-in or selfmade) that returns a desired value of choice
-- sequence: any iterable data type

One thing to note about the map function is that it doesn’t return a specific data type, but rather, an python iterable data. 
Therefore, after we apply the map function, we just execute a list function on it.

filter(bool_returning_function, sequence)

-- function: The function name we provide for filter() must be return a boolean value ... should also be able handle the items inside the sequence as its arguments
-- sequence: any iterable data type
