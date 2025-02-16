# Report on SVN and Mercurial 📜

## 1. Introduction 🚀
Version control systems (VCS) are essential tools for managing code and tracking changes in software development. **SVN (Apache Subversion) 🏛️** and **Mercurial 🪐** are two popular version control systems used by developers worldwide. This report provides an in-depth comparison of SVN and Mercurial, along with their basic commands.

## 2. Apache Subversion (SVN) 🏛️
### 2.1 Overview
Apache Subversion (SVN) is a centralized version control system (CVCS) that enables multiple users to collaborate on a project by maintaining a single central repository. It was originally developed by CollabNet and is now an Apache Software Foundation project.

### 2.2 Key Features ✨
- Centralized repository model 🗂️
- Atomic commits 🔄
- Branching and merging capabilities 🌿
- Directory versioning 📂
- Access control and authentication 🔑
- Efficient handling of binary files 🏎️

### 2.3 Basic SVN Commands 📜

| Command | Description |
|---------|-------------|
| `svn checkout <repository_url>` | Clone a repository to a local machine 🖥️ |
| `svn update` | Update working copy with the latest changes from the repository 🔄 |
| `svn add <file>` | Add a new file to version control ➕ |
| `svn commit -m "message"` | Commit changes to the repository with a message ✅ |
| `svn status` | Show the status of working copy files 📌 |
| `svn log` | View commit history 📜 |
| `svn diff` | Show differences between local and repository versions 🔍 |
| `svn revert <file>` | Revert local changes ⏪ |
| `svn merge <source_branch>` | Merge changes from another branch 🔀 |
| `svn delete <file>` | Remove a file from version control 🗑️ |

## 2.4 Implementation of Some Basic SVN Commands

![SVN Version](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/a183b1e38b13c0069448d4683b3fdb0129b7d410/images/svn%20version.png)

---

![SVN Repo](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/svn%20repo.png)

---

![Checkout](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/Checkout.png)

---

![SVN Commit](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/svn%20commit.png)

---

![SVN Update and Log](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/svn%20update%20and%20log.png)

---

![Revert](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/revert.png)

---

![Branching & Merging](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/4c9b83a76a5c9f6abb9bd6ad3136500803792a38/images/Branching%20%26%20merging.png)

---

## 3. Mercurial 🪐
### 3.1 Overview
Mercurial is a **distributed version control system (DVCS) 🌎** known for its simplicity and performance. It is designed to handle projects of all sizes and emphasizes speed and scalability.

### 3.2 Key Features ✨
- Fully distributed architecture 🔄
- High-performance and scalability ⚡
- Simple and intuitive command-line interface 🖥️
- Efficient handling of large codebases 📦
- Strong support for branching and merging 🌿

### 3.3 Basic Mercurial Commands 📜

| Command | Description |
|---------|-------------|
| `hg clone <repository_url>` | Clone a repository to a local machine 🖥️ |
| `hg pull` | Retrieve changes from a remote repository ⬇️ |
| `hg update` | Apply retrieved changes to the working directory 🔄 |
| `hg add <file>` | Add a new file to version control ➕ |
| `hg commit -m "message"` | Commit changes with a message ✅ |
| `hg status` | Show the status of working copy files 📌 |
| `hg log` | View commit history 📜 |
| `hg diff` | Show differences between revisions 🔍 |
| `hg revert <file>` | Undo local changes ⏪ |
| `hg merge` | Merge changes from different branches 🔀 |
| `hg remove <file>` | Remove a file from version control 🗑️ |

# 3.4 Implementation of Some Basic Mercurial Commands

![HG Version](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20version.png)

---

![HG Repo](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20repo.png)

---

![HG Echo](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20echo.png)

---

![HG Commit](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20commit.png)

---

![HG Clone](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20clone.png)

---

![HG Pull Update Log](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20pull%20update%20log.png)

---

![HG Revert](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20revert.png)

---

![HG Branch](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20branch.png)

---

![HG Merge](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20merge.png)

---

![HG Commit Merge](https://raw.githubusercontent.com/harsh0371/DevOps-Assignment/aa228fb77a3d52e770a07636178a3420515c19c1/images/hg%20commit%20merge.png)

---

## 4. Comparison of SVN and Mercurial ⚖️

| Feature | SVN 🏛️ | Mercurial 🪐 |
|---------|-----|----------|
| Type | Centralized 🎯 | Distributed 🌎 |
| Performance | Moderate ⏳ | High ⚡ |
| Scalability | Good for small to medium projects 📊 | Suitable for large projects 🚀 |
| Branching & Merging | Available but complex 🌿⚠️ | Simple and effective 🌿✅ |
| Offline Work | Limited functionality 🌐 | Full support ✅ |
| Ease of Use | Requires more commands 📖 | Simple and intuitive 🎯 |
| Security & Access Control | Centralized access control 🔐 | Local and remote repository access 🔓 |

## 5. Conclusion 🎯
SVN and Mercurial serve different needs in version control. **SVN** is well-suited for teams that require a centralized repository with strict access controls, while **Mercurial** is a great choice for projects requiring a fast and scalable distributed system. The choice between them depends on project requirements, team workflow, and familiarity with version control systems.

Both tools provide essential version control features, and understanding their commands and workflows can help teams collaborate efficiently and maintain robust software development processes. 🏆
