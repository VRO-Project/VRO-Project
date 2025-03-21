## VRO: Verifiable Routing Origins via AS Cooperations

### Project Introduction

The Internet faces significant challenges related to legitimate MOAS (Multiple-Origin Autonomous System) conflicts and route origin hijacking, which often exhibit similar patterns. VRO addresses these issues through a decentralized cooperative system among ASes (Autonomous Systems) to enhance routing security. 

![vro_project.png](https://github.com/VRO-Project/VRO-Project/blob/main/vro_project.png)

### Key Features

**Decentralized Cooperative System:** VRO enables cooperations among ASes to improve routing security.

**Allowlist Mechanism:** ASes collaboratively announce prefixes using aggregated signatures, forming a Signed MOAS Group (SMG).

**Blocklist Mechanism:** Neighboring ASes vote on the most credible AS based on local routing history in case of prefix conflicts using smart contracts.

### TODO List

Draft Specifications

- [x] [Problem Statement Draft](https://github.com/VRO-Project/draft-jiang-sidrops-psvro)
- [x] [Allowlist Mechanism Profile Draft](https://github.com/VRO-Project/draft-li-sidrops-rpki-moasgroup)
- [ ] [Allowlist Mechanism Verification Draft](https://github.com/VRO-Project/draft-li-sidrops-smg-verification) (In Progress)
- [ ] Blocklist Mechanism Draft

Development

- [x] [Allowlist Mechanism](https://github.com/VRO-Project/signed_moas_group)
- [x] [Blocklist Mechanism (Smart Contract)](https://github.com/VRO-Project/vro_smart_contract)
- [x] [Blocklist Mechanism (Off-Chain)](https://github.com/VRO-Project/vro_agent)
- [ ] RTR


<!--
**VRO-Project/VRO-Project** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
