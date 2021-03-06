# @actions/core Releases

### 1.2.2

- [Fix escaping for runner commands](https://github.com/actions/toolkit/pull/302)

### 1.2.1

- [Remove trailing comma from commands](https://github.com/actions/toolkit/pull/263)
- [Add \"types\" to package.json](https://github.com/actions/toolkit/pull/221)

### 1.2.0

- saveState and getState functions for wrapper tasks (on finally entry points that run post job)

### 1.1.3 

- setSecret added to register a secret with the runner to be masked from the logs
- exportSecret which was not implemented and never worked was removed after clarification from product.

### 1.1.1

- Add support for action input variables with multiple spaces [#127](https://github.com/actions/toolkit/issues/127)
- Switched ## commands to :: commands (should have no noticeable impact) [#110)(https://github.com/actions/toolkit/pull/110)

### 1.1.0

- Added helpers for `group` and `endgroup` [#98](https://github.com/actions/toolkit/pull/98)

### 1.0.0

- Initial release
