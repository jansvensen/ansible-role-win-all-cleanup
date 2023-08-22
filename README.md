# ansible-role-win-all-cleanup

This role

- cleans up files and directories created by my ansible roles during installation and configuration
- Rename System Drive
- Sets the local administrator password to never expire
- Disables the 'IE Enhanced Security Configuration' for all users

## Requirements

- None

## Role Variables

- directory_install: Directory used for install files during installation and configuration
- directory_logging: Directory used for logging during installation and configuration
- directory_gpo: Directory used for gpo content during installation and configuration

## Dependencies

- none

## License

- MIT

## Author Information

- Sven Jansen, github(at)jansvensen.de
