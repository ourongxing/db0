# Changelog


## v0.1.6


### 🚀 Enhancements

- Add posgresql connector ([51823eb](https://github.com/unjs/db0/commit/51823eb))
- Support string templates for query ([feea30f](https://github.com/unjs/db0/commit/feea30f))
- Drizzle integration support ([#17](https://github.com/unjs/db0/pull/17))
- Add libsql support ([#25](https://github.com/unjs/db0/pull/25))
- Support multiple libsql exports ([#31](https://github.com/unjs/db0/pull/31))
- Support static placeholders with `sql` template ([378fe62](https://github.com/unjs/db0/commit/378fe62))
- Add bun sqlite support ([d6de297](https://github.com/unjs/db0/commit/d6de297))

### 🩹 Fixes

- **d1:** Support `__env__` for accessing binding ([2ef9d57](https://github.com/unjs/db0/commit/2ef9d57))

### 💅 Refactors

- Merge `db.query` into `db.sql` ([eef2417](https://github.com/unjs/db0/commit/eef2417))
- Use `createDatabase` ([84c52d8](https://github.com/unjs/db0/commit/84c52d8))
- Update drizzle integration ([74c909e](https://github.com/unjs/db0/commit/74c909e))
- **d1:** Throw a better error if binding not found ([#60](https://github.com/unjs/db0/pull/60))

### 📖 Documentation

- Add wip notice ([e7a551c](https://github.com/unjs/db0/commit/e7a551c))
- Initialize new docs ([c897405](https://github.com/unjs/db0/commit/c897405))
- **readme:** Fix links ([#52](https://github.com/unjs/db0/pull/52))
- Fix typos ([#56](https://github.com/unjs/db0/pull/56))
- **vercel:** Fix the connector name ([#74](https://github.com/unjs/db0/pull/74))
- Fix typo ([#108](https://github.com/unjs/db0/pull/108))

### 🏡 Chore

- Update deps ([0d47eea](https://github.com/unjs/db0/commit/0d47eea))
- Fix eslintrc ([6c5a07d](https://github.com/unjs/db0/commit/6c5a07d))
- Initiate docs ([16922ac](https://github.com/unjs/db0/commit/16922ac))
- Add vercel.json for docs ([3a45877](https://github.com/unjs/db0/commit/3a45877))
- Rename to `db0` ([61188b4](https://github.com/unjs/db0/commit/61188b4))
- Prepare for initial release ([459c055](https://github.com/unjs/db0/commit/459c055))
- Update dependencies ([52da7c2](https://github.com/unjs/db0/commit/52da7c2))
- **release:** V0.1.1 ([a177e68](https://github.com/unjs/db0/commit/a177e68))
- Add autofix ci ([32a43e3](https://github.com/unjs/db0/commit/32a43e3))
- Update dependencies ([e3f1828](https://github.com/unjs/db0/commit/e3f1828))
- Format code ([282c286](https://github.com/unjs/db0/commit/282c286))
- Update deps ([6fe166d](https://github.com/unjs/db0/commit/6fe166d))
- Update repo ([269efde](https://github.com/unjs/db0/commit/269efde))
- Update landing ([5fcdb67](https://github.com/unjs/db0/commit/5fcdb67))
- Update landing ([c17fa09](https://github.com/unjs/db0/commit/c17fa09))
- Add npmrc ([859cc05](https://github.com/unjs/db0/commit/859cc05))
- Update readme with automd ([303f138](https://github.com/unjs/db0/commit/303f138))
- Update docs ([ea29f15](https://github.com/unjs/db0/commit/ea29f15))
- **release:** V0.1.2 ([08713ba](https://github.com/unjs/db0/commit/08713ba))
- Update docs ([598e90c](https://github.com/unjs/db0/commit/598e90c))
- Update docs ([5eda18e](https://github.com/unjs/db0/commit/5eda18e))
- Update readme ([#53](https://github.com/unjs/db0/pull/53))
- Update autofix ci ([ecf97f1](https://github.com/unjs/db0/commit/ecf97f1))
- **release:** V0.1.3 ([52f012e](https://github.com/unjs/db0/commit/52f012e))
- Apply automated updates ([5760665](https://github.com/unjs/db0/commit/5760665))
- **release:** V0.1.4 ([7955c1a](https://github.com/unjs/db0/commit/7955c1a))
- Bump deps ([545f4f5](https://github.com/unjs/db0/commit/545f4f5))
- Release @ourongxing/db0 ([1532d4c](https://github.com/unjs/db0/commit/1532d4c))
- Use libsql instead of better-sqlite3 ([54b7f02](https://github.com/unjs/db0/commit/54b7f02))

### 🤖 CI

- Use conventional commit for autofix action ([#34](https://github.com/unjs/db0/pull/34))

### ❤️ Contributors

- Ou ([@ourongxing](http://github.com/ourongxing))
- @beer ([@iiio2](http://github.com/iiio2))
- Rishi Raj Jain <rishi18304@iiitd.ac.in>
- Pooya Parsa ([@pi0](http://github.com/pi0))
- Sébastien Chopin <seb@nuxtlabs.com>
- Neil Richter ([@noook](http://github.com/noook))
- Shoshana Connack ([@moshetanzer](http://github.com/moshetanzer))
- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Heb ([@Hebilicious](http://github.com/Hebilicious))

## v0.1.4

[compare changes](https://github.com/unjs/db0/compare/v0.1.3...v0.1.4)

### 🩹 Fixes

- **d1:** Support `__env__` for accessing binding ([2ef9d57](https://github.com/unjs/db0/commit/2ef9d57))

### 💅 Refactors

- **d1:** Throw a better error if binding not found ([#60](https://github.com/unjs/db0/pull/60))

### 📖 Documentation

- Fix typos ([#56](https://github.com/unjs/db0/pull/56))

### 🏡 Chore

- Apply automated updates ([5760665](https://github.com/unjs/db0/commit/5760665))

### ❤️ Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Sébastien Chopin <seb@nuxtlabs.com>
- Neil Richter ([@noook](http://github.com/noook))

## v0.1.3

[compare changes](https://github.com/unjs/db0/compare/v0.1.2...v0.1.3)

### 🚀 Enhancements

- Add bun sqlite support ([d6de297](https://github.com/unjs/db0/commit/d6de297))

### 📖 Documentation

- **readme:** Fix links ([#52](https://github.com/unjs/db0/pull/52))

### 🏡 Chore

- Update docs ([598e90c](https://github.com/unjs/db0/commit/598e90c))
- Update docs ([5eda18e](https://github.com/unjs/db0/commit/5eda18e))
- Update readme ([#53](https://github.com/unjs/db0/pull/53))
- Update autofix ci ([ecf97f1](https://github.com/unjs/db0/commit/ecf97f1))

### ❤️ Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Shoshana Connack

## v0.1.2

[compare changes](https://github.com/unjs/db0/compare/v0.1.1...v0.1.2)

### 🚀 Enhancements

- Add libsql support ([#25](https://github.com/unjs/db0/pull/25))
- Support multiple libsql exports ([#31](https://github.com/unjs/db0/pull/31))
- Support static placeholders with `sql` template ([378fe62](https://github.com/unjs/db0/commit/378fe62))

### 💅 Refactors

- Use `createDatabase` ([84c52d8](https://github.com/unjs/db0/commit/84c52d8))
- Update drizzle integration ([74c909e](https://github.com/unjs/db0/commit/74c909e))

### 📖 Documentation

- Initialize new docs ([c897405](https://github.com/unjs/db0/commit/c897405))

### 🏡 Chore

- Add autofix ci ([32a43e3](https://github.com/unjs/db0/commit/32a43e3))
- Update dependencies ([e3f1828](https://github.com/unjs/db0/commit/e3f1828))
- Format code ([282c286](https://github.com/unjs/db0/commit/282c286))
- Update deps ([6fe166d](https://github.com/unjs/db0/commit/6fe166d))
- Update repo ([269efde](https://github.com/unjs/db0/commit/269efde))
- Update landing ([5fcdb67](https://github.com/unjs/db0/commit/5fcdb67))
- Update landing ([c17fa09](https://github.com/unjs/db0/commit/c17fa09))
- Add npmrc ([859cc05](https://github.com/unjs/db0/commit/859cc05))
- Update readme with automd ([303f138](https://github.com/unjs/db0/commit/303f138))
- Update docs ([ea29f15](https://github.com/unjs/db0/commit/ea29f15))

### 🤖 CI

- Use conventional commit for autofix action ([#34](https://github.com/unjs/db0/pull/34))

### ❤️ Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Heb ([@Hebilicious](http://github.com/Hebilicious))

## v0.1.1


### 🚀 Enhancements

  - Add posgresql connector ([51823eb](https://github.com/unjs/db0/commit/51823eb))
  - Support string templates for query ([feea30f](https://github.com/unjs/db0/commit/feea30f))
  - Drizzle integration support ([#17](https://github.com/unjs/db0/pull/17))

### 💅 Refactors

  - Merge `db.query` into `db.sql` ([eef2417](https://github.com/unjs/db0/commit/eef2417))

### 📖 Documentation

  - Add wip notice ([e7a551c](https://github.com/unjs/db0/commit/e7a551c))

### 🏡 Chore

  - Update deps ([0d47eea](https://github.com/unjs/db0/commit/0d47eea))
  - Fix eslintrc ([6c5a07d](https://github.com/unjs/db0/commit/6c5a07d))
  - Initiate docs ([16922ac](https://github.com/unjs/db0/commit/16922ac))
  - Add vercel.json for docs ([3a45877](https://github.com/unjs/db0/commit/3a45877))
  - Rename to `db0` ([61188b4](https://github.com/unjs/db0/commit/61188b4))
  - Prepare for initial release ([459c055](https://github.com/unjs/db0/commit/459c055))
  - Update dependencies ([52da7c2](https://github.com/unjs/db0/commit/52da7c2))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))

