# C-StyleGuide

## Classes

### Class Names
Pascal case, e.g.

```c++
class MyClass { ... }
```

### Member Variables
Snake case, e.g.

```c++
class MyClass {
  int my_int;
}
```
### Methods
Snake case, e.g.

```c++
class MyClass {
  int my_method();
}
```

## Namespaces
Snake case, e.g.

```c++
namespace my_namespace { ... }
```

## Globals
### Variables
Snake case, e.g.

```c++
int global_int = 0;
```

### Functions
Snake case, e.g.

```c++
int global_function() { ... }
```

#### Function variables
Snake case, e.g.

```c++
int my_func(int num_a, int num_b) {
  return num_a + num_b;
}
```

### Macros
Uppercase with underscores, e.g.

```c++
#define MY_MACRO 10
```
