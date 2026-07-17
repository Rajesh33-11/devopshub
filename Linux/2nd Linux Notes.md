# Linux permissions

## drwxrwxr-x

### d = Directory , - = It means File.

### Example : drwxrwxr-x   → Directory    |    -rw-r--r--   → File

<img width="225" height="82" alt="image" src="https://github.com/user-attachments/assets/58ef3820-94dd-4359-ab7b-36142361cc6f" />

## List all users
```
cat /etc/passwd
```
<img width="616" height="366" alt="image" src="https://github.com/user-attachments/assets/0f0ac8bb-dd06-44ca-821d-10515f99037d" />

## Only usernames
```
cut -d: -f1 /etc/passwd
```
<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/6642bd8f-14b2-46d0-8d44-85af4ee6f101" />

## Change Owner
```
sudo chown root:rajesh notes.txt
```
<img width="957" height="507" alt="image" src="https://github.com/user-attachments/assets/09ee75d0-c603-4da9-a5cf-41f2ef94145f" />

## Change group
```
sudo chown :jks notes.txt
```
<img width="857" height="460" alt="image" src="https://github.com/user-attachments/assets/c460d64a-9751-4588-b718-b79cbcc28506" />

## current user information
```
id
```
### uid → User ID       |    gid → Primary Group   |     ID groups → User belongs to which groups
<img width="1207" height="95" alt="image" src="https://github.com/user-attachments/assets/230c432c-f433-4771-83fc-b7dda65394e7" />

## new user create
```
sudo adduser username
```
<img width="797" height="407" alt="image" src="https://github.com/user-attachments/assets/3dbe096a-d229-4b66-b59d-fd2c07ccb3fd" />

## Verify User
```
cat /etc/passwd | grep kamesh
```
<img width="947" height="87" alt="image" src="https://github.com/user-attachments/assets/3b0c89c5-d279-499d-ad5b-52136e074889" />
_________

<img width="1092" height="437" alt="image" src="https://github.com/user-attachments/assets/7c4504fb-a02e-41e5-af5e-edc0828af2c7" />

## Switch to another user
```
su - username
```
<img width="1226" height="227" alt="image" src="https://github.com/user-attachments/assets/860769d5-60aa-4a55-96bb-6d83051a4a4e" />

```
echo rajesh hello
```

```
echo "rajesh hello " > test.txt
```

```
echo "rajesh from bhimavaram " >> test.txt
```

```
wc test.txt
```

```
head -3 file_name
```

```
tail -3 file_name
```

```
tail -f file_name
```

```
find / -name *.txt
```

```
sudo find / -name sudoers -mtime +30
```

```
grep z file_name
```

```
grep -i z file_name
```
