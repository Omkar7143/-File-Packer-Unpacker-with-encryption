# 🔐 File Packer-Unpacker with Encryption

A powerful Java-based tool that allows users to **pack multiple regular files into a single encrypted file** and **unpack them back** with integrity and security preserved. This system mimics file archival functionality similar to `.zip`, but with built-in **encryption/decryption** and a **custom GUI interface**.

---

## 📦 Features

- 🗃️ Pack multiple files into one secure archive
- 🔓 Unpack files from the encrypted archive
- 🔐 Encrypt/Decrypt file content for data protection
- 🖥️ GUI interface for easy user interaction
- 🧾 Custom file format with metadata tracking
- 🏁 Fast execution with `.exe` support for deployment

---

## 🛠️ Tech Stack

| Category         | Technology             |
|------------------|------------------------|
| Programming Lang | Java                   |
| GUI Library      | Java Swing / AWT       |
| Encryption       | Custom logic-based     |
| OS Compatibility | Windows / Cross-platform (.exe) |
| Build Tool       | Manual Compilation     |

---

## 🧬 Project Structure
```bash
📁 -File-Packer-Unpacker-with-encryption/
├── 📁 .vscode/ # VS Code configuration
├── 📄 Marvellous.txt # Example input file
├── 📄 OK.txt # Example input file
├── 📄 PPA.txt # Example input file
├── 📄 demo.txt # Example input file
├── 📄 pk.txt # Example input file
├── 📄 Myexe.exe # Executable binary
├── 📄 Program415.c to Program442.c # Test C programs packed/unpacked
├── 📄 README.md # Project documentation

```

---

## ⚙️ How It Works

### 🧳 Packing Process

1. User selects multiple regular files.
2. Tool combines file data into one packed archive.
3. Metadata (filename, size, etc.) is added.
4. File content is encrypted and stored securely.

### 📤 Unpacking Process

1. Tool reads the packed file.
2. Metadata is parsed to identify original files.
3. File content is decrypted.
4. All files are restored in original format.

---

## 📸 Sample Output Screenshots

### 🎞️ GUI Interface

## 📸 Output Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63d6c7e3-a70e-4a0d-9a14-c1e19437623c" />



---

## 🚀 How to Run

### Using `.exe`:

```bash
# Double click on Myexe.exe (for Windows)

```

## Using Java (CLI):
```bash
# Compile (if source is available)
javac FilePackerUnpacker.java

# Run the application
java FilePackerUnpacker
```

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and enhance encryption, GUI or add support for compressed file packing.

## 🧑‍💻 Author

Omkar Jadhav

Java Full Stack Developer

📧 Email: omkar.s.jadhav321@gmail.com

🌐 GitHub: [Omkar7143](https://github.com/Omkar7143)
