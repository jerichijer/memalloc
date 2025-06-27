# memalloc

A simple memory allocator for managing memory allocation in C programs.

## Key Features and Highlights

- Efficient memory allocation and deallocation
- Simplified interface for managing memory
- Suitable for small to medium-sized projects

## Usage Examples

### Allocating Memory

```c
// Allocate memory for 10 integers
int* numbers = (int*)memalloc(sizeof(int) * 10);
```

### Freeing Memory

```c
// Free the allocated memory
memfree(numbers);
```

## Dependencies

The `memalloc` library has no external dependencies.
