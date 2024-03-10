**FlareGate**
Flaregate will be the first-of-its-kind fully decentralized, bi-directional cross-chain bridge from Flare to all EVM chains for any fungible asset.

The MVP built at **ETHOxford** from scratch demonstrates potential in a bidirectional bridge between Ethereum Sepolia and Flare Coston from Flare-provided tokens (USDT-0 - USDT-9) on Sepolia to Flare-provided tokens (USDT-0 - USDT-9) on Coston especially created for this hack.

We will show end-to-end transfer of the tokens (USDT-0 to USDT-9) (bidirectionally) at 1:1 pricing as we can only use the whitelisted token on the relayer.

The Dapp is publically usable on: https://flaregate.vercel.app

Loom video explaining the demo is available at: https://www.loom.com/share/ed4b3f5b98b24c32ba76939a3e204195?sid=de81c03e-f919-4876-b3ae-27d64c5bcbfe

Canva pitch : https://www.canva.com/design/DAF_DQAMfes/66fZMe4YDLNaywi0KU8fEA/edit?utm_content=DAF_DQAMfes&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Relayers used: (deployed by the Flare team) 

COSTON_RELAY=0x2f48135AdF44c99999cA0d6d21bD49466AaD74Fd
SEPOLIA_RELAY=0x7b4d5e9388dBdB0161186D605379dafA3dc22100 

Sample Execution transaction hashes from Coston to Sepolia of USDT-0:

Coston - 0x7bd7b246f1eaee87591198723f6bde824a9d42486a8ad26e3f457e6104e04874
Sepolia - 0x689c692bfac1cc63d6e7237686ea28713c00f9789fc7a0ceee1f9c8ee1fe72c3

Sample Execution transaction hashes from Sepolia to Coston of USDT-0:

Sepolia - 0x486f08f9f406048cffda8faf0074164365653e1ffc90e6e658d8616041f9d409
Coston - 0x1698f5f1f23fe802701f1b3e310f6d0b3a82e3dd92609eba2906b49600c24741


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

As of now, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
