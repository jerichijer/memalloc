# memalloc

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

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

## Contributing

Contributions are welcome! To contribute to `memalloc`, follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
