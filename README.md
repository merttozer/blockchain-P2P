
# Blockchain Project

This Blockchain Project is designed to demonstrate a simple blockchain implementation. It includes functionalities for creating and managing blocks, handling nodes, and establishing a server for node communication. The project uses modern C++ practices and is structured across multiple modules including core blockchain functionalities, networking, and utility components.

## Prerequisites

To build and run this project, you will need:
- C++17 compatible compiler
- CMake 3.10 or higher
- OpenSSL
- Boost libraries (specifically Boost System)

## Getting Started

Follow these steps to get a local copy up and running.

### Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://your-repository-url
cd your-repository-directory
```

### Install Dependencies

Ensure you have the required dependencies:
- OpenSSL can be installed via your package manager or from [https://www.openssl.org/source/](https://www.openssl.org/source/).
- Boost libraries can be installed via your package manager or from [https://www.boost.org/](https://www.boost.org/).

### Build the Project

Use CMake to build the project:

```bash
mkdir build && cd build
cmake ..
make
```

### Running the Application

Run the executable generated by CMake on different terminals respectively:

```bash
./Blockchain 8080
./Blockchain 8081 8080
```

## Project Structure

- `Block.hpp`: Defines the block structure.
- `Blockchain.hpp`: Manages the chain of blocks.
- `Node.hpp`: Handles the node operations in the network.
- `Server.hpp`: Establishes server functionality for node communication.
- `UserInterface.hpp`: Provides an interface for user interaction.
- `main.cpp`: The entry point for the application.
- `CMakeLists.txt`: Contains build configurations.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your features or fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.