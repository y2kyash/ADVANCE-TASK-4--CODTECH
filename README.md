# ADVANCE-TASK-4--CODTECH

### **Overview of the Project: Advanced Encryption Tool**

---

#### **1. Objective**
The primary goal of this project is to provide a secure, user-friendly tool for encrypting and decrypting files. It enables users to safeguard sensitive data from unauthorized access by leveraging robust cryptographic techniques.

---

#### **2. Key Features**
- **Strong Encryption**: Utilizes AES (Advanced Encryption Standard) in CFB (Cipher Feedback) mode for secure data encryption and decryption.
- **Password-Based Key Derivation**: Employs PBKDF2 (Password-Based Key Derivation Function 2) with a salt and multiple iterations to derive cryptographic keys from user-provided passwords.
- **Randomized Initialization**: Generates a unique salt and initialization vector (IV) for each encryption operation to enhance security.
- **Graphical User Interface (GUI)**: Provides a simple and interactive interface for file selection and password entry.
- **Cross-Platform Compatibility**: Designed using Python, making it usable on different operating systems (Windows, macOS, Linux).

---

#### **3. How It Works**
1. **Encryption Process**:
   - The user selects a plaintext file and provides a password via the GUI.
   - A cryptographic key is derived from the password using PBKDF2.
   - A random salt and IV are generated and stored with the encrypted file.
   - The file is encrypted using AES in CFB mode and saved to the specified location.

2. **Decryption Process**:
   - The user selects an encrypted file and provides the correct password.
   - The stored salt and IV are read from the file.
   - A cryptographic key is derived using the same password and salt.
   - The file is decrypted using AES in CFB mode and saved as the plaintext file.

---

#### **4. Components Used**
- **Programming Language**: Python
- **Cryptographic Libraries**:
  - `cryptography.hazmat.primitives` (for AES, PBKDF2, SHA-256, and CFB mode)
- **GUI Library**:
  - `tkinter` (for file dialogs, password input, and user notifications)
- **File Handling**:
  - Standard Python libraries (`os` and `struct` for file operations)

---

#### **5. Applications of the Project**
- **Secure File Storage**: Protects sensitive documents, such as financial records or confidential business data.
- **Data Transmission**: Ensures the secure transfer of files over potentially insecure channels (e.g., email or cloud storage).
- **Personal Privacy**: Helps individuals secure personal information, such as diaries, photos, or identity documents.
- **Corporate Security**: Can be integrated into business workflows to encrypt files shared among employees or stored in archives.


### ** 6. Glimpes **
![image](https://github.com/user-attachments/assets/a60074f1-7428-4b04-90be-ac9fa43cb269)

![image](https://github.com/user-attachments/assets/972e90b7-54d9-478c-b224-59b68e509844)

![image](https://github.com/user-attachments/assets/68df702a-2e2a-4216-8ddf-486d376faadd)

![image](https://github.com/user-attachments/assets/18132890-b563-4b20-8964-2cc4da0c2baf)



