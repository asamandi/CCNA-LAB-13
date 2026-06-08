# IPv6 + OSPFv3 (3 Routers + 2 PCs)

### Topology

PC1 — R1 — R2 — R3 — PC2

### IPv6 Address Plan

LAN1 (PC1 side): 2001:DB8:1:1::/64
- R1 G0/0: 2001:DB8:1:1::1/64
- R1–R2 link: 2001:DB8:12:12::/64
- R1 G0/1: 2001:DB8:12:12::1/64
- R2 G0/0: 2001:DB8:12:12::2/64
- R2–R3 link: 2001:DB8:23:23::/64
- R2 G0/1: 2001:DB8:23:23::2/64
- R3 G0/0: 2001:DB8:23:23::3/64

LAN2 (PC2 side): 2001:DB8:3:3::/64

- R3 G0/1: 2001:DB8:3:3::1/64
