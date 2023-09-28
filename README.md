# Advanced-Port-Scanner

## Description

Advanced-port-scanner is a high-performance port scanning tool designed for Kali Linux. It offers a significant speed improvement for port scanning operations, enabling users to efficiently scan ports in less time.

## Installation

If you are using Kali Linux and do not have Python and Git installed on your system, follow these steps to set up the Advanced-port-scanner:

1. Update your package list:
sudo apt update

2. Install Python 3:
sudo apt install python3

3. Install pip for Python 3:
sudo apt install python3-pip

4. Install Git:
sudo apt install git

5. Clone the Advanced-port-scanner repository:
git clone https://github.com/aaronfoxxx/Advanced-Port-Scanner.git

Now you have Python 3, pip, and Git installed, and you've obtained the Advanced-port-scanner project.

## Usage

To use the Advanced-port-scanner to scan ports on a target host or IP address, use the following command:

python3 AP_scanner.py <target> -s <starting_port> -e <ending_port>

- `<target>`: The host or IP address you want to scan.
- `<starting_port>`: The starting port of the scan range.
- `<ending_port>`: The ending port of the scan range.

For example:
python3 AP_scanner.py 192.168.1.1 -s 80 -e 100

This command will efficiently scan ports 80 to 100 on the target host (192.168.1.1).

## Additional Information

- Advanced-port-scanner is optimized for use in Kali Linux environments.
- It can only be run with Python 3.

Please ensure you have the necessary permissions and authorization to scan the target host, as unauthorized scanning may be against the target's policies and may be illegal in some cases.

Feel free to customize and enhance this port scanner to suit your needs. If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request on GitHub.

Happy scanning!


