# `user add <admin/regular> <username> <password>`

---

### Command
`user add <admin/regular> <username> <password>`

### Function

Adds a new user account to the GS3 with the specified role. The username and password
can be a maximum of 33 characters each.

### Example
```
[admin@ssh -to -serial]>user add GS3user password1 regular
Adding user GS3user with admin status: 0
User GS3user added successfully.
```