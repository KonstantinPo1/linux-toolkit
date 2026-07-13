# Networking Commands

Practical Linux commands for checking interfaces, connectivity, routes, ports, and remote services.

---

## ip a

**Purpose**

Display network interfaces and IP addresses.

```bash
ip a
```

---

## ip route

**Purpose**

Display the system routing table and default gateway.

```bash
ip route
```

---

## ping

**Purpose**

Test whether another host is reachable.

```bash
ping google.com
ping -c 4 google.com
```

---

## ss

**Purpose**

Display network connections and listening ports.

```bash
ss -tulnp
```

---

## curl

**Purpose**

Send requests to URLs and test web services or APIs.

```bash
curl https://example.com
curl -I https://example.com
```

---

## wget

**Purpose**

Download files from the internet.

```bash
wget https://example.com/file.zip
```

---

## hostname

**Purpose**

Display the system hostname.

```bash
hostname
```

---

## hostname -I

**Purpose**

Display the IP addresses assigned to the system.

```bash
hostname -I
```
