# Vigilante Metadata Verifier

This repository aims to demonstrate how to verify that the Vigilante NFTs are randomly distributed while using a commit-reveal scheme.
An initial verification approach was described by the team in the article [How to verify that HonestNFT Vigilantes are randomly distributed](https://medium.com/@convexlabs/how-to-verify-that-honestnft-vigilantes-are-randomly-distributed-2592665c5c72).

This is a more automated approach with annotations for every step. 


## Prerequisites

Make sure you have installed all of the following prerequisites on your device:
1. git
2. python3



## Installation

1. Download the repo + submodules: `git clone --recurse-submodules git@github.com:Convex-Labs/vigilante-verifier.git`
2. Change directory to the downloaded repo: `cd vigilante-verifier`
3. Rename `.env-example` to `.env`
4. Add your personal web3 providers to `.env` (Alchemy, Infura, ...)
5. Symlink your .env file into the submodule:`cd honestnft-shenanigans && ln -s ../.env .env && cd ..`
6. Install the dependencies with `python3 -m pip install -r requirements.txt`



## Usage
Either run the notebook and follow the inline instructions or read the article for a comprehensive walk-through: [Vigilante NFT Metadata Verifier](https://medium.com/@barabazs/vigilante-nft-metadata-verifier-612a2dbf6bc2)
    
## License
[MIT](https://choosealicense.com/licenses/mit/)
