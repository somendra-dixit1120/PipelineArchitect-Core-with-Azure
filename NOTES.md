# 📝 Project Notes & Development Log

This document tracks development progress, technical notes, pipeline configurations, and future ideas for the **Automated trigger pipeline azure** project.

## 📌 Milestone Log
* **[Current Phase]:** Integrated ASP.NET Core Razor Pages template with automated Azure DevOps CI/CD triggers.
* **Version Control:** Migrated solution structures, configured `.gitignore` to exclude temporary `.vs/`, `bin/`, and `obj/` build artifacts.
* **Pipeline Integration:** Successfully configured triggers to detect master/main branch pushes and automatically build code.

## 💡 Technical & Debugging Notes
* **Solution View vs. Folder View:** Always ensure the `.slnx` or `.sln` solution file is opened directly in Visual Studio to prevent "Select a folder for run" errors and enable correct web hosting (`F5` execution).
* **Git Conflict Resolution:** Always perform a rebase pull (`git pull origin master --rebase`) if remote repositories contain initialized updates before pushing local changes.
* **Ignored Files:** Temporary files are intentionally omitted from tracking to keep the repository clean and avoid "Permission Denied" file locks.

## 🚀 Future Roadmap & Enhancements
* [ ] Add unit testing projects to the Azure DevOps build pipeline.
* [ ] Implement Docker containerization support (`Dockerfile`).
* [ ] Configure automated deployment stages to a live cloud environment (Azure App Service).

---
*Note: This log is actively updated as new features and automated workflows are integrated.*
