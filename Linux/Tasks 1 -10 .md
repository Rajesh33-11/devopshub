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
_______________________________

# 2.Navigate to the home directory.
### Using cd
```
cd
```
<img width="515" height="172" alt="image" src="https://github.com/user-attachments/assets/d6c7fcc3-5ba6-45fa-8901-c7efe6249617" />
____________________

# 3.Create a new directory.
```
mkdir rajesh33
```
<img width="581" height="152" alt="image" src="https://github.com/user-attachments/assets/7f0e3fe5-0111-4b48-889e-36ffbbe9baf1" />

# 4.List the contents of a directory.
```
ls
```
```
ll
```
```
ls -a
```
<img width="797" height="337" alt="image" src="https://github.com/user-attachments/assets/820ed020-3017-45c2-b525-9e97a65ff50d" />

____________________________________________________________ 
# 5.Change the current directory.
```
cd dir_name
```
<img width="502" height="162" alt="image" src="https://github.com/user-attachments/assets/b4531792-02b0-4a3c-bc8f-44bd596794e3" />

____________________________________________________________ 
# 6.Create a new empty file.
```
touch <file-name>
```
<img width="562" height="142" alt="image" src="https://github.com/user-attachments/assets/3c518ddb-26e2-49c9-9127-ceb1306f1172" />

_____________________________
# 7.View the contents of a file.
```
cat <file_name>
```
<img width="661" height="231" alt="image" src="https://github.com/user-attachments/assets/bdc6c8bc-a978-4b40-8ec2-1ba48b64e7a5" />

_____________________________
# 8.Copy a file to another location.
```
cp <source_file> <destination>
```
<img width="597" height="332" alt="image" src="https://github.com/user-attachments/assets/bf99ebc0-e8a0-459a-9c5d-a33cd47ccd02" />

________________________________

# 9.Move a file to another location.
```
mv <source_file> <destination_directory>
```
<img width="607" height="191" alt="image" src="https://github.com/user-attachments/assets/5f50c508-cdf0-433b-8413-b92b0ecafed8" />

_________________
# 10.Rename a file.
```
mv <old_file_name> <new_file_name>
```
<img width="757" height="182" alt="image" src="https://github.com/user-attachments/assets/027aedf1-8ec4-430a-97e9-6d028e17fb5f" />

