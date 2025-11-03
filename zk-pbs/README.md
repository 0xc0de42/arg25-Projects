# ARG25 Project Submission Template


##  Project Title
Optimistic Non Interactive Zero Knowledge Proposer Builder Seperation (ONIZK-PBS)
## Team
- Team/Individual Name: Gil Henkin
- GitHub Handles: 0xc0de42
- Devfolio Handles: Gilles

## Project Description
Proposer-Builder Separation (PBS) has emerged as a key design to democratize block construction and mitigate MEV centralization.  In Ethereum’s MEV-Boost era, validators outsource block building to specialized relays and builders.  However, the reliance on trusted relays and cleartext block proposals introduces a new trust assumption and centralization risks.
We propose an \emph{Optimistic Zero-Knowledge PBS (ZK PBS)} architecture in which block builders commit to a proposed block via its header and a succinct zero-knowledge proof.  This approach allows the proposer to validate that a block is correct and the promised bid will be paid, validation happens only when needed.  We detail a system design with distinct roles (Proposer, Builder, Prover, Verifier and a Challenger) and a two stage protocol to prove and verify blocks securely.  We present a ZK construction for the block validity statement for generating and verifying proofs. The ONIZK PBS protocol preserves proposer-builder trustlessness, and enforces proposer-builder honesty.  We discuss performance trade-offs, potential limitations, and directions for future work. 



## Tech Stack
I am starting by writing a paper.


## Objectives
Research the possibility of a decentralized PBS.


## Weekly Progress

### Week 1 (ends Oct 31)
**Goals:**
Initial research and information collection
**Progress Summary:**  
Paper draft.

### Week 2 (ends Nov 7)
**Goals:**  
 
**Progress Summary:**  


### 🗓️ Week 3 (ends Nov 14)
**Goals:**  

**Progress Summary:**  



## Final Wrap-Up
_After Week 3, summarize your final state: deliverables, repo links, and outcomes._

- **Main Repository Link:**  
- **Demo / Deployment Link (if any):**  
- **Slides / Presentation (if any):**



## 🧾 Learnings
_What did you learn or improve during ARG25?_



## Next Steps
_If you plan to continue development beyond ARG25, what’s next?_
