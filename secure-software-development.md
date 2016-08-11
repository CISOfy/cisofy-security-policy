# Secure Software Development

Security is embedded in our products.

Usage of common technologies:
* HTTPS
* GPG signed
* Vulnerability scanning

Repository:
- Limited access
- Preference for HTTPS, HTTP as fallback option
- All repositories are signed
- Highest possible checksums, unless compatibility is required for still supported operating system versions

sha256 on repositories that only support newer operating systems


## Software Quality

### Defensive programming

All code written should be written from a defensive standpoint. This means it should properly validate input, and check if a condition is true before using it. So when using a file, first determine if the file is really there.

### Linting

Scripts and code should be 'grammar checked' with a linting tool. This reduces errors in code and helps with getting the same code style. By using the same style, we can improve the code quality.

Examples:
- Python: PEP8
- Shell: shellcheck

### Vulnerability checking
