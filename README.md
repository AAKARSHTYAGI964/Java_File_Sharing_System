# Java_File_Sharing_System
Created a Java-based local network file sharing application that enables automatic server discovery, concurrent file transfers through multi-threading, and a Swing-powered GUI.
 
# Features

* Supports concurrent file transfers through server-side multithreading.
* Provides a Java Swing-based graphical interface for selecting and sending files.
* Uses Java Socket Programming for reliable client-server communication over a local network.
* Displays live file transfer progress during transmission.
* Lightweight application that runs on any system with a Java Runtime Environment (JRE).

---

# Technologies Used

* Java
* Java Swing
* Multithreading
* Socket Programming
* File Handling

---

# How to Run

### 1. Compile the server and client programs

```bash
javac FileServer.java
javac FileClient.java
```

### 2. Launch the server

```bash
java FileServer
```

![0](https://github.com/user-attachments/assets/ab2505df-ef7e-4605-9392-fbb62210d96b)

---

### 3. Launch the client

```bash
java FileClient
```

![Screenshot (6)](https://github.com/user-attachments/assets/07bc6093-ef88-47c8-81f0-fabc1abe02f0)

---

### 4. Discover the server on the local network

![Screenshot (7)](https://github.com/user-attachments/assets/0bb2c283-c85d-437b-bef7-2fe1dabdea48)

---

### 5. Select and transfer files

Choose the desired file using the client GUI and send it to the server over the local network.

![Screenshot (8)](https://github.com/user-attachments/assets/b4b99d3d-e9d4-4815-b6fa-a2fbf0e90ae1)

---

### 6. Successful file transfer

**Client**

![Screenshot (4)](https://github.com/user-attachments/assets/1cefdd35-13d1-477b-9e17-5c7f3a619117)

**Server**

![1](https://github.com/user-attachments/assets/bdf712ee-3292-4a47-b7fc-0d220922b1ec)

---

### 7. File Transfer Demonstration

https://github.com/user-attachments/assets/2b1f5368-61d8-466a-b459-219053e7dc27
