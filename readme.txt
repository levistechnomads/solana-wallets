#Sugar
https://docs.metaplex.com/developer-tools/sugar/tutorials/my-first-candy-machine

#RPC

# mainnet -beta
https://api.mainnet-beta.solana.com

#devnet
https://api.devnet.solana.com


# create a new wallet
solana-keygen new --outfile ~/.config/solana/id.json

# set wallet
solana config set --keypair ~/.config/solana/devnet.json

#set RPC
solana config set --url https://api.mainnet-beta.solana.com

solana config set --url https://api.devnet.solana.com
solana config set --url https://metaplex.devnet.rpcpool.com/
