# Valorant Account Database (VAD)

This is a mini project built to target the problem of storing Main and Alternate Valorant IDs locally. :briefcase:

## Features

- **`/add`** or **`/new`** : To add an Entry in the Database :ledger:
- **`/find`** or **`/lookup`** : To lookup an Entry in the Database and automatically copy the Username and Password to clipboard. Ready to Paste :clipboard:
- **`/update`** : To update password of any existing Entry in the Database :black_nib:
- **`/listall`** : To list all the Entries in the Database :mailbox_with_mail:

**NOTE:** _Whatever you add as Riot ID Name, will be used as your primary key to lookup the database in future._
<br>

### /add

**Input:**
```cpp
/add //input command
NOOBIE //primary key: easier to remember, just put your in-game Valorant Name
admin //username
abc123 //password
```

**Output:**
```cpp
Account Added Successfully
```
<br>

### /find

**Input:**
```cpp
/find
NOOBIE //primary key. May also put noobie/Noobie/noobiE
```

**Output:**
```cpp
NOOBIE:
username: admin
password: abc123

Username has been copied to your Clipboard.
Press any key to continue . . .
Password has been copied to your Clipboard.
```

