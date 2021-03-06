# Jira to GitLab migration scripts

## Description

Right now this is just a simple Python script to retrieve all the issues from one or more Atlassian Jira projects using the Jira API and insert those issues together with their attachments and comments into a GitLab instance.

Users are not migrated in the current version. There is also no attempt made to
match Jira users with GitLab users.

This is meant purely as a once-off for archival purposes.

## Dependencies

* [Python 3](https://python.org/)
* [requests](https://pypi.org/project/requests/)

## Installation on Ubuntu / Debian

```bash
# Install the necessary dependencies
sudo apt-get install python3 python3-pip
sudo pip3 install requests

# Edit the configuration section at the top of the file first and then execute
python3 migrate.py
```
