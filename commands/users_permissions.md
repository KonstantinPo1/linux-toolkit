# Users and Permissions

Practical Linux commands for working with users, groups, ownership, and file permissions.

---

## whoami

**Purpose**

Display the current username.

```bash
whoami
```

---

## id

**Purpose**

Display the current user's UID, GID, and group membership.

```bash
id
```

---

## groups

**Purpose**

Display the groups a user belongs to.

```bash
groups
groups username
```

---

## sudo

**Purpose**

Run a command with elevated privileges.

```bash
sudo systemctl status ssh
```

---

## chmod

**Purpose**

Change file or directory permissions.

```bash
chmod +x script.sh
chmod 755 script.sh
```

---

## chown

**Purpose**

Change the owner and group of a file.

```bash
sudo chown user:group file.txt
```

---

## ls -l

**Purpose**

Display file permissions, ownership, size, and modification time.

```bash
ls -l
```
