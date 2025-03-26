# CO655-Network-Security

## Part 1 Task 2 | Setup a Network for secured Website Access 

### Router Configuration
![image](https://github.com/user-attachments/assets/c8de6b87-818d-44e4-8afa-8c97ca9b8abb)

- Enter global configuration mode: `enable` `configure terminal`
- Set Router Hostname: `hostname richard-Router`
- Configure Encrypted Passwords:
`service password-encryption`
`enable secret YourStrongPassword123!`
`line console 0`
 `password ConsolePassword456!`
 `login`
 `exit`

`line vty 0 4`
` password VTYPassword789!`
 `login`
 `transport input ssh`
 `exit`
 - Configure Virtual Terminal Access:
`username Admin password Test`
`ip domain-name device-name.com`
`crypto key generate rsa`
 `1024`

### Switch Configuration

