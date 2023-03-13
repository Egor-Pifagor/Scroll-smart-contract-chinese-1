# Scroll-smart-contract-chinese-1
// SPDX-License-Identifier: MIT pragma solidity ^0.8.4; contract FunctionTypes{     uint256 public number = 5;          constructor() payable {}      // 函数类型     // function (&lt;parameter types>) {internal|external} [pure|view|payable] [returns (&lt;return types>)]     // 默认function     function add() external{         number = number + 1;     }
