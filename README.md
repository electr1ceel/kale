# Kale 羽衣甘蓝 - Intrusion Detection System  侦测入侵系统 (Port Mirroring)

```bash
                                                                            +------- WIFI AP
                                                                            |        (if any)
         (Incoming)             (Outgoing, WAN)           (LAN)             |
   Modem ----------- Croissants ---------------- Router -------- Switch ----+------- PCs
                          |                      (WIFI)             |       |
                          |                                         |       |
                          +-----------------------------------------+       +------- Kale (Port Mirroring)
                                         (Monitoring)

```

```bash
                                                                    +------- WIFI AP
                                                                    |
         (Incoming)            (Outgoing, Port #1)                  |
5G Modem ----------- Croissants ---------------- Switch ------------+------- PCs
WIFI Router (unused)      |                        |                |
                          |                        |                |
                          +------------------------+                +------- Kale (Port Mirroring)
                                 (Monitoring)

```
