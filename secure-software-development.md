# Secure Software Development

Security is and should be embedded in all of our products and supporting services. This includes the website, our build machines, and software repositories. Users of our software should be able to trust that we took every action to protect our software from any unauthorized changes.

## Software Repository:

Usage of common techniques:
* HTTPS
* GPG signed
* Vulnerability scanning

Basic security principles:
- Limited access
- Preference for HTTPS, HTTP as fallback option
- All repositories are digitally signed
- Highest possible checksums, unless compatibility is required for still supported operating system versions

Known limitations:
- Yum/RPM can't work with newer key types, or subkeys yet
- CentOS 5 does only support weaker hash


## Software Quality

### Defensive programming

All code written should be written from a defensive standpoint. This means it should properly validate input, and check if a condition is true before using it. So when using a file, first determine if the file is really there.

### Linting

Scripts and code should be 'grammar checked' with a linting tool. This reduces errors in code and helps with getting the same code style. By using the same style, we can improve the code quality.

Examples:
- Python: PEP8
- Shell: shellcheck

### Vulnerability checking
