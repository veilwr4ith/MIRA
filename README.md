![GIF](https://github.com/veilwr4ith/MIRA/blob/main/wolf.gif)

# Mira Password Manager

Mira is our innovative password management solution designed specifically for the command-line interface (CLI). With a streamlined and efficient approach, Mira provides a robust solution to the vulnerabilities associated with password management in the digital era.


## [+] Objectives

- **Offline Security**: Mira prioritizes offline functionality to ensure password management without dependence on internet connectivity. This approach enhances security by minimizing the attack surface and reducing exposure to online threats.

- **Local Storage**: The password manager facilitates secure storage and retrieval of passwords locally on the user's machine, ensuring data confidentiality and reducing reliance on external servers or cloud services.

- **No Cloud Dependencies**: Mira does not rely on external servers or cloud services for enhanced privacy and control. This approach eliminates the risk of unauthorized access or data breaches associated with online storage.

- **Data Confidentiality**: To ensure the privacy of user data, Mira implements encryption and secure storage procedures, employing Argon2 for hashing the user data. This ensures that even if the device is compromised, the stored passwords remain unreadable without the decryption key.

- **Isolated Environment**: Mira operates within the user's system, minimizing exposure to external threats or vulnerabilities. This isolated environment enhances security by reducing the likelihood of unauthorized access or data breaches.

- **Usability**: Mira provides a user-friendly command-line interface for easy interaction, allowing users to efficiently manage their passwords without the need for complex technical knowledge.

- **Security Best Practices**: The password manager encourages secure practices such as safeguarding master keys, enabling Two-Factor Authentication (2FA), and emphasizing password complexity to enhance overall security.

- **Control**: Mira empowers users with complete control over their password manager, as it operates locally within the system and functions entirely offline. This provides users with a sense of independence and control over their sensitive information.


## [+] Why MIRA is Considered Secure?

- **Limited Attack Surface**: Operating offline reduces the potential attack surface, minimizing vulnerabilities and enhancing overall security.

- **No Cloud Dependency**: Mira does not store user data in the cloud, reducing the risk of unauthorized access or data breaches associated with online storage. Users have direct control over their data, enhancing privacy and security.

- **Lower Exposure to Online Threats**: Due to its offline nature, Mira is less susceptible to phishing attacks or server breaches common with online password managers. Offline managers are not reliant on online authentication, reducing exposure to online threats.

- **Local Encryption**: Mira employs strong encryption algorithms to protect user data. Data is stored locally, and encryption ensures that even if the device is compromised, the stored passwords remain encrypted and unreadable without the decryption key.

- **Zero-Knowledge Architecture**: Mira ensures the privacy of user data by handling passwords without actually knowing what they are. It encrypts and decrypts data locally, ensuring sensitive information stays private, even from the password manager itself.

- **User Independence**: Users have full control over their password manager since it operates within their system. There's no reliance on external services, providing a sense of independence and reducing potential points of failure.

- **No Password Retrieval Over Network**: Password retrieval and storage occur locally, eliminating the need to transmit sensitive information over the network. This reduces the chances of interception or man-in-the-middle attacks.

- **Offline Password Generation**: Mira can generate passwords without requiring an internet connection, offering convenience and security, especially in situations where online access is limited.

- **No Third-Party Involvement**: Mira operates autonomously without any reliance on external service providers, ensuring enhanced security by eliminating potential risks associated with third-party entities. Users can fully trust the locally implemented security measures without involving external platforms.

- **Increased Privacy Control**: Users benefit from enhanced privacy control as their sensitive data remains within their own environment. There is no need to trust external servers with personal information, contributing to a more private and secure user experience.

- **No Connection Latency**: Users experience minimal latency since their password data is instantly accessible locally. This absence of network communication reduces the risk of delays or disruptions that might be exploited by attackers attempting to compromise the system.

   *Note: While offline password managers provide significant security benefits, users should remain vigilant about security best practices. It's crucial to store the master key and encryption key in a secure location on their device. Unfortunately, human error often poses the primary challenge in adhering to these practices.*


## [+] MIRA's Credential Storage Capabilities

MIRA supports various types of credentials, including:

- **Account Passwords**: MIRA enables users to securely store and manage passwords for a variety of accounts, such as those used for websites, applications, and services. It employs encryption techniques to safeguard these passwords, preventing unauthorized access and ensuring user privacy and security online.

- **Credit/Debit/Prepaid Card PINs**: MIRA provides a secure repository for storing sensitive financial information, including PINs for credit and debit cards. By encrypting this data and implementing robust security measures, MIRA ensures that users can safely store and access their card PINs, protecting them from unauthorized use and fraudulent activities.

- **API Keys**: MIRA offers a secure environment for storing API keys, which are authentication credentials used to access web services or APIs. By securely managing these keys, MIRA helps prevent unauthorized access to sensitive data and resources, enhancing the overall security of applications and systems that rely on API authentication.

- **SSH(RSA) Keys**: MIRA supports the storage and management of SSH keys, which are cryptographic keys used for secure remote access to servers and systems via the Secure Shell (SSH) protocol. By safeguarding SSH keys within its encrypted storage, MIRA helps users securely authenticate and access remote systems, minimizing the risk of unauthorized access and potential security breaches.

- **Source Codes**: MIRA allows users to store and protect their project source codes securely. By providing encrypted storage for source code files, MIRA helps developers safeguard their intellectual property and sensitive project information, ensuring that their code remains confidential and protected from unauthorized access or tampering.

- **Private Notes**: MIRA enables users to securely store private information, such as personal notes, sensitive documents, or confidential data. By encrypting these notes and providing secure storage, MIRA helps users safeguard their privacy and sensitive information, ensuring that it remains inaccessible to unauthorized individuals or malicious actors.

- **Operating Systems Passwords**: MIRA enables users to securely store and manage passwords for a variety of Operating Systems, including Windows, macOS, Linux. This feature allows users to organize their OS-specific credentials in one central location, ensuring quick access and enhanced security.


## [+] Features

- **Versatile Credential Storage**: MIRA provides advanced storage capabilities for various types of credentials including Platform Accounts, Credit/Debit Card PINs, API Keys, SSH(RSA) Keys, Source Codes, and Private Notes. This wide range ensures MIRA can securely manage diverse credentials for users.

- **Multi-Factor Authentication**: Secure your MIRA account with multi-factor authentication. Users need to enter the master password, encryption key generated during registration, and a time-based 6-digit code from 2FA if enabled, before accessing the main menu.

- **Password Manager Lockout**: MIRA automatically locks after four failed login attempts, preventing brute force attacks for 5 minutes.

- **Password Generator**: Quickly generate strong passwords with enough length and character requirements.

- **Clipboard Copy**: Automatically copies retrieved credentials or generated passwords to the clipboard for 30 seconds convenience.

- **Secure Storage**: Encrypts credentials using the Fernet symmetric encryption algorithm, ensuring data confidentiality and integrity.

- **Carrier Lookup**: Detects the carrier when a phone number is used for platform credentials, aiding in phone number validation.

- **Mnemonic Phrase**: Convert encryption keys into memorable mnemonic phrases for easier recall.

- **Password Strength Checker**: Ensures passwords meet recommended strength criteria based on established policies.

- **Password/PINs Expiry Notifications**: Receive warnings when passwords are about to expire for proactive security measures.

- **Password/PINs Expiry Lister**: View remaining time until password/pin expiry for effective password management.

- **Accessible Instructions**: Prioritize intuitive guidance for MIRA, ensuring user-friendliness even in a Terminal-Based Password Manager.

- **Loggings Tracker**: Tracks login attempts including time, status, and entered username.

- **Configuration Loggings Tracker**: Tracks previous configurations such as adding, changing, or deleting credentials.

- **Password Breach Monitoring**: Scan passwords against previous data breaches to ensure security. (REQUIRES INTERNET CONNECTION)

- **Reset Functionality**: This feature allowing users to reset MIRA instance, deleting all stored credentials including the primary MIRA account for comprehensive data management. 

   *Note: Resetting MIRA will permanently delete all stored credentials. Please ensure you have backed up essential data before proceeding, as this action cannot be undone.*


## [+] Supported Card Brands by MIRA

MIRA supports the following Card Brands for secure PIN identification:

- Visa
- Mastercard
- American Express
- Discover
- JCB
- Diners Club
- Maestro
- Verve


## [+] Supported Password Types of Operating Systems by MIRA

MIRA supports the following Password Types for secure OS Password Storage:

- Phrase
- PIN
- Pattern

*Note: In Pattern you need to describe what the pattern looks like.*


## [+] OS Compatibility

- [x] Tested on Windows
- [ ] Tested on macOS
- [x] Tested on Linux


## [+] Installation for Unix-Based Systems 

- Download the executable: [here](https://www.mediafire.com/file/uwrhsp0byn2jywz/MIRA/file)

- Install xclip

  ```bash
  sudo apt install xclip
  ```

- Add an executable permission for MIRA

  ```bash
  chmod +x MIRA
  ```

- Launch MIRA (with elevated privileges, with sudo or root user)

  ```bash
  sudo ./MIRA
  ```


## [+] For Executable Version of MIRA (Windows)

- Click this link and Download: [here](https://www.mediafire.com/file/x1wigt7vj1w2ab5/MIRAInstaller.exe/file)

   *Note: For executable file, run it as Administrator. (In Executable the Paste is not Ctrl+V, just click the Right Mouse Button Once to paste.)*


## [+] Usage

To use Mira effectively:

- Typing `h` or `help` in the Mira prompt provides guidance.
- Before logging in, create a master user to secure the password vault.


## [+] Commands

Once logged in, users can utilize various commands, including:

| **Command**             | **Description**                                                                |
|-------------------------|--------------------------------------------------------------------------------|
| **1. Adding Credentials** |                                                                              |
| `add_platform_passwd`   | Add a new password                                                            |
| `add_api_key`           | Add a new API key                                                              |
| `add_card_pin`          | Add a new PIN                                                                  |
| `add_ssh_key`           | Add a new SSH Key                                                              |
| `add_src_code`          | Add a new Source Code                                                          |
| `add_priv_note`         | Add a new Private Note                                                         |
| `add_os_passwd`         | Add a new Operating System password                                            |
| **2. Retrieving Credentials** |                                                                          |
| `get_platform_passwd`   | Retrieve the plaintext version of the password for the desired account ID     |
| `get_api_key`           | Retrieve the plaintext version of the key of the desired account ID           |
| `get_card_pin`          | Retrieve the plaintext version of the PIN for the desired card ID             |
| `get_ssh_key`           | Retrieve the plaintext version of the SSH Key for the desired key ID          |
| `get_src_code`          | Retrieve the plaintext version of the Source Code for the desired code ID     |
| `get_priv_note`         | Retrieve the plaintext version of the Private Note for the desired note ID    |
| `get_os_passwd`         | Retrieve the plaintext version of the Operating System Password for the desired OS ID    |
| **3. Deleting Credentials** |                                                                           |
| `del_platform_passwd`   | Delete a saved password according to your desired account ID                  |
| `del_api_key`           | Delete key according to your desired account ID                                |
| `del_card_pin`          | Delete a saved PIN according to your desired card ID                           |
| `del_ssh_key`           | Delete a saved SSH Key according to your desired key ID                        |
| `del_src_code`          | Delete a saved Source Code according to your desired code ID                  |
| `del_priv_note`         | Delete a saved Private Note according to your desired note ID                 |
| `del_os_passwd`         | Delete a saved Operating System Password according to your desired OS ID      |
| **4. Changing Credentials** |                                                                          |
| `ch_platform_pass`      | Change the password for the desired account ID                                 |
| `ch_card_pin`           | Change the password for the desired pin ID                                     |
| `ch_api_key`            | Change the API Key for the desired account ID                                  |
| `ch_ssh_key`            | Change the SSH Key for the desired key ID                                      |
| `ch_src_code`           | Change the Source Code for the desired code ID                                 |
| `ch_priv_note`         | Update the Private Note based on note ID                                       |
| `ch_os_passwd`          | Chane the Operatin System Password for the desried OS ID                        |
| **5. Security and Configuration** |                                                                        |
| `enable2fa`             | Enable Two-Factor Authentication for added security                            |
| `genpasswd`             | Generate a strong password                                                     |
| `changemaster`          | Change the masterkey                                                            |
| **6. Listing and Analysis** |                                                                              |
| `show_passwd_exp`       | List the username and their status on a specific platform or all              |
| `show_pin_exp`          | List the card number and their status on a specific card type or all          |
| `show_api_key`          | List the available API Key with their Key ID, Platform, Key Name, and Date or all    |
| `show_ssh_key`          | List the available SSH Key with their Key ID, Username, Key Name, and Date or all     |
| `show_src_code`         | List the available Source Code with their Code ID, File Name, and Date or all          |
| `show_priv_note`        | List the available Private Note with their note ID, Title, and Date or all            |
| `show_os_passwd`        | List the available Operating System with their OS ID, Password Type, and Date or all  |
| `show_passwd_strength`  | List the strength of the password of a username on a specific platform or all         |
| `show_loggings`         | List all the previous login attempts                                            |
| `show_config_loggings`    | List all the previous configurations that has been made                       |
| **7. Securing Encryption Key** |                                                   |
| `check_my_passwd_if_pwned` | Check if your password has been compromised in existing data breaches (Internet Connection Required!)  |
| `mnemonic_enc_key`      | Convert the encryption key to a mnemonic phrase                                 |
| `dec_mnemonic`          | Decode a mnemonic phrase to the original encryption key                         |
| **8. User Actions**     |                                                                               |
| `lout`                  | Logout                                                                          |
| `exit`                  | Terminate MIRA                                                                  |
| `reset`                 | Delete all data, including the user account permanently (Be cautious!)         |


## [+] Security Recommendations

- Regularly monitor password expiration using the Listing and Analysis commands provided.
- Ensure your master password and encryption key are kept secure at all times.
- Enable Two-Factor Authentication for an extra layer of protection.
- Avoid copying your credentials directly from MIRA. Instead, utilize the clipboard feature provided. MIRA automatically copies retrieved/generated credentials to the clipboard, giving you 30 seconds to paste them securely. This helps prevent privacy concerns, especially when dealing with sensitive information like passwords. It's a good practice to utilize this feature for enhanced security.
- MIRA operates on a Zero-Knowledge basis, meaning the security of your account depends solely on the strength and secrecy of your master password, without involvement from the service provider. Therefore, it's crucial not to compromise your account's security through careless actions. Stay vigilant!


## [+] Note

- Master Password strength policy requires at least 15 characters with uppercase, numbers, and special characters. (Mandatory).
- Password strength policy for platforms requires at least 10 characters with uppercase, numbers, and special characters also. (Optional, but we recommend you to follow our password policy.)
- Japanese Language in Mnemonic Phrase can be faulty sometimes. Use it at your own risk.
  

## [+] License

Mira is licensed under **End-User License Agreement (EULA)**


## [+] Acknowledgements

- Zephyr
- DappleFire (GIF)
