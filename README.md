## Router Access Configuration

| Access Type                   | Password                            | Purpose                                                       |
|------------------------------|-------------------------------------|---------------------------------------------------------------|
| Enable (Privileged EXEC Mode)| `class`                             | Protects access to the router's configuration mode            |
| Console Access               | `cisco`                             | Required to log in when accessing via console cable           |
| VTY (Remote Access - Telnet/SSH) | `remote`                       | Required to access the router remotely (e.g., Telnet/SSH)     |
| MOTD Banner                  | `"Unauthorized access is prohibited"` | Warning message displayed on login                        |
