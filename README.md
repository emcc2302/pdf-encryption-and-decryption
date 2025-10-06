I'd be happy to generate a comprehensive `README.md` file for your PDF Encrypter/Decrypter GUI project.

Here is the content, which follows standard documentation best practices:

````markdown
# PDF Encrypter & Decrypter GUI 🔒🔓

## Project Summary
This is a simple, standalone desktop application built with Python and Tkinter that allows users to easily **encrypt** or **decrypt** PDF files using strong **AES-256** security standards. It provides a user-friendly Graphical User Interface (GUI), eliminating the need for command-line interaction.

---

## 🚀 Features

* **GUI Interface:** Easy file selection, password input, and single-click operations.
* **Strong Encryption:** Uses the **AES-256** algorithm for robust security.
* **Dual Password Support:** Supports setting a **User Password** (to open/view) and an **Owner Password** (to control permissions).
* **Decryption:** Removes password protection to restore the original, unencrypted file.
* **File Permissions:** Restricts actions like printing, editing, and content copying during the encryption process.

---

## 🛠️ Installation and Setup

This project requires Python 3.x and the `pypdf` library (along with its `cryptography` dependency).

### 1. Install Dependencies

Open your terminal or PowerShell and run the following command to install the required libraries:

```bash
python -m pip install pypdf cryptography
````

### 2\. Run the Application

Navigate to the directory containing your main script (`pdf_security_app.py`) and execute it:

```bash
python pdf_security_app.py
```
<img width="1918" height="1024" alt="Screenshot 2025-10-06 215110" src="https://github.com/user-attachments/assets/22994a12-379d-4baa-804c-bc3089847104" />
<img width="1915" height="1021" alt="Screenshot 2025-10-06 215208" src="https://github.com/user-attachments/assets/d9d44a7d-2c41-45e7-b36d-d1c9df2ef3bd" />

<img width="1919" height="1019" alt="Screenshot 2025-10-06 215257" src="https://github.com/user-attachments/assets/e15c2e1a-ff4a-4534-8092-8a2eec08d10c" />

-----

## 📝 How to Use the App

### 1\. Encrypting a PDF

1.  Click the **"Browse"** button and select the unencrypted PDF file you wish to protect.
2.  In the **"User/Open Password"** field, enter a password. This is required to open the file later.
3.  In the **"Owner/Admin Password"** field, enter a separate strong password. This is required to remove security or change permissions.
4.  Click the **"🔒 ENCRYPT PDF"** button.
5.  A save dialogue will appear, prompting you to name the new encrypted file (e.g., `original_encrypted.pdf`).

### 2\. Decrypting a PDF

1.  Click the **"Browse"** button and select the encrypted PDF file.
2.  In the **"Owner/Admin Password"** field, enter the correct **Owner/Admin Password** (or the User Password, if it grants sufficient permission).
      * *Note: The Owner Password is generally required to fully remove the encryption structure.*
3.  Click the **"🔓 DECRYPT PDF"** button.
4.  A save dialogue will appear, prompting you to name the new unencrypted file (e.g., `encrypted_decrypted.pdf`).

-----

## 👨‍💻 Developed By

Made By Soriful Islam Sk

```
```
