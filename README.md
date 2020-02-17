# solidity-tips
1 - uint8 is not always cheaper than uint256
2 - Mappings are cheaper than Arrays!
3 - Elements in Memory and Call Data cannot be packed. There is no gas saving in solidity by using smaller variables in function calls and memory.
4 - Use bytes32 rather than string/bytes.
5 - Use external function modifier.
6 - Use Short Circuiting rules to your advantage.
7 - Avoid changing storage data.
8 - Deletion
9 - Storing data in events
10 - initialization is expensive
11 - fixed size vars (arrys) are cheaper than dynamics.
12 - Initializing structs like this:
  Mystruct storage mst = Mystruct();
  mst.x = 0;
  mst.y = 0;
13 - don't call libraries
14 - use modifier instead of using require inside the function
15 - internal is cheaper than private





########### 
1 - what is pure
2 - what is interanl and ...
3 - read famous contracts
