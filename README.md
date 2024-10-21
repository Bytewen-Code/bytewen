
# Bytewen

Bytewen is a minimalistic, efficient, and powerful programming language designed to give you control with simplicity. Whether you’re a beginner or an experienced developer, Bytewen provides a straightforward approach to writing clean and concise code.

## Key Features

- **Simplicity:** Bytewen is designed with an intuitive syntax that's easy to understand and quick to learn.
- **Possibilities (Functions):** Bytewen replaces the concept of functions with “possibilities,” which help you create reusable blocks of code.
- **Sandboxing:** Bytewen can run in isolated environments, making it safe for web-based applications.
- **Cross-Platform:** Bytewen is lightweight and works across various environments and platforms.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bytewen-Code/bytewen.git
   ```

2. **Run your first Bytewen program:**
   After cloning, you can run your Bytewen scripts using the provided interpreter.
   ```bash
   bytewen examples/hello-world.bw
   ```

3. **Example Script:**
   Below is an example of a simple Bytewen script:

   ```bytewen
   x = 10
   y = 20

   possibility add(x, y) {
       output "Sum: " + (x + y)
   }

   call add(x, y)
   ```

   This script defines a possibility (function) to add two numbers and outputs the result.

## Documentation

You can find the complete documentation for Bytewen at [Bytewen Documentation](https://bytewen.pages.dev/docs).

## Contributing

We welcome contributions from the community! Whether you want to add features, fix bugs, or improve documentation, feel free to fork the repo and submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Submit a pull request.

## License

Bytewen is open-source under the MIT License. See [LICENSE](LICENSE) for more information.
