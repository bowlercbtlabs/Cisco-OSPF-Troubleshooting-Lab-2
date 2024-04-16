# Cisco OSPF Troubleshooting - Lab 2

## Trouble Ticket #1

### Problem
- R1 is unable to form an OSPF neighbor relationship with R2.

### Desired outcome
- Configure the network so that R1 and R2 form an OSPF neighbor relationship.
- Once connectivity is fully restored, R1’s Loopback 0 Interface (1.1.1.1) should be able to ping R2’s Loopback 0 Interface (2.2.2.2).
- You may only modify one line of configuration on either R1 or R2 to restore connectivity.
- Do not delete any configuration on R1 or R2

## Trouble Ticket #2

### Problem
- After OSPF connectivity was restored between R1 and R2 you have noticed the network 33.33.33.0/24 from R3 is not showing up in R1’s Routing Table.

### Desired outcome
- Configure the network so that 33.33.33.0/24 appears in R1’s Routing Table and that you can ping R1’s Loopback 0 interface (1.1.1.1) from R3’s Loopback 33 interface (33.33.33.33).
