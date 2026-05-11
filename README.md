# 🕷️ Web Scraper – OOP Semester 2 Final Project
📌 Overview

This project is a Web Scraper application developed as part of the Object-Oriented Programming (OOP) Semester 2 Final Year Project.
It extracts data from websites using Jsoup and presents it through a simple JavaFX GUI interface.

The scraper allows users to enter a URL, extract content (like headings, links, or paragraphs), and save results into a local file.

🚀 Features
🌐 Extract data from web pages using URL input
🧠 Scrapes HTML elements (h1, h2, p, links, etc.)
💾 Saves extracted data to a local file
🖥️ User-friendly JavaFX interface
🔄 Real-time scraping results display
⚠️ Basic error handling (invalid URL, file issues, etc.)
🛠️ Tech Stack
Java (OOP Concepts)
JavaFX (GUI)
Jsoup (Web Scraping Library)
File Handling (Java I/O)
📂 Project Structure
src/
 ├── com.example.scarpper
 │    ├── Launcher.java
 │    ├── Scraper.java
 │    ├── Type.java
 │    └── (other UI/scene classes)
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/web-scraper-oop.git
2. Open in IntelliJ IDEA / Eclipse
Import as a Maven/Java project
3. Add JavaFX SDK
Download JavaFX SDK
Add VM options:
--module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml
4. Add Jsoup Library

If using Maven:

<dependency>
    <groupId>org.jsoup</groupId>
    <artifactId>jsoup</artifactId>
    <version>1.17.2</version>
</dependency>
▶️ How to Run
Run Launcher.java
Enter a valid website URL
Click Scrape
View extracted data in the next scene
Save output to file if needed
📸 Screenshots

(Add your JavaFX UI screenshots here)

⚠️ Known Issues
File path errors may occur due to Windows OneDrive restrictions
Some websites may block scraping
Scene switching may require proper event handling setup
📚 Learning Outcomes
Object-Oriented Programming (OOP) implementation
JavaFX GUI development
Web scraping using Jsoup
File handling in Java
Exception handling and debugging
👨‍💻 Author
Student: Your Name
Course: OOP Semester 2
University: Your University Name
📄 License

This project is for academic purposes only.
