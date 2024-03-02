# Design Document for Chipper Exam Guard & EncripterForChipperExamGuard

## Overview

Chipper Exam Guard is designed to revolutionize online exam security by introducing innovative features. The project encompasses two applications: one for teachers to encrypt exam links and another for students to decrypt and securely take exams. Inspired by the problem set in Week 2, the application employs layered encryption using Caesar and substitution methods.

## Key Features

1. Dual-Layered Encryption: The use of Caesar and substitution methods provides robust security, ensuring the integrity of exam links.

2. Secure Exam Browser: The student application features a secure exam browser that prevents access to other applications during exams, maintaining a controlled exam environment.

3. Enhanced User Interface: An intuitive and aesthetic user interface enhances the user experience, making navigation and interaction seamless.

4. Automatic App Embedding: When users navigate to the exam page, the application embeds automatically, streamlining the process and minimizing manual efforts.

5. Clear Exam Instructions: To enhance clarity, the application includes explicit exam instructions for participants, reducing potential confusion.

6. Security Measures: The application prevents split-screen usage and screenshot capture, ensuring a secure exam-taking environment.

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


## Source Code 

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

Chipper Exam Guard strives to set a new standard in online exam security with its cutting-edge features and commitment to ongoing improvement. Your feedback is invaluable in shaping the future of this project.

---

**Note:** This is Final Project for CS50x program in collaboration with Kemendikbudristek, LPDP, and Harvard University. by Andi Zul Qadri, an educator from UPTD SMPN 5 SINJAI.
