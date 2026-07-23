# 1.Create user with name Techie and provide sudo access to user.
### Step 1: Create the User
```
sudo adduser Techie
```
<img width="566" height="275" alt="image" src="https://github.com/user-attachments/assets/015c6b53-1cc6-4a38-8904-f00a51ce0bce" />

### Step 2: Verify the User
```
id Techie
```
<img width="547" height="77" alt="image" src="https://github.com/user-attachments/assets/2036a893-6ea8-4493-99a5-d31737e95da0" />

### Step 3: Provide Sudo Access
```
sudo usermod -aG sudo Techie
```
<img width="622" height="67" alt="image" src="https://github.com/user-attachments/assets/aef58b35-f951-43bf-b91e-a4a75f669b74" />

### Step 4: Verify Sudo Access
```
groups Techie
```
<img width="492" height="72" alt="image" src="https://github.com/user-attachments/assets/f25bd4c4-7115-4988-b464-375c0db8a47f" />

### Step 5: Switch to the User
```
su - Techie
```
<img width="542" height="126" alt="image" src="https://github.com/user-attachments/assets/4e561f68-5712-4bc9-a030-58dc8751f804" />

### Step 6: Test Sudo Privileges
```
sudo apt update
```
<img width="770" height="172" alt="image" src="https://github.com/user-attachments/assets/81c7a732-7a11-43b6-aa81-93972a66bf0a" />

# 2.Navigate to the home directory.
# 3.Create a new directory.
# 4.List the contents of a directory.
# 5.Change the current directory.
# 6.Create a new empty file.
# 7.View the contents of a file.
# 8.Copy a file to another location.
# 9.Move a file to another location.
# 10.Rename a file.
