# Linux Basics and File Permissions - Summary

## Common Operating Systems
- **Windows**: Closed source (1985).
- **macOS**: Partially open source (1984).
- **Linux**: Fully open source (1991).
- **ChromeOS**: Partially open source (2011), derived from **Chromium OS**.
- **Android**: Fully open source (2008).
- **iOS**: Partially open source (2007).

## How OS Works
- **BIOS/UEFI** activates and loads the **bootloader**, which loads the OS.
- **BIOS**: Basic Input/Output System.
- **UEFI**: Unified Extensible Firmware Interface (more secure, 2007).

## Virtualization
- **KVM**: Open-source hypervisor in the Linux kernel.
- Virtualization extends to **servers** and **networks**.

## OS History
- **UNIX** inspired both the **GNU project** (Stallman) and **Linux kernel** (Torvalds).

## Linux Architecture
1. **User**: People interacting with the system.
2. **Applications**: Installed using package managers (e.g., APT, YUM).
3. **Shell**: CLI interface (bash, zsh, etc.).
4. **Kernel**: Manages processes and memory.
5. **Hardware**: Physical components.

## Popular Linux Distros
- **Debian-based**:
  - **Kali Linux**: Penetration testing.
  - **Ubuntu**: User-friendly, community-supported.
  - **Parrot**: Similar to Kali with GUI enhancements.
- **Red Hat-based**:
  - **RHEL**: Enterprise use with subscription support.
  - **CentOS**: Similar to RHEL, no official support.

## Pen Testing Tools on Kali Linux
- **Metasploit**: Exploit framework.
- **Burp Suite**: Web vulnerability scanner.
- **John the Ripper**: Password cracker.

## Key Shell Variants
- **bash**: Default in most systems.
- **zsh**: Enhanced shell.
- **csh** / **tcsh**: C-based shell.

## File Permissions and Management
- **ls -la**: List all files with permissions.
- **chmod**: Change permissions.
  - Example: `chmod o-w file.txt` (Remove write access for others).
- **chown**: Change file ownership.
- **Permissions string**:  
  Example: `-rw-r--r--`
  - File type (`-`), user (`rw-`), group (`r--`), others (`r--`).

## Virtualization Tools
- **grep**: Search within files.
- **find**: Locate files based on conditions.
- **nano**: Simple text editor.

## Conclusion
This summary covers essential Linux commands, file permissions, user management, OS concepts, and security tools. Mastering these will help with both **labs and professional roles**, providing a solid foundation for further work in cybersecurity and system administration.
