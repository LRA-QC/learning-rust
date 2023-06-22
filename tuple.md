# TUPLE


## Assignment

```
let cat = ("Furry McFurson", 3.5);
```

## Example

```
fn main() {
    let cat = ("Furry McFurson", 3.5);
    let (name,age) = cat;

    println!("{} is {} years old.", name, age);
}
```

## Access specific element

```
let numbers = (1, 2, 3);
let second = numbers.1; 
// starts at 0 so .0=1 .1=2 .2=3
```


### REFERENCES

- Rustlings examples