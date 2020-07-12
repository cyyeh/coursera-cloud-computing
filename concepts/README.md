# Cloud Computing Concepts

## Overview

Cloud computing systems today, whether open-source or used inside companies, are built using a common set of core techniques, algorithms, and design philosophies – all centered around distributed systems. Learn about such fundamental distributed computing "concepts" for cloud computing.
 
Some of these concepts include: clouds, MapReduce, key-value/NoSQL stores, classical distributed algorithms, widely-used distributed algorithms, scalability, trending areas, and much, much more! 
 
Know how these systems work from the inside out. Get your hands dirty using these concepts with provided homework exercises. In the programming assignments, implement some of these concepts in template code (programs) provided in the C++ programming language. Prior experience with C++ is required.
 
The course also features interviews with leading researchers and managers, from both industry and academia.

## Key Concepts by Week

### Week 1: Orientation, Introduction to Clouds, MapReduce
- This course is oriented towards learners with similar backgrounds as juniors and seniors in a CS undergraduate curriculum. Since learners come from various backgrounds, it is critical you view this lecture AND pass the prerequisite test. This will ensure you have many of the assumed prerequisite pieces of knowledge required to enjoy this course.

---

- Identify and apply key computer science concepts that you are expected to know before you take this course.
- Take the prerequisite quiz and socre above the high threshold.
- Identify key differences and similarities between cloud computing and previous generations of distributed systems.
- Identify why this course is about distributed systems and how they underlie today’s clouds.
- Design MapReduce programs (in pseudocode) for a variety of problems.
- Identify how Hadoop schedules jobs.

### Week 2: Gossip, Membership, and Grids
- Lesson 1: This module teaches how the multicast problem is solved by using epidemic/gossip protocols. It also teaches analysis of such protocols.
- Lesson 2: This module covers the design of failure detectors, a key component in any distributed system. Membership protocols, which use failure detectors as components, are also covered.
- Lesson 3: This module covers Grid computing, an important precursor to cloud computing.

---

- Identify the design of and analyze various gossip/epidemic protocols.
- Identify the design of and analyze various failure detection algorithms.
- Identify the design of and analyze various distributed membership protocols.
- Identify key characteristics of Grid computing.

### Week 3: P2P Systems
- P2P systems: This module teaches the detailed design of two classes of peer to peer systems:
  - popular ones including Napster, Gnutella, FastTrack, and BitTorrent
  - efficient ones including distributed hash tables (Chord, Pastry, and Kelips). Besides focusing on design, the module also analyzes these systems in detail.

---

- Identify the design of and analyze popular peer to peer systems, including Napster, Gnutella, FastTrack, and BitTorrent.
- Identify the design of and analyze peer to peer distributed hash tables (Chord, Pastry, and Kelips).

### Week 4: Key-Value Stores, Time, and Ordering

- Lesson 1: This module motivates and teaches the design of key-value/NoSQL storage/database systems. We cover the design of two major industry systems: Apache Cassandra and HBase. We also cover the famous CAP theorem.
- Lesson 2: Distributed systems are asynchronous, which makes clocks at different machines hard to synchronize. This module first covers various clock synchronization algorithms, and then covers ways of tagging events with causal timestamps that avoid synchronizing clocks. These classical algorithms were invented decades ago, yet are used widely in today’s cloud systems.

---

- Identify why key-value/NoSQL systems are popular.
- Identify which systems fall where under the CAP theorem.
- Identify the design of and analyze Apache Cassandra.
- Identify the design of and analyze Apache HBase.
- Use and analyze various time synchronization algorithms.
- Tag any given run of a distributed system with Lamport and/or vector timestamps for ordering events.

### Week 5: Classical Distributed Algorithms
- Lesson 1: This module covers how to calculate a distributed snapshot, leveraging causality again to circumvent the synchronization problem.
- Lesson 2: This lecture teaches how to order multicasts in any distributed system. Algorithms for assigning timestamp tags to multicasts using various flavors of ordering – FIFO, Causal, and Total – are covered. The module also covers virtual synchrony, a paradigm that combines reliable multicasts with membership views.
- Lesson 3: Consensus is one of the most important problems in a distributed system, enabling multiple machines to agree. This module uses Paxos, one of the most popular consensus solutions used in the industry today. Paxos is not perfect because consensus cannot be solved completely – an optional lecture presents the famous FLP proof of impossibility of consensus.

--- 

- Identify the design of and analyze a causal algorithm to calculate a distributed snapshot.
- Tag any given run of a distributed system (with multicasts) with timestamps for FIFO/Causal/Total ordering.
- Be able to identify whether a given run of a distributed system satisfies virtual synchrony or not.
- Appreciate, understand, and apply key design concepts in the industry-standard consensus-solving protocol called Paxos.
- (Optional) Be able to follow the FLP proof of why consensus is impossible to solve.

