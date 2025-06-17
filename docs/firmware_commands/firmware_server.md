# `firmware server <set/get>`

---

### Command
`firmware server <set/get>`

### Function

Retrieves the credentials for connecting to the SFTP server where the firmware file is
stored.

### Example
```
[admin@ssh-to-serial]>firmware credentials get
SFTP Server Name: 192.0.2.15
SFTP Server Port: 22
SFTP Username: sftpuser
SFTP Password: [REDACTED]
SFTP Filename: firmware.bin
Trusted Host Keys:
1. ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCt+XyWSafc8FoSvuGmsKDJ7iW9bkq6U54cCmR4iWPB6CTBYz5wTFkC4qGJI4NN+nFjpKZFA1waPnYesP/U/OX2UCtSW1S9cJ5ZvMLKX/PBFgzKPbHUuxdUmKXSnrVI97QY7OXIJIxTAin4TYkVnWyIebRDgq/OkUsFrF1huVJr8/goFvVgzj+85iegS38wwCirW2K1fBNdSOK7xdPOb7oOVtP3L96kx4Mw+k6Q/YbOo+8YOgZ8zNCLnPQJ9RWg/3mZUkEjGy/CyaZNM1lRI37QLCHFtyXpX8JtbepJ+HoR4imDuG3eh8iFaGFO1cD7xpPsH7/hRZW1lm8wtgwA4UIdRnMnThP5xIBVaXnpRpL
2. ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBOUIitFs64Ahe4CwiH2kD4Lnik+pWVTfhZkmQbLNs/wAJpLdJdLqCeXJlwzJjDA1pTngTnHuw7OqXqFykxaNTzo=
3. ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIDKUSKKib3doDVZz1UmBaIVsIti45A6/klU6AnamYPJk
```