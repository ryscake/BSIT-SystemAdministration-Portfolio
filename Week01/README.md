# Week 1 – Building My Professional Environment

Name: Krystal Margareth B. Villanueva

Course: BSIT

Section: 4A - WAMD

Date: August 7, 2026

---

## Objectives

* To configure professional online profiles on GitHub and LinkedIn for collaboration, portfolio building, and digital professionalism.
* To set up version control workflows using Git, GitHub Desktop, and structured portfolio repositories for tracking academic outputs.
* To prepare and configure the local system administration workstation with essential software, tools, and virtual machine images.

---

## Software Installed

* Git
* GitHub Desktop
* VS Code
* VirtualBox
* Ubuntu ISO
* Windows ISO

---

## Professional Accounts

* **GitHub:** https://github.com/ryscake
* **LinkedIn:** https://www.linkedin.com/in/villanueva-krystal-margareth-b-34174a426

---

## Installation Screenshots

* Verification screenshots stored inside `Week01/screenshots/`
* Account screenshots stored inside `Week01/accounts/`

---

## Challenges Encountered

1. **Slow Download Speed for OS ISO Files**
   * **Issue:** The Windows 11 Enterprise ISO file was over 5 GB, resulting in long download times and intermittent network timeouts.
   * **Solution:** I utilized a download manager to ensure the download could resume automatically if disconnected, and scheduled the download during off-peak network hours to secure higher bandwidth.

2. **Creating Nested Folders for Empty Directories in Git**
   * **Issue:** When trying to push the empty folder hierarchy (Week01 to Week15) to GitHub, Git automatically ignored the empty directories because standard Git tracking only commits files, not empty folders.
   * **Solution:** I generated hidden `.gitkeep` files inside every week folder using a loop command in the terminal (`touch Week$i/.gitkeep`) so Git would register and maintain the directory tree structure on the remote repository.

---

## Reflection

For any IT practitioner, especially in System Administration and Maintenance, setting up a dedicated, professional environment is a crucial first step. During this exercise, I came to understand that setting up a developer workstation entails much more than just downloading programs; it also calls for careful planning, appropriate configuration, and creating an identity that adheres to professional standards.

The technical foundation needed for the remainder of the semester was established by installing programs like Git, Visual Studio Code, and Oracle VM VirtualBox. Operating system ISOs like Ubuntu and Windows 11 Enterprise, when combined with virtualisation tools like VirtualBox, will act as a sandbox for the safe execution and testing of system administrative procedures like user management, network configuration, and security policies.

Concurrently, I was reminded of the significance of digital branding in the technology industry while honing my professional online presence on GitHub and LinkedIn. I learned discipline in version control and project management by keeping my repository structure neat from Week 1 to Week 15. Overcoming setup obstacles, like managing big binary files and environment settings, strengthened my troubleshooting mentality. All things considered, this exercise established the professional discipline and virtual infrastructure I need to be successful in ITEP 414.

---

## References

Git Documentation. (2026). Getting Started - Installing Git. Retrieved from https://git-scm.com/doc

Canonical. (2026). Ubuntu Desktop Official Downloads. Retrieved from https://ubuntu.com/download/desktop

Microsoft. (2026). Windows 11 Enterprise Evaluation Download. Microsoft Evaluation Center. Retrieved from https://www.microsoft.com/en-us/evalcenter/

Oracle. (2026). Oracle VM VirtualBox User Manual. Retrieved from https://www.virtualbox.org/wiki/Documentation
