# macOS Forensics: The Basics

This project documents the forensic analysis of a macOS system image performed in the TryHackMe room: **macOS Forensics: The Basics**.

## 📂 Project Structure

- `report/` – Contains the detailed forensic report.
- `screenshots/` – Visual evidence and screenshots of key steps, especially from Task 8.
- `tools/` – Utilities and files used during analysis (e.g., `apfs-fuse`, `apfsutil`, etc.).

## 📌 Objectives

- Learn how to perform forensics on macOS systems
- Analyze `.E01` forensic disk images
- Understand key macOS artifacts and the APFS file system
- Practice using tools like `mac_apt`, `Autopsy`, and CLI utilities

## 🛠️ Tools Used

- `mac_apt`
- `Autopsy`
- `plutil`, `cat`, `less`, `grep`, `sqlite3`
- TryHackMe AttackBox (Linux)

## 📝 Report Summary

The full step-by-step report with answers, explanations, and methods for each task (Tasks 1–8) can be found in:


It includes:
- Basic concepts of macOS forensic artifacts
- Analysis of APFS filesystem and `.E01` image
- Answers and methodologies for all room questions
- Task 8 screenshot guide

## 📸 Screenshots

Screenshots are located in the `screenshots/` folder and demonstrate key outputs during Task 8 (such as using `mac_apt`, finding artifacts, inspecting logs, etc.).

## 🔧 Included Tools

Some tools and helper files used during the analysis are stored in the `tools/` directory for reference.

---

## 📖 Reference

- [TryHackMe macOS Forensics Room](https://tryhackme.com/room/macosforensics)
- [RosanaFS Walkthrough](https://medium.com/@RosanaFS/macos-forensics-the-basics-tryhackme-walkthrough-35b6a567db9b)
