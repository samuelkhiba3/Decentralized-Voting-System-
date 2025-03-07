# Decentralized-Voting-System-
Simple Decentralized Voting System that promotes security and transparency of votes

# Tech used:
- JAVA
- JAVAFX

# Functionalities:
- Users can register and get unique key instantly
- Login using their registered credentials along with their key which was provided.
- Users can view their successful cast vote
- Votes integrity and transparency can be verified through blockchain option(feature) and results.
- Users are allowed to vote once.
- Transaction is broadcasted to all peers and added to their blockchain only if validated successfully

# Issue:
- Peer transaction were not able to sync with others
  
# Solution proposed (Not efficient but works) 
- Introduced a master server that holds the TCP address and ports of all registerd peers(But not Voting data), this is to enable peer connections.
  
Still under development...
![Voting System(JPG version)](https://github.com/user-attachments/assets/7f367060-aea6-44cf-9e5b-9bfe4474e0c8)
