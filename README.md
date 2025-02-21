# Off-by-One Error in VHDL Counter

This repository demonstrates a common off-by-one error in VHDL code and its solution. The `buggy_counter.vhdl` file contains a counter that doesn't correctly reset when it reaches its maximum value, leading to unexpected behavior. The `fixed_counter.vhdl` shows the corrected version.

## Bug Description
The buggy counter has a flaw in its reset condition. When `internal_count` reaches 15, it should reset to 0. However, the original code had a subtle error in this condition resulting in incorrect behavior.

## Solution
The solution is provided in `fixed_counter.vhdl` which demonstrates a simple fix of the resetting condition within the counter.