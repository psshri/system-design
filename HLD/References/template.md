# Step 1: Requirements Clarifications

### 1. Functional requirements
### 2. Non-functional requirements
### 3. Who will be using the system ?
### 4. How will they be using it ?
### 5. How many users are there ?
### 6. What does the system do ?
### 7. What are the inputs and outputs of the system ?
### 8. How much data is expected to be handled ?
### 9. How many requests per second are expected ?
### 10. What is the expected read-to-write ratio ?


# Step 2: Back-of-the-envelope estimation

### 1. Read-to-write ratio
### 2. Number of concurrent requests
### 3. Number of monthly users
### 4. Number of daily active users 
### 5. Required storage capacity
### 6. Bandwidth requirements


# Step 3: Create a high-level design

![design-png](https://markdown-here.com/img/icon256.png)


# Step 4: Database design

### 1. Define how data will be processed
### 2. Define how data will flow through the system
### 3. Determine which database will be the best fit in this case


# Step 5: Design core components

### Present various approaches, benefits & drawbacks of each option and justify your approach


# Step 6: Scale the design

### Discuss: Load Balancing, Horizontal Scaling, Caching, Database Sharding, Replication


# Step 7: Identifying and resolving bottlenecks

### 1. Is there any single point of failure in the system? What steps can be taken to mitigate this risk?
### 2. Are there enough replicas of data to ensure that users can still be served if a few servers are down?
### 3. Are there enough copies of different services running to ensure that a few failures will not cause a total system shutdown?
### 4. How is the performance of the service being monitored? Are there alerts in place to notify the team when critical components fail or their performance degrades? 