# CLI Port Sniffer

This is a command-line interface (CLI) port sniffer implemented in Rust. It allows you to scan a range of IP addresses and ports to discover which ports are open and available for network communication.

## Features

- Scan multiple IP addresses and ports simultaneously
- Detect open ports and report their status
- Adjustable concurrency level for efficient scanning
- Timeout settings to control the duration of scanning
- Clean and intuitive command-line interface

## Requirements

- Rust (version 1.54 or later)

## Installation

1. Clone this repository to your local machine:

   ```shell
   $ git clone https://github.com/girordo/port-sniffer-with-rust.git
   ```

2. Change into the project directory:

   ```shell
   $ cd port-sniffer-with-rust
   ```

3. Build the project using Cargo:

   ```shell
   $ cargo build --release
   ```

4. The binary will be located in the `target/release` directory. You can either add this directory to your system's PATH or run the binary directly from the project directory.

## Usage

The basic usage of the CLI port sniffer is as follows:

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
