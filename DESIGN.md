# Design Document for Chipper Exam Guard & EncripterForChipperExamGuard

## Introduction

This design document provides a technical overview of the implementation of Chipper Exam Guard and its companion tool, EncripterForChipperExamGuard. It aims to give an insight into the underlying architecture, design decisions, and technical details of the projects.

## Chipper Exam Guard

### Architecture

Chipper Exam Guard follows a modular architecture, with distinct components for link encryption, the secure exam browser, and integration with exam platforms. The application is built using Android Studio, utilizing Kotlin for backend logic and XML for the user interface.

### Encryption Methods

Link encryption is implemented using a two-layered approach, incorporating Caesar's method and substitution. This approach enhances the security of exam links, making them accessible only through the secure exam browser.

### Secure Exam Browser

The secure exam browser prevents users from opening other applications during exams, ensuring the integrity of the examination process. It employs Android's security features to restrict access and provides a seamless exam experience.

## EncripterForChipperExamGuard

### Simplifying Encryption

EncripterForChipperExamGuard focuses on simplifying the encryption and decryption process of exam links. It provides an intuitive interface for teachers to secure exam links effortlessly.

## Source Code and Comments

All source code for Chipper Exam Guard and EncripterForChipperExamGuard is available in the respective GitHub repositories. The code is thoroughly commented to enhance readability and understanding. 
1. the repository CipherExamBrowser:
     ```bash
    git clone https://github.com/AndiZulQadri/CipherExamBrowser.git
2. the repository EncripterForChipperExamGuard
   ```bash
   git clone https://github.com/AndiZulQadri/EncripterForChipperExamGuard.git

## Dependencies

Chipper Exam Guard relies on Android SDK libraries and external dependencies for secure browser functionality. EncripterForChipperExamGuard has minimal dependencies, mainly utilizing standard kotlin libraries for encryption.

## Future Enhancements

Potential future enhancements include improving security measures, exploring additional encryption methods, learning about deep linking, addressing the possibility of misuse in Picture-in-Picture (PIP) mode, and adding a timer feature to the exam pages. These advancements aim to enhance the overall security, functionality, and user experience of the application.

## Conclusion

The design choices made in Chipper Exam Guard and EncripterForChipperExamGuard prioritize security, simplicity, and user experience. The modular architecture and thoughtful encryption methods contribute to creating a robust and user-friendly exam security solution.

---

**Note:** This is Final Project for CS50x program in collaboration with Kemendikbudristek, LPDP, and Harvard University. by Andi Zul Qadri, an educator from UPTD SMPN 5 SINJAI.
