# Detector Testers - Archived SVN Projects

Welcome to the Detector Testers GitHub organization. This organization hosts archived projects that have been migrated from Subversion (SVN) to Git.

---

## 📋 Important Information About Project Structure

### SVN to Git Migration

All projects in this organization have been converted from SVN repositories to Git. During this migration, the project structure has been transformed to accommodate Git's repository model.

### Understanding Project Naming

> **⚠️ CRITICAL: Nested Project Structure**
>
> In the original SVN repository, projects were organized in a nested folder hierarchy. These nested projects are now represented as **flat, independent Git repositories** with modified naming conventions.

#### Naming Convention

The folder path hierarchy has been converted to repository names using **dashes (`-`)** as separators:

**Original SVN Structure:**
* ROOT/
* ├── PathA/
* │   └── PathB/
* │       └── ProjectName/

**Becomes Git Repository:**
ROOT-PathA-PathB-ProjectName


#### Examples

| Original SVN Path | Git Repository Name |
|-------------------|---------------------|
| `propius/Firmware/MainBoard/400573-1A` | `propius-Firmware-MainBoard-400573-1A` |
| `propius/Firmware/OpticalReader/400574GK` | `propius-Firmware-OpticalReader-400574GK` |
| `propius/Firmware/CustomBootloader` | `propius-Firmware-CustomBootloader` |

### What This Means for You

- **Each repository is independent**: What were once nested subdirectories in SVN are now separate Git repositories
- **No parent-child relationships**: The dash-separated naming preserves the organizational context but repositories are not nested
- **Full history preserved**: Each repository contains the complete SVN history for that specific project path
- **Standard Git layouts**: Projects maintain their original SVN layout (trunk/branches/tags) or flat structure as appropriate

---

## 🔍 Finding Projects

To locate a specific project:

1. **Identify the original SVN path** (e.g., `propius/Firmware/MainBoard/400573GN`)
2. **Replace slashes with dashes** → `propius-Firmware-MainBoard-400573GN`
3. **Search for that repository name** in this organization

---

## 📚 Repository Contents

Each repository contains:

- **Complete SVN history** converted to Git commits
- **Original branch structure** (trunk, branches, tags where applicable)
- **Empty directories** preserved with `.gitkeep` files
- **SVN metadata** in commit messages for traceability

---

## 🏗️ Repository Layouts

Projects follow one of these layouts based on their original SVN structure:

| Layout | Description |
|--------|-------------|
| **Standard** | Contains `trunk/`, `branches/`, and `tags/` directories |
| **Flat** | Single-level project without SVN standard layout |
| **Custom** | Mixed or non-standard SVN layout |

---

## ⚠️ Important Notes

> **Read-only archives**: These repositories are archived and should not receive new commits

- **Historical reference**: Use these repositories to access historical code and understand project evolution
- **Migration artifacts**: Some repositories may contain `.gitkeep` files in empty directories to preserve SVN structure

---

## 🔗 Related Resources

- **Migration date**: December 2025
- **Original SVN repository**: `https://repos.noclimb.com/svn/`
- **Migration tool**: Custom Python-based SVN-to-Git migration framework

---

## 📞 Questions?

For questions about:

- **Project history**: Check the repository's commit history and tags
- **Migration process**: Contact the repository administrators
- **Access issues**: Open an issue in the relevant repository

---

**Last Updated**: December 2025  
**Migration Status**: Complete  
**Total Repositories**: _[Count varies by organization]_

---

## License

These archived projects retain their original licenses. Please refer to individual repositories for specific licensing information.
