
# Perennial v2.3 contest details

- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)

# Q&A

# Audit scope


[perennial-v2 @ 22ba19c323a13c9f02f95db6747d137a3bf1277a](https://github.com/equilibria-xyz/perennial-v2/tree/22ba19c323a13c9f02f95db6747d137a3bf1277a)
- [perennial-v2/packages/perennial-extensions/contracts/Coordinator.sol](perennial-v2/packages/perennial-extensions/contracts/Coordinator.sol)
- [perennial-v2/packages/perennial-extensions/contracts/MultiInvoker.sol](perennial-v2/packages/perennial-extensions/contracts/MultiInvoker.sol)
- [perennial-v2/packages/perennial-extensions/contracts/MultiInvoker_Arbitrum.sol](perennial-v2/packages/perennial-extensions/contracts/MultiInvoker_Arbitrum.sol)
- [perennial-v2/packages/perennial-extensions/contracts/MultiInvoker_Optimism.sol](perennial-v2/packages/perennial-extensions/contracts/MultiInvoker_Optimism.sol)
- [perennial-v2/packages/perennial-extensions/contracts/types/InterfaceFee.sol](perennial-v2/packages/perennial-extensions/contracts/types/InterfaceFee.sol)
- [perennial-v2/packages/perennial-extensions/contracts/types/TriggerOrder.sol](perennial-v2/packages/perennial-extensions/contracts/types/TriggerOrder.sol)
- [perennial-v2/packages/perennial-oracle/contracts/Oracle.sol](perennial-v2/packages/perennial-oracle/contracts/Oracle.sol)
- [perennial-v2/packages/perennial-oracle/contracts/OracleFactory.sol](perennial-v2/packages/perennial-oracle/contracts/OracleFactory.sol)
- [perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory.sol](perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory.sol)
- [perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory_Arbitrum.sol](perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory_Arbitrum.sol)
- [perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory_Optimism.sol](perennial-v2/packages/perennial-oracle/contracts/chainlink/ChainlinkFactory_Optimism.sol)
- [perennial-v2/packages/perennial-oracle/contracts/keeper/KeeperFactory.sol](perennial-v2/packages/perennial-oracle/contracts/keeper/KeeperFactory.sol)
- [perennial-v2/packages/perennial-oracle/contracts/keeper/KeeperOracle.sol](perennial-v2/packages/perennial-oracle/contracts/keeper/KeeperOracle.sol)
- [perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory.sol](perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory.sol)
- [perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory_Arbitrum.sol](perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory_Arbitrum.sol)
- [perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory_Optimism.sol](perennial-v2/packages/perennial-oracle/contracts/metaquants/MetaQuantsFactory_Optimism.sol)
- [perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory.sol](perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory.sol)
- [perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory_Arbitrum.sol](perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory_Arbitrum.sol)
- [perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory_Optimism.sol](perennial-v2/packages/perennial-oracle/contracts/pyth/PythFactory_Optimism.sol)
- [perennial-v2/packages/perennial-vault/contracts/Vault.sol](perennial-v2/packages/perennial-vault/contracts/Vault.sol)
- [perennial-v2/packages/perennial-vault/contracts/VaultFactory.sol](perennial-v2/packages/perennial-vault/contracts/VaultFactory.sol)
- [perennial-v2/packages/perennial-vault/contracts/lib/StrategyLib.sol](perennial-v2/packages/perennial-vault/contracts/lib/StrategyLib.sol)
- [perennial-v2/packages/perennial-vault/contracts/types/Account.sol](perennial-v2/packages/perennial-vault/contracts/types/Account.sol)
- [perennial-v2/packages/perennial-vault/contracts/types/Checkpoint.sol](perennial-v2/packages/perennial-vault/contracts/types/Checkpoint.sol)
- [perennial-v2/packages/perennial-vault/contracts/types/Registration.sol](perennial-v2/packages/perennial-vault/contracts/types/Registration.sol)
- [perennial-v2/packages/perennial-vault/contracts/types/VaultParameter.sol](perennial-v2/packages/perennial-vault/contracts/types/VaultParameter.sol)
- [perennial-v2/packages/perennial/contracts/Market.sol](perennial-v2/packages/perennial/contracts/Market.sol)
- [perennial-v2/packages/perennial/contracts/MarketFactory.sol](perennial-v2/packages/perennial/contracts/MarketFactory.sol)
- [perennial-v2/packages/perennial/contracts/libs/CheckpointLib.sol](perennial-v2/packages/perennial/contracts/libs/CheckpointLib.sol)
- [perennial-v2/packages/perennial/contracts/libs/InvariantLib.sol](perennial-v2/packages/perennial/contracts/libs/InvariantLib.sol)
- [perennial-v2/packages/perennial/contracts/libs/VersionLib.sol](perennial-v2/packages/perennial/contracts/libs/VersionLib.sol)
- [perennial-v2/packages/perennial/contracts/types/Checkpoint.sol](perennial-v2/packages/perennial/contracts/types/Checkpoint.sol)
- [perennial-v2/packages/perennial/contracts/types/Global.sol](perennial-v2/packages/perennial/contracts/types/Global.sol)
- [perennial-v2/packages/perennial/contracts/types/Local.sol](perennial-v2/packages/perennial/contracts/types/Local.sol)
- [perennial-v2/packages/perennial/contracts/types/MarketParameter.sol](perennial-v2/packages/perennial/contracts/types/MarketParameter.sol)
- [perennial-v2/packages/perennial/contracts/types/OracleVersion.sol](perennial-v2/packages/perennial/contracts/types/OracleVersion.sol)
- [perennial-v2/packages/perennial/contracts/types/Order.sol](perennial-v2/packages/perennial/contracts/types/Order.sol)
- [perennial-v2/packages/perennial/contracts/types/Position.sol](perennial-v2/packages/perennial/contracts/types/Position.sol)
- [perennial-v2/packages/perennial/contracts/types/ProtocolParameter.sol](perennial-v2/packages/perennial/contracts/types/ProtocolParameter.sol)
- [perennial-v2/packages/perennial/contracts/types/RiskParameter.sol](perennial-v2/packages/perennial/contracts/types/RiskParameter.sol)
- [perennial-v2/packages/perennial/contracts/types/Version.sol](perennial-v2/packages/perennial/contracts/types/Version.sol)


