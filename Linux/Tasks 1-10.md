# 1.Create user with name Techie and provide sudo access to user.
### Step 1: Create the User
```
sudo adduser Techie
```
### Step 2: Verify the User
```
cat /etc/passwd | grep Techie
```
### Step 3: Provide Sudo Access
```
sudo usermod -aG sudo Techie
```

### Step 4: Verify Sudo Access
```
groups Techie
```
### Step 5: Switch to the User
```
su - Techie
```

### Step 6: Test Sudo Privileges
```
sudo apt update
```
# 2.Navigate to the home directory.
# 3.Create a new directory.
# 4.List the contents of a directory.
# 5.Change the current directory.
# 6.Create a new empty file.
# 7.View the contents of a file.
# 8.Copy a file to another location.
# 9.Move a file to another location.
# 10.Rename a file.
