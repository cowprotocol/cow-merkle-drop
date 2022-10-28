# CoW Protocol Merkle Data

Merkle data with claims used for token distribution.

There's different claiming data per network (`Goerli`, `Mainnet`, `Gnosis Chain`).

Each network will contain information about:

- **Mappings** (`<NETWORK>/mapping.json`): List of all the group of addresses and it's mapping to an specific chunk.
- **Chunks** (`<NETWORK>/chunks/<CHUNK>.json`): Claiming details or investment opportunities for a given chunk.

# Goerli

Claiming information for Goerli.

- **Claiming data**: [goerli/originals/claims.json](goerli/originals/claims.json)
- **Mappings**: [goerli/mapping.json](goerli/mapping.json)
- **Chunks**: [goerli/chunks](goerli/chunks)

The accounts for testing this are the first 10K accounts of the awesome mnemonic:
`claim all milk together toward moon swap coin become rich quick guitar`

# Gnosis Chain

- **Expiration**: `TODO: It would be nice, if we add expiration date for the claimings`
- **Claiming data**: [gnosis-chain/originals/claims.json](gnosis-chain/originals/claims.json)
- **Mappings**: [gnosis-chain/mapping.json](gnosis-chain/mapping.json)
- **Chunks**: [gnosis-chain/chunks](gnosis-chain/chunks)

# Mainnet

- **Expiration**: `TODO: It would be nice, if we add expiration date for the claimings`
- **Claiming data**: [mainnet/originals/claims.json](mainnet/originals/claims.json)
- **Mappings**: [mainnet/mapping.json](mainnet/mapping.json)
- **Chunks**: [mainnet/chunks](mainnet/chunks)
