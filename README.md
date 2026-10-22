![Custom Color](https://img.shields.io/badge/Version-v1.0-blueviolet)

---
***
___

```In Progress...```

$$\color{#3498db}\rule{\linewidth}{2px}$$

> Single vertical line on the left margin
>> Nested vertical lines

| Left Column | Center Column | Right Column |
| :---        |    :----:   |         ---: |
| Text        | Text          | Text         |

| Task | Status | Priority |
| :--- | :--- | :--- |
| User Authentication | ![Done](https://img.shields.io/badge/-Completed-2ea44f) | ![Low](https://img.shields.io/badge/-Low-blue) |
| Payment Gateway | ![Pending](https://img.shields.io/badge/-In%20Progress-f1e05a) | ![High](https://img.shields.io/badge/-High-red) |
| Dark Mode | ![Blocked](https://img.shields.io/badge/-Blocked-e05d44) | ![Medium](https://img.shields.io/badge/-Medium-orange) |

| Endpoint | Method | Note |
| :--- | :--- | :--- |
| `/api/v1/users` | `GET` | Standard endpoint |
| `/api/v1/auth` | `POST` | <mark>Requires Bearer Token</mark> |

| Environment | Configuration | Active Version |
| :--- | :--- | :--- |
| Production | `ssl_strict=true` | `v2.4.1` |
| Staging | `debug=enabled` | `v2.5.0-rc1` |

| Metric | Status | Level |
| :--- | :---: | :--- |
| Database Latency | 🟩 | Normal |
| Memory Usage | 🟨 | Elevated (> 75%) |
| Disk I/O | 🟥 | Critical Bottleneck |
| Network Traffic | 🟦 | Monitored |