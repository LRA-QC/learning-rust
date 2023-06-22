# Variables

## Assign 10 to variable k
```
let k = 10; 
```

## Assign 10 to variable k and specify datatype as uint 32
```
let k:u32 = 10; 
```

## Assign 10 to variable k, but don't thrown a compiler warning if the variable is not used
```
let _k = 10; 
```

## Immutable by default: try updating an existing variable
```
let k = 10; 
k=4;  // trigger an error, by default variables are immutable
```

## Define a mutable variable: assign 10 to variable k and update it after
```
let mut k = 10; 
k=4;  // ok, since k is now mutable
```

## Throw away variable
```
let _ = my_func();
```

# TUPLES

## ASSIGNMENT
```
let values = (1,"hello");
// values.0 = 1
// values.1 = "hello"
```

## ASSIGNMENT: enforce data type
```
let values: (i32, i32) = (1,2);
// values.0 = 1
// values.1 = 2
```

## SPLIT TEXT
```
let (left, right) = slice.split_at(middle);
```

## SPLIT TEXT AND DISCARD
```
let (_, right) = slice.split_at(middle);
```



# **EXTERNAL REFERENCES**

- Amos [fasterthanli.me] (https://fasterthanli.me/articles/a-half-hour-to-learn-rust)

