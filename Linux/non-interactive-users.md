## Interactive vs. Non-Interactive Users
- Interactive Users: These are users who interact directly with the system, usually through a shell. When you log into a computer using SSH or a terminal, you're operating as an interactive user.

- Non-Interactive Users: users or system accounts that execute specific automated tasks without direct human interaction. These users often run background services such as web servers (apache), databases (mysql), or other system services.

## How To Add Non-Interactive User
`sudo adduser -s /sbin/nologin <username>`

## Resources
- https://romankurnovskii.com/en/blog/linux-interactive-non-interactive-users
