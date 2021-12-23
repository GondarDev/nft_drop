# buildspace Solana NFT Drop Project
### Welcome 👋
To get started with this course, clone this repo and follow these commands:

1. cd into the `app` folder
2. Run `npm install` at the root of your directory
3. Run `npm run start` to start the project
4. Start coding!

### What is the .vscode Folder?
If you use VSCode to build your app, we included a list of suggested extensions that will help you build this project! Once you open this project in VSCode, you will see a popup asking if you want to download the recommended extensions :).

### Questions?
Have some questions make sure you head over to your [buildspace Dashboard](https://app.buildspace.so/projects/CO77556be5-25e9-49dd-a799-91a2fc29520e) and link your Discord account so you can get access to helpful channels and your instructor!

eric@ubuntu:~/Git/nft-drop-starter-project$ ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-cli.ts upload ./assets --env devnet --keypair ~/.config/solana/devnet.json

Beginning the upload for 3 (png+json) pairs
started at: 1640252985979
wallet public key: HX6iRagxofpiZoTBHDq46EAY6CcpCxcpRSELSac6zTcV
Processing file: 0
initializing config
initialized config for a candy machine with publickey: qEPGXJLYXoERgZrQGRDEPQV6Km1nLbFbmZjJ5nWUn7q
lamport cost to store assets/0.png: 14423.376007525083
REST no confirmations for 2Fav9edEv4ZUbtog4Jdy8k1k23JtZAwFngvmJ8A6nSgANYtn2kmsfjBshMYPTzEV9iDs7dCLqC9jAgvEdGJHcpej {
  confirmationStatus: 'confirmed',
  confirmations: 0,
  err: null,
  slot: 102810298,
  status: { Ok: null }
}
lamport cost to store assets/1.png: 13234.959331730768
lamport cost to store assets/2.png: 13234.959331730768
Writing indices 0-2
Done. Successful = true.
ended at: 2021-12-23T09:50:35.137Z. time taken: 00:00:49
eric@ubuntu:~/Git/nft-drop-starter-project$ ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-cli.ts verify --keypair ~/.config/solana/devnet.json
wallet public key: HX6iRagxofpiZoTBHDq46EAY6CcpCxcpRSELSac6zTcV
Name Jacky with https://arweave.net/ANnhAqaaQm0ypB2OhX6ZeVAbk7yr-kd08ECh2CRTSok checked out
Name Simba with https://arweave.net/GZWPiAR8zjJQTx7_nslyiT7EEFS4u0grHxJEThTiT7c checked out
Name Monkey with https://arweave.net/TP87C7-UVoIAcYYViaQSpAdaDYFmUzRyp_5IegtTujA checked out
uploaded (3) out of (3)

eric@ubuntu:~/Git/nft-drop-starter-project$ ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-cli.ts create_candy_machine --env devnet --keypair ~/.config/solana/devnet.json -p 1

wallet public key: HX6iRagxofpiZoTBHDq46EAY6CcpCxcpRSELSac6zTcV
create_candy_machine finished. candy machine pubkey: FSDZKEFTUY72oiR27p2jepH3Np8GTYquCnSLWSc2HeTg

eric@ubuntu:~/Git/nft-drop-starter-project$ ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-cli.ts update_candy_machine --date "1 Dec 2021 00:12:00 GMT" --env devnet --keypair ~/.config/solana/devnet.json

wallet public key: HX6iRagxofpiZoTBHDq46EAY6CcpCxcpRSELSac6zTcV
 - updated startDate timestamp: 1638317520 (1 Dec 2021 00:12:00 GMT)
update_candy_machine finished 4UscLmrQ1RTiiPfDJWN5uvF5mvgJe7Xc7pf6MKYkD4i8qZHWgdYBEX1botb7zvV1iZuRjktdY1Qd3N2dUykzBibE

