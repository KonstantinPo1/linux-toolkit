# Process Management

Practical Linux commands for viewing, monitoring, and managing running processes.

---

## ps

**Purpose**

Display running processes.

```bash
ps
ps aux
```

---

## top

**Purpose**

Monitor processes, CPU usage, memory usage, and system load in real time.

```bash
top
```

---

## htop

**Purpose**

Display an interactive and user-friendly process monitor.

```bash
htop
```

`htop` may need to be installed separately.

---

## pgrep

**Purpose**

Find the process ID of a running program.

```bash
pgrep nginx
```

---

## kill

**Purpose**

Send a signal to a process using its PID.

```bash
kill 1234
```

---

## pkill

**Purpose**

Stop processes by name.

```bash
pkill nginx
```

---

## jobs

**Purpose**

Display jobs running in the current shell session.

```bash
jobs
```

---

## uptime

**Purpose**

Display system uptime and load averages.

```bash
uptime
```
