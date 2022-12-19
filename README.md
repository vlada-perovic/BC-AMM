# BC-AMM
AMM ( automated market maker ) is implemented in Solidity ( 0.8.7 ) via Remix online IDE for 2 ERC20 Tokens ( VPT and MMT ). Adresses of tokens are hardcoded. Mint/burn of LP tokens and fees are not implemented due to simplicity. addLiquidity and removeLiquidity are implemented in a way to keep price constant. swapVPT2MMT,swapMMT2VPT are implemented to keep prudct constant - x * y = k. All contracts are deployed on test Ethereum BC - Goerli BC.

Address on Goerli BC:

VPT
0x77B829a682Ed71EF6D99F2Eec0B373770A64b519

MMT
0xc80E2d87C1Be040bf66557195d4CE8E194eEb14A

AMM_VPT2MMT
0x68CeEcD8d932f6a83E7c4aEdEf15f7FE5a7a08Ed
