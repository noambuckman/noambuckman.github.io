---
title: "Dynamic Decentralized Task Allocation"
excerpt: "Decentralized algorithms for planning and replanning task allocations in dynamic environments with new information. 1<br/><img src='/images/prcbba.png'>"
collection: research
---

In time-sensitive and dynamic missions, multi-UAV teams must respond quickly to new
information and objectives. This paper presents a dynamic decentralized task allocation algorithm
for allocating new tasks that appear online during the solving of the task allocation
problem. Our algorithm extends the Consensus-Based Bundle Algorithm (CBBA), a decentralized
task allocation algorithm, allowing for the fast allocation of new tasks without a full
reallocation of existing tasks. CBBA with Partial Replanning (CBBA-PR) enables the team to
trade-off between convergence time and increased coordination by resetting a portion of their
previous allocation at every round of bidding on tasks. By resetting the last tasks allocated
by each agent, we are able to ensure the convergence of the team to a conflict-free solution.
CBBA-PR can be further improved by reducing the team size involved in the replanning, further
reducing the communication burden of the team and runtime of CBBA-PR. Finally, we validate
the faster convergence and improved solution quality of CBBA-PR in multi-UAV simulations.
