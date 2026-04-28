### *This project has been created as part of the 42 curriculum by joao-vri*

# **Description:**

The **NetPractice** project introduces fundamental networking concepts through a hands-on training interface. The goal is to understand how devices communicate over a network by correctly configuring IP addressing and routing across different levels of difficulty.

Through progressive exercises, the project covers how data flows between hosts, routers, and the internet, requiring the student to fix misconfigured networks and ensure proper connectivity.

### 1. Goals:
- Understand how IP addressing works (IPv4)
- Learn how to configure subnet masks correctly
- Identify and fix routing issues
- Understand the role of default gateways
- Gain practical knowledge of how routers and switches operate
- Apply networking theory to solve real configuration problems

---

# **Instructions:**

### 1. Access the NetPractice training interface

You can use the official 42 NetPractice interface via browser or locally depending on your setup.

If running locally:

```
./run.sh
```

This will launch the training interface where you can solve each level interactively.

---

### 2. Solve the levels

- Each level presents a network with incorrect configurations
- You must fix IPs, masks, and routes to make communication possible
- Validate your solution using the interface tools

---

### 3. Export configurations

Once a level is solved:

- Use the **“Export”** button in the interface
- This generates a `.json` configuration file for that level

---

### 4. Submission requirements

- You must export **10 configuration files (one per level)**
- Place all exported `.json` files at the **root of your repository**
- Ensure they are correctly named and correspond to each level

Example:

```
level1.json
level2.json
...
level10.json
```

---

# **Resources**

### Networking Concepts Studied:

During this project, the following core networking concepts are explored:

- **TCP/IP addressing** (IPv4 structure and usage)
- **Subnet masks** and network segmentation
- **Default gateways** and routing logic
- **Routers and switches** (their roles in a network)
- **OSI Model layers** (especially Network and Data Link layers)
- **Packet routing and delivery**
- **Local vs remote network communication**

---

### Learning Resources:

- Computer Networking basics  
  https://www.geeksforgeeks.org/computer-networks/tcp-ip-model/

- Subnetting explained  
  https://www.geeksforgeeks.org/introduction-of-subnetting/

- OSI Model overview  
  https://www.w3schools.com/cybersecurity/cybersecurity_networking.php

- IP addressing and routing  
  https://www.cisco.com/c/en/us/products/switches/what-is-a-network-switch.html

---

### How AI was used:

AI tools were used as a **support tool**, mainly for:

- Clarifying networking concepts (subnetting, routing, IP ranges)
- Explaining why certain configurations failed
- Helping debug incorrect network setups
- Providing alternative explanations for difficult topics

AI was **not used to directly solve levels**, but rather to reinforce understanding and speed up learning when concepts were unclear.

---

## **Additional Notes:**

This project is less about memorization and more about developing intuition for how networks behave. Mistakes in configuration are part of the learning process, and each level builds on previous concepts.
