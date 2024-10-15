
# NetProbe

**NetProbe** is a high-performance port scanning CLI tool designed to quickly identify open ports on target systems. By leveraging the power of threading, NetProbe ensures fast and efficient scanning, making it an essential tool for network administrators and security professionals.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
        [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/nikhil--chaudhari/)
        [![Medium](https://img.shields.io/badge/Medium-Writeups-black)](https://medium.com/@nikhil-c)

## Features

- **High-Speed Scanning**: Utilizes threading to enhance scanning speed.
- **Comprehensive Reports**: Provides detailed output of scanned ports.
- **Easy to Use**: Simple command-line interface for quick deployment and usage.
- **Customizable Options**: Allows users to specify target IP ranges and port lists.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/NetProbe.git
   ```

2. **Navigate to the NetProbe Directory**
    ```bash
   cd NetProbe
   ```

3. **Install the Required Dependencies**
  ```bash 
  pip install -r requirements.txt
  ```


## Usage

Navigate to Scripts folder
```bash 
cd Scripts
```

To run the basic scan

```bash
python adv_scanner.py -t target_ip -p ports
 ```


Example 
 ```bash
 python adv_scanner.py -t 192.168.1.1 -p 1-65535
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request.

