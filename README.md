# CPPInternship

## About PermissionChecker
PermissionChecker is a command line tool that recursively checks if a given user has write permissions for a tree of directories

## Usage

1. Build the project with gcc
2. Run `./checker username groupname topleveldir` as root (so that setuid() can run)
