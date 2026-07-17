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

