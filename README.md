# solidity-trips
1 - uint8 is not always cheaper than uint256
2 - Mappings are cheaper than Arrays!
3 - Elements in Memory and Call Data cannot be packed. There is no gas saving in solidity by using smaller variables in function calls and memory.
4 - Use bytes32 rather than string/bytes.
5 - Use external function modifier.
6 - Use Short Circuiting rules to your advantage.
7 - Avoid changing storage data.
