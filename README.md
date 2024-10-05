# Pont Network
Pont Network offers a revolutionary blockchain-based solution to transform record-keeping in the maritime industry. By leveraging the power of blockchain technology, Pont Network creates a secure, tamper-proof, and transparent record of a ship's history.
<br><br>
Pont offers real-time visibility and tracking for all observer stations, improving tracking efficiency and minimizing delays. As a blockchain solution, it ensures a secure and decentralized system with immutable records and distributed storage, effectively eliminating fraudulent activities and maintaining data integrity. Additionally, Pont enhances cybersecurity by implementing robust protocols to safeguard against data breaches and unauthorized access.

## Progress so far
🤝 Working on collaboration with the Faculty of Maritime Studies in Rijeka, one of the most prestigious maritime faculties in Europe. <br>
🥈 place at Solana Build Station. <br>
🏗 Participating in Solana Radar Hackathon.

## Docs
**Pitch Deck - https://docsend.com/view/2cs3qgzvs3jgbrrb** <br>
**Twitter - https://x.com/pont_network** <br>
**Whitepaper - https://docsend.com/view/gxrcap7g3qq5zcwa** <br>
**Demo - https://docsend.com/view/jvyx2en2dq9ueexw** <br>

## System Architecture
The Pont Network system consists of several entities:

- **Ship Management** - Manages all ships in the system
- **Observer Stations** - Stations around the world that monitor data from ships for which they have received permission
- **Onboard Program** - Collects data from sensors, encrypts it, and sends it to Solana decentralized storage for secure recording

Accordingly, this repository consists of submodules:

- **pont-network-contracts** - Program on Solana
- **pont-network-backend** - Application on ship
- **pont-network-indexer** - Application running on observer stations
- **pont-network-observer-frontend** - Frontend application for observer stations
- **pont-network-management-frontend** - Frontend application for ship management
