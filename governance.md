---
title: Governance
description: Overview of CubeDAO governance utilities
published: true
date: 2023-12-14T16:38:19.024Z
tags: 
editor: markdown
dateCreated: 2023-07-24T16:32:37.731Z
---


A game needs players. By simply playing the game, community members are adding value to the network and should be rewarded.


> Disclaimer: Please note that anything written on this page and other docs pages should not be taken as financial advice. CubeDAO is incorporating unfinished, highly experimental technology. Development priorities and features are subject to change based on research, traction, feedback from the community, and other factors.
{.is-warning}




 ## Governing The Cube
A utility case for the $CBIT Token is that it would allow holders to propose and vote on on-chain governance proposals to determine future features, policies, content, and parameters of The Cube gameserver. Voting power and say are given proportionally to the voters amount of held tokens. Voters with a Founders $PASS are given a greater degree of influence (voting weight) in deciding whether to apply the changes listed in a governance poll.
  
However, during the early phase of the game, the governance decision will be made by the core team. This will prevent malicious actors from making hostile takeover efforts and disrupting the ecosystem during the early and crucial phases of platform development.

During this period, more advanced technological infrastructure will be developed and released to facilitate the decision-making process.

We estimate that the majority of undistributed tokens will be distributed, and the team will likely be a minority stake by 2025. At this point, we anticipate that the governing committee will transition into a community-owned DAO (Decentralized Autonomous Organization), fully controlled by the $CBIT token holders.
<h4><ul class="links-list">
    <li>
        <a href="https://proposals.cubedao.net/#/" class="blue-text">
            ⚡ Proposals <em> Submit ideas & vote on decisions </em>
        </a>
    </li>
</ul>
<br>
  
> **Decentralization has not been fully established yet.**
>*Full decentralization has not been achieved yet, and our core team members are not making any profits or seeking monetary gain. We want to clarify that this community is not driven by profit-seeking motives.  The 'DAO' we mention is simply an organization of like-minded individuals collaborating on advancing a specific domain of technology. It's important to understand that joining our community means recognizing that financial remuneration is not the goal, and significant risks are involved if you decide to contribute. Please be aware of these factors before getting involved.*
{.is-danger}
  
## Founders Pass
There is a maximum of 1000 Founders on the Polygon blockchain. Owning a pass gives the ability to stake & earn Cubits. Founders receive exclusive access to benefits such as a VIP membership on The Cube. 

Creators of the DAO will reserve 100 passes for development, promotions, partner incentives, airdrops and events. 

Founders Passes can be minted here: https://opensea.io/collection/cubedao/drop - if they have sold out, you can buy from the secondary marketplace on OpenSea.

50% of proceeds generated from the OpenSea Drop will be contributed towards $CBIT liquidity on Uniswap (~$27,000) progressively.

## Smart Contracts


<figure class="table">
  <table>
    <tbody>
      <tr>
        <td>
          <p>Contract</p>
        </td>
        <td>
          <p>Purpose</p>
        </td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/token/0x4c989b872e96c37bc6fcb2f0fe5fdcabecc405a2">Cubit ($CBIT)</a></td>
        <td>$CBIT contract - ERC-20</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0x7ed7a705026ffc9a8a6273422b4a77733100acb9">Founders Pass</a></td>
        <td>Founders Pass - ERC-721</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0xe9a51d1a90341f4d68b801125b67d24c908733f2">Founders Pass Staking</a></td>
        <td>Staking Contract</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0xE16B797BDC944e9C60Fc37539303c6876e423c13">Liquidity Pool</a></td>
        <td>Pool Contract (Uniswap V3 Pool)</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0x3f5f52150515e26ba76c914489aa030e6272894f">CUBE Players</a></td>
        <td>Handles player wallet information for Proof of Play rewards</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0x20723de8e6ab77181bef9478f7c3cf4f44698e69">CUBE Tx Handler</a></td>
        <td>Handles gasless transfers</td>
      </tr>
      <tr>
        <td><a href="https://polygonscan.com/address/0xbf476ae0127d6128d77790ffb3299c42bd8f2d4f">CUBE Proxy V2</a></td>
        <td>Handles in-game shop purchases</td>
      </tr>
    </tbody>
  </table>
</figure>