# Change Log

## 0.4.0

- Made `Commander` `Send`able, means actions must be `Send`able as well.

> 0.4.1
> - Added `action_result` fn to `LineResult`

## 0.3.0

- Added `root()` to `BuilderChain` which short-circuits back to the root.
- Added `at_root()` to `Commander` to flag if currently sitting on root.

## 0.2.0

- Actions now produce a specified return type, defaults to `()`
- `LineResult` has variants pertaining to the outcome of `parse_line`
- `LineResult` is public