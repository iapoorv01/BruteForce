

# **BruteForce Tool**

This tool can be used to **brute force websites** with all the possible common usernames and passwords. However, you need to adjust the configurations accordingly for each page you want to brute force.

> **Note:** This tool is intended for **knowledge purposes** and **skill testing** only. **Do not misuse** this tool for unauthorized access or any illegal activity.

## Password Lists Included

This tool comes with several password lists that you can use for brute-forcing:

- **8-more-passwords.txt**:  
  Contains passwords with more than 8 characters. Excludes numeric-only passwords, consecutive characters (3 or more), all-lowercase passwords, and passwords without at least one capital letter and one number.  
  **Total passwords**: 61,682

- **7-more-passwords.txt**:  
  Includes passwords with 7 characters or more. Numeric-only passwords have been excluded.  
  **Total passwords**: 528,136

- **1000000_password_seclists.txt**:  
  A collection of 1,000,000 passwords sourced from the **SecLists** project.

- **2151220-passwords.txt**:  
  A collection of 2,151,220 passwords sourced from **dazzlepod.com**.

- **38650-password-sktorrent.txt**:  
  Contains 38,650 passwords from **sktorrent.eu**.

- **uniqpass_v16_password.txt**:  
  A large password list designed for use with **John the Ripper** (JtR) to convert large numbers of hashes (such as MD5) into cleartext passwords.

## Installation

1. **Clone the Repository**  
   To get started, clone the repository to your local machine:
   ```bash
   git clone https://github.com/iapoorv01/BruteForce.git
   ```

2. **Set Up the Environment**  
   If necessary, create a virtual environment and install the dependencies (if any):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt  # If there is a requirements file
   ```

## Usage

### Configuration
Before using the tool, make sure to configure the settings to match the target website you're testing. You may need to adjust the login URL, request headers, or other configurations.

### Running the Tool
After configuring the tool, you can run it to start the brute-force attack. Example:
```bash
python bruteforce.py
```
Make sure to specify which password list you want to use by adjusting the script or passing it as an argument (depending on how the tool is set up).

## Disclaimer

This tool is for **educational purposes** and for **testing** only. **Do not use this tool to gain unauthorized access** to any website or system. Always have explicit permission from the owner of the website or system you are testing. Unauthorized use of this tool is illegal and unethical.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
