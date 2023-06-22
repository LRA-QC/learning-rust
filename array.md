# ARRAY

## Define Int32 array of 300 elements (initialized to 0)
```
let array:  [i32; 300] = [0;300];
```

## Array slice
```
let a = [1, 2, 3, 4, 5];
let nice_slice = &a[1..4];
// nice_slice  = [2,3,4];
```


## Iterate an array
```
for x in array {
    print!("{x} ");
}
```
