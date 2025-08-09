# CashuCardWallet
*"Writing a description for this thing for general audiences is bloody hard. There's nothing to relate it to."*
--Satoshi Nakamoto, July 5, 2010

The goal is to vibe code a NIP 60 cashu wallet using MKStacks on Shakeshpeare.diy.

This is an experiment in using AI to create a NIP 60 Cashu wallet using Standard American English as a computer language. The goal is to create [realia](https://www.merriam-webster.com/dictionary/realia) designed to teach children how to use bitcoin, a peer-to-peer electronic cash system.


Here is my English Code.

```
Create a nostr client named Cashu Cards. The client shopuld allow a user to create a nostr key using NIP 06. Once the user creates a nostr keypair, the user should be instructed to backup the identity by writing down 12 seed words.

This client also creates a NIP 60 cashu wallet for the user and the ability to chose a reputible mint using NIP 87. All Nip 57 zaps should be redirected to the user's cashu wallet. The user should also be able to send cashu to any other cashu wallet.

The site should warn that this is for educational purposes only and not cybersecurity or investment advice. The user should not use make cashu than they are willing to lose.


The theme should be bitcoin orange and white.

It should be mobile responsive and UX friendly using Tailwind's mobile-first classes.
```

###
Here is the result:

https://cashu-passport-kp02.shakespeare.to/


MKStack
Assistant ($0.264 • claude-sonnet-4)
✅ Successfully Removed NIP-06 Functionality
I have successfully removed the NIP-06 portion of the Cashu Cards client. Here's what was changed:

🗑️ Removed Components:
Seed phrase generation: No more BIP39 mnemonic generation
Key derivation: Removed BIP32 hierarchical deterministic key derivation
Backup flow: Eliminated the seed phrase backup and confirmation steps
Import functionality: Removed ability to import existing seed phrases
🔧 Updated Functionality:
Simplified setup: Users now go directly from warning to mint selection
Random key generation: Cashu wallet keys are now generated using crypto.getRandomValues()
Existing Nostr identity: Users must log in with existing Nostr accounts (browser extensions, etc.)
Streamlined UX: Reduced setup steps from 4 to 2 (warning → mint selection)
📦 Dependencies Removed:
bip39 - BIP39 mnemonic phrase library
@scure/bip32 - BIP32 hierarchical deterministic keys
@types/bip39 - TypeScript definitions
📝 Documentation Updates:
README.md: Updated to reflect NIP-07 browser extension integration instead of NIP-06
NIP.md: Changed from NIP-06 to NIP-07 implementation details
Setup instructions: Simplified to reflect new flow
Security considerations: Updated to focus on existing Nostr key management
🎯 Current Flow:
User logs in with existing Nostr identity (browser extension or keys)
Educational warning about Cashu risks and experimental nature
Mint selection from reputable educational mints
Wallet creation with randomly generated Cashu keys
Ready to use educational Cashu wallet
The application now focuses on integrating with existing Nostr identities rather than creating new ones, making it simpler and more aligned with established Nostr ecosystem practices. Users can still enjoy all the educational Cashu functionality while using their existing, secure Nostr key management solutions.







## Help Wanted

I've been working on simmilar cards for about three years as of block 909,312.

**Special thanks to [BitPopArt](https://primal.net/p/nprofile1qqsy8w40ps5wdna3jkchacyrux0t8f90m7k9fkdkhtchqfcw6xf7xnqjrwfkf) helped design some cartoon characters.**
