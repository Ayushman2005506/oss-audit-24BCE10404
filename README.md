
Run using:

```bash
./scripts/script5_manifesto_generator.sh
```

---

# Dependencies

The following tools are required:

- Bash
- LibreOffice
- RPM package manager
- grep
- awk
- cut
- du
- tail
- sudo

Install LibreOffice on Fedora using:

```bash
sudo dnf install libreoffice
```

---

# How to Run the Entire Project

1. Clone or download the repository.
2. Open the terminal in the project folder.
3. Make all scripts executable:

```bash
chmod +x scripts/*.sh
```

4. Run the scripts one by one:

```bash
./scripts/script1_system_identity.sh
./scripts/script2_package_inspector.sh
./scripts/script3_disk_auditor.sh
sudo ./scripts/script4_log_analyzer.sh /var/log/messages
./scripts/script5_manifesto_generator.sh
```

---

# Screenshots

The `screenshots/` folder contains screenshots showing the successful execution of all five scripts:

- `script1_run.png`
- `script2_run.png`
- `script3_run.png`
- `script4_run.png`
- `script5_run.png`

---

# Conclusion

This project demonstrates both the philosophy and practical use of open-source software through LibreOffice. It combines Linux system analysis, package inspection, permissions auditing, log analysis, and shell scripting concepts into a complete audit project.
