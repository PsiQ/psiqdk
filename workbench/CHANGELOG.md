# CHANGELOG

<!-- version list -->

## v4.38.2 (2026-04-23)

### Bug Fixes

- Bug fix in HermitianWindowFilter
  ([`5c0f7b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c0f7b971b9fbbd93e06b362aadf990aa72f72a8))

- Fix QFTAdd/QFTSubtract Qubricks for integer rhs
  ([`43c4d53`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43c4d53752ff453fe038d4aa88740432b6770610))

- Fix QFTAdd/QFTSubtract Qubricks for integer rhs
  ([`ed8d372`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ed8d3727186134554630cc6e9bde9a4c2cfbdf94))

### Chores

- Refresh example and tutorial notebook outputs
  ([`aadd61f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aadd61f8008049dfa767984e081ca583e81f8389))

- Refresh example and tutorial notebooks (outputs and selective warning silences)
  ([`3899e45`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3899e45edf2ebf3c4fabf2850b582872fff57ed2))

### Continuous Integration

- Treat example notebooks warnings as errors
  ([`964704b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/964704b1f2606ff4595d3f0d55a7866220678eba))

- Treat example warnings as errors in the examples test suite
  ([`76fac4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/76fac4d11d4b6fc728aa50b7e508e094add58452))

- Treat example warnings as errors in the examples test suite
  ([`87b03b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87b03b934c523bdc704c2b0ae1efaf798ff42608))

- Updated examples/conftest.py to match latest in WBA
  ([`3f4e3dc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f4e3dc6afc9b043b063cf3f502b4b52f2e72465))

### Documentation

- Clean up API docs of exposed Qubricks
  ([`ff16473`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff164731d6e59b9273b83d7e0ee7f18bc5b20dea))

- Make pages missing from nav and incorrect anchors into errors
  ([`7507d79`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7507d795d2c3219c3beb6094507349a17f86c7f2))

- Make pages missing from nav and incorrect anchors into errors
  ([`a780f1e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a780f1e4f3e1f90011b7d00bb8bf726657eaad44))

### Refactoring

- Refactor qpu methods to act on specific filter types rather than pass down filter chain
  ([`a278402`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a278402cfa85f10249576203d2a52c35f4620c69))


## v4.38.1 (2026-04-21)

### Bug Fixes

- >>qasm-export>> handles zero-target gates and ignores nop
  ([`b251766`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b25176662d1ec52968637e014ebfa200d4714389))

- AST-2050 >>qasm-export>> handles zero-target gates and ignores nop
  ([`ede5e75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ede5e756caff5685fb866bf47dcf1c5da363ec56))


## v4.38.0 (2026-04-20)

### Features

- AST-3556 CUDA-Q: Improvements to peek_read_probability() and measurement
  ([`e8631ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8631ee261bc7330ac8a56e86e52ec7e70a1202d))


## v4.37.3 (2026-04-17)

### Bug Fixes

- Update format_stream to output runnable code in asm format
  ([`0272dce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0272dce71924259f548a7be76f6731eeed039df0))

- Update format_stream to output runnable code in asm format
  ([`7ece2c6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ece2c64f240a0ed98ec5d0c1b0fc082cae62a6c))

### Chores

- Use FutureWarning for deprecations
  ([`c3af8d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3af8d37a0392c7acb7ab193f6f1ee1d2acd72ea))


## v4.37.2 (2026-04-17)

### Bug Fixes

- Migrate from GoogleSelectOptimized to BinaryTreeSelect
  ([`a8c5ac9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a8c5ac93d6fde1ecff5a8ace4539cb1ab8f213d9))

- Migrate from GoogleSelectOptimized to BinaryTreeSelect
  ([`9b4bf75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b4bf75650f1f49d41e4bcf20c76016e4a88db1f))

### Continuous Integration

- Fix broken changelog generation
  ([`faa7986`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/faa7986d2d28a3e336b7446382f94ca2d43ded75))

- Fix broken changelog generation and regenerate
  ([`755fef0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/755fef0242fdb9bf9c06e23fe47c4675cf777260))


## v4.37.1 (2026-04-16)

### Bug Fixes

- Resolve merge conflict
  ([`75e64ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75e64ba2941a0e2cbfeb2a5eb04350004993f5a9))

### Documentation

- Modernize example_rotation_api.ipynb example and mark Rotation Qubrick as experimental
  ([`bd624eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd624eb2c9ef42eb9114d6cccc78efe161a79b69))

- Modernize example_rotation_api.ipynb example and mark Rotation Qubrick as experimental
  ([`894eb97`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/894eb97e665f4d89dbe4b857a948c53759d0bf07))

### Features

- Resolve "Revert QFT into Hardcode"
  ([`bb4b87c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bb4b87c8082ccee28f5b6d1a4f90a6e819060d01))


## v4.37.0 (2026-04-14)

### Bug Fixes

- Add abstract classes to average qubit estimator
  ([`3275431`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/327543190115f5a4c41193f8b8dbb717607a6ecb))

- Categorize composite filter and device filter
  ([`edbfa92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/edbfa92e6cda835a49df96739c759cb400b10456))

- Update IMS model to not be simulation or device for now
  ([`a5f7991`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5f79913594cbaed9cb631dc9b6272d09d5be865))

### Features

- "ast-2834 Add Filter Base Classes"
  ([`447c225`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/447c22510521a4cefd97636c58daa4d076dfd13f))

- Adding base filters initial implementaiton
  ([`d4e9b0f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4e9b0f80776e8ff745c24c8840a32beee0c04ab))


## v4.36.2 (2026-04-13)

### Bug Fixes

- Add edge case to avoid swap
  ([`aa36ed7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa36ed72f4d31f9df48647d75fc0df5ee345188c))

- Delete other reference for naive phase gradient
  ([`46466cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/46466cc8ef14c008d0bcc374ba95260f7ee26304))

- Delete phase gradient example notebook
  ([`4a808f2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a808f29dd27a5539014d28e0786871eb604929b))

- Fix interoperability bug causing warning
  ([`0be14d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0be14d6306ee681f5c37619683cbe542e19e4676))

- Fix interoperability bug causing warning
  ([`c855ce1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c855ce12f53626cbf07f151af5e335b69efc3d9c))

- Flip control order, fix swap code
  ([`0d94350`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0d94350d8f2b60151d5e7d785fdc983d927a86c0))

- Remove symbolic test for PGA error reporting, remove catalyst test for QFT
  ([`569a81e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/569a81ee17fb93fa3a1e587c10cd499335884ba6))

- Revert QFT code, delete phase gradient Qubricks and tests
  ([`57599ff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57599ffda27fde070cf000368dcb4c1f87d3339b))

### Documentation

- Add Units support to docs for reflect theta
  ([`22ea984`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22ea98420c88e7e988ecd12b7267e97b54a3f560))


## v4.36.1 (2026-04-10)

### Bug Fixes

- Ppr gate bug when called with identities
  ([`b464f80`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b464f80cf3f924b2ce616bd67c6ec51e7f84f1e7))


## v4.36.0 (2026-04-10)

### Bug Fixes

- Fixing linting
  ([`8debb3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8debb3e0e9c70827330298452729ec28b8b96f40))

- Ppr bug in unitary filter
  ([`0a29b49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a29b495a70b9e6c4cd9e8d8f462e4f2e58bcce3))

- Qpu.pps can return probability slightly > 1"
  ([`1c6b1ff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c6b1ff8b3493956f5c00718d488e5e3b538d8da))

- Remove errant change in qpu
  ([`6f04c87`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f04c87c64b91534777d4f50006b13519795a1b8))

- **path**: Minor import path fix
  ([`cb4f16d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb4f16d8f9f61b1104f6407ebb4e6e47dd704709))

- **timing**: No longer measuring witness
  ([`dd8a8af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd8a8afd74ec1d16dd44af52f81f1fbf63884916))

### Chores

- Clean up latest changes
  ([`7c479eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c479eb4ba4598d3c1dcf3a6a29025a36f9925bf))

### Documentation

- Document qpu.enable_qubit_allocation_debugging
  ([`c2d75ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2d75eedb2b0b260fa3f48a7ab3532a1e84eabee))

### Features

- Adding check, analyze and process to basic filter
  ([`4f316b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f316b43236e4f493ae108506825131fb2391287))

- Adding clean ladder with new filter
  ([`997ba49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/997ba49116cc8ed570bf3e4f0a27c2d35846946a))

- Adding example filter
  ([`83932e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/83932e3b193e8cc0b64355fdd8d3487da5cb8a3b))

- Adding the By Operation Type Filter
  ([`e4cfd48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4cfd48dd6276b58fa79dcc6b7a8b7b47617bcc7))

- Document qpu.enable_qubit_allocation_debugging and add flushing if this check is enabled
  ([`30de0cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30de0cd07e484712c4be55c1c2d35e7b5263f1e3))
- Prototype for simple filter test
  ([`1ac34a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ac34a26c31921b7f109883c025730d57d4b53e9))

### Performance Improvements

- **cache**: Add op cache for speed
  ([`a503920`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a503920ef5606f0d97f64b104f47dccfbc1431cf))

- **filter**: Another filter without cache but with index checking
  ([`27cb66a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27cb66a732c3c9d040b0d9ee3366a4df9bbc22f6))

- **filter**: Speed up filter with index scanning, v1
  ([`a7a78c6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7a78c661a2cd2a31b6ee9d7023dd114db4f34b2))

- **prototype**: Testing filter prototypes
  ([`0f216a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f216a2bd4faeb59e7946a806d59fe7e4e20a186))

- **scan**: 10% speedup for op scanner
  ([`32738b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32738b45951d0e5dc4d5e32d64a2380674319e3c))


## v4.35.5 (2026-04-08)

### Bug Fixes

- Updated unitary filter to properly handle zero target gates
  ([`42208d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42208d7c7eff8d6f216b81b991c355e2d8a6d96e))


## v4.35.4 (2026-04-02)

### Bug Fixes

- Round rotation angles in diagrams to 3 decimal places
  ([`8a6488e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a6488ef2519034d0362b6e92bc59499fdaa3fbe))

### Chores

- Add removal version 5.0.0 to deprecation notices
  ([`2f2fdf0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f2fdf068bc17a868f77f2a2529e05ce0fa655ed))

- Make sure .pyi files are included in wheels
  ([`0fef1c6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0fef1c60d67238033aa3e4b1801bef25a727cb12))

### Continuous Integration

- Added project-specific webhook for release notification
  ([`78b1116`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78b1116dc9ffa2ef6448aaa5f187befed29a8202))

- Revert cp to mv for post-build artifacts
  ([`a2c7a28`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a2c7a2801ef0090612dad1e15d6303ff57448788))

- Updated dev-ops/common include reference from 0.2.0 to 0.2.1
  ([`de7a7b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de7a7b40a62b26ea274449f6f9407b14d6a54a98))

### Documentation

- Add IntelliSense/API docs for compute method of qubricks
  ([`0c8937e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0c8937e347c66014f7225223c20d6ae3f63ae0b6))

- Add QubrickCosts to numeric QRE tutorial
  ([`666376b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/666376bdd65152f0448b8fe1b34dd300bae90881))

- Add static images for circuit designer howto
  ([`bfaae0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bfaae0c754f559849e05c885f0872bbe62823d21))

- Add unpkg.com to IGNORE_DOMAINS
  ([`7ae03c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ae03c2b320c1e6dba9a3b3bc4fd4aae1740ab1a))

- Fix typos + other changes suggested in review
  ([`e776f81`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e776f81f086e783e322df87a5bbd2e375adbf585))

- Include static svgs in Circuit Drawing howto
  ([`8334159`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/833415971e891c3437a8ca1ac83e2e4e1844c087))


## v4.35.3 (2026-03-30)

### Bug Fixes

- Fix small bug with parsing generics for DI container
  ([`cd11d89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd11d89c148254c58a3698922867c581a331f33a))


## v4.35.2 (2026-03-26)

### Bug Fixes

- Updated build job to copy instead of move from dist
  ([`7ba1244`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ba12446be7dcde9ec09d52fdd8cc9ec1713777e))


## v4.35.1 (2026-03-25)

### Bug Fixes

- Update ci to build all images on tag
  ([`dac359d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dac359db78612aa4c3510d84e2c1870e0b9ed4a3))


## v4.35.0 (2026-03-25)

### Bug Fixes

- Fix WB -> CD export for Qubricks with no inputs
  ([`b66dd63`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b66dd639a7a914f9241f252528d4d59b8128aea8))

### Chores

- Bump version to 4.34.2
  ([`981ef9c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/981ef9c459b49a25677d9b4134221d9b65d8fbbc))

- Remove do_boxes from Qubrick constructor arguments
  ([`0c1b5ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0c1b5ab8048868c2f13a093a687686c7c773fb38))

### Continuous Integration

- Deprecate old webhook URL variable
  ([`a52f510`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a52f510550f80f537fa13bc5b93eebebecb7ea8c))

- Fix broken image matrix on test:macos:extras job
  ([`8b61f5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b61f5ceecee534c3181f0a3646812cf9ef70068))

- Fix issues in test:macos:extras job script
  ([`9a088fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a088fd34fcad004ffc6f7aa33a40a98b97501af))

- Overwrite rules to test new matrix setup
  ([`c442027`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c442027cebc8b2bb36b4cef21452890409338f8c))

- Re-enable default rules for test jobs
  ([`275a235`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/275a2356e3ba36790fdf8275b08186603ea5ac6c))

- Removed commitlint job
  ([`35a1d9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35a1d9be3999f0f379e57437dc8e85b6f0487745))

- Updated dev-ops/common include reference from 0.1.6 to 0.2.0
  ([`52e279a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/52e279a45370da361374a35c7d316300923727c2))

### Documentation

- Add instruction about installing graphviz
  ([`5b10b8d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b10b8d1834284051b81a984a70001555bae6834))

- Fix release notification channel name
  ([`21a29a9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21a29a93f2087e1b1d2bdc2dea247c18b1b6e4f5))

- Move items from private docs to examples
  ([`af4dedd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af4deddf35a2db143959790112059824355d3791))

- Remove info about private docs from configs
  ([`df3b33c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df3b33c9e79de3221f5ab59f3dd94045057f104f))

- Unify internal and external docs builds
  ([`be16b89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be16b8934b655cc03777e1d972cf760b30c6252c))

- Update graphviz instructions
  ([`a1c3dfb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1c3dfb356cf4054821d157284f0b92c1891e6db))

- Update Slack webhook variable reference
  ([`2d61325`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d613258e7dcefde5e2949a75cebc7f47aa852e7))


## v4.34.2 (2026-03-19)

### Bug Fixes

- Remove IP-sensitive QPU Driver model
  ([`0463ad6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0463ad67eea447f78700c37a3f613b6fa7f76093))

- Remove unneeded parents from function
  ([`65579fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/65579fd982e4ff0d519852eed213f9a7d35b8c3e))

- Update DI logic to handle more complicated interfaces
  ([`4aa4273`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4aa4273667e203c2d63f245986c7f976cd12353a))

- Update IMSModel docstring
  ([`5c7c95b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c7c95bb80ca83964aaa43033daa96c25b8623f6))

- Update interoperability code to work with more complicated generic types
  ([`59c73c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59c73c3b4957ab71cb4efcba6baa3003c12ec602))

- Update logic for subtype specification
  ([`42c7c1c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42c7c1cd7ae63da99dd8b6a7001d31e6803def8b))

### Chores

- Add tests for the new functionality
  ([`d741bce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d741bce0823588d318a895ba000c34e5f742c9ea))

- Address reviewer comments
  ([`6111b77`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6111b777da3804b984af2dd8c3d6877d93bbafdf))

- Bump version to 4.34.1
  ([`8fdb845`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8fdb8454e4e6fc7a7a112019a7eb98f46d1ae480))

- Tidy up old code
  ([`983de97`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/983de97674bf8200e51029978982ab799467cd6d))


## v4.34.1 (2026-03-18)

### Chores

- Bump version to 4.34.0
  ([`a3fd14c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3fd14c9ac6d1dcd2bf6e7be1f86cfa8f64e073e))


## v4.34.0 (2026-03-18)

### Bug Fixes

- Address reviewer comments
  ([`7f1d631`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f1d631d9c07b02f346d5fe22764214f0e2de99c))

- Fix converting programs releasing rotation catalyst to QREF
  ([`b9fc7f6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b9fc7f61ebea5f2414796b464589fa05ad0441a0))

- Make symbolic catalyst QREs more robust for multiplicities of pi/8
  ([`7d11b8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d11b8c5d5748e373f3dbec8db97d4d639a66304))

- Remove debugging import
  ([`cb77aa6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb77aa6571b4bddfd485186fc833ab493f0f65f1))

- Remove networkx as default dependency
  ([`a5b60c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5b60c2f51d0265baa8565fddb10e6c2f8b36627))

- Remove unused imports
  ([`c580a27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c580a279904ddedda02ea6e24c50f0d0e4d768d9))

- **cuda**: Add >>cudaq-sim-v2>> for testing
  ([`8848d82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8848d824edb930ed74ffd11b77b8d03762ffb55e))

- **cuda**: Comment out second run
  ([`9964ff5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9964ff5c7e827a69ec96aa49b8c66163231fc2f0))

- **cuda**: Iteration on new kernel
  ([`796be55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/796be55daf4c305af916f152c66a8c21f7e19110))

- **cuda**: Iterative fixes for ops
  ([`4a1bd4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a1bd4b406351a8011db0dc6735148a4c33ea71b))

- **cuda**: Iterative fixes for ops
  ([`8ee2880`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ee28800cfc3c029dc801270f6f18e658a57468b))

- **cuda**: Just small cleanup
  ([`419af45`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/419af45b6a423d24a1dd1adaa513fa9ac85886c5))

- **cuda**: Merge fix for iterative car/les changes to kernel
  ([`15a689b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/15a689b231105a8b575ea1df1839ce9936a77901))

- **cuda**: New kernel logic
  ([`bbedf00`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bbedf00b38209eb1cfde9b51a264dd80bafdfaed))

- **cudaq**: Make CUDAQ a soft-import per AST-3457
  ([`9d011c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d011c91d4454afd039d6b6e9489bb55e6fb58b4))

- **test**: Add test file
  ([`acdab19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/acdab195a959c909e07360c8abb8ac132972353e))

- **test**: Test now checks the state vec
  ([`b7133f3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7133f3a74482100a461ce705909728c8ea249bf))

- **tests**: Kernel and speed test adjustments
  ([`41941a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41941a8cea9f8df824ca74610afded4247c800c0))

- **tests**: Small fixes to speed testing
  ([`05bbd1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05bbd1ae2add0367198b1311c6a757f67378e492))

### Build System

- Fix networkx dependency
  ([`740f870`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/740f870ea64f9bbb26ed1e900144c9cf29b5c7ab))

### Chores

- Add specific warning text to ignore
  ([`efe45ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/efe45ac2c3138dfe7a38412a8a45bc9769752403))

- Add version to deprecation warning
  ([`0223ebd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0223ebd42967b51c0e58fe96b2a7ff76d49f698f))

- Address Ian's comments
  ([`2fcbfd9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2fcbfd938d45804ed52cf0c9ee91b33e208a1255))

- Address Michal's comments
  ([`2b8d690`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b8d690b4737c10f809b77084472350c65cf903e))

- Address Michal's comments
  ([`aaaaa9e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aaaaa9e9a5d351a7337ab6a1530f36c1d7b3e894))

- Address more comments
  ([`d031289`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0312892d60237f40dd9a750d4aae950089f0ca0))

- Address more comments
  ([`46b8d22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/46b8d22d0be00e891a3e8805c003b0a8a214e5c1))

- Bump version to 4.33.7
  ([`34aa05e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/34aa05e45bbd75636e8156397526cd9cd878b952))

- Improve handling of warnings showcased in tutorials
  ([`56afd10`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56afd102b935ddc394fe46532a78f699935f6344))

- Remove a few more warnings
  ([`1c31805`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c318056dd2018cad9e33a58a806ba6bc7a65da7))

- Remove CODEOWNERS
  ([`2987f19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2987f19b67b8326a6b9d009e66948bc5bfda638a))

- Remove global warnings filtering from QPU
  ([`acdbad0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/acdbad0090330eacb6f7f4d175f6195649e77254))

- Remove psi-basquiat from dependencies
  ([`e4c0aa7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4c0aa71ea295fb4e01651681c3a51c776cdf8ae))

- Remove unneeded commitlint config and pre-commit job
  ([`7e49618`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e496185cc46c409632a7d57a98c3acb2dc58393))

- Rename condition_mask argument of Qubits methods to cond
  ([`4be28b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4be28b4ff11fee8e014e81986756b9809b103c5f))

### Code Style

- Fix formatting
  ([`f6afd5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6afd5eb38fc9f0b5e84b5e7b7ec6394e353088e))

- Formatting fixed
  ([`e6ffdec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e6ffdecff02dfc37c8b89dedc70d0cf136f3eec8))

- Tidy-up imports
  ([`5c4814f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c4814f7fc94439b70e08141c591df3ce7635eb5))

### Continuous Integration

- Add deploy stage for docs:deploy jobs from construct/devops
  ([`dbdf4d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbdf4d7da0767de8e11a67fc5fd9b8cea8d9d93f))

- Add missing version bump config to semantic release
  ([`5ff112a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5ff112a212e6ff66be65f017c3a12cc3429559b7))

- Add semantic release config, fix version, delete set_version.py
  ([`fc948be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc948be46aeaac76a3c99341e579524553da0cf1))

- Bumped dev-ops/common dependency to 0.1.1
  ([`8948487`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89484876ccdce1fe495043b323c2c3d988ad4d6d))

- Cleaned up .gitlab-ci.yml for new pipeline config
  ([`1d10c78`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d10c7800372d3e7859ad185359e91ab85bea7bb))

- Removing skip_on_version_tag and removing construct/devops include
  ([`526164b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/526164bb760c91253c771647af5b7ebe51f8f307))

- Switching to centrally defined release jobs
  ([`d5deb25`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5deb2568b741d3d002a60f960cebf13613520bd))

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0
  ([`7fe76a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7fe76a31cd2880eddf8a9e8a0414addaf6e33d0f))

### Documentation

- Add 'Advanced Gates' tutorial and docs map
  ([`d0dcb98`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0dcb9800b360cc3942c8c33671fe5184d108ce2))

- Add 'Basic numeric QREs' tutorial
  ([`c40e97a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c40e97a5fa4edfedf94973a52c7081faf9d238cb))

- Add basic docstrings to QPU ops.
  ([`cc21252`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc21252f5d6b29179c1a3e926e35b3c8c6ba8a52))

- Add basic numeric QRE how-tos
  ([`1eef3f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1eef3f4ec6fa518dbb9feb4d06bc387b93100089))

- Improve API docs for ppm and peek_ppm_probability
  ([`8d0874a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d0874ae46c7d4bf63c401642184eb379727dea7))

- Place comment about QPU_op where it should be
  ([`6f2b259`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f2b25926b9e5ae75fa40242c781eb090014b729))

- Remove reference to igraph in example
  ([`0a0a7c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a0a7c37a222329cfd34e276f3f3cf6bfe1fc67a))

- Replaced commitlint README section with MR title linting docs
  ([`23e328b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/23e328b2a8c944975971204106b2f55560705816))

- Update comment
  ([`c04a3a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c04a3a48622109bc2eee0c07221a5512e365735a))

- **api**: Clean up API docs
  ([`9746ee3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9746ee3690c5ee856d722359e0c10f519e3d7682))

- **wip**: Outline CUDA-Q simulator tutorial section
  ([`fd169a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd169a66f5c0431d34aabe48de9046f4bd21e6e0))

- **wip**: Outline CUDA-Q simulator tutorial section
  ([`a00e196`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a00e19641371b579c0488ea86f5b6a8dd7ec470f))

### Features

- Draft filter
  ([`e4e3884`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4e388412bf3110e422e5ceee43594415272485b))

- Enable AV comparison in assert_resources_equal by default
  ([`4f80857`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f8085736828a97197fdb622dc9a11c161d67522))

- Implement parsing of box close and box open events
  ([`9af63b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9af63b39905274f3d202c386591ae48ddc1ea217))

- Support special angles < 45 degrees in symbolic rotation catalyst
  ([`499b2d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/499b2d726906082721f42905ec082e72d81c70e9))

- WIP initial functions needed for cudaq filter
  ([`90dcf7f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90dcf7fc615f9ed5b64bfaeac2f59e009bcd09ea))

- **cuda**: Add mini kernel test, and lots of mess
  ([`a48bac7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a48bac726e201e605afce610ad0ebf129a6e4f8e))

- **cuda**: Early prototype and speed test iteration
  ([`943ea32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/943ea32f0ca2297d68b06bc51e13330d56bc5b93))

- **cuda**: Iteration on Construct CUDA testing
  ([`252b4bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/252b4bd1299885b39a5b507e5d76a2df9ba2b9a9))

- **cuda**: Iteration on the cudaq sim filter
  ([`ffe2967`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ffe296782897299fece5a639787d88312d5bbe95))

- **cuda**: Iteration, integration of filter with static kernel sim
  ([`aabb6b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aabb6b7b35992f51bf7e009e40ae86e9920234d0))

- **cuda**: More iteration and fixes
  ([`487bd1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/487bd1aa3b9a76b8b573308cb6f07641ef3779ec))

- **qft**: Add native QFT
  ([`affc1c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/affc1c5ba01f610cc4ea89f6d6a265359d58915a))

- **test**: Update from car/les to test #1302
  ([`9057199`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9057199e5b7928d0c15bcd9bb15052b2716b176a))

### Refactoring

- Add helper functions serving as type guards
  ([`3987132`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3987132efb93dc2f3228aea702a19aaa848a52c8))

- Add type hints and minor style changes
  ([`5487cb0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5487cb06a0c40320b7170c066af118b9c9467d9d))

- Get rid of unused if statement
  ([`40b0be3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/40b0be3c0e3121346e75a111f5a7dc2a2113d50d))

- Remove known_discrepancy marker for RotationCatalystHandler
  ([`4354610`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4354610df1d2acd14c22b0ca9e331919c3b9b9d6))

- Remove unusd check_and_fix_op function
  ([`406732b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/406732babd097dde204d7a90992a75cc57cc110c))

- Rename _has_masks to is_pauli_product
  ([`c67e9a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c67e9a494539d97c0c61bf4a16d1ab4d3b7e10f3))

- Rename op_labelid_to_label to op_label_id_to_label
  ([`3deaa1f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3deaa1fa234a7edc22b0ee9496dda150cc893b18))

- Simplify expressions for number of pi/8 and 3pi/8 phases gates
  ([`e8789cb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8789cb3db7d5a02f879d1a8ed23a566df1abc46))

- Turn QPU ops into new style NamedTuples
  ([`4c57d46`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c57d463dcc4fc349f017bbb8665bdb0771d4874))

- Use op_label_id_to_label instead of op_labelid_to_label
  ([`6ac0e7d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ac0e7d5d11a9b657346aed2997d671f8168cd3e))

- Use typeguard helpers
  ([`7d5a5c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d5a5c37a9a2c94a9a09e42e541bb04d4609007d))

### Testing

- Add tests for converting program with boxes to CD
  ([`9399cac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9399cac4768a9915d4574f91c0469801b841e784))

- Enable AV comparison in symbolic rotation catalyst tests
  ([`3428b03`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3428b03341a910400ed42a7d2cd7453c0c37d2be))

- Extract logic for constructing 3 symbolic rotation catalyst fetches to a separate function
  ([`f2bfb68`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2bfb681957688fd6bf8bea763926ac7fbf7df43))

- Optimize symbolic rotation catalyst test cases
  ([`5963bef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5963bef22f32093e3fa0c274f753ab2c57c8e279))

- Rename fixture and clarify why we use 3 fetches
  ([`0ee3c30`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ee3c303b2a74b56ddfa38d8e7a339185b6b11c7))

- Skip dag-related tests if networkx not installed
  ([`3723b05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3723b05e80702ea71f2a6c801102a8a519a09ba4))


## v4.33.7 (2026-03-05)

### Bug Fixes

- Add missing type-checking import
  ([`9227ec7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9227ec7c23f21db7745ced392dbfd14d692098fd))

- Add tests and a missing compute in qubrick
  ([`7798d99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7798d99afd1274c4aa77c44ac61083071874ecfa))

- Add type checking import of construct_tools.Circuit
  ([`fd0339d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd0339da2546d45a0b2b7ac3f9c883e5d3e64a4c))

- Edit docstrings
  ([`2496b7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2496b7a5d7e4216e8d2a0396b046a13eb7f813aa))

- Fix register sorting
  ([`59c0a6c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59c0a6c7f08086fb4c0213bd8f4513ba98821367))

- Make expand default to False
  ([`3ba2274`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ba2274cd6d10a0f71038942181722060a5b8250))

- Make imports from construct_tools optional
  ([`9a44a47`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a44a47801fa32b2386964ba7bc482dea7a00dcf))

- Minor fixes in get_dag_from_qpu
  ([`b5c372a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5c372a3c6150465b2ad01f9ae25fcc6b4b21216))

- Remove incorrect TYPE_CHECKING import
  ([`dd5269b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd5269bbb12a6ab6b638e2c06f2276e62e43d8fb))

- Remove unnecessary option for dags progress bars
  ([`0f61c00`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f61c00c8506b77ab9ab9458e09fca30de778876))

- Skip alloc_ref and free_ref in register tracking
  ([`dfc2612`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dfc2612dca419b1d8f6695e52b1fb55dd83f8211))

- Use correct action when constructing subroutine enter event
  ([`db8b500`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db8b500097ef33d5a5599fe23452637b16256fdd))

- **cicd**: Trivial change to fix build lint error
  ([`baf188c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/baf188ce22563ffd180cfcfa1bfe1852bc174eac))

- **cicd**: Trivial change to fix CICD lint error
  ([`a52a2b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a52a2b4ab249f48c206915ac3891f62ccd42f940))

- **compareEQ**: Fix the == compare to be efficient for all types
  ([`2b5ef8a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b5ef8aa05d1557d248ed80b8118afc9ddeddec6))

- **docs**: Add text per MR feedback
  ([`2b92b24`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b92b2440ca5be5ecb1d1081284c52fab9182b94))

- **MR**: All MR feedback addressed!
  ([`dfe23a1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dfe23a141d829f94e271aef4aab9fdd0a9e961a5))

- **MR**: Fix per MR feedback
  ([`7d9473e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d9473e19fdca70c7b97a535e44c749b5fc364e3))

- **MR**: Fixes based on MR feedback
  ([`5ebbbd8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5ebbbd8221e7dca14dfad0327334cd4dc96d950a))

- **MR**: Fixes per MR feedback
  ([`64dcf2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/64dcf2f4d8f9b3dba50f42dfed99a4dfa13078a6))

- **MR**: MR ideas addressed, first pass
  ([`343d85f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/343d85f14704a7ef769fd261290e9ef734ea38af))

- **MR**: Paramaterize test
  ([`ca36d8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca36d8cec990301509295210738894aab9a697c8))

- **MR**: Respond to all MR feedback
  ([`c40b752`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c40b7524a2b4b7eb4a3d89c34c3f7955f629a0f7))

- **MR**: Robustify witness removal pr MR feedback
  ([`eeba9c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eeba9c55c4077aa1d67a28227e2b713367f7a859))

- **simplify**: Remove special cases and fix a test
  ([`5071385`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5071385007523986721b8edbcbf075aa2646f834))

- **unitary**: Fix per MR feedback
  ([`b04a039`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b04a039d08c0b4d700e80f32b72c64dcc2957a85))

### Chores

- Add cond_reg api docs (with deprecated note)
  ([`33e67b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/33e67b317e8a0173a27f29420212277bf4d24f9c))

- Add construct_tools to examples group
  ([`5945d6a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5945d6ab486382af1b9aaa122b5fb66c437243a4))

- Add optional dependency on construct_tools
  ([`7c9fdb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c9fdb4f6186400b8482f2046eb2b70e40a6ffe7))

- Bump version to 4.33.6
  ([`a17323f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a17323f8e3852ce6516ba5ac26e31fa67f71b8ab))

- Regenerate lock file
  ([`b5b590a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5b590aa695e53626f344dc0d72cb8bd7b5d0b63))

- Remove dependency on igraph – stage 1
  ([`8768027`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8768027eabc190e51c9165dee25b719d5cf1b071))

- Remove igraph codepaths
  ([`c9ffa5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c9ffa5c43be4211139e7af939d55a8a17ad8f947))

- Remove temporary files
  ([`68c9549`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68c9549ea293ce440aaf3ef3b207189711938e08))

- Replace use of qpu.metrics with resource_estimator in new_tutorials
  ([`781b9c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/781b9c130e017ce772df7aa5b9af9428f470feec))

- **review**: Apply 4 suggestion(s) to 2 file(s)
  ([`9c88e61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9c88e61ef63e38051b2be5652e718cde79d841df))

### Code Style

- Apply formatting
  ([`9f19802`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9f19802ba475e283deed5ce64aea9e1ac71b671a))

- Improve formatting
  ([`69b3193`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69b3193a5283260654d4e23fb21b1bc733c7e00a))

### Documentation

- Add example notebook with CD conversion
  ([`1906085`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/190608563e28a34acc47e9e379ed1f09eedf8ef1))

- Fix reaction depth example
  ([`dc4eae0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc4eae0559d3f51301a5e0fd7b3c5bbd38cb8232))

- Fix typo in docstring
  ([`8cc6a34`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8cc6a3427c6690754cccffc406a9e602d43c47cf))

- Refresh notebook
  ([`3460a1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3460a1adfb81654fd460c92253ca8fea64cc33b4))

- Update WB -> CD notebook to correctly discuss expand kwarg
  ([`11c6c3a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11c6c3af60e68703938fff49449a30d90487d503))

- Wrap Qubrick labels in \\text{}
  ([`76bb7c0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/76bb7c0d79ad61de6c6de00074891cf18130f96c))

### Features

- Add basic support for depth argument in circuit_designer.export
  ([`31e238d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31e238d599acc70c48238a73e02494c3e6e7bc28))

- Add hash and eq methods to LabelReference
  ([`4b627aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b627aafb6e5d37c614d11584f5b2636b8c311de))

- Add path tracking in exporter base
  ([`00f0931`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/00f09316b89aa4a9a34e8b21a69ec2d57cb2c253))

- Implement `expanded` flag
  ([`14b5a3f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14b5a3f196c55b698b0542d224a8e5b80d3a8652))

- Implement basic circuit_designer.draw function
  ([`7e8b1ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e8b1ac8e986fe8c9b77db8318105817112da833))

- Implement proper handling of implicitly accessed registers
  ([`d165ef5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d165ef5c68c8b3dbf91a01d5df9592f7ada06350))

- Implement somewhat functioning register placement in WB -> CD conversion
  ([`bd03caf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd03caf197d2fff1734b6e294a6a83dab16c9239))

- Sort registers to make output more predictable
  ([`54532d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54532d364d32d85314cbadaf9100ef7e5ad2bcee))

- **diagonal_matrix**: Implement Diagonal Matrix, with test
  ([`5302ccd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5302ccdabd4da288974a399f9ee402a060883773))

- **fallback**: Add new fallback scripts
  ([`a6de069`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6de06944b7a648f59ead5e75dc1657b5ba07472))

- **falllback**: First pass prototype of fallback measurement generators
  ([`cf77c12`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf77c128d9eee4c9a9cf6ba25a125df9455d03db))

- **modular_add**: Add comments and expand to use different core adders
  ([`c75c1d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c75c1d54a22378300ff4cf4d20d118b63a84a2d7))

- **modular_add**: First pass, with test
  ([`962c6c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/962c6c19fb75ca9b5afaf75176814cfad1de9548))

### Performance Improvements

- **parametrize**: Added parametrize
  ([`e909eda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e909eda561375828965f6918e6f6cfbd1e4c7bb5))

- **test**: Add in test optimization from #1274 into #1297
  ([`4c3941b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c3941bd98417af383f162b0eeb3dcc70c6edd50))

### Refactoring

- Add register tracker as an attribute to exporter
  ([`53f7c7e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53f7c7e36a4d7dc5c25933d62566ddb1c4b6925e))

### Testing

- Add tests for draw function
  ([`4865b4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4865b4bc9de313f2019c4a13fbfd13bff70cc5a3))

- Add tests using rotation catalyst
  ([`355c8f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/355c8f78ed4d70ca997ad11314e80e81be5a65b9))

- Include examples with registers currying in CD integration tests
  ([`ca25726`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca25726eabd43871f5cde70d9738e13b0e41ac03))

- Indulge ruff with removal of lambda usage
  ([`d889b63`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d889b63417dcaa212385206b45a9d914c68ceb1a))

- Rename test as suggested by reviewers
  ([`0020712`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/00207128b1e17d0afa7a05602f492157e2e44b9b))

- Restore test skips
  ([`19d01ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19d01eafad9c07aeaf4fbd6ccaaab8fdd613567d))

- Reword terminology about implicit registers and currying
  ([`90972b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90972b50979a3f229e7a046db86966a724e2fec2))

- Temporarily disable currying test
  ([`9e12c89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e12c89d90654f30082e3a23a780d725e229b40e))


## v4.33.6 (2026-03-02)

### Bug Fixes

- Add support for changing unitary dimension between get calls
  ([`1f0225a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f0225aa3e75ecac7cc5b02dda8e06c89df7f56d))

- Address reviewer comments
  ([`c48ce32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c48ce328e80547aa41048e67143c58b4f951d49b))

- Improve performance of unitary filter and add catch for slowness
  ([`0991b2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0991b2b1876ec16e93d262d95276f9936186b2d0))

- Reduce number of unnecessary warnings
  ([`760b0ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/760b0cae5c53eb3648483d05f1a9ec039b72c763))

- **cicd**: See if we can autodetect the correct one
  ([`edc399f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/edc399f0edacbbbb150e6e552588d6bc8fa170c4))

- **cicd**: Signed/unsigned errors and warnings fixed
  ([`112dd4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/112dd4d5225a463cf86d0bdd55127f484d399e01))

- **cicd**: Try to install just the compatible wheel and relax when the incompatible ones fail
  ([`57c50d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57c50d0d3e315652bf8d4625669b85a6134c55fa))

- **cicd**: Try to install just what's compatible
  ([`d4520c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4520c5fef2fa24b173b723768efdd1720c65df3))

- **MR**: Fix typo per MR feedback
  ([`81c712b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81c712b36de7fb2b179612822bf50dd5b42593f6))

- **test**: Debugging CICD fail
  ([`c6af53c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6af53c87214af28d04287c1eed594d64b05323e))

### Chores

- Add missing sams
  ([`9a3d1c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a3d1c107885fe09afbbedb3516fb7b0884cc4b3))

- Bump version to 4.33.5
  ([`2c34ee9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c34ee94a9afb6dd295dc895ec161fdd72df11dd))

- Ignore profiling directory
  ([`18c9ed5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18c9ed5780138f855a1a68c5a51042d597b3a64b))

- Move unitary benchmark to speed tests
  ([`ecf54db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ecf54db7ebdfa57bedd3cd722d35a2db0cb388db))

- Remove explicit psi-liqtr dependency
  ([`6d671fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6d671fc084ea100e0c2ea6b6c76bea766b534399))

- Remove references to internal sources
  ([`941691d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/941691d4559cfa2010d4065fb4020d8c0498da52))

- Remove references to internal sources
  ([`39162e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/39162e5a48f9ddf6b867d966dd999eee4e549c07))

- Remove support for psi-liqtr in rotation synthesis
  ([`9490a65`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9490a653c738647c48e99bd360130d8df7c56eec))

- Update tutorial notebook and add tests for exceptions/warnings
  ([`fa027d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fa027d075e02b924862ab3eb4cdcdc1783f1a9fc))

### Continuous Integration

- Add docs preview job to CI pipeline
  ([`e57ab33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e57ab33998eadfdf6a43fc872d5cbb9e117d8cad))

- Disable lint:commitlint
  ([`33e6ebc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/33e6ebc072c45951787ddf9adfeaefa3cb3e14ce))

- Make per-image wheel passing between jobs more deterministic
  ([`505afe6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/505afe6d03b8e88b536af67558a66083ab39787d))

- Pull SMS out as specific codeowner
  ([`6a4a915`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a4a915911874fe5589ae3768edb628d0a33fe13))

- Update preview job to use docs build artifact instead of docs.psiquantum.lan
  ([`35e6d3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35e6d3eab4575fa1293773fac32034a5d4a0b11f))

### Documentation

- Fix issue with broken w3.org links
  ([`2e73556`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2e735561dfcafb5d1217272baa978cfc3dc2a32e))

### Features

- 18s for CC, 8s for Cuccaro
  ([`409d6fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/409d6fc2f80342c10348f4649ed91103d048012f))

### Testing

- Remove QPU.draw call in CC test suite
  ([`bc71e92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc71e920cbc6997df7bd12b70fd6281b01ddf4d1))


## v4.33.5 (2026-02-17)

### Bug Fixes

- **cicd**: Remove all aws references from build scripts and .gitignore
  ([`0b752f3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b752f37dc85935e1a52430682c7de3e3f75acaa))


## v4.33.4 (2026-02-17)

### Bug Fixes

- **cicd**: Remove AWS version file from version update script
  ([`f4f58e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f4f58e924596ca390109421bdc31f378506b05c7))


## v4.33.3 (2026-02-13)

### Bug Fixes

- Check for catalytic T warning checking
  ([`4e820fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e820fddc580ee5e87f3665d21ea4082fad0b53b))

- Check for conditional RS warning
  ([`7745c3a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7745c3a829e1b64743a4b0b05e7d7cca26f764c3))

- Control only the center CNOT in controlled SWAP
  ([`9887b0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9887b0eebe1c21b33c07b51483378faa52d669cc))

- Fix cswap handing in UnitaryFilter
  ([`74d41ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74d41ced604bd677831a58d7d7e0a10c5c3aebff))

- Get rid of DeprecationWarnings
  ([`650b6cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/650b6cd3d78de32344a7d6df310780fdcbbe1b67))

- Remove warnings triggered when expected
  ([`e2a71fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e2a71faf86226ab4a80b29be7416f6da16220097))

- **linux**: Again, try to force no bookworm
  ([`7087f80`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7087f805d49557b96ddf0a7645585ad1525d4127))

- **linux**: Test building 6 flavors, both pinned and unpinned
  ([`928b6a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/928b6a8999a3e89a7985a3aac4ca4147f67dfc62))

- **linux**: Test unpinned default build
  ([`54259d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54259d1ae89afb93dd74bfdf2c19192631702e14))

- **linux**: Try to force no bookworms
  ([`1c5b6e7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c5b6e74695c57344a052c76a2434065006a02eb))

### Chores

- Add security policy
  ([`87d3fde`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87d3fde15de47a9836a12c24b5d796b7b0ba4bde))

- Bump version to 4.33.2
  ([`11c0b1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11c0b1def51b8be821d049ca57a73555a92374bc))

- Deprecate aws code
  ([`9018d1b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9018d1b2f640473a664d6783ce4c1a0be79d23b3))

- Improved warning messages
  ([`2646526`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2646526386e2a262c3dcaca4cb3610c37b9bddf4))

- Remove a few more deprecation warnings
  ([`043019c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/043019c054941f9577ece879a336feef21b6fa09))

- Remove newlines from warnings
  ([`959abec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/959abec72a2ea335b58ce4f7ce426fd3448de396))

- Remove outdated comment
  ([`72986f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72986f1ebfb7b85c8533e91bc9358316212b9a26))

- Silence ross-selinger warnings if pygridsynth isn't installed
  ([`59bf621`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59bf621a6a73f42efe5247e1784764f06b008801))

### Continuous Integration

- Add dependency scanning to GitLab options
  ([`313b754`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/313b754cbb58c1a88aeecb348c24e9dfff4ac20d))

- Enable full matrix for build job testing
  ([`7eaa471`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7eaa47191644389a4a3aa4911ebde7361ea5df40))

### Features

- All warnings bashed
  ([`3c0e02e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c0e02ec07a4ed3ec6e1795819d3357b7dd4bae6))

- Fixed unc bug in edge case for ltc and included this in tests
  ([`3e2f4c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e2f4c3763eebc40eeec8405dc00c809a3a2ad95))

### Refactoring

- Remove unnnecessary witness functionalities
  ([`42e0a5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42e0a5c5bbfba184c79dc66b298d65b661c05e78))

### Testing

- Ignore warnings about DAG support in test suite
  ([`c685da1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c685da12f36a999af3cc234cc3b75a5ed78eb2bb))


## v4.33.2 (2026-02-06)

### Bug Fixes

- Fix handling swap in compute_args
  ([`216827a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/216827a6084130126682c79080a760d61de2c6fb))

- Fix how registers are sifted up
  ([`dffeff2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dffeff2dcbafd1832e5a518ada36a0a47bafc773))

- Fix main call in test
  ([`103f4b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/103f4b3b621bdc839680a457e9373bf84f6e97a0))

- Fix pyliqtr calc and switch off warnings
  ([`247da61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/247da61d27a70d2c7ad862cdc037b38bd13fe331))

- Fix typing errors
  ([`c7d01f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7d01f1cd194aab2288bcb0e87c555f646bde287))

- Fix typo making controL_type for phases incorrect
  ([`abadc53`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abadc5340bee5eb591187914a4f8a9af22c92b53))

- Implement support for PPMs and PPRs
  ([`6bca36e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bca36e489d5161fabda4a4c04681a1fa1312854))

- Make display label for subroutines correct
  ([`a62a604`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a62a604f7989adbe746d052e3539982be4b8aaaf))

- Make registers bubble up when finalizing qubrick conversion
  ([`b9161f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b9161f9b0347c5ec1050ac086f4f07eaef7e867e))

- Remove debug print
  ([`870ee5d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/870ee5d216e932e5819fa59ef7ad049fde777417))

- Remove nonexistent import
  ([`349ec08`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/349ec08c09548ad43a6078bdee025f6c34f84ffa))

- Remove nonexistent LabelType from __all__
  ([`4d602cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d602ccee807ad01d10c35240d575f524790972c))

- Remove unnecessary pass statements
  ([`7ec0882`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ec08821bf007935788cf9750373fa267b175aaf))

- Remove unused imports
  ([`650548e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/650548e83c3a4562d8ce7c0d6ca6a78e1b1583f8))

- Remove unused variables
  ([`db5206e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db5206ec34f4686afb6d2d53668d43333970f922))

- Removing print statement
  ([`b695f7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b695f7b2da77f2ba3921075f89b9fa6650a2d6d4))

- Returning single filter option correctly
  ([`41c3b6c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41c3b6c02e8dc6506ae2d51902ac541b5856622c))

- Reuse variable instead of calling get_instructions twice
  ([`5d2355d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5d2355d8bbdc18a92e2b2f4c6f0dc31f42246ee1))

- Use cnot gate type instead of plain "x"
  ([`6099584`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6099584789b9065b62336659a3882d8ec909fddb))

### Chores

- Add kwargs to dummy qubrick
  ([`a5ba4e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5ba4e364a488cb17006aac55319b400aaeca23b))

- Bump version to 4.33.1
  ([`9fff7c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9fff7c8a5d80ba99e31ed96fa2022beb75c1fece))

- Configure codeowners for integrations submodule
  ([`db381f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db381f77e2b162b0059c779ea45b3e3de6ffe8b9))

- Fix the rest of the qiskit warnings
  ([`b5b29a0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5b29a090ede07bd240fe4ba19660823c2212386))

- Fix warnings for dag conversion
  ([`8ab6dd0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ab6dd0db1ef5a1501da422fce3c7396ba1aaa39))

- Move to new_tutorials
  ([`5040013`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/50400138d1b4a4bd128562db4f38fd56a1518838))

- Remove radians param set from qasm export
  ([`c2d30f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2d30f9b368e75fb8ed8ce055591067dc3f8129e))

- Remove references to deprecated AV counter
  ([`25ff37c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25ff37c95c58064f3d6cf2c0f4c3339d9ec24150))

- Remove whitespace changes to file
  ([`93c3501`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93c3501af38e5236522bee527eb817be5951caed))

- Skip tests properly for pyliqtr
  ([`29ec7e6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29ec7e6c96bd1616f28ec31bc59121b65d95f6f6))

- Spelling, removing code from headers, improving readability and style matching other docs
  ([`136fe66`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/136fe661c5bbe8faa3d7bb5989d99df15cf682a1))

- Suggestions added, deleted old tutorial
  ([`6af710e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6af710e8d73f27cfc4f3afc7dca7915c91bc2503))

- Update master -> main in README
  ([`f01eb7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f01eb7b1aeef672ceb25ecf005a1a710ca4d0562))

- Update pyproject.toml to ignore qiskit deprecation warnings
  ([`9cfa5fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9cfa5faa0591f013429503bcfeaf288b21bfb43c))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`2bced7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2bced7b6cdac32acbaa0d4c2233ee682e3174e88))

- **review**: Apply 11 suggestion(s) to 4 file(s)
  ([`c6cbd16`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6cbd16a0d21be7840821ccde87313312300ce81))

### Code Style

- Add type hints to some functions in bit_utils
  ([`856b43d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/856b43d87b836576545a547b4905be4e7da92d3e))

- Apply formatter
  ([`0731c76`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0731c7662a1a912895b1fe9756c768ddd9a900c6))

- Change cond_mask to cond_xor
  ([`ee89b18`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ee89b181078a89b46fa4f5572354c5f7b4d552d9))

- Fix typing in _common.py
  ([`02a38e7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/02a38e7730c7040f0952a6e252da5f0d1d5c9079))

- Improve formatting
  ([`4fd04aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4fd04aa7b581806695a7789213434ca2cf002040))

- Improve typing in events.py
  ([`f0dd1a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0dd1a8ce891847b22710f1b0ecf0d1026b915cc))

- Improve typing in qpu_ops.py
  ([`ea83128`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea83128e007144aab5e028571c67b896ce2239c3))

### Documentation

- Add basic howtos
  ([`a26b210`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a26b2108e753a77db62400442e0664ce6dd88ce9))

- Adding correct capitalization
  ([`d64901e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d64901eefe95b2e9bfc0b58e82f2d1cd2f2af513))

- Fix docstrings still mentioning serializers
  ([`87be215`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87be2156aec0405bc445eb390f40abd4184fa451))

- Replace 'how to define routine' example with ReflectAboutMean
  ([`da4772e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/da4772e64e15687ecb526eae32375afd97615e70))

- Update example names in RotationEvent
  ([`f05a17c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f05a17ca4117e464240ddb39e31dd880828f1529))

### Features

- Add base class for CD serializer
  ([`4a2d30c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a2d30c802b63c04fbf85bd7878baf8fed67514f))

- Add explicit input registers to routines
  ([`533f46d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/533f46d8f64b0ecbd2e76fb68b300333ecbae00c))

- Add s and t to gate mape
  ([`e9e90ff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9e90ffc3d1095e4876896e12ca2ca5591698f91))

- Add stub for circuit designer serializer
  ([`d98973f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d98973f4e1474543318a35b685cf3c412363d725))

- Add support for exporting missing ops
  ([`9ee0a01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9ee0a01231d42b5dbc96fec3dca1e0d43340e3fe))

- Add utilities for converting ops to abstract events
  ([`c0f1f07`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0f1f0744e37fac4338b6d0d94d2557d64695428))

- Added Cuccaro and benchmark graphs
  ([`679bf1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/679bf1adfbf1e1f7b3bf62a6232b1e3e20a4fc46))

- Adding list option to get_filter_by_name
  ([`9602d70`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9602d708c786c8f7d22e5e8e78a15878b352a182))

- Fixed bug and added test for >2 ctrl op's.
  ([`4848d26`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4848d26ced99b615f8755004e008d762912ca226))

- Implement forward referencing of labels
  ([`3238f35`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3238f354925c6c11914dab720726bea2a93f1623))

- Implement helpers for register-tracking
  ([`54e9ff1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54e9ff1d9778088fa13a8ab7356cf1a1421c9dc4))

- Implement missing details of RegisterTracker and MaskBasedTracker
  ([`d5e8a7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5e8a7b993005d3fe7d7300360cef1f85e74c802))

- Implement public interface for Circuit Designer serializer
  ([`82e6e8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/82e6e8f3fa15a7d583219d88860e27952e698184))

- Implement serving exported diagrams directly to file
  ([`b2d2b2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2d2b2f82d2628efb06abb33a70ed5c482c08eb1))

- Improving test and removing dead code
  ([`9c3b871`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9c3b87190c95c2c81109c12ddf2539a49db33320))

- Thinning code examples and other style changes
  ([`939263d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/939263df95235c6a182d21e60e2d64442f80338e))

- Thinning code examples and other style changes
  ([`2f64095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f6409564598efb5f64c5a655070c86e0861faac))

- Use correct control type with phase operation
  ([`970aaff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/970aaff736d550e7972eb525a9fe119eb411ca3c))

- Wrap labels in \text{}
  ([`d78da42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d78da42c37f0b0fef4433cb84d1e39148459bd81))

- Wrap returned implementations in sorted to allow pytest parallelisation, update test_tags, and
  separated out adder interop test file
  ([`823a49c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/823a49ced2d31f915f4411495f2d88d2ad55a70b))

### Refactoring

- Change gate_id to opcode
  ([`25b5d03`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25b5d034c8b2c992b6e48bf8566d9c4c2901dae9))

- Change terminology: serializer -> exporter
  ([`fdebf8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fdebf8f1de8c7ec67def79505dae229e7b246945))

- Remove LabelType
  ([`dcccf36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dcccf368747f4b76837007592811d36c39c73cf8))

- Remove numeric_op_to_event
  ([`3da3503`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3da35037ab647fc584699d1474aba635d4ba0dca))

- Rename release -> dealloc
  ([`7229698`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7229698109b6715a48f288d2da5f920c43ca04a1))

- Rename serialize -> export
  ([`bf89fac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bf89faca983505308f79d6158b908a0d6492bf1d))

- Simplify getting CD gate type from WB opname
  ([`8df464c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8df464c477709c6528b3777ccba1f8373347528e))

- Simplify logic in _resolve
  ([`886dca9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/886dca966abdfdb99e9db6f47d85ef18f60d2c35))

### Testing

- Add missing tests
  ([`5350f68`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5350f68a86a8a0d531975a739de56a45450afab3))

- Add tests for exporting qubrikcs
  ([`dd0aaa8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd0aaa8920db3b7593799070e32227e0496d1e0d))

- Add tests for repeating primitive ops of the same type
  ([`5b77d3d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b77d3da205f64f91d6028783500ef64e769b7bd))

- Adding missing tests and fixing docs
  ([`32553a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32553a3abfadf4fa9230e80e88b6af55623b8014))

- Fix PPM and PPR tests
  ([`b43f853`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b43f8533f77c881ec721d0987aa917d8d0ba9936))

- Fix register tracker tests to match changes in corresponding module
  ([`ca6df23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca6df238c002ae9d427ae6bcdf4efe8557a701d2))

- Update tests
  ([`c5d4132`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5d41327667cd7ff811faa9842943600d3f99213))


## v4.33.1 (2026-01-30)

### Bug Fixes

- Add missing known_discrepancies for GidneyAdd and RotationCatalystHandler.
  ([`8dbf40b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8dbf40b4e89aafff30835721addf207ebb8596d3))

- **drawing**: First pass at a fix for #1249
  ([`015a1c0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/015a1c007674f70fa452c6d66f8b5c37f7456e2e))

### Chores

- Add free_symbols to old parameters to make exceptions easier to understand
  ([`6edfd17`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6edfd1793f43965a75abd08d0f4e7bdde98db3b6))

- Address 'condition arg is deprecated' deprecation warning
  ([`95949a1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95949a1326d72a6e377b3486a25fece4e8372c34))

- Address a few more deprecation warnings
  ([`1f370c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f370c4906ba3b2229c980d7838170e016d231d5))

- Bump version to 4.33.0
  ([`cc803d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc803d68477b7e1fd261c59b181513841bc4cf8a))

- Fix deprecation warning Qubits.QFT is being considered for deprecation
  ([`08453c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08453c87637349f9add3ea6b2848598da38ecd8c))

- Fix warning for non-svg file extension in qpu_draw
  ([`83b9306`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/83b9306c090d77640c7aa7d81a88b1893304f2fe))

- Remove errant warning missed in previous commit
  ([`5ab4741`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5ab4741d83e6b1b82d9f0ce3c2c9206ac6518280))

- Remove unnecessary warning
  ([`d8723b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8723b51866e7c2420bc88bb70c649c6e3cce8e9))

- Remove warnings when dealing with baseline architecture filter
  ([`841336b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/841336b9702b54395df272b38eee8277a5c3892f))

- Update cond_reg -> cond_zip
  ([`a6947c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6947c419682c5493a66b50a952a8408e69518bb))

- Update to new resource_estimator interface
  ([`a37222d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a37222df7c22ea01120f51a30544dcd4fb2aa889))

### Continuous Integration

- Add pytest reporting for extras job
  ([`6f390f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f390f94c19ac86b17dee9766121a6ee4d220fb7))

- Added pytest report generation for linux test jobs
  ([`14e9f72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14e9f7213b1d2e278aeb1f7b5897baad4eec2e08))

### Documentation

- Address Ian's comments
  ([`550bba2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/550bba29ccedb66cd15d6fc2fc9fc5cf40a8d378))

- Fix wording in docstrings
  ([`7890b01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7890b0137e7a4c4fba0b8096f56a03903065f8a3))

- Improve Qubricks docs based on mentees' feedback
  ([`3765eaf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3765eafa55e2a84209f0ff924ab89793979c47f6))

- Updated reg issue in releasing qubits
  ([`b483c23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b483c230bd67d35d09699423bdfde40fcec54cb7))

### Features

- Add discrepancy decorator to comparators
  ([`5e7088e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5e7088e1bc9e224f11257c33336ef5c54932676c))

### Testing

- Address warning in qpu ram limit test
  ([`c047290`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c04729044de4196f17b41c7961fe89f2e575d41e))

- Addressed some easy-to-resolve warnings in our test suite
  ([`62e898d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/62e898dfd3801e4a574b770bc82d51b5968d247c))

- Avoid using get_av_from_instructions in test_1113_y_parity_in_av_costs.py
  ([`3c4ae86`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c4ae867edb9bf54d673096fb0fd165df3c550d9))

- Remove unnecessary test
  ([`c16c0c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c16c0c389852dc27f94a513d2f91db73713479a4))

- Update tests for GidneyAdders
  ([`bd8b0df`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd8b0df39fc02cec3a9334b501733781acac06fb))


## v4.33.0 (2026-01-19)

### Bug Fixes

- **MR**: All MR requests met
  ([`14e8431`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14e8431b35f900e86a08127e3faee3fe31574730))

- **test**: Update an old test to the new behavior
  ([`6b6f938`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b6f938f76e2b0eb96d9e615a00663c3ecfb4626))

### Chores

- Bump version to 4.32.0
  ([`8ae5527`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ae55275bf0b7ce9b668ffb92a0c99528baabd78))

### Documentation

- Update readme
  ([`29e6f4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29e6f4bce6f1a95cd8166ffcab3c1a5b4674e1ec))

### Features

- Initial commit
  ([`e60869c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e60869c6e09a13d334a9eb79a60d73afcd3d3ccc))

- **reset**: Clear ops on reset per #1276
  ([`f6badd4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6badd484a23d729c3ca0436f84ab4d9ded47dd2))

### Testing

- Fix faulty logic for AV in test_black_box_exact_coverage
  ([`b80b1e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b80b1e57b0de0b6655e1329055a0165276d710e5))


## v4.32.0 (2026-01-15)

### Bug Fixes

- Add default functions_map
  ([`37c8008`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37c80084160db85d637e8f45bd2f6b6f40fa6e46))

- Change idx mechanism in catalyst to using ARBITRARY_ANGLE
  ([`1ff62a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ff62a84fbaf239e9a826d8706943effef6dba85))

- Condition needs to default to 0 not none for interface tests to pass
  ([`2a6c5e8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a6c5e8be1a371b90646c067a8301d2562299819))

- Fix handling of rotation epsilon override for catalyst
  ([`30827e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30827e5dbbd2d367f1e4fea49aa8c7de1952a6ff))

- Fix import problems
  ([`06d951f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06d951f89332b965c4a8c0d376d2a9f96109fede))

- Fix issue with av for ppm
  ([`b8af404`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b8af4041370bb9f11a59e2f93632b904b8144f8a))

- Fix issue with wrong defaults in default_functions_map
  ([`5e4f2aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5e4f2aae749fb67f2c9312dfcf472c56e41bc416))

- Fix some edge cases for symbolic ops compilation
  ([`5f53807`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5f538076861a33f63d3e6a91b608945841451917))

- Fixed symbolics for rotations certain angles
  ([`a1284a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1284a413d57606f2cfc00d45433c0f1fec18a69))

- Fixes calculation of z_mask with control
  ([`96652b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96652b5c136dcc1f7e40f87b99b963c8c579961a))

- Fixes calculation of z_mask with control
  ([`5755c23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5755c237d0bb46fa6179e094510b22805fcb8cc3))

- Fixing me repeatedly mispelling cuccaro
  ([`6eae426`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6eae426c74482259b0423c1a3ded91264d875a2c))

- Improve handling symbolic rotations
  ([`3ff0f43`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ff0f43a71a2a67aebdb7f5bbdfc9051cbcfad8c))

- Intermediate stage of fixing AV of PPRs & PPMs
  ([`b453fae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b453fae6587679020c54cb740e385018550b0d95))

- Intermediate stage of fixing AV of PPRs & PPMs
  ([`a8ef207`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a8ef20746ee6501061ff1c677d00a6152206afaa))

- Less zealous override for rotation
  ([`7ef261f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ef261f45ed021b599d393fe94d1dc6832297c3c))

- Make default value for rotation epsilon 0
  ([`c934179`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c934179c509b3b4e937d6352bd31f00dd0ac5908))

- Make interface extraction more robust to parallelization
  ([`acc3223`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/acc32239e9ccdf4f06f416e32c6d2f53fb8cdd08))

- Qint range
  ([`55fccb9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55fccb91985648a62755813bb4e9dcdfeb0d212c))

- Remove additional string append
  ([`b6ed095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b6ed095edaf734ba3620a15acea1560ada026167))

- Remove incorrect changes to active_volume_lookups
  ([`64d1871`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/64d1871448d35072ecf4cd03aae6a6a35a355d0f))

- Remove leftover mentions of rot_bits
  ([`39f67fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/39f67fe7fee5abeddd519a0430949b65e05277de))

- Remove redundant assignment
  ([`3151fde`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3151fde56b9b077ff3e50e043d2ddb3c85b816ae))

- Remove some leftover code
  ([`8019205`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8019205496d0b63e90901726a5fdc5b77862516d))

- Remove unnecessary "error_param" user parameter
  ([`7d4f8a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d4f8a5d095adad3713613dd89ea591f93d7a999))

- Remove unnecessary logic
  ([`91b43c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/91b43c9cee431f37a16c73701cabffc63c2ca6e9))

- Remove unnecessary None case
  ([`364620e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/364620e66ffcf85792dc750a259564f18f9c9892))

- Remove unused arg to get_gate_cost
  ([`01a82b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01a82b3ad94d8162d3c26df1b7323ec386df2e3b))

- Remove unused default value to compute_active_volume_rotation_ross_selinger
  ([`0157c5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0157c5ef7a6cb0edf75739a996dbd8392a7e5dfd))

- Repeated test line
  ([`98d2600`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98d2600c6afcdaf8466dfcd52c2217638dc39ce9))

- Revert meaningless changes to qpu.py
  ([`cbf9054`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cbf9054f6287f24768c174197f7daba30ddaa58e))

- **adder**: Sign-extension fix for adders
  ([`b8da759`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b8da7594fb8b03ea16c751f61e57aa0fa20fe6bb))

- **check_zero**: Check that allocations are returned to zero when freed
  ([`18a47fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18a47fa11b646c39b2122c44fb0ff708c7a01ea8))

- **cleanup**: Add switches to different behaviors
  ([`61e2857`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61e2857778ed85bc1826ff329cbcbd5d3de92f53))

- **cleanup**: Remove all 64bit references, add a test and a warning
  ([`d3fac6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d3fac6e3aa054e98d052ae4552e0eb929582c97d))

- **cleanup**: Remove commented-out exception
  ([`9598845`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95988459c72fad0a3dfacf26f51bd792d307d384))

- **cleanup**: Simplify measured testing
  ([`4d1d14c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d1d14ccd5e1943e7b9949b7198a34f69321b394))

- **cpp**: Fix returning of new array
  ([`c796ed9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c796ed96b8f25bd1803a3a16f24be41ae613bb4a))

- **debugging**: Add simple stack debugging
  ([`ebd49b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ebd49b8dd287237153795a1ac243313e14b6e744))

- **debugging**: Fix debugging feature so it works as requested in MR
  ([`bab8ee7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bab8ee7fe58bf1ce10f27ce59c2bb5a878d8a61e))

- **elbows**: Remove elbow measurements, which are hiding errors
  ([`d484591`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4845911d465bcd43acdabd44e1d8d70c4424526))

- **elbows**: Temporarily always enable debugging
  ([`dbde308`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbde30874dc904bdcf9f1190c683353979261b2d))

- **get_dag_from_qpu.py**: DAG should now produce the correct graph and run faster.
  ([`e377a15`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e377a154d6c78942eac7dedff4c10017bc63c447))

- **get_dag_from_qpu.py**: Refactored some code at the bottom of get_dag_from_instructions.
  ([`3261e26`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3261e267ad6c50d4b51928055bdd8974c484c545))

- **get_dag_from_qpu.py**: Updated a comment.
  ([`383f8ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/383f8ce17e20221ea63e47aba7ef989e549215eb))

- **jumps**: Fix minor op counting error
  ([`28a776d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/28a776dce747079f77353cd192b27772dbee1d56))

- **lint**: Fix lint issue
  ([`c2e54aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2e54aab878db41b5ce438eb7bf92980342816aa))

- **MR**: Fixed per MR feedback!
  ([`ca932d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca932d6fa973cba257ef4c14ebb54b33eab34787))

- **namd**: Minor typo fix
  ([`8ffa73d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ffa73d37a40a890e3830f1600be8dbe5fb8de27))

- **release-check**: Iteration on #648
  ([`f8cb847`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8cb8478c6eeadf0403c2eaeb7e61bdf01903dd9))

- **simplify**: Further simplification
  ([`7798f6a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7798f6ad76c7afc7c022079ce632d75d5d05e519))

- **simplify**: Reduce the set of changes to get this delivered soon
  ([`2326925`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2326925dd3d52bfb0a5c7047b48377df3b29be7d))

- **swap**: Fix tracking when we swap measured qubits with non-measured ones
  ([`e913cc1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e913cc1a9e054fe8aa299a75fc536a9704f0e2e1))

- **test**: New fail case from Mariia to handle
  ([`7b66d92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7b66d9265268a1dddc7428f25baf5780243e2c75))

- **tests**: Fix a few test issues
  ([`0ecc85f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ecc85f02c7b2fd8dbc8ce1e406c76dd599e62eb))

- **typing**: Minor type fix
  ([`2008828`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20088289b9c6f6eb378dc6294c27dd9c14647d72))

- **user_error**: Provide a much better user error on non-zero release
  ([`b5ebead`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5ebead1a0d171c1d798b8cba4dd87e7908358cd))

- **zero-ckeck**: WIP on the zero-check fix
  ([`9165832`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/916583206d27b0713748ad3d2c1c7d2a7113c82f))

### Chores

- Add newline to test_1266_qubits_bit_qpu_pull_state.py
  ([`19328cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19328cc68a35da82ed4163f60bfa0faf5c4ba949))

- Add override rotation method for epsilon
  ([`9d80124`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d80124346b986bb1ef4de2c73b6240f4a4503f6))

- Add type hinting
  ([`c77b8fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c77b8fd81cfad06de9a725bad676d182ef085e74))

- Adding copyright header
  ([`dc59080`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc59080bd3180396fec241ab547d001785bd72ed))

- Adding more docstring
  ([`c0ccfef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0ccfef36008c4f91b8b90c49cf9b1f7e73c458a))

- Adding more type hinting, removing empty lines, moving arg to init
  ([`2ac1881`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2ac188131be476027414ebbb504a917a9942584b))

- Adding tests for rotation precision interface
  ([`0fcf8de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0fcf8deb57090891e7c294932f6f2de4a7725fbb))

- Adding xfail for zero case to be solved in EJ's revamp of file
  ([`61451c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61451c4bcc73c76f5d482d07ea5e7b33ff9627d7))

- Bump version to 4.31.2
  ([`fb4a022`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb4a022d5d34b7fbe1ba0e8421b9117a1067a1cb))

- Catalyst-specific epsilon override
  ([`24c2ae8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/24c2ae8b091304ba4fbef53a57cd84bc21cb51bc))

- Copyright dating
  ([`3f1294b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f1294b3a41c3797344667fe81de70267400e98c))

- Copyright statement
  ([`90b2e81`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90b2e815203cc251ff9b9e3ac4eaa0a83e06a720))

- Delete benchmark notebook
  ([`8ec86c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ec86c4462366c9872d32084501915e0347fb3b7))

- Delete unused variable
  ([`9a25ce2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a25ce229d279f25414b39b2db6081cd1c6bf873))

- Deleting non AddBase versions
  ([`e595983`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e595983b6a6c49007e6fd87aa8fccd5a69b36dd7))

- Deleting notebooks, moving refs to gidney arithmetic doc
  ([`231ad9a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/231ad9a44e39ca9daaafa9d724aac918373eefbd))

- Fix comment string and remove elbow option from dirty case
  ([`eda6519`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eda65191c16dcfc523080f401041f985b7d77273))

- Fix mod in docs
  ([`de859b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de859b398320901cf64ffceca840d6ab526f98ce))

- Fix my fix
  ([`585338a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/585338af314070af1bb31c47717cfcdbcfd291f5))

- Fixing broken test and updating rot_bits in active_volume_lookup and gate_costs
  ([`8d9d82f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d9d82f308a520a57910f5ee76a80cae9e3e2307))

- Fixing nonfunctional inconsistency in qubit register names that was copied throughout
  ([`2ef3128`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2ef3128bd7ae8329cf71c210b93cde2e222f23f9))

- Increasing test register size
  ([`d3e671c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d3e671caf24536dbe8470bfd588f7ae464b6d726))

- Madd with signed values
  ([`331633d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/331633da17216657d24d5f2a1d485fefae687448))

- Made rotation precision helpers abstract and added docstrings
  ([`8631abf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8631abfa3191b4607e2cd4533dec421cadf9fc9d))

- Making changes in base qpu to support echo workflow.
  ([`b0e288d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b0e288dc1cd22e4ede35f861152e2a6076ba68d8))

- Making update to qbk_rotation for error param
  ([`f963a65`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f963a6527eca9f662158cbbb1fb4f75e0b78454d))

- Moving rotation_precision content to rotation_utils
  ([`41d6ba8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41d6ba81e19fc15e6dc7ece81d6b88100320499c))

- Remove testing code
  ([`5644606`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56446064e32da88ce46a023515f50bc6689d7645))

- Remove unstable warning and patch Ross-Selinger synthesis
  ([`d4b2893`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4b2893fd358fb9e6712244f56ba59bcd9ac157d))

- Removing repeated comment from tutorial
  ([`c152381`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1523812658bbd3077e99f978744790b54c8b28c))

- Removing unnecessary string
  ([`ec72491`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ec72491085646fe4f12c453ea0be127e21f6edde))

- Restore branch
  ([`2962ee8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2962ee8d199deb5fcf6a4907cd9cb9aef4264e09))

- Spelling
  ([`228f14a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/228f14a53f6413f29b4699e2c01f6510a92a9d41))

- TO RAISE: break case when int=0 for lt, zero qubit register for all.
  ([`b7accd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7accd281a7689f1b51d58afceb4762087f28fd1))

- Undo test changes
  ([`18f94d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18f94d25132cf854d1c0dc3aef0022353c9b5e3f))

- Updat ctx and cat to better respective naming conventions
  ([`78d6dd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78d6dd25407f81ef30929ba5b0d3833c00ab9a25))

- Using bit default, spaces before args, adding tutorial
  ([`c129ea7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c129ea7d3204f88ff89105cb6bf139fa4fec2cbe))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`0e9501f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e9501fbc64ef8269831747dcf47625d38fc4379))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`181393d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/181393d06e1aa885cb6204b6386d6050ee67bfc6))

- **review**: Apply 7 suggestion(s) to 5 file(s)
  ([`c30addf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c30addf9a934b45ef68599ac7967dc014337ce12))

### Code Style

- Minor fixes
  ([`9d1774e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d1774e2fc4d29fd372a4403dd12a6412acf4bd1))

- Update copyrights
  ([`4ff78b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ff78b0da3008df5a9c04f9b2e1e40d6807ecd72))

### Documentation

- Add missing docstrings
  ([`aa39dc6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa39dc6086e4c0a76bb98448fba46370f0acffad))

- Change comment about bit-vector simulator
  ([`8ff9248`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ff9248aae65a530bf9c1bc00391e566e4e0c429))

- Explain purpose of Overridable class
  ([`6a44da4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a44da4bc58b5f707a506101f3a371aa06a65f77))

- Minor clean up of API docs and tutorials
  ([`90b794a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90b794ab94bc9a24f732cb8796cb0d66aee7d99e))

- Update docstring of ResourceTolerance
  ([`0f2bd41`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f2bd41c5afd83ba035c28bf8690aead3a4a2555))

### Features

- 100% coverage
  ([`585fed9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/585fed99a62c289ac9e22dd23e37bae473a1e589))

- Add overridable objects to QPU
  ([`199f99b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/199f99b101ae9e1b315a6c44a7302c47194e2682))

- Add support for error_param for PPRs
  ([`113dae9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/113dae9f9fb912b60914641baa3f0c9fe3016fbb))

- Add support for pull_state_specific to bit-qpu
  ([`0993168`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0993168f6b0e963442d0cad23ec9626949e49c57))

- Added carry input for subtractor functionality, added tests for QInt, added doc references
  ([`355905c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/355905c1f85c8c37de9b77b5a4d633c465a948b9))

- Added edge case
  ([`61ef865`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61ef8658d3f242dc1e912177f9e3238b7cfc58ed))

- Adding Cuccaro to quantum arithmetic doc
  ([`2b02679`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b0267913e77c6a1cc872023a8bc6fe5e37f7eb3))

- Adding hermitian-window-filter to docs and removing ctrl (added to work with WBA which is now its
  own MR)
  ([`1271a11`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1271a11bf27fc0d0c18628812eb111df33ce8da4))

- Adding option to do controlled qubricks. translated to AddBase but not all inhereted tests passing
  instantly.
  ([`75831d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75831d15103371778da80f296f6be9895fd1c724))

- Adding QUFixed, QFixed testing pyres
  ([`e83ef6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e83ef6f023175ea5e8cfc4235adbc474d532ba36))

- Adding select test specifically for sparsity
  ([`be41b33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be41b337f0963884a2e6f886bc0b0fefab76ea31))

- Adding sparsity trick for CC and edgecase fix for Cuccaro adder
  ([`07e3c99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/07e3c99e73623eeeb3b39b1395b2dfdbaea4fc73))

- Adds payload ancilla when non-Pauli and most tests passing. need to update dirty ancilla version
  ([`0ba6fed`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ba6fedea4f95ad4bdfc5a30fca5e6cd8a1028db))

- All test passing
  ([`7f3ede0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f3ede0adfe2d63f75eb0e866134897d0e72e004))

- Allow computing RS AV when precision is symbolic
  ([`5792b60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5792b60d00c0316cee45ea5e03182cdf45fddcb9))

- Borrowing naive adder for quantum + classical value for multiply add to work with QInt
  ([`900b941`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/900b941211fb47960a5e99946a314cd37e4a3d1c))

- Cleaning test file
  ([`7107e6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7107e6e8145e546f4890f75fe69bd65f054b206b))

- Coverage 92%
  ([`60e32ff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/60e32ff956b549bf3be3c1fb55ba17d7b78dd825))

- Cuccaro with AddBase passing all tests
  ([`eb699ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eb699ce56e49a429349933ae498a1b0cccf401d5))

- Deleting unused file, EJ fix for bug for deferred result
  ([`f33a147`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f33a1472fa21fad2215248dfa5ff732b28788fc4))

- Doc fixes, CC ltc edge case caught, made CC tests more efficient, tutorial notebook for benchmarks
  (to be deleted)
  ([`4f16784`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f1678490d1a4952bc61b7082f70f76762e9c2e3))

- Final optimisations
  ([`1f091a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f091a5feebae4c3275447519c319063bf2f9257))

- Final tests tidyup
  ([`1b12d67`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b12d67791270ee4e41c9b150d3b6ef6965b0c47))

- Hybridising Cuccaro and Gidney for lhs > rhs addition.
  ([`66cd4d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/66cd4d60f01a13718f3b421052cfc56be4dbaa5a))

- Implement Overridable class
  ([`f901d91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f901d9163737c9da6d87e0c540f6ebb3e40fa7d9))

- Implement overriding epsilon for SymbolicQPU
  ([`211c0e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/211c0e5f4125959e1aff0db0a2d61eee0bcbd475))

- Implement overriding epsilons per Qubrick instance
  ([`39e274e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/39e274eaa9b63f83b664c11359b820a1e16dc4ac))

- Implement overriding symbolic catalyst rotation epsilon
  ([`8db4451`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8db445113f137b9a1288144015a939c5867fd026))

- Include MAdd
  ([`825d3a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/825d3a857e63062048e4d84c1aacaeaefd1cd86c))

- Interface to alter bits of precision for rotation.
  ([`96f87c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96f87c855e3b95aabb966eb06597b68bce917747))

- Pragma cases
  ([`e55d99b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e55d99b88d82e24991c09b73f6436151e897e96c))

- Qubricks for cuccaro addition with tests
  ([`bb6fbdc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bb6fbdcc7acdf4120ed4b48405b25db969bfd3cf))

- Removing partial call and adding swap to self-inverse ops
  ([`c5d88d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5d88d5100d0df73aea4ad8648943a21c761f315))

- Sign extension and carry-in, slight bug left with combination of sign extension and carry-in
  ([`ef3f510`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef3f51086b1bae0389b6a73e819de0c62810d1e5))

- **64bit**: Move 64bit conversion into cpp conversion
  ([`109edab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/109edab4ba7d8dc05cf41f101aa3a300141eaa1a))

- **64bit**: WIP, first pass unhooking the 64bit converter
  ([`3d83785`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d837853d85189e9b1dce3afe81451da237aaa8d))

- **assert**: Iteration on zero-assert in #648
  ([`0fa3f9e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0fa3f9e085eb970edfb9b08c9fbae3f582e04773))

- **bit-check**: Assert if bit-sim error detected
  ([`0a4571d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a4571d4673e272542a635d8f82c663833182b15))

- **classical-tracking**: Track classical values for warnings
  ([`acf6130`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/acf61306b5c909ef36797e93ed042c00bb0313a0))

- **clear-on-free**: Second pass at auto-clear classical qubits on free
  ([`11f67ff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11f67ff34c89314239edad7489bf74a79454a834))

- **events**: Event system first pass
  ([`a53239e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a53239ead7ab99e9de3578528b61550ec2d414ae))

- **events**: First pass of event reporting system
  ([`ae5405d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ae5405d1ffb2349fda1ac62acdffe799eea08350))

- **get_dag_from_qpu.py**: Added a comment and a fix strat for incorrect dag construction.
  ([`8bbe046`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8bbe046fcaf5f02d6c718ba0300b6afc9371c3b1))

- **stack**: Wip-stack-collection
  ([`afc2f8b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/afc2f8bf8f4ac2ddf95ac42410e7d7c4e8013919))

- **wip**: First pass of state vector classical checking
  ([`6f040f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f040f5693f5252982ce6c41a47c78aaf020b2c7))

- **zero-check**: Simplification iteration
  ([`32c2ce4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32c2ce45071c811303ac4337b0da63d38ba12155))

### Performance Improvements

- **64bit**: Much faster 64bit conversion
  ([`289de79`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/289de795e120f67b80103fea317274b5b1440340))

- **64bit**: Speed improvement for 64-bit checking
  ([`601128f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/601128f8a0c58d3a3c9feb8501e26717926af75e))

- **witness**: 2x speedup for witness collector
  ([`951e21d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/951e21df264b56b8553966d78c11639367e1701a))

- **witness**: Quick dive into why the witness takes time
  ([`9e287c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e287c2a3c44778e418bde70a9fabb2d7f16b883))

### Refactoring

- Change get_effective_rotation_epsilon and its catalyst counterpart to properties
  ([`3c979f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c979f011c62c3d3f682c97e2ec703703fc33398))

- Change weight to mask in symbolic PPR and PPMs
  ([`cda44dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cda44dd728418e5173d26e8121773d6a6bae83ec))

- Cleaning symbolic code for active volume of PPRs & PPMs
  ([`9f612b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9f612b6fa68002ba3cff4b887430b0cef5c9346e))

- Extract computing effective error_param into separate method
  ([`d058168`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0581682af48600a9d71eb4e33b6a13c8c98b40a))

- Get rid of _get_override_rotation_epsilon
  ([`7c144c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c144c7bc200d933e9c603add04d6f9fc80058a8))

- Get rid of _get_override_rotation_epsilon
  ([`6898136`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/689813627164a8e3169bfa446e636f9c965b199e))

- Get rid of get_default_rotation_bits
  ([`8299686`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8299686bc64a08a3ca5e8e24eea22755f8200c2b))

- Get rid of get_effective_rotation_bits
  ([`3f11da4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f11da47e505ab9429953e47753192c263963760))

- Get rid of override_error_param
  ([`549026a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/549026a358c925174aa445af75bd0b8ae0fc88ef))

- Improve interfaces definition
  ([`7e4252b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e4252b3863e9c76a1cabc7cda30f20c43bf246f))

- Move override mechanism to BaseQPU
  ([`5d57f39`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5d57f39ca0ad837fe301ce34d5394dcb7ab24294))

- Move rotation epsilon configuration from __init__ to QubrickSettings
  ([`8e1a20b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8e1a20b962bc702f13fc76ac78f67a31a03d0191))

- Refactor symbolic ops tests
  ([`0e8fbe5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e8fbe544ce40c526f3514307fb3321c4c84e7e1))

- Remove eror_param from __init__ method of QPU
  ([`867db40`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/867db40c8f838be0635f51bed95ebee5467b68e3))

- Remove old, unused implementation of rotation overrides
  ([`7b1206e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7b1206ef048e99d743689ffbb05b9dd5a8e95f23))

- Remove unused imports
  ([`0895c6b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0895c6b3458c5ae2d18b7252e9c8c97fed9c0baf))

- Remove unused imports
  ([`52a09be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/52a09be550c89da140094e8a86bed71c20e8e02d))

- Remove unused rot_bits
  ([`bdf51b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bdf51b8e58c3492705c08b7b8a0ad865c1e748b2))

- Restore "effective eps" logic in Ross-Selinger filter
  ([`70b0524`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/70b05242bebd24eef4e19607a1a809424a87081a))

- Restore previous import structure
  ([`53bfcbd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53bfcbd3f73ebe73bf9484329f2a467f08e29bb6))

- Tidy up logic for symbolic pprs & ppms
  ([`688642e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/688642e7f65da647a81bfcf97f03b7af7aef891a))

### Testing

- Add test for bitwise_and in parameter
  ([`0869378`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0869378fc19259592ea897d4c65b393c010dfdf9))

- Add tests for pull_state_specific in bit-qpu
  ([`82f1508`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/82f1508cf841157d76e2fc1ca868181a0a5bc4cd))

- Adding coverage for qint
  ([`cd19914`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd199145e3310b7062ae12bcc22c5467e6204289))

- Correct and improve the test cases
  ([`7b57197`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7b571976f10414a6e0ec9013d9f498dbcf38bbb1))

- Fix failing tests
  ([`0aade36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0aade36abf3b731939dca95a773e95989f0aff24))

- Fix typo (gres -> qres)
  ([`9598875`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95988756c7be46b24098e7293886b61bc55ce247))

- Improve tests
  ([`e896789`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e896789f54951b2621f838e8bfd1275916b834d0))

- Mark rotation eps symbolic tests as needing Bartiq
  ([`8cc32f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8cc32f119385c0989e5f37cce09f47143730adab))

- Minor fixes
  ([`118f49c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/118f49ccd544902374a63a28ae47a8214f0bbb4a))

- Minor fixes
  ([`fcde7a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fcde7a64716d5c4d643e705bca1e2596e0d72e3d))

- Reorganize tests and rotation parametrization
  ([`87e9fb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87e9fb42b8c4a19991b07494140721bf48a1c49d))

- Update coverage tests to use operator rather than private methods in most cases
  ([`302f225`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/302f225197272258c93729d759726b3d97bea12e))

- **bit-sim**: Add tests for bit-sim
  ([`817b9c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/817b9c94e57d652d659e8fadbe8645ae6e40d26d))


## v4.31.2 (2025-12-18)

### Bug Fixes

- **cicd**: Remove --skip-existing to try to work around a CICD server issue
  ([`17d7c28`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/17d7c28d7e41580355ad3a482c6b88dd8b890bcd))

- **cicd**: Remove references to core_expiration.cpp from build and distro
  ([`983306a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/983306ae8fb9f21c00ff89225f929aa9a729cee5))


## v4.31.1 (2025-12-16)

### Bug Fixes

- Caught bug in calling none ctrl
  ([`14b4a95`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14b4a95d0d3c3b2f7c4334a1f58cfcf2f9e84880))

- Change to list of messages to allow for mutability
  ([`684b0b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/684b0b41cdf9fc9e9644ef9f044bde0be71eb688))

- Docs misprint
  ([`20f24f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20f24f08004c6e56a78c4864fb2b8e4edba8ee65))

- Forgot about elbow->x replacements in filter
  ([`a43d4bf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a43d4bfad70f65b31d0f8d3e6c4d24883daef441))

- Qint range and type hinting
  ([`f0abc73`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0abc739667e0d86f523852d39b5f656f8339ba4))

- Running more tests of filter mux issue
  ([`c0b5f72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0b5f728e0340cee56fe505fba094240a678f740))

- Something is failing with the filter which is only obvious with MUX with grey counting
  ([`1a0c2be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a0c2be1d7bc4503557e13194655df8be89bce46))

- Workaround getting new message in qpu debugging when warnings turned off
  ([`3ae4881`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ae48816a1eea21c9fdc0a4a4b9f553eb22f09bc))

- **cond_xor**: Fixes for invalid cond_xor constructions
  ([`e118c34`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e118c3463665e9dd6ff412d9acee29aadc41c499))

- **MR**: Fixes and cleanup per MR feedback
  ([`0b2b105`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b2b105a3713eef40f8fe5834407882e9f0f921c))

- **MR**: Fixes per MR feedback
  ([`13ee056`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13ee0560924b41c0174b0cd4f2567a0755e78500))

- **poetry**: Poetry lock
  ([`133e8fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/133e8fa7b5e81fe6573e950a43bab760f1f0fd4c))

- **test_ops.py**: Removed failing test cases from
  test_controlled_phase_special_angles_numeric_theta as they are not valid equivalent comparisons
  when written as controlled operations.
  ([`32f9caa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32f9caaa4bae2e920ba1941d5a8df663a36f18e2))

- **tests**: Remove capsys from printing tests
  ([`dd743a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd743a869c9ad3ec95581ee6c5f4d52cec71756b))

- **tiny**: Very small fixes
  ([`b617504`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b61750445773ec2a794b6d75c4158ae45c7f8843))

### Chores

- Add do_draw to test_arithmetic, delete plotting notebook
  ([`e19c716`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e19c716e165da366d4127cc5e356041b79c106cb))

- Add type hints, add extra test for filter problem
  ([`eefffcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eefffcc6f4a1b1f152a571b2491c3a72fd4a3124))

- Bump version to 4.30.6
  ([`18df0c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18df0c5f46c9cef08eb97146f81d7ae5449bdb86))

- Delete notebook
  ([`054801c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/054801c3ddd509ab4c95505c6387f28ffd1d63a0))

- Expanding cov
  ([`6fc70a7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6fc70a729bffba7134fedf141383128bf67aaa38))

- Fix in notebook and adding helper functions
  ([`7686d22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7686d22f772843fad9dbd882c2f18d5efbef3352))

- Fixing ctrl so that adder interface test passes
  ([`90eeb07`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90eeb079b1f7f86fada10ba60d4e7949bb71ea25))

- Fixing type hinting, adding seed to tests
  ([`e2e11c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e2e11c1f991506e1d9ffc0687dad57fe0c70cd0c))

- Incrementer was occasionally including one too many ancilla, extending test cov with previous
  adder tests
  ([`98d47e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98d47e386ad766988264961bde2f211b9572b506))

- Linting
  ([`b52dc33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b52dc33cf0335c0e7746894fa255c7529811a3b0))

- Linting
  ([`7aac322`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7aac3221994420e6b5caa6a33bb5a89ba3e1bdb0))

- Moving filter and expanding test to all self-inverse ops. making qubrick names more verbose and
  fixing minor ancilla logic bug.
  ([`ce752c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce752c9826a8e13673db4da734829f3e6876c42e))

- Removing same functions from example notebook
  ([`570076a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/570076a7283d2edb589b5bb4ac1bf931bcc7d834))

- Removing unnecessary helper functions and inputs
  ([`9a36ae1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a36ae1f79bf33990c0d990cd7f3dbd7431ff384))

- Update basquiat-adapter to 0.5.0
  ([`545777b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/545777b7c82df9f936669f5c38a04adb7a5d960b))

- Updating example notebook
  ([`fc57155`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc571554e0413806f53dffa6c38e118a8c658d1c))

### Continuous Integration

- Added release stage
  ([`db67ef2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db67ef2282cbaa3795e052458396e7fc86f12aa5))

- Manually specify number of runners
  ([`cd01c6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd01c6e7c520960224dfdf4523781598b7dab7dc))

- See if 2 workers does better than 8
  ([`01153b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01153b70a1e941d7bad9022d660a6ccd15c89c8b))

- Set number of pytest workers to 8
  ([`0143942`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0143942f82efc34e5c08eb03a179dab4ebdb5d49))

- Test performance with 4 pytest runners
  ([`fc8d65e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc8d65e7433335f86ca7f3d765c2f9106c6b7ab1))

- Updated dev-ops/common include reference from 0.0.8 to 0.0.9
  ([`2f306c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f306c8cfcdbc9922917583fce07ecf8360b01e3))

### Documentation

- Adding a few fixes
  ([`ee7856f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ee7856f590ecb718713bcdd41d4a44fc4eb4e1c1))

- Adding batch filter messages, and more drawing
  ([`c0439ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0439ec6d419eac38beeba6f1318402d27d59a7e))

- Adding clarifications to the compilation pipeline outline
  ([`a70ebc4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a70ebc40692722c5b92502dff1d1b359c0ba8e74))

- Adding conclusion and edits from mariia
  ([`281a99c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/281a99ca2414ffca337cb9ae1d83e14bcf538c18))

- Adding deepdive feedback
  ([`9312801`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93128014c04d6ef542524e1af62726c87413c6be))

- Adding examples to pipeline deep dive with extra verbosity to be shown during some passes
  ([`6a4be41`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a4be4107f02c2c904561dc99e9a739c6eed80f3))

- Adding explanation of register type printing to testing-debugging notebook
  ([`e05cdc7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e05cdc7a21f78ab06cc659b6c5a6c1dafc36c67d))

- Adding fixes to docs and examples
  ([`986230b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/986230bb1b6c18c7dc34f702a3db66c6c1ba7dc8))

- Adding more to outline
  ([`b7754fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7754fa066f198a855ceb3f098b33bb7ad4208e1))

- Adding outline of compilation deep dive
  ([`542d12a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/542d12a899b0a9eb7f9feace0ba26158de65cfbc))

- Adding rough draft text for QPU section
  ([`6bd62a1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bd62a1601702d178d93b2698acac261fce0c1e5))

- Adding text and examples to the compilation pipeline deep dive
  ([`f192d8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f192d8c31f45693480f8e3463cf1e9cb338b6689))

- Edits for clarity, spelling, and grammar
  ([`e5f1a5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5f1a5c06d040dddde24ea52022a2a1543f13c12))

- Filling out links
  ([`777de1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/777de1abe734174f39d1a6c309cd0d2be6888c71))

- More edits
  ([`e9d7802`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9d78022be4c8da8b263a48f802d7ae47f9f68f5))

- Remove autoreload, add to mkdocs
  ([`f84cb4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f84cb4ddba059015e9373a4013155eccb22f552e))

- Sneaking in a typo fix
  ([`55cb70e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55cb70e91cdfd6a086adfb1ec64cf1d81db6d4c5))

- Updating docs language and tests
  ([`9102361`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9102361cc3f708e927a741a0e394860005e91d8a))

- Updating title to match file name
  ([`4b93234`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b932347c379663c41375cf323586fd944d4b495))

### Features

- Add docs references, add QInt testing fro incrementer, adder. Remove cond input from
  CondCleanBuild.
  ([`a76df47`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a76df47db8ec6ff2cd871699de847280a7c86740))

- Add initial typing to print_state_vector
  ([`291aae5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/291aae53ec42422d3fd636f178a6418cff99e951))

- Add padding for floating point values
  ([`9ae2cf7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9ae2cf7aeb66028eb729b9d5dbcea8963d7a1d02))

- Add witness_qre-analysis serialization dialect
  ([`f2b0717`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2b0717d77a1821c9944fc05f3c61ccb19a160d0))

- AddBase versions tested.
  ([`e50522c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e50522cf287e480bff0fc3e0f82ab21a0bf79268))

- Adding QUFixed, QFixed tests.
  ([`a9c411d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a9c411d3b704670eba0850b1cb2b7c09b24bd8d6))

- Adding sorting for typed register values
  ([`4791fad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4791fadd08d3fa2e50150fc237b6d0edfd448275))

- Changed filter to work for any self-inverse op. made partial_compute qubrick to avoid reverse
  input and utilise dagger. small chore's from MR feedback.
  ([`fe8affc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe8affc999df047fc3b8849296b96b6aef354fb7))

- Deleting dead code, adding more comments, temporary tutorial notebook
  ([`4019e4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4019e4b01cf21955d69592576719608423281711))

- Fixing argument names
  ([`bef26ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bef26ea265b5bd6927304e327d438e2548bbbc68))

- Toffoli window filter with cond clean MUX
  ([`3d86744`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d86744edb1dc3688ae0311bafbb8c1b873becf6))

- Transforming adder to AddBase and making ctrl case apparent for incrementer. Notebook with
  possible bug case in AddBase.
  ([`387c347`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/387c347dff18275ba7107bd698014b41bc0adfc1))

- **get_dag_from_qpu.py**: Rename instruction_dag to operation_dag and update related logic for
  clarity
  ([`84720b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/84720b77be18671dad4c0ef92686a2e44a683dc8))

- **get_reaction_limit.py**: Speed up node removal
  ([`652fc34`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/652fc34b3044b10aa3b8e9d27dd1181345e8423a))

- **gridsynth**: Add pygridsynth and mpmath as optional dependencies
  ([`9e80ad9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e80ad9a7beef4821466f069531058c1c14d879a))

- **pygridsynth**: Built-in support for pygridsynth
  ([`f9ae7b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9ae7b8ec0b967697499af39515cd74c810f02b0))

- **synth**: Allow selectable synthesis filters
  ([`3af9b6d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3af9b6d6e0c5535eb8f754604fd265a2b476f324))

- **visualization_tools**: Add newlines and progress bars
  ([`c624c44`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c624c44786feb828c60164d7825036094723212e))

- **visualization_tools**: Enhance progress iterator with improved ETA calculation
  ([`6f05c10`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f05c1000ca7895869d0cd86004aaa6c67e411c8))

### Testing

- Adding tests for new typing with print state vector
  ([`60f4dbe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/60f4dbe0c83be3fc597a29bd0f5936fda31ebd62))

- Adding typing test
  ([`8bb0744`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8bb07446963f512cc3dbc8a904dd981fe5908f45))


## v4.30.6 (2025-12-04)

### Bug Fixes

- Add fix for old parameter
  ([`26f6f7d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/26f6f7d70d5cff5a576b48f1cc5f043b661811dc))

- Adding rel and abs tol to validate to prevent WBA upstream failures.
  ([`13cf64c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13cf64cd33f8d46964a156f59934b2ce7802937e))

- Bounds check Nonetype
  ([`8533258`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/85332587bba036c7108e08f7618ce541f5248e99))

- Fix av cost for 0-target lelbow
  ([`f80e6de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f80e6de9a4cdf54ac616ff7e8c3fd7c3b154ab5d))

- Fix bit length calculation
  ([`5c3b590`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c3b590181477a044b1e2f8c100404dd21d045f1))

- Fix lambdified resources for assert_resources_equal
  ([`cbf561b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cbf561b70769a11e5412a4d7d2343eea1ae4d8a2))

- Fix test_elbow_av_calculation_from_get_av_from_op_symbolic
  ([`b978355`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b978355c88f07a7b070b10a120f36cb34552fb0c))

- Imports in qubricks.py
  ([`cf09c91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf09c91c74d31a190f217ec136789271ba254c39))

- Lint
  ([`5d0666c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5d0666c393cacebfa47c9701224b1e72ecb03ce5))

- Simplify logic for get_gate_cost and fix 0 for s or z angles.
  ([`7533bce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7533bcec0f9cc78d3c1553d84b8cba9860cff1fa))

- Symbolic qres for controlled adder (and other qubricks)
  ([`2a4df69`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a4df6953ab6c77f2f7c9c648955ee243d051083))

- Testing downstream qdk triggers
  ([`28c1c3c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/28c1c3cc5fbe28635fe3561c71b1e360cb81846b))

- Update av costs for symbolic comparators
  ([`75e1431`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75e143105d5d80ad78bb0937ce3bf25f72474234))

- Update QFT to give correct AV counts
  ([`e749bd1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e749bd1403cd78b37d9a71debf011fcf80811f3b))

- **_op.py**: Changed double quote to single quotes due to issues with f string.
  ([`5dc3c50`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5dc3c50737aaf94e0938e6a80ffb64c57b7051d5))

- **_op.py**: We now only trigger validation logic for numbers, i.e. symbolics are fine. Also allow
  for target = 0 so other tests pass.
  ([`5b800c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b800c26ccf4ee0559f7398308579c3052176e10))

- **build**: Fix setup_legacy.py
  ([`b03b0c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b03b0c8ab904f8c32625bb901c53597a137d5476))

- **cleanup**: Migrate namespaces form Tau to PsiQWorkbench
  ([`7e6cf05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e6cf05849a4f338496bac2907ede2d1f7c5ffcc))

- **cleanup**: Move exception to a warning
  ([`7d6d10b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d6d10b7505ec0c85700736e1ac67b1bdc9de223))

- **cleanup**: Remove cpp from docs
  ([`4f929d8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f929d8296aeb737d976a1557bd60e38c09b83a7))

- **cleanup**: Remove straggling refe to the old lib
  ([`dbe1d7f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbe1d7f43eb51c14f956aa65905bf82541fb75c1))

- **cpp**: Cleanup on C++ rework
  ([`adc0c5a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adc0c5a29f1a287344fe6e572efd81b5b2b53054))

- **cpp**: Iteration on C++ refactor
  ([`f3b5426`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3b5426b85dca2b43b96973563716a1ff97db3f7))

- **cpp**: Iteration on C++ rework
  ([`56d0d98`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56d0d984cf6488ed5f6cea86380f335378ceff74))

- **cpp**: Iteration on pybind11 removal
  ([`8695e88`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8695e88fe9ea775da73ad2ab63eb6ad3c311547c))

- **cpp**: More iteration on C++ rework
  ([`cc423b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc423b2caf6c77d0d2496ee0bc26b7fdcb0ed0ee))

- **cpp**: WIP for C++ rework
  ([`bfbd5e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bfbd5e460b8c81047c9b5e7004464511268f4ee7))

- **cpp**: WIP progress on C++ refactor
  ([`7bcf31b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7bcf31bad59e2470f44567443bd598d781fca383))

- **docs**: Fix warning from mkdocs
  ([`03e7c13`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/03e7c138a81eee1748b44b48a385f47065f70f5a))

- **expiration**: Complete removal of the license and expiration systems
  ([`4af91c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4af91c2a8e2396f3033757baa567ea59efd8005a))

- **get_av_from_op.py**: Accomodate symbolics in lelbow
  ([`fb614ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb614ecd7a249759597417610707559a87a8f30c))

- **get_av_from_op.py**: Allow for no symbolics
  ([`9446bcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9446bcc883ea8c8b1df56310d74e06a93ab770c0))

- **get_av_from_op.py**: Get rid of sympy
  ([`9f68bea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9f68bea99e59b223da38efcec453fa85848aa14b))

- **get_av_from_op.py**: Is_symbolic
  ([`294db4c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/294db4c48aeb3ae86b1ffda21b16c12c178688d0))

- **get_av_from_op.py**: Tests pass
  ([`8d9b5c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d9b5c4acf53ff8164480b931e04bb4cd7d2f956))

- **lock**: Update poetry lock
  ([`d159eba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d159eba7b97bcb2d4d442dbc292da464569dece0))

- **pybind11**: Set up more functions for external calling
  ([`3f21beb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f21bebb31cff687188f9ff152046c662dadbade))

- **pybind11**: WIP on C++ overhaul
  ([`c0dee20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0dee201ff6ddf7a5b49793bbedcce1ae87f29e9))

- **python**: Properly incref None to fix tests
  ([`0357275`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0357275a95eecf3f33eb1e4d2cd4039a4258d369))

- **test_1128**: Move to tests/qre folder
  ([`e8fa38d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8fa38dd0588d9cf79b11948c6d34d853d829bf0))

- **test_994**: Move lelbow tests to test_994
  ([`bbd652e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bbd652e870cab07d4b6f4aaf33ef1857ed8f9590))

- **test_optimized_multi_target_elbows.py**: Add symbolic tests
  ([`2669d10`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2669d1044bff361caeea27526f71eef4fcefdfff))

- **test_optimized_multi_target_elbows.py**: Rename to exclude number.
  ([`fad45ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fad45ef38a37dce104dbff8814a3e609f743c8d5))

- **test_optimized_multi_target_elbows.py**: Specified conditions
  ([`6886174`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68861742477eaa153717802e8c7aef7435634e01))

### Chores

- Accomodating phases and rotations for gate cost
  ([`6babcd7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6babcd77c3723f9baa000cc69ab18bf867946341))

- Add xfail and relevant comment for failing test for compare_av
  ([`7bb0d29`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7bb0d29ccc1b62e2d9e875e47945bf00ee6ea65d))

- Adding additional angles to test_rx_ry_right_angles_uncontrolled_symbolic.
  ([`6a5cfd4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a5cfd47db35a5d484d0a30d702bcf23f6038ee9))

- Adding compare cost for ref and cost in compare_costs
  ([`15509ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/15509ead986d0b9565f39bdf9648c86b75661fc0))

- Adding tests and removing isclose functionality.
  ([`e71d79d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e71d79d435de77921b6d00a22dbee2b2c874c8bb))

- Altering to a Pydantic dataclass
  ([`3c00e29`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c00e29c25d45af253404cd4e5f3259eb1abdf7d))

- Broaden numeric-like handling in _normalize_resource_tolerance
  ([`3d452dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d452ddb878779ada68ee35b6c26b5090e186761))

- Bump Bartiq version to 0.16.0
  ([`933bbd6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/933bbd60cc98dbad5ec57c8de4f8f72ec40e2f64))

- Bump version to 4.30.5
  ([`9b47802`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b47802b99f8bb9591ea24735f309fa90e469b7a))

- Condensing test cases for controlled slices
  ([`0996f23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0996f232860929910039eaffeabd9c5e77eda076))

- Consolidate tests
  ([`a0d13f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0d13f5495947f66f594bffd5e13e9a9e90c6f18))

- Empty commit to trigger GitLab
  ([`5dd728f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5dd728fd908c503cb88bcc1282f4c997eb7a6c4b))

- Enhance testing for test_ops
  ([`e7d0fc6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e7d0fc67e6650758d9ea244c6e4f3d0eb7cce32c))

- Enhancing test for rtol and tol
  ([`36028fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/36028fa36b6d3ee54d8c59393785907f40e3a409))

- Fix lint warnings
  ([`f0ebba0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0ebba0fb6a6d979ad4339d62aff276c6e366631))

- Make ToleranceSpec not return None but always return ToleranceSpec
  ([`263c00e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/263c00efa8d53cc2b7d5fb0619c1cb3dd3e8ebdc))

- Merge master and minor update
  ([`27c31a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27c31a6425b8b88c377e96529dd2d1485adf41c4))

- Merge master and minor update
  ([`f5d8ce5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f5d8ce5b9e07fd4f2f7dea298cf4aeb2155a0023))

- Minor cleanup
  ([`a7ffd33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7ffd33615f4ee1c8345f47cd1c5faf5f6aa4573))

- Minor tweaks to comments
  ([`0963c2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0963c2a313201b36b3d0d97bb6dd1802490b26a3))

- One approach to using resource tolerance
  ([`24c2ce7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/24c2ce7d8623436516410d885b3b2c8eb2a6eb76))

- Reduce None for tolerance interface
  ([`3c04cb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c04cb4c0dc8009ee5de4ba978f3bb8a8b88cc13))

- Reducing constants for theta angles
  ([`cdc6dbf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cdc6dbf1a6c63e640dba819d361a2a437cd32832))

- Remove test_special_angles_symbolic_get_gate_cost test
  ([`9acf810`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9acf810967bc265ca9b60d1d738ab45d2a6b76a7))

- Removing comment
  ([`dcd49d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dcd49d5058f88414ab3c071024f62d7cea56e236))

- Removing unneeded block of code in test.
  ([`ef3e141`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef3e141109a4b4002cea49955da74123f3e2496b))

- Rename expect_op to expected_op
  ([`086a720`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/086a720834ba22bc6b7bde1b2c6ad2efc578204a))

- Rename qa_n qb_n to qbts_a and qbts_b for consistency
  ([`11dc889`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11dc88991363a7a19a1f3323a58677b15e448526))

- Simplify tests by passing Qubits
  ([`206e8b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/206e8b39e6a2e0d8e11f57b6585a9a4379ece526))

- Update codeowner file
  ([`89c11d9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89c11d94ca356fc02390f1f7b49e0b25b21ef75a))

- Update to exclude
  ([`c41895e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c41895e6a200e55ff656ed7f2b9c60a3db32a030))

- Updated _validate_cost_with_tolerance so tolerance defaults directly to an immutable
  ResourceTolerance.
  ([`4e942e6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e942e6e84a683810788defa8b6d26183b2f479d))

- Updating ToleranceSpec to a frozen dataclass
  ([`1f5806f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f5806f20160e6735d9904b90c0be925beca89d2))

- Use field validators instead of post_init
  ([`a7b4035`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7b4035074a6895093bc2922cf5425aadbe4575a))

- Using conditions for heaviside logic in gate costs
  ([`7b21042`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7b210421eeba4583b9b71c45e2ab5deae0d3bdbe))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`70ace81`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/70ace8172f20eeee80912f8e7455b2c0213671d9))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`6787ede`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6787edeee5f58d10f97b0ba87b7ae06229104c3c))

### Code Style

- Remove unused import
  ([`4da2048`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4da2048812867d0f095d1f3b18985905c615d499))

### Continuous Integration

- Debugging manual job
  ([`2593d20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2593d20da62016173e0a0641c34e52da97005bf0))

- Don't allow failure for docs warnings or broken links
  ([`4c82881`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c8288118a3c4065e6c363ad8370f708c605ce3b))

- Updated psi-qdk trigger jobs
  ([`0090144`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0090144a3ed1027da3c871e25a6cd258c9a05a86))

### Features

- Add random.seed() in set_param()
  ([`98b46f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98b46f76a6db9eda65e5474ade775dc59ecf8209))

- Add support for zero target T, S, t_inv, and s_inv stale count
  ([`62fc985`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/62fc985125b612d11458cf81cbde4310ad503c83))

- Mark RotationCatalystStatePrep as first-pass only routine for Bartiq
  ([`57be062`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57be0625ed87156e081487f3a128e7f38d360375))

- Optimize mutli-target lelbow AV
  ([`4165ddc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4165ddc780d40f2194026c0b9b633f1d1637f51f))

- **_op.py**: Added code to restructure_op that catches SWAP gates that have invalid arguments.
  ([`4cb0bde`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4cb0bde79ad2a418da331e94d2b32357e45e5138))

- **test_1232_swap_gate_target_validation.py**: Added tests for new swap gate validation code.
  ([`6128af8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6128af8fa75d05cc79b1b812aace2d6082524f23))

### Refactoring

- Change is_pauli to is_opcode_pauli
  ([`021ddbb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/021ddbbc84a955f0b70acf1616028268b2b12b8e))

- Get rid of qubrick_handler class
  ([`49bf786`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49bf786e337f369d359275721ee6f2de3390c193))

- Remove unnecessary commit
  ([`1064d42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1064d42db2b5af024b81fed9e5606970ca15f844))

### Testing

- Add tests for repeated nested qubricks with rotation catalyst
  ([`5a3c190`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a3c190784205dda7e50487fd59f2eaefb66e364))

- Add xfail to QFT tests
  ([`c879a6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c879a6f27afc2c29af0d769695a181a1f86862a4))

- Fix tolerance for av in comparators
  ([`40ac69d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/40ac69da68fc5ce8d629076f4f85afb2511797d3))

- Minor fixes
  ([`b2db1d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2db1d353e346c86ccd87add6f5d4ed2a2ccaaf8))


## v4.30.5 (2025-11-20)

### Bug Fixes

- All resources except AV working
  ([`5981ecb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5981ecbd0343ae16382c91253c1b452461a55e89))

- AV working, code needs refactor
  ([`6704a4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6704a4b544514061888574d2a2515c8832ac2b26))

- Fix issue for handling specific angles for rotation catalyst with symbolic size
  ([`3348ca7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3348ca797fc2a27663e4ddd8b64373bca02089da))

- Remove atomic attribute from Parameter
  ([`97fe781`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/97fe781fb7cc4a6fcce3e902ceb77dcbd99b60ff))

- **active_volume_lookup.py**: Made lookup table entries occupy only one line.
  ([`bba0141`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bba01416521df55659ab8334956c0e6933e8b5b9))

- **active_volume_lookup.py**: Simplified some code as t_cost is the same as reactive_t_cost.
  ([`74dd93c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74dd93cdc42b0ee45f7d3e8a8cbaad14a7673961))

- **coverage**: Coverage and cleanup, removal of unused stuff
  ([`05be19f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05be19ffd5ac8fb8dde7ffeea9dc641376c7f811))

- **coverage**: Coverage WIP for #1236
  ([`b7b7046`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7b704685eec78fcaab4c6895f3c268028b4ea2d))

- **coverage**: Increase in coverage per #1236
  ([`8fd24e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8fd24e468a83094db7827bd7b3886085d19c4950))

- **coverage**: More coverage improvements
  ([`d0bd3fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0bd3fb1f8688615e15f310b1e3146c6ac481e7e))

- **coverage**: More coverage updates
  ([`c407f19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c407f195981ac413a8c58d47a345f2b777448fb8))

- **cpp**: Minor cleanup
  ([`8b8d3e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b8d3e928675ed59f59d1b165106a663293502b6))

- **cpp**: Start by removing cpp functions we've outgrown...
  ([`3e367d9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e367d9b1b632369c06ed6f6709a265571ad2db2))

- **cpp**: WIP first success at c++ rework
  ([`d0cf504`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0cf504795b839aee184f4f80865eb66a274b261))

- **cpp**: WIP on C++ remap
  ([`13d9289`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13d92896cdce6ecd1f7125cec276e2312ccdb628))

- **cpp**: WIP removing pybind11
  ([`ce333eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce333ebb9a6d6fe81d9900e00cbae9535d2c0c79))

- **expiration**: Push expiration to Dec 2026
  ([`6960a04`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6960a04f0e8ad8f265cc02dfe1c7e7d9c619d3b7))

- **get_av_from_op.py**: Added 33.75 angle to _get_av_from_qpu_op_ppr_symbolic function.
  ([`ccf2ffe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ccf2ffe7755efc1fb4805280f0af5dd0573d8d8a))

- **get_av_from_op.py**: Changed divisors to integer divisor for if states in the numeric and
  symbolic get_av_from_qpu_op_ppr function.
  ([`bb3b993`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bb3b99352f0d7db51c3d65d619ce63d1c509cbda))

- **get_av_from_op.py**: Fixed ppr numeric and symbolic functions for pi/16 and 3pi/16 rotations.
  ([`9959db3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9959db3e8fa10908715fd6064b98438dd94e4192))

- **get_av_from_op.py**: Removed white space for linting.
  ([`944c122`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/944c12283b0b11b7af30ed24299940656a9147b1))

- **get_stale_state_count_from_op.py**: Fixed 33.75 and 11.25 identification for the
  _get_stale_state_count_from_qpu_op_ppr function.
  ([`8cd8e03`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8cd8e0384345e32b7c29973cf34e5d876581d52b))

- **get_stale_state_count_from_op.py**: Reformatted elif logic.
  ([`42e849c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42e849c0e3ee215637a8c4503dea472861b060cd))

- **get_stale_state_count_from_op.py**: Reorders thetas to be optimal.
  ([`10d2fff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10d2fffed76136b4f7eeecccdd3f59af3ec536dd))

- **MR**: Fixes per MR feedback
  ([`f02d4ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f02d4ee36cce011611d16c878e31a937bdc4a109))

- **MR**: Use parameterize, per MR feedback
  ([`75c5199`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75c51995790616bb2b825c2e89622a492aa04702))

- **ppm_functions.py**: Updated docs to point to the new note for PPM formula.
  ([`41c4f00`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41c4f00e71bee1f9e5c70add0b65c1cd850864d7))

- **ppr_functions.py**: Changed import to t_gate_cost rather than the now disused reactive_t_cost.
  ([`a7046bc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7046bc440decd144f7ef2da8e9bb883f699e5fd))

- **ppr_functions.py**: Fixed typo in docs and improved readability.
  ([`3dcd36d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3dcd36d4d52b05e84c96a09c5399ba905aa967b6))

- **ppr_functions.py**: Imporved readibility of the _get_3pi_16_ppr_av_cost function formula.
  ([`1cfa919`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1cfa9198a9aeb5a9f3eccd9daf3dac4bea88adbe))

- **ppr_functions.py**: Improve code readability in _get_pi_4_ppr_av_cost function.
  ([`b04777c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b04777c6e94c8269747844a9ccf4f7a56c2a8796))

- **ppr_functions.py**: Improve doc to provide a link to a note and state how classical interpretion
  must be updated.
  ([`e612361`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e61236150ad31520f70c7aaf7f27775fbaba841f))

- **ppr_functions.py**: Reordered lines the _ppm_injection_cost function.
  ([`ba13f9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba13f9d01277740b6b7b22d312bf56dfa4b0b7a2))

- **ppr_functions.py**: Updated doc to say corrective measurements rather than reactive.
  ([`3105347`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3105347833f9198a355c70935142b555d3f0f8cc))

- **ppr_functions.py**: Updated doc to use or new definition of reactive and conditioned corrective
  measurements.
  ([`0ebbed6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ebbed61abb7e30d7419735cf5078037a569988a))

- **pybind11**: LARGE change: complete removal of pibind11, WIP
  ([`5ecd865`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5ecd8651ffeec22e1ba585f99a00a85c767d91b8))

- **test_1063_create_get_stale_state_count_from_op_function.py**: Updated
  get_stale_state_count_from_op tests to include new operations.
  ([`3d10678`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d1067810c293267538f106bbf77d522f99a0ff9))

- **test_1113_y_parity_in_av_cost.py**: Fixed the tests in 1113.
  ([`84f4094`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/84f40945188067636e34c8c132bfdd726aa06cf7))

- **test_1113_y_parity_in_av_cost.py**: Updated test for 1113 to use the corrected AV for a single
  qubit Y ppm.
  ([`56b6dbc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56b6dbc4833a12ac4ba255d2ffab6bbe42ff9d3b))

- **test_1209_single_qubit_ppm_av.py**: Updated another deprecated function call.
  ([`98285a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98285a3842e218adeedb49652bdd489aeb1774da))

- **test_1209_single_qubit_ppm_av.py**: Updated from deprecated function call
  ([`9d3af2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d3af2e18a181a2143674e6487e32214b67a3385))

- **test_native_dialect_numeric.py**: Fixed expected test results to match new AV formulas.
  ([`f229560`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f22956019229715b51d4c56a71e4e18059004335))

- **test_native_dialect_numeric.py**: Updated hard coded AV in test file such that test passes
  updates to AV costs.
  ([`f792d42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f792d42febcc87436c57d58f63b01518fdb70bbb))

- **tests**: Restore reverse_bitsa and add coverage
  ([`8a69f67`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a69f6765029040d50edcfd5d6fe761f278e3efe))

### Chores

- Bump version to 4.30.4
  ([`ad87794`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad877944ec51f30f8682d3148c440cec263db6bd))

- Clean up some pieces of the reworked tests
  ([`55385c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55385c13da541815e82aaa3e9a1adb343d0e0fa3))

- Remove Qubrick statefulness
  ([`499a62b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/499a62b0ecc9c6c92c154e90c9995e7aeb684e83))

- Removing gate_costs_v2.py
  ([`f89da58`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f89da58bc908610e6c7b9b0f6ed695175400ab9d))

- Update codeowners
  ([`f0dfc3c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0dfc3c0165d6ff86e0ede258636d4b7cf709c2a))

- Update codeowners again
  ([`a062d08`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a062d0887f5e3642b188644219434d7111848874))

### Continuous Integration

- Run examples in serial
  ([`42b5476`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42b54767cf74240dad0c897a27e6f9b41c056386))

### Documentation

- Add 'Built-in Qubricks' tutorial
  ([`95a98ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95a98aea44478db762c5e2b5742532964dceb903))

- Address reviewers' comments
  ([`75dc605`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75dc605a3f4a64b99dfaad1a77e9cbf695f191f8))

### Features

- **active_volume_lookup.py**: Added references to AV derivation files.
  ([`ded1748`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ded174858d7fe4f71bb7ab385871d7c74a4b840a))

- **ppm_functions.py,ppr_functions.py**: Added doc to link tl formula derivations.
  ([`453a186`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/453a1866b905db09955f2db87a0fb06ec65cf56b))

- **test_994_create_get_op_av_function.py**: Add a comment to explain the location of CX and CZ
  gates in the test file.
  ([`d1a4e79`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d1a4e79fa5db57048d01ec6abfe126abeb200e9a))

- **test_994_create_get_op_av_function.py**: Added more tests and fixed test values for new code. CH
  is not a support op also.
  ([`6e28e6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e28e6f834df00bfbf3970f739db08468b93e644))

### Refactoring

- Minor refactors
  ([`8b4ed22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b4ed22cfcb75ece96887e94e0ac39eefe06006c))

- Update code for symbolic AV
  ([`53e85d4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53e85d466ca57a9a3e14e274cbf7329166721277))

### Testing

- Converting to operator norm in one more test
  ([`11ab1ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11ab1eefdf9fac6438eb6adde7490cc189d5e694))

- Use epsilon instead of bits of precision for Ross-Selinger test and update to new operator norm
  ([`e8d0f9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8d0f9d8cedeff0ed5db3f4dbf280aa21a9effd2))


## v4.30.4 (2025-11-06)

### Bug Fixes

- **reflect**: Handle error_param=None in reflect Qubtick
  ([`1d45720`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d45720ce68591e3c1148a5448da2e2536945360))

- **synth**: Fix for not-conditions in rotation synthesis, and re-run notebook
  ([`75da03c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75da03ccead6b0ac684a5466782528d0aaebd12f))

- **USP**: Some fixes for USP, and the characterization notebook, first pass
  ([`b06a836`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b06a8365ec5b8554b5175dd09705ed9b5b8759e5))

### Chores

- Bump version to 4.30.3
  ([`82939f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/82939f0687f2b3ba55c97198b1c08c3d53a71696))

- Removing unused variable
  ([`ed5d729`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ed5d7290693f6ef9d3d38ac7a4b8aced90be0a23))

- Skip tests that require bartiq or sympy
  ([`a46f1db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a46f1db4d2f4867011f0d34299d20a1ecb073ba1))

### Documentation

- Add 'Controlled Qubricks' tutorial
  ([`7da0d34`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7da0d34a28a3bb8ee04f5def18d521f5ed1cca20))

- Add allow_multi_qubit_ctrl info
  ([`1a6b9af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a6b9af644243758ba829b1f2a029c0c16f8d479))

- Remove accidentally added link to QRE reference
  ([`4a51f99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a51f99397c2602b187cadbb7d1e1a8ef1bdbc6a))

### Features

- **notebook**: Characterization notebook, second pass
  ([`40fed84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/40fed84e07045cf859abc2c5d1ccb59e58014811))

### Testing

- **synth**: Add a test for the synth fix
  ([`eb027a9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eb027a96c2e96ebabc4984ba8c6b240299333746))


## v4.30.3 (2025-11-03)

### Bug Fixes

- Actually use ntz instead of nlz
  ([`8b0b85f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b0b85f56c5589bb51ca321279142c263d8e3232))

- Add missing _type_aliases file
  ([`a8853fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a8853fef7661d6e91aa8a23cb04fed36fe7aeeff))

- Adding min_val_to_print check for qregs
  ([`5eef931`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5eef9313da87af0e69376e59263313d8baa69507))

- Attempt to fix broken test
  ([`0613cda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0613cda72b1d410350b33368a102236bdde5a4e1))

- Ensure resource estimator is not expanded when constructed with factory function
  ([`4496733`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/449673369421ede7bacb6f55e2572ff02ec32b39))

- Failing test
  ([`5526ebe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5526ebe4e88f755c6fd40a951b3b21b5b702c67f))

- Fix some type annotations
  ([`cbb54fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cbb54fa07dc3f7811abe78a4c8df3ec957e3a8d2))

- Fixing bug in roll_left and adding verbose check in qubrick
  ([`df521a9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df521a99b4e0a979d4012cb56d379faea029fb87))

- Fixing tests and updating comments for new code
  ([`9876b90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9876b903ffca1f55fce5ad248c03549f7f827edb))

- Fixing typos, adjusting phrasing, updating warning
  ([`a94c8e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a94c8e42a1ec3f570b61561fc992f21e967a7373))

- Formatting
  ([`71bfd2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71bfd2a58eb10dca8b018b174184670a637798ef))

- Handle phase fixup correctly
  ([`903f842`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/903f842fffdbc5a8d4cc3cddb0fb84c4c4e92344))

- Make estimators non-expanded by default
  ([`fca2c15`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fca2c15838cf92ec9b6e2d6faeda25275d3f6180))

- Make tests runnable without Bartiq installed
  ([`69a7732`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69a7732e18fe6dfff23c23cd7ae900e2ea740e05))

- Remove tree map example to simplify dependencies
  ([`4e3d8b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e3d8b161f452db05286fd51b5c28fb92f9d0169))

- Remove unreachable code path
  ([`84120df`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/84120dfe273da7d3fc0d69e5365834dc9600756e))

- Resolve the bit utils deprecation
  ([`9437fa9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9437fa9f35ee64684a3ea79ac10248e52e2e6742))

- Update usage of children_names
  ([`1860a19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1860a1999e4a6e960f07992112550ba6733b7a8a))

- Updating docstrings, fixing bug where 0 state treated differently
  ([`de612ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de612ea09e8bfbd9e20e0e1625a18f3471a72533))

- Using preset instead of filter pipeline
  ([`c1c6cfd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1c6cfdafa556d8d4fa946adbcd31faf27a72c68))

- **archive**: Archive ims_transpilation filter per #1213
  ([`a05e154`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a05e154523f4a3b5daf796132940b6ce0eb91f15))

- **cleanup**: Remove commented code
  ([`be1ff38`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be1ff3852985e41dcd7e67c91968fdbf50c3d09f))

- **dagger**: Raise an exception when a daggered compute is used on a qubrick which allocates RAM
  and doesn't release it, per #1211
  ([`1e4f3ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1e4f3ab78ea30f135a25978d21b92dab78ccc667))

- **deprecation**: Per MR requirement, re-add potential deprecation warning for Qubits.QFT()
  ([`ff62400`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff6240093c5679c1345114081b90204044940b41))

- **flush**: Remove extra pipeline flushes per #1222
  ([`ebe1bac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ebe1bac5fc992ca43efaa5e14d35828c8dcf439e))

- **get_allocs**: Fis get_allocated_qubits per #1224, first pass
  ([`e5c4dd5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5c4dd5a5400e0cb341b3b73731a56baa8fa29a8))

- **MR**: Add comments about never_uncompute
  ([`9087490`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90874900099fe535951103dffcaec77d0a754321))

- **MR**: Apply feedback per MR
  ([`b60840a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b60840a3c7dfc50422ef52b6458ce64289b4268a))

- **MR**: Two small changes per MR feedback
  ([`8d721c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d721c5662a31e59f181646027cc66ad459697b5))

- **pyproject.toml**: Add pylatexenc to qiskit install
  ([`6795447`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6795447e17f020b61c9b1b7d7855b8c712661be2))

- **pyproject.toml**: Remove pylatexenc to qiskit install
  ([`f99d02d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f99d02d53965b79a99f2cd4ba4d7e7bb630299c2))

- **QFT**: Remove all zero-target phases, unify QFT with Qubits.reflect() and QFT Qubrick
  ([`2e2a234`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2e2a2347749db380affd7719567210ddad3f4799))

- **qiskit_qpu.py**: Add docstrings for __init__ args
  ([`829ab7f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/829ab7f1d062f0cdbf8d80826bd4b47512e26f23))

- **qiskit_qpu.py**: Correct device spefication for MPS simulator
  ([`1a4416f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a4416f9203f7eca3a30c830033d254a2a8387e7))

- **qubit_interation.py**: Create SwapPushEngine
  ([`403a1f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/403a1f4746bea32eedea09e0aeb6b728d118df96))

- **qubit_interation.py**: Don't require matplotlib
  ([`b45fdd5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b45fdd505c069c64a4cbb6d4a5a9f9b20a13fada))

- **qubit_interation.py**: Don't require matplotlib again
  ([`26aa37e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/26aa37e21028f58a66af562c6c07a05db57c1991))

- **qubit_interation.py**: Get rid of matplotlib objects in function definitions
  ([`f31b6d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f31b6d584ea6e1c7fd9612e72c3fa0f6f0c9cf08))

- **qubit_interation.py**: Remove unneeded import
  ([`360d9e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/360d9e5de2d227f5475c61dc1fcb4f5ade1e55fc))

- **test**: Fix failing test caused by override of >>batch>> filter
  ([`b7410ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7410ad6ad4b8c5050841bd28f0e8258cb51f90f))

- **test**: Fix for test #617, related to changes in #1221
  ([`e281a4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e281a4ecb90a7e55c6a63d1c740b8a61bf8344dd))

- **test**: Fixes for failing tests in #1224
  ([`1aa75b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1aa75b594336390ce5620e4de33d8211e045f70e))

- **test**: Test for #1211
  ([`eb5fb8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eb5fb8ccf92d439289a431130f7333d7afd211ab))

- **test_1148**: Add copyright
  ([`22bbc4c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22bbc4c98918716726a25a3a121e33459b42485e))

- **witness**: Allow witness to smooth out symmetric Z gates for the AV counter
  ([`17d6430`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/17d64306668640047d6ba4b24c0702caf344bb90))

### Chores

- Add as_basquiat() to docs ref.
  ([`104a07c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/104a07c80f01b6870ceb6129d1957f43bac67b86))

- Add needs_sympy where needed for tests that require sympy
  ([`8f35c4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f35c4e6e62a65b44d6f2b6a3256d4280948858f))

- Add tests for multicontrol case
  ([`35742a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35742a6ffc7a08712c61427c6703e2b94fed3f98))

- Adding back in abs func
  ([`f8e58a9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8e58a9ea856e98a31615d5cdaf9a840b0a6fd5a))

- Adding docs and updating notebook.
  ([`e2c771f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e2c771f1c0c02d2ba0b8222f05d51326301c273a))

- Adding gidney_lelboew and gidney_relbow costs
  ([`be8d6fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be8d6fab772c6fac58cff1b7455243353981573c))

- Adding new location for compute_T_rotation_magnitude_approximation_numeric
  ([`29590ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29590ba14c4a2b3711abe43f5735bcbb1697f6d1))

- Adding sympy back in docs deps
  ([`fb17483`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb174833f34d7692cd0cfed989bfff7153a95761))

- Adding sympy back in docs deps
  ([`7175405`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71754051b483f90382310b5dd01a29bb5f475a66))

- Adding tests and removing unused imports.
  ([`bdf303c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bdf303c388947116928b06c4bb435d1646000f4c))

- Apply suggestion for gates for states.
  ([`a1aa502`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1aa502846e66e9c3ea80ff8d4a343a66940ecfe))

- Apply suggestions from MR.
  ([`4d16845`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d16845c7ff4b30be0f8b7c5fbffd4a60ecfd7bf))

- Attempt docs build fix
  ([`790bb5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/790bb5bd9a6a98e8f3ceb63f99b3f0129ebefaf4))

- Attempt docs build fix
  ([`e9638bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9638bbd7cf625b40b3bb761b1e1173067f4bbbb))

- Attempt docs build fix
  ([`674f274`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/674f27412e9826f7acf87c3d4e5791257febaad5))

- Attempt docs build fix
  ([`a2269ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a2269ac6c77614a49058955ea8e6a445af1d0f0a))

- Attempt docs build fix
  ([`0d8bc1e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0d8bc1e2abe80daf4044c80eff87073601f196bb))

- Attempt docs build fix
  ([`4b7c43c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b7c43cf526cfbaa93d565744224bee429b2a869))

- Bump Bartiq to 0.15.2
  ([`942ad32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/942ad325368ac419fddca89f75247dc66121dd46))

- Bump Bartiq version to 0.15.1
  ([`883773a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/883773afc7c1b6ee84a26726d9b369984426e04e))

- Bump minimum compatible version of Bartiq to 0.15.0
  ([`915dc43`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/915dc435cae710914eacc148b5fb43c3ef5f3a77))

- Bump version to 4.30.2
  ([`e064fbb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e064fbb1dc15dd7e39501c358cae18d930001bec))

- Check deprecation shims
  ([`c9f9e78`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c9f9e7805a7e7db2455c82f43c86d50d1aace7a2))

- Clarify comment and test.
  ([`bbaeeea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bbaeeea1e447d6d0a8208694bd86ae748131a27c))

- Deprecation stubs:
  ([`8f466b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f466b2be3ddf832dc3ef4d8b796b713e43d1dc5))

- Deprecation stubs:
  ([`15168b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/15168b3244ed6abebdc9a4b4016e4b72045f76a0))

- Deprecation stubs:
  ([`853bc9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/853bc9df973047a8a8fcf1b445bd3a81aa9f8530))

- Deprecation stubs:
  ([`9ec515c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9ec515c1f3ea33072a5d1066e542fc277760c8a7))

- Don't use bartiq in test.
  ([`a79a17f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a79a17f132fd92e22cc50f813312d6c80760cae5))

- Don't use bartiq in test.
  ([`e3166fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e3166fee3c86790813de3ac287f0b025e54de680))

- Expected to fail fix av from op stuff
  ([`ecf81f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ecf81f7fcfc46d90d702bb22b03487759ff162b7))

- Ffs
  ([`b113229`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1132293fcdb84d57e3b8e6a10431ad59da11f89))

- Ffs
  ([`4363ba5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4363ba55e2c36c7c81180435211dbd254911acbd))

- Fix imports
  ([`f682bd4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f682bd4a72bfdf09d8418fe3198fe2f7d756174f))

- Fix KeyError issue
  ([`2a77f48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a77f48fe24aeb240ff5578ea0409f5fb10423e9))

- Fix test and demonstrate lambdify
  ([`89aca14`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89aca143e3457a2133a3e895908a90787639c87a))

- Fix test skip
  ([`3ecf319`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ecf31975bc595b68b7f5b7d143c06121eb85d11))

- Fixing typos
  ([`651f667`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/651f66716a2bb658f190d67295e809112c5d5ea5))

- Ignore AI agent files
  ([`d6758cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6758cd763237110d2a4ad6041564644d5b454a2))

- Lelbow/relbow fix
  ([`15c3e45`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/15c3e457a8c792af7623d17dd839093e57ab07d3))

- Let's just change one.
  ([`ef592ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef592cac4fb951141c715fb6b7779b1bcd8ecfad))

- Making things on one line
  ([`cf4285a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf4285ad2600b122e6e40b983a70a9ad52903631))

- Move typing info into args
  ([`6e65102`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e651025d39a1907b99fb1b443c70d6f0697f36e))

- Partial eval better example
  ([`6e33862`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e3386279544e13cbf01af7053a45b99d02fc4f6))

- Poetry lock
  ([`2f3d03d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f3d03d3111959f3568b978cac073a7fb40e65f6))

- Reintroduce Bartiq to examples deps group
  ([`7c0532f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c0532f1063718e8f314c6adde1b9266ac700f61))

- Remove future annotations import
  ([`56d06b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56d06b1074f3d2c7469e6cc75b8299ae5795c3eb))

- Remove test skip
  ([`827be3d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/827be3d8c617ab8004ea9d2fb1b78fb8542faa27))

- Remove unneeded line
  ([`b263199`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b263199b6e65ac490a0c7c60c340d03cedd7519a))

- Remove warning
  ([`a9cebf1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a9cebf1b8ed8fb73156525fffab38f825f61d8fa))

- Remove workaround for ntz as it's no longer required with newer Bartiq
  ([`9eb3d7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9eb3d7bc94f64efea2fe82818875cab32ac8bcea))

- Removing dead code
  ([`29d65ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29d65eada61817d462d1b873b772e0286ef0ed37))

- Removing gate_costs_v2
  ([`2c622e7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c622e7fab30bacefd5c750f54be378e45250949))

- Removing unused vars/imports and replacing sympy back in optional deps
  ([`7041180`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/70411802cd3d2f8420cdd71f8208993b73fff2df))

- Reverting costs for elbows in gate costs
  ([`2dae9a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2dae9a4a5cea35aa8ff4f6917afea6ff412021f3))

- Trying something silly to see if tests pass
  ([`22d4ae2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22d4ae248d5b0314b9e2b562393e23ed88e67153))

- Trying something silly to see if tests pass
  ([`c158e94`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c158e9495e13e27c47ebea3af14a68f74ae20b72))

- Trying something silly to see if tests pass
  ([`09f4089`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09f4089c7eddfb29f7b8417e87b5c3af44ad06ff))

- Trying something silly to see if tests pass
  ([`6dc6e4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6dc6e4a9355cab3f0879d67f1d1b1d5ce161cb4f))

- Trying something silly to see if tests pass
  ([`0ad5903`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ad590313d1c9c44b3328b98d986b09f5bca3590))

- Trying something silly to see if tests pass
  ([`d525e4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d525e4dca961e2c2773929234da693831a438b2d))

- Trying something silly to see if tests pass
  ([`343b69c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/343b69c763dfedaffdd1070fb69aa5ded862ba64))

- Undo replacement of lock
  ([`72c01ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72c01abcad5b5b5163b5fcc218c0a57320da9d3b))

- Update descend function
  ([`789c210`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/789c210c1f0fbb850885173b73ff18eef75db452))

- Update reference doc with better example
  ([`3e18fda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e18fdaf041e4031fd8d461678b1669bc6cd6cff))

- Updating comments
  ([`a3d0e84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3d0e843cd97ca44cb165b41508cf7757c9b52df))

- Using new AV interface
  ([`07511e6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/07511e666d6e188d43eefdb03f28b04ec38a675b))

### Code Style

- Fix lint issues
  ([`5a273c6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a273c603b717fc126b3a1d7666425036bc0ddd8))

- Improve typing
  ([`daeb2c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/daeb2c7a47398406d52661f2cd7b713ddbfbe567))

### Continuous Integration

- Removed unused examples dependencies
  ([`30cf589`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30cf589384cac9aa9f0eccc1c4e5a2d6a2fe27b9))

- Updated dev-ops/common include reference from 0.0.7 to 0.0.8
  ([`9e49306`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e49306f483d5a3ceff8bd76a2cf60d8109cbfc7))

### Documentation

- Adding docs changes
  ([`086e9a1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/086e9a1e50cce7d9576916536e9482c7a0a40ac4))

- Adding requested language change in Qubricks
  ([`1d5a85f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d5a85fbaa4c264ecd10035e5e7d23ab6abee5e4))

- Adding small changes to Testing-Debugging notebook
  ([`2895a3b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2895a3b5d9cf7b8de4e55995cbeae631e5f549cb))

- Change Return: to Returns:
  ([`4d98bf1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d98bf17f23dc95011982c7559d2b353b33fd203))

- Massive docstrings improvements
  ([`750e0b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/750e0b880bb2e967eee0f408630d51ef77a856a3))

- More typos
  ([`1048b2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1048b2ef5b6fdbc11d20c8de0f2968dcb27b3b14))

- Remove unneeded docs page
  ([`c62a5b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c62a5b057899158d1b540ccd16eb8da30c8767a8))

- Rerunning notebook for new outputs
  ([`90f6867`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90f6867bcc8e302b903f8750a79f77a0c1795a36))

- Update docs
  ([`cf3e4eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf3e4ebebb7bb062139c066ae0190b9bb2c9f8e3))

- Update docstring of resources() method
  ([`6b31e4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b31e4a339683e5d88bee74624dd4171bb6e5c78))

- Update QRE example notebook
  ([`4f2e930`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f2e930ad85bcfc2a69333988fca329634bc81e5))

- Updating docstrings
  ([`d4a1713`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4a1713690eb8caea83a5a15fbac558df6becc54))

- Updating documentation notebooks
  ([`d9c75d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d9c75d2fe3ad1911c4bf7046745a693fe630e86a))

- Updating explanation of entangled states in print_state_vectro and print_probabilities
  ([`a6cbd86`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6cbd8635f97aa6d6828a5b79d78b3d12eaef2b3))

- Updating language based on pair programming
  ([`3e43c36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e43c36dc5394390bff865174dbc90083524663c))

- **dev**: Update developer README
  ([`c7915e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7915e05ca2031a22f7a087767fbaa0eb1b0b875))

### Features

- Add depth argument to children_names
  ([`d4ebbec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4ebbecdf28209df723875d3fad585c094058511))

- Add prototype of high-perf resource evaluator
  ([`10c622e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10c622eefd1444f43fda0d81b111b0460938aea3))

- Adding verbose option to kwargs for qubrick to use
  ([`308c66c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/308c66cdae25785714c3648b7b1cccde9f8244fc))

- Allow passing keywords to sympy.lambdify
  ([`8c27233`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8c27233703c7a0cc27833d7becf3c7152854bc72))

- Allow querying children names through children_names property
  ([`45d2672`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45d2672b7ec967005c0662e30afa72545210f547))

- Make symbolic estimator expanded by default
  ([`6e1358c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e1358c3f1ee87ddd20fd4d29525ad8a83a65b65))

- Print state vector for qubits now shows state vectro rather than state vector, also adds
  print_probabilities as an alternative
  ([`adb2613`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adb2613a5252cbe05234206fba824d87ba38e765))

- Refactor so we do cheap entanglement check first, and make show_entangled the default
  ([`88cabc3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/88cabc375fabe4cad12fe1246d1291d2b44b6fb0))

- Remove duplicate qbk_control_decomposition file
  ([`4504c18`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4504c18ab8c3316ada2a924d215757831b495f47))

- **pyproject.toml**: Add pylatexenc as dependency for qiskit
  ([`d524b95`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d524b95b35ebca3632cd83aa2aac87ade0fe6b18))

- **qasm3_export.py**: Add cz gates
  ([`394f7a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/394f7a3744fd16c182cdb6790bf7db2da906db04))

- **qasm3_export.py**: Add large CCZ gates
  ([`b1a6fee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1a6fee6b43a01ac8f33f6043fb0b7d158834dfd))

- **qasm3_export.py**: Support no target, no control circuits
  ([`822c48f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/822c48f26f0d1f17d9c0376af577ae48927c2068))

- **qiskit_qpu.py**: Added comments
  ([`9b96bad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b96bad13b9ad4e6cc88d9c934fbb1d18e712705))

- **qiskit_qpu.py**: Added qiskit result object link
  ([`837156b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/837156bdfbe33fd9ab1fe18c73200b7d5f9fe015))

- **qiskit_qpu.py**: Allow GPU accelerated MPS
  ([`c67fb3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c67fb3e19814c5d93bb4394eb61c8d7ee0b986fb))

- **qiskit_qpu.py**: Allow GPU accellerated tensor network sims.
  ([`0dbef89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0dbef8924cafaa818655bdc4767fe5b25388746b))

- **qubit_errors**: Raise exceptions if Qubrick result qregs are freed before they can be used, per
  #1221
  ([`8c291f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8c291f93483747129a4dab0598f8b358e0575847))

- **qubit_interactions.py**: Add qubit interactions filter
  ([`8099538`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/80995386269efa80a754646a982d56ec1b328766))

- **test_1190**: Add integration tests for cz gates
  ([`19fcca6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19fcca66afb1827c60f1c52d3dd7c90c3363dd42))

- **test_1190**: Add negctrl tests
  ([`27b0227`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27b0227737598980e9a6ac565e2839f678efbe0f))

- **test_1190**: Add tests for cz gates
  ([`fd4a4f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd4a4f9c512e4a34a9171c85b356f476e406012a))

### Refactoring

- Extract _resources method and improve typing
  ([`b69ca64`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b69ca64ee4812ed695a64f1b31f5f71de1f45bd7))

- Flipping logic in is_symbolic and adding a few more needs_sympy decorators
  ([`8d31d6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d31d6f87bd7d8446183570827470d7dfe961b9f))

- Revert as sympy will not be dep.
  ([`a321b62`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a321b628cd496dec5102423cf020620be49df7df))

### Testing

- Add test for obtaining child names of depth > 1
  ([`c2e2ff3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2e2ff3403cb652635e911fdb73b5fd06475f783))

- Adding assertions and checks for warnings
  ([`5852405`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5852405db7ea479005771538f1995a00c3710dbe))

- Adding more coverage, 34 lines left to cover
  ([`ac7fb7f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ac7fb7f7dec1ad8ae2210a3ecb3c36ca7937f966))

- Adding tests for print_state_vector on qubits
  ([`e13cd52`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e13cd5223ec14b12ba68d14c9dac61483125c4e6))

- Fix tests to use reasonable expression for register sizes
  ([`2104997`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21049970aa9454b111c15f7e03cc0aca31a07515))

- Initial coverage testing for gidney arithmetic
  ([`f07dbe8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f07dbe892910b878dd85bb1c5e501f828e8890d3))

- Rename variables in conftest to better match their contents
  ([`a995367`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a995367ccbaa64fe7571d5d191efec47e9f73619))


## v4.30.2 (2025-10-22)

### Bug Fixes

- Add http://www.w3.org/2000/svg to ignored urls
  ([`05e7788`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05e7788a97f3c61306c81ed82cbb2278e33e2a23))

- Broken from symbolic comparators
  ([`211e63e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/211e63ee87962677e16386181e0f34d9ac5cd5ed))

- Broken from symbolic comparators
  ([`10d1474`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10d14748e8a8776f8f288ad8c736c09046382d85))

- Broken from symbolic comparators
  ([`f8fc6cb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8fc6cb3582381a29ffd67381f372df557408fcd))

- Broken test for comparators
  ([`cb2e203`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb2e20322daa323b1036b8db8793553fecaa66ab))

- Lint
  ([`3ea08a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ea08a32adf2808ef022d9709f701289dda3e504))

- **active_volume_lookup.py**: Accidently left some bridging cost addition in the table, these may
  be added back later.
  ([`20626ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20626ef6d7c5ed5325900df069aad91690ba1433))

- **active_volume_lookup.py**: Added optimised cost for Y pi/4 PPR rotations. Also updated table
  cost to use Y state distillation cost instead of hardcoded 3 cost (this was previously missed).
  ([`1f7844d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f7844d6eb45a42ff1ac58ebcc17ecebfe02b096))

- **active_volume_lookup.py**: Found optimised costs for ctrl Y and sqrt y, also update other
  clifford formulas to use the distillation of Y states explicitly.
  ([`d4ffc02`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4ffc02067294e380011e9739db10ef8664fb382))

- **active_volume_lookup.py**: Update entries in the av look up table to agree with the new
  formaulas.
  ([`1ffcd47`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ffcd473333a72e38ce75ee5a366f1729315744b))

- **active_volume_lookup.py**: Updated an incorrect comment.
  ([`2a0af17`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a0af17df178a33cc0193a4d4e8717735a174065))

- **active_volume_lookup.py**: Updated reactive T measurement AV formula to be more optimal.
  ([`6cc7827`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6cc7827511d6026db52f89be1317ff03681ed6e8))

- **cleanup**: Comment removed
  ([`dbee841`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbee841375b39edf8303d37b882b7f90c3805c2e))

- **example_swap_push_filter.ipynb**: Use Qubits()
  ([`25752b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25752b072e0950f0ca48c3df92a6c060e5cd5a97))

- **get_av_from_op.py**: Fixed the cost of single qubit y ppms. Now costs 5 av instead of 7.
  ([`c557598`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c557598bde5297893f0763a82fd53e382c42ab0d))

- **get_av_from_op.py**: Single qubit Y measurement cost 3 not 5 as bell measurements are free.
  ([`d263cf0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d263cf008e511bd5122bd3a2071260b7864a1f1f))

- **ppm_functions.py**: Fixed the dirty ppm function formulas to include y_parity in the return
  cost.
  ([`837a807`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/837a8073de97d75c44824405db2bdf5c75770420))

- **ppm_functions.py,get_av_from_op.py**: Moved new case logic from _get_av_from_qpu_op_ppm in
  get_av_from_op.py to _get_ppm_av in ppm_functions.py, this solves an issue with symbolics and a
  testing issue.
  ([`2573c9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2573c9bb4b4dfe76e38ab27efa483b5062a7ca9c))

- **ppr_functions.py**: Reverted back to original function for pi/8 rotations as X injection does
  not work for T gates.
  ([`fb9f073`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb9f073d5cf6245913452532583327dc166ff8ab))

- **ppr_functions.py**: Update to _get_pi_4_ppr_av_cost function such that we use a more optimised
  formula.
  ([`1d676ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d676ce6b39bd34186313a7bf69ceb8ef767cfc2))

- **reflect**: Convert all known symmetric Z gates to Qubits.reflect()
  ([`ad224e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad224e58e9e04cacf230a4238582415ff1bbf472))

- **reflect**: Re-add reflect to decomps
  ([`06a6909`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06a6909015c87b6b44650dff19ff6c89348e9d5e))

- **swap_push.py**: Added copyright notices
  ([`7e53bb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e53bb430f4aa4ad4ac12cdcb1a5ada9252ff258))

- **swap_push.py**: Flushed swaps corrected
  ([`6bc84ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bc84ab2662ac31c2cce4b4c20f616dd1a6006c0))

- **swap_push.py**: Formatting and comments
  ([`17d5f4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/17d5f4e56f50d08843165f456190d20796be2e17))

- **swap_push.py**: Write operations support
  ([`09c1000`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09c100007943bf9faa4a3bca3b450a7c01312aed))

- **swap_push_filter.py**: Get rid of unneeded checks
  ([`31f7a6a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31f7a6a4035aa73ce8b73bb35ce7101fff8548ba))

- **swap_push_filter_example.ipynb**: Cal -> can
  ([`38b85da`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38b85da254841306ca172d69f6fecd81f087e1f1))

- **symbolics**: Better workaround for symbolics issues
  ([`fce64e7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fce64e7aeead9bf22ec1e622fe5474672319978b))

- **symbolics**: Two small symbolics fixes
  ([`ef425b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef425b3f4dd8f730c8fd0a2fa5b00d6e1f99d23a))

- **test**: Tiny test fix
  ([`860373a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/860373a448e821cec6f5ee05a6c73f87e2d0ac9b))

- **test_1187**: Delete repeated test
  ([`ad8aa91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad8aa91513ce32c52a029d052aba39371de2317a))

- **tests**: Several test fixes
  ([`0b10cd7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b10cd773d37ae2b89f3cf1777e27b5bb7a861c9))

### Chores

- Bump version to 4.30.1
  ([`cba0247`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cba0247e0cc3fb4513ce36aed0070f590b43d271))

- Don't define symbolic a twice
  ([`8ccefdf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ccefdfe3e63eaea72a488441a11caf48f792e00))

### Documentation

- Address reviewers' comments
  ([`c7c58e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7c58e34427d8fdb4e9122d00c5cccb3418ac881))

- Fix docstring for .
  ([`2379369`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2379369ad430eab5cc0ad4179a8411c6b4388454))

- New 'Uncomputation context manager' tutorial
  ([`5bcad9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5bcad9b55bd373ad39245760fdf32c56e5bfc3c9))

- Ran code cells
  ([`0c04b05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0c04b059a7103e6866ac5d8197dfd4dec93e27e7))

- Updated final code example to be self-sufficient
  ([`7c48219`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c48219693f23827fbba9e2d2c8d97f813e4b272))

- Updated kernel to not include images
  ([`51a784f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51a784f921d556fd4b551335e8d6a14348f8e4b2))

### Features

- Added pi/16 and 3pi/16 PPR rotations as well as some updates to the AV lookup table.
  ([`989e0eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/989e0eb160811093afd8c91bcaf2597b6cd0dfe4))

- **active_volume_lookup.py,stale_state_count_lookup.py**: Added optimised ctrl H to av and ssc
  lookup tables.
  ([`359de5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/359de5f0b3f60d615bb022581dbd386bb30d8f31))

- **active_volume_lookup.py,stale_state_count_lookup.py**: Added rx, ry, rz support for theta = 90
  as this are just control paulis.
  ([`1c4d75f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c4d75f534edcbc90576440c2bfa425b0824723a))

- **get_av_from_op.py**: Updated _get_av_from_qpu_op_ppm such that single qubit x and z ppm have no
  AV.
  ([`be6b2ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be6b2ad36058c11eaf0a8de718df891f176a8927))

- **get_stale_state_count_from_op.py,stale_state_count_lookup.py**: Added stale state count formulas
  and logic for 3pi/16 PPR rotations.
  ([`f644239`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6442396895c8d347856e85d5c7ea2dadb545e9a))

- **ppm_functions.py**: Updated dirty ppm functions to now include the block cost of bridge qubits,
  also implemented a small cost optimisation.
  ([`4142770`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4142770e57074a060710ce8abc12079617f3a1a6))

- **ppr_functions.py**: Added a comment to mention that ppms outcomes must be interpreted
  differently for y_injections.
  ([`9bee3e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bee3e372e52b320850c9bd9179e74dc0a064a2a))

- **ppr_functions.py**: Change get_pi_4_ppr_av_cost to calculate both methods of doing the pi/4
  rotation and then return the minimum cost, as this is more robust and has a minimal impact on the
  computation cost.
  ([`1342eba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1342eba98af6f6eebe488f8ff61f4e2a55c0ad0b))

- **ppr_functions.py**: Update pi/4 rotation function to use one of 2 formulas depending on y
  parity.
  ([`92287d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/92287d706f0525e18b3e998ec42b44a71b16786e))

- **ppr_functions.py**: Updated pi/8 function to use X or Z for state injection.
  ([`abefbbd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abefbbd0b000ca6997df7979956705baabd74b84))

- **swap_push.py**: Implement calling filter from string
  ([`66a7867`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/66a7867d56b4f2f970050e87de083c1cf7fc7c3b))

- **swap_push.py**: Implement swap push filter and tests
  ([`3606483`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/36064839de2b25cd29f380cd2138120cb53664c2))

- **swap_push.py**: Push to end by default
  ([`644601a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/644601a8b60715b6ba6c46b362957ab412ed438d))

- **swap_push.py**: Support qpu.write()
  ([`1f416a1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f416a151cbef72aced9f40fe7782c61fc5f1792))

- **test_1187**: Add read() test
  ([`2349e1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2349e1a164a6d1e98a88b641a3b2e0a3e5569909))

- **test_1209_single_qubit_ppm_av.py**: Added test for new single qubit and 2 qubit ppm
  optimisations.
  ([`58bc509`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/58bc509ddc245737f23593caf3d1679ad40fbea2))

### Refactoring

- Comparator calculation refactor
  ([`67cf962`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/67cf962fe68696d1d759013affecf3833b43838e))


## v4.30.1 (2025-10-16)

### Bug Fixes

- Added needs_sympy in appropriate places
  ([`7a4ca11`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a4ca1160837928aa3ddbd1fd20506611d5cb772))

- Fix get_instructions with format="asm-stack" for SymbolicQPU
  ([`7a8ee22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a8ee22a2d5dbc8e725e60a4151aa3ded5ea0d38))

- Fix outdated import
  ([`89dfb0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89dfb0e2412bbdf8f887ef0c57796dd4407b59d2))

- Fix test with scipy
  ([`01a846a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01a846aa113a9a29ae059d4921d1434dc57eef64))

- Typos
  ([`30a4d47`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30a4d47c7808508c7d451438b9d21fb8cc219c96))

- **cicd**: Per #1203 make examples optional
  ([`edb1728`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/edb1728b4097d313e0b183333aab3936126d86e0))

- **lock**: Add updated poetry.lock
  ([`883bcc1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/883bcc1db4a027741adcedf718c1ef21fcf1bbbb))

### Chores

- Bump version to 4.30.0
  ([`469604f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/469604fdc4286b62430665e21e807b27cf7f2c79))

- Change imports from relative to absolute
  ([`30eebe0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30eebe007fbaaac0046c02b4bf053159a6134916))

- Remove old tutorial symlinks and unneded examples
  ([`62b0223`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/62b0223cf6e221de8498ff67b5f1bdb7680a5153))

### Code Style

- Style fixes
  ([`8db9f86`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8db9f86b0f1ae0881f7d5abe9233f1fa47803a93))

### Documentation

- Update docstring for capture_instructions
  ([`af2deef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af2deef3da1fcc8725e70e4a7de0c52b776db984))

### Features

- Add negation to Parameter (both new and old)
  ([`10193eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10193eb17cf69b98c62b9da709558a259c78f003))

- Correctly count rotations and other gates when preparing rotation catalyst state
  ([`51041d8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51041d8e6a9cc14d34b9b17e65fd094f32f2a427))

- Support angles >= 360 in symbolic rotation catalyst via padding
  ([`fd2a66a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd2a66a9dd2a579e58090aa7ab9de01be9591935))

### Refactoring

- Move conditions to a separate module
  ([`a48dbad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a48dbadf2ab2106cf3e931b3ca50a2fadf107191))

- Remove _expr suffix from condition functions and use them in rotation catalyst state prep
  ([`f0ca05c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0ca05c202e560f7ea97ca499e1a09f072c87edc))

- Simplify class hierarchy for conditions
  ([`607be6c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/607be6c4af99ac61d7024e252a28ffefcb3c2218))

### Testing

- Add missing test
  ([`6b8c5da`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b8c5dadc384781f58230c29302bb029bb1ae2df))

- **lock**: See what happens if there's no lockfile
  ([`16a9837`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/16a983750b4a7aa3c70892c1f3848dfaeedf96fa))


## v4.30.0 (2025-10-10)

### Bug Fixes

- Address parallelisation failure
  ([`ec3c784`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ec3c7847984bd39b3c07035bcfc1d650c8900e6e))

- Address sean's comments
  ([`4111ad1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4111ad1736409e5e74726fe1ec420b43dde84b26))

- Answer code review comments
  ([`e8734e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8734e397cbb335618e9f53063c34f522a4b8a3b))

- Eliminate qiskit warning deprecation in test
  ([`9d089be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d089be769467692966672231a5f4ae7caab2c99))

- Fix lint problems
  ([`f8cba05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8cba05932042dfb78fe4fd6a09aab03c0ca9935))

- Fixed AV calculation for symbolics
  ([`cb797ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb797ac627d500152cf2c18e19905a1c893ce047))

- Lint
  ([`3bdcb5a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3bdcb5a3b01a2b28ba98a207eb35c3a06b9e433c))

- Remove warning: UserWarning: Returning QubrickCosts objects from estimate/unestimate methods is
  deprecated...
  ([`d4bc76b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4bc76b7ef55999b43aa57cc7813bac7db54b0c7))

- Skip test if antlr4 not installed
  ([`e74a2d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e74a2d7f51f1b388b497178c48210e343f15492f))

- Test_811_qasm_export_filter.py qiskit warning
  ([`1735464`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1735464f8be90e849af31e3cdaba207057f02cb6))

- **detect_entanglement**: Fix for #1178
  ([`02d70a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/02d70a47ddb69f9ead7f026dd383e78861de0a29))

- **filtername**: Handle failing tests in transition from >>qpu>>, per #1139
  ([`bc51a90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc51a905659b1be17b471b35690446ad64388e47))

- **formatting**: Revert reformatting changes, leaving (I think) the relevant changes intact, with a
  few fixes.
  ([`586d8aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/586d8aa230eef305ee64c5886621151135b6a10c))

- **minor**: Fix witness setup to include bit-sim
  ([`56d2660`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56d26600d8670628090665b96a395ab2ee0c9334))

- **MR**: Add a test as requested
  ([`4834bfb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4834bfb81a77d3cd75fc8c757ecb068c5875fff8))

- **MR**: Fix per MR feedback
  ([`0f9daa2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f9daa2beb8ffd4506ab44e2e72266c65bc6f470))

- **MR**: Reworked all tests to keep the changes just as needed and make deprecation easier
  ([`6a90bcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a90bcc5b443bd9dd68c49c5213d8ef49a276222))

- **scatter**: Cleanup for scatter assert
  ([`9387ac7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9387ac7491dc64cc2f7363b55ccead702ec8eec7))

- **scatter**: Restore qubit masks for scatter Qubits, with a fix for numpy int-poisoning
  ([`561c029`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/561c0291ac56a50591a13eb4433700ed91843d6e))

- **test**: Fixed an AV bug so now this test succeeds in failing again.
  ([`4765d59`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4765d59c5bef68bf06f01fae90bd9ed5bf38ba09))

- **test**: Small adjustment to test 614 for #1139
  ([`3a73ef9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a73ef90a559e02d0574a55b9fe6fe6a9c82a4b8))

- **tests**: Revert all tests to main
  ([`bc83ba9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc83ba97410125ad96801ea0de7f1f33829070c5))

- **witness**: Fix for witness counter treatment of conditional PPRs per #1155
  ([`89e9d2c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89e9d2cc7b8422783ad0b8638bf4023b16b4d259))

### Chores

- Add a more general test
  ([`9264c4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9264c4d8dd6c9b59d0211680ec4cabbf10b622b6))

- Added >>state-vector-sim>> to speed_tests/small_circuit_speed_test.py
  ([`abaaf1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abaaf1ab11fa875b83899a03932f141fde37f239))

- Added >>state-vector-sim>> to test_205_feedforward.py
  ([`6b88e9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b88e9dbad7d9c36210ba57a47831433dcaadc6e))

- Added >>state-vector-sim>> to test_269_feedforward_demo.py
  ([`bc1444d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc1444d23670acad3c259e27274120407c79923c))

- Added >>state-vector-sim>> to test_269_feedforward_demo.py
  ([`ebdeb29`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ebdeb2900cafc3f2c2dfe7d16cd1d785cd5cfd07))

- Added >>state-vector-sim>> to test_767_jump_back_iteration
  ([`b3a5b96`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b3a5b960515a3d3b80339b67bb52d1687cd92dda))

- Added >>state-vector-sim>> to test_767_jump_back_iteration
  ([`217d6eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/217d6ebe7d0a1dde6559f78d942aba11ab120eb9))

- Added >>state-vector-sim>>, >>bit-sim>> and >>clifford>> to test_339_postselect.py
  ([`923ea0f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/923ea0fafbd2ef3eff152840328cdd861fee915a))

- Added >>state-vector-sim>>, >>bit-sim>> and >>clifford>> to test_339_postselect.py
  ([`3cae47d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3cae47d08f034d66c80d5596a83ba4b7127544f8))

- Bump version to 4.29.1
  ([`20045e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20045e5f12a5b2918c27cbc2743bdd895f5df961))

- Eliminate deprecation warning for truncate angles test
  ([`d169374`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d169374c45879d6e44ddfcb4034c8889f997566c))

- Removed return notes
  ([`bdb0f20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bdb0f20be4b98c47090c6e1e9f5f2d6f7165d2bc))

- Universal -> Uniform State Preparation
  ([`40cdc28`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/40cdc289db245ed8abef38b91517029720f2ab6d))

- **review**: Apply 1 suggestion(s) to 1 file(s)
  ([`a7a8226`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7a82267769f05ea1d292729094cbdeeaacab114))

### Code Style

- Minor changes
  ([`9fe7f27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9fe7f27f761522443ae779c5e0bb5a80fcbe0360))

### Continuous Integration

- Run tests in parallel
  ([`af6edf4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af6edf4080a622681a171b3fa3afbbd8fb9a7f8b))

- See if limiting to just one runner fixes CI error
  ([`036e6fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/036e6fb67317d3b407d65182f5070bc5732abdf6))

### Documentation

- Add new 'Quantum Arithmetic Data Types' tutorial
  ([`4cb360a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4cb360a14075e69a29c6b56fbd5a76b94b4f3ef7))

- Address reviewer's comments
  ([`4e2dfb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e2dfb423a471e0885718cca343d6c4bee9d2fb7))

- Address reviewers' comments
  ([`e1dbfaf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1dbfafc78c31abc8adefae17fe789c972148d03))

- Clean up Qubricks API docs
  ([`bd79000`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd79000d6e78e78e70cb981ee9307aef816e2fd4))

- New 'Quantum Arithmetic' tutorial
  ([`d8baa1c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8baa1c32b20309a3eafaafdfd127c6f6113beb9))

- Replace old filter names with new ones
  ([`2173ed7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2173ed77b9a46638ec0676d6e55e9075fb0454fd))

- Update the docstring explaining caching strategy
  ([`20bcf42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20bcf42881dbd1df69d62830ceecc69f90009fdb))

### Features

- Add global phase invariant op norm
  ([`3078ea1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3078ea1ad22f45cf3cf3f3dfc5d5496ca4eff83d))

- Add tests for globally invariant op norm
  ([`55545cf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55545cf609faf44ed3c49361c406af38e802dede))

- Narrow down numeric types when extracting value from parameter
  ([`38bb499`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38bb49972a235b5ff52cba9160ae6e2d510ae48d))

- Working version of new AV for symbolics
  ([`1e412c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1e412c9bd0bfb46c8db01d939fb73cad66a02f0e))

### Performance Improvements

- **witness**: Double speed of witness test case by changing operator overload
  ([`ea39f80`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea39f80c9ac0ad6d922bf8453620db2937936d92))

### Refactoring

- Remove gate_costs_v3 and update gate_costs_v2 instead
  ([`79da713`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/79da7134b429862d410b093d2400d4fcdb98533a))

### Testing

- Add AV reference assert to RS QRE trends test
  ([`18593ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18593ca85531a924813d74e4a8e484abc8c2b3d0))

- Add missing tests
  ([`aaecf7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aaecf7ccf5d8f60d1e249b4b6331df126b90b423))

- Add test for symbolic ppm
  ([`3dcd646`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3dcd646cc01cd6f878085c3ec0423eb3e833a8fe))

- Added test for slope of Ross-Selinger T-count costs
  ([`0b1190e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b1190edd9604995ea122f6035f8bcb04e3edb9f))

- Added tests for naughty theta values and fixed bug
  ([`bccb4b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bccb4b79963a6712b94560340b3bdbf0df84e423))

- Increase range for RS synth tests
  ([`99417d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/99417d2fa2d884acf4e556516ecbf7b58e38dcd5))

- Loosen RS synth absolute error bound for controlled RS qubrick
  ([`d5c50e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5c50e45b0f62c6d8fab3862897a0f05b2b4c243))

- **MR**: Add requested tessting
  ([`75ca1a0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75ca1a083e1485f885a63df85bbde04915bb3b0e))


## v4.29.1 (2025-09-29)

### Bug Fixes

- Avoid registering unbound "idx" parameter when using rotation catalyst with symbolic QPU
  ([`8aa738f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8aa738f714103c4455ed8d419b50fbb0a5cdf8ac))

- Short term fix for the allocation bug in AST-2340
  ([`5607c12`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5607c12ef0fd0f703c6887f55649e1495121c514))

- **rounding**: Fix rounding error in #1188
  ([`7414088`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74140883018c108d27934933948a128901db3850))

### Chores

- Bump version to 4.29.0
  ([`9507003`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9507003ce7c4efa2f464d6d43bf19edf4753aeb2))

- Merge master
  ([`39c1762`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/39c17625d323bea7226acdcee5d9802089dc5f30))

### Documentation

- Fix docstrings and comments
  ([`826c7af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/826c7af0d30caec142f93f6db7030fa4612bf2a2))

- Improve register_dummy_parameter docstring
  ([`294cdb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/294cdb44d851ed795235c293c71cb6e2a1b4a9e5))

### Features

- Add ignore_dummies argument
  ([`fd470ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd470ba3211cddad691dfedd7af2c183ce23dde6))

- Allow register dummy parameters for symbolic QPU
  ([`49d1e76`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49d1e7605fedcd45708d5dd479ef222b42959daf))

### Refactoring

- Use Parameter object instead of string in register_dummy_parmmeter
  ([`07d13d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/07d13d12dc7c68c586b8c516427f85ef025ed47d))

### Testing

- Check that adding dummy param does not prevent compilation
  ([`c4c6be9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c4c6be9e7196a8e0949d87293280423e314f94eb))

- Improve testing of dummy param registration
  ([`3b16310`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b163105175e03aa6810732c13da6c6c4192a92b))


## v4.29.0 (2025-09-26)

### Bug Fixes

- Accounting for case where cond_reg_deprecated could be an integer, and checking that first before
  checking it is 0
  ([`7ff8797`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ff87971b1c78da4655d3ad1a3f2df719c42013d))

- Add extra line for rendering docs
  ([`4da10d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4da10d2f9ad2f2937a61d71e0886f066efa5db11))

- Add tie breaker for equal probability state vectors to select to state vector with more non-zero
  amplitudes
  ([`06b4fcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06b4fcc321c5669af3b47084cb97ea8d91d27f86))

- Added parameterization to tests rather than loops
  ([`6f3e79d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f3e79d567b68c27a597c646387693f7b58e22fa))

- Adding error when AsynReadResult used directly as boolean
  ([`b3b3345`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b3b3345d28c4ee4f296798a6ee50abea194b5d93))

- Adding fix for printing state vector with bit-qpu when no qubits defined
  ([`d8310de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8310de3b6098f9690512327a1e166c2f9c1af38))

- Changed from userwarning to deprecationwarning
  ([`0a529ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a529ac016e8730e74c95ded96c6cb010ccb84cf))

- Correct docs notebooks
  ([`e9cd529`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9cd5292b06064ea5eb369202340da9c8a0ab590))

- Correcting notebook to remove excess information
  ([`01943f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01943f4c42bdd45e63f91bf52899218763922c45))

- Ensuring dummy qubrick uses its keywords
  ([`2aa64fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2aa64fe445e27fbc16ba0ce953fac1d896230953))

- Ensuring kwargs are passed explicitly
  ([`0500354`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05003542f89bd6d0e68568494dcd7a685a3342e1))

- Ensuring tests pass
  ([`4d03560`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d035604c7062f130e79506ea5fdc8eaa39cbf51))

- Error on pydantic none fields
  ([`f071217`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0712177dd3dbbe0f00f7df2e4fe6fa6cd012479))

- Intermediate fix for off-by-two comparators
  ([`76f3fec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/76f3fecd818b3f086c05febd693e4177d9532851))

- Invalid number of reset qubits
  ([`efca6e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/efca6e14097beaf7d69efffb90855e5c398aeab2))

- Lint
  ([`e1064be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1064be8480bfb02d7bc1ac049f306459dc14633))

- Lint
  ([`be49a0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be49a0c2d6645cc1667206ce04304710fa0de871))

- Lint.
  ([`b6ba639`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b6ba6399812832828a437129cc6ca1075a485615))

- Missing conditional statement
  ([`6e8b0db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e8b0dbebb2f936b8ca1c574297bb6bb97f63552))

- Moving normalization logic to python, adding tests for normalization
  ([`6bb5c0f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bb5c0f44885831919e1279dc5021f541280d95a))

- Removing another loop from a test
  ([`30534e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30534e3a8ab0d4974f375f487ce0415c3e023949))

- Removing debugging
  ([`6c0525a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6c0525ab931249449eb62ac3dbd7c3ffe8ae270d))

- Removing mutable obj fromm default argument
  ([`11c5716`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11c571610bb39ce470bfeb7c0deb35c96b05f3e6))

- Removing testing code
  ([`57afecb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57afecb14fb1deaa49f8cc9bf2f6c11e1ad25679))

- Removing unused kwargs
  ([`5981ab6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5981ab6480dbd1b15377e69d7be617deeb7737d2))

- Tests.
  ([`35cebd7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35cebd74fd85c4ac87c743fb0a5719df7afd8444))

- Typos, adding option to turn off normalization, adding adjustment to make the first element of the
  state vector positive
  ([`f8e5b0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8e5b0e65dffe34abff4b3e2a384903701d20b47))

- Undoing unintentional change
  ([`abc3527`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abc3527b6532bd4d083a8a4e10fcf1bcd653cbe8))

- Updating and adding tests
  ([`1acd7cf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1acd7cfe9039ddf4f6258eaf06a8a6ddd3d97e8f))

- Updating warning message, and checking entanglement with probabilities rather than amplitudes
  ([`075b369`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/075b369aabf4e4a7cff1461bce6e56554944f88f))

- **arg**: Remove use_mod arg from integerize_truncated_rot_angle(), as it never changes the output
  ([`357f15a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/357f15ac466bf4e2b0984f7d59869ed4e998336c))

- **cleanup**: Docs and warnings
  ([`3a2f080`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a2f08082f5af7053c0b97f02bcc88fccbdbe930))

- **cleanup**: Remove commented print
  ([`d0dd60e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0dd60e6d49f83497603b92875ca3bd0f2d68f25))

- **cleanup**: Simplify scatter to always be a tuple
  ([`f5d47b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f5d47b929ab5f0db64b25160f74af767b3e42fc5))

- **composite**: Fix for failing CompositeReg test also a lint fix :]
  ([`f87b985`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f87b9854cf8e9f0834c2ff7812f66fa744c05860))

- **deprecation**: A suggestion for #1177
  ([`2a4d37a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a4d37a9a0ee285ed382f2ebda6817685e98a33a))

- **int**: Fix the case where integer angles are passed
  ([`d55d72f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d55d72f9a9d483f9a34f22c1e04748c64c319c9e))

- **lint**: Fix a linting error in the speed test
  ([`8810b5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8810b5ebfa208f5946cea4448368d4528a409a66))

- **lint**: Minor lint fix
  ([`cddc0f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cddc0f7638e7c05e2256619720d9c8fb08024252))

- **modulo**: Minor fix to optimization in #1106
  ([`f61d899`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f61d8993f0ba5f4c75bd90718028a4e173da2b32))

- **test**: Test fix for list/typle checking in #1183
  ([`8bdea25`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8bdea257739c13c315450a74a9e2c223bd8b716c))

- **use_mod**: Replace legacy code with new code, and ignore use_mod
  ([`22d3ad9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22d3ad9dc1cc9dee0754713558f0013c5e652940))

### Chores

- Add docs page and script for generating.
  ([`25fcff5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25fcff59226ad69fa113930586ddf3ebb7cf81ae))

- Better exception catching for qubrick discovery
  ([`c6c5f99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6c5f99ba4d171ae8e9b4337db082b47fac76c4c))

- Bump version to 4.28.6
  ([`72104dc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72104dc71a82f7233e6dfcfc029fdca8cb6d859b))

- Cleaning up orphan comments and misc. refactors
  ([`0b2dfb4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b2dfb4353e3ca6ab03cd73d97d17b3c68e81276))

- Combining get_known_discrepancies conditions
  ([`29f250f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29f250f0b862ef1290b30dd52ee993ed2313fcd7))

- Filtering objects for getmembers
  ([`d4e8d98`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4e8d9878b6b83202dc00bc2569798b425fecf42))

- Fix formatting
  ([`cf31d43`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf31d435a2ad9d219ed2400f3683147503cba3ec))

- Fixing linting errors
  ([`934e5ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/934e5ad5c5af6dc2a775bc9edca3f2a030ee9719))

- Fixing test name
  ([`c6e3e6b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6e3e6b4390e4bcf03282917400c81bbb29e521e))

- More deliberate error raise for walk submodule
  ([`589d00c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/589d00ced1a0ba41faa6ae9b448b8288ab9a40b1))

- More minor refactors.
  ([`a7d5fa0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7d5fa023030b7a380ba0b5c6e42928ff86e57c0))

- Moved test back into class
  ([`714d2d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/714d2d6933cd530a318fa5307bef1fbf5ef3a590))

- Moving discrep. page to private
  ([`a276c8b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a276c8b6293e01a8d9851ea8ab3d540e3182a730))

- Moving page for better discoverability
  ([`739d5c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/739d5c2311165094162f46ca46c0165ffc5b3878))

- Pulled in master
  ([`51abb16`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51abb165c568b477ce06b98a3bb651bd68a1ef48))

- Reduce warning with mismatched @implements signature to a deprecation warning to reduce visibility
  ([`5b366fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b366fb821947ed91cee9ac457e28f62b78bf4b2))

- Remove callable bucket
  ([`ab38504`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab38504a69d571cadc0cff0d16e144941609f2d6))

- Remove debugging code
  ([`d04b44e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d04b44ea1b6277b2944980728a824a71dfe49cdf))

- Remove try/except in _iter_module_objects
  ([`f8ad31e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8ad31efcb78e3f446461b54230eb705eea0db26))

- Remove unnecessary bound from typevar.
  ([`7a85b97`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a85b974a0eb02c9d60f30aa254e33e9b9df8425))

- Removing resets from tests and consolidating tests and using BIT_SIM preset
  ([`c5fd582`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5fd582eb34ee3028571e6da472888f9e93fc8ad))

- Removing stray print debugging
  ([`9c3b9af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9c3b9af164f232538960ac33556de4b2a62990a0))

- Respond to diff comments
  ([`933d26a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/933d26a0a774a0d18d1d2bc14153f2769b39052a))

- Respond to diff comments
  ([`70c7cda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/70c7cdaa8f43e79919aaa8ed7fdf0185594114cd))

- Respond to diff comments
  ([`90bb176`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90bb176b66112d3676a522f84fbf24f74af253ca))

- Responding to diff comments
  ([`053b945`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/053b9458b8ebc556fc7c33ca82d8168bf3da3caa))

- Rewriting docstring for qubrick __init__
  ([`b06d9d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b06d9d1bac245357a6e092eff3e6e6216e554bdd))

- Simplify record add.
  ([`b1ad39c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1ad39c8992539abaca5e9cc0ed65e1c559b59a5))

- Simplify walk submodules
  ([`9417b04`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9417b04c671c55d63349e20f3badeddcf4654944))

- Undoing formatting changes
  ([`d177c6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d177c6fecfa104ce1946773ef42a679fcdb8530d))

- Updating type-hint return for known_discrepancies
  ([`b516c07`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b516c07cb065abffef2bfc634ab58154986bc88c))

### Documentation

- Add 'Auxiliary Qubit Management in Qubricks' tutorial
  ([`0a803ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a803ab7da8f33d8d09d8b7028c54310bb3d3707))

- Add cross-references between tutorials
  ([`ba612be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba612bec2963795503bea48171e810aed320a887))

- Adding better descriptors for fields in DiscrepancyRecord
  ([`8209209`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8209209949cc44bfb753d99259d8f1030c06fb54))

- Address reviewers' comments
  ([`a7a67cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7a67cdd87710e59f2694d661665c0a7e50597c8))

- Delete user guides
  ([`577603c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/577603c277d43c810d0106428b78677be4a002ab))

- Minor text edits
  ([`c678781`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6787817fed758d3a175377429f698ee230a4dad))

- Remove user guides and old tutorials replaced with new ones
  ([`801b01d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/801b01d99785d6e9928793aa0882f1db1242d285))

- Updated getting started import instructions
  ([`1b08f6d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b08f6dd9e6ba97092d3a3fbea4ed4c15f8fde73))

- Updated release instructions in README.md
  ([`031cda5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/031cda5b693fe15f169e9f44f218a8dd074beb67))

- Updated sidebar nav color
  ([`b0fcfeb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b0fcfeb07ce72d187ea88e27697579b5c058ef72))

- Updating docstirng for Qubit.pull_state()
  ([`2a38622`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a386228fa630ec1320071a71d1e55dc1cb2c4ff))

- Updating documentation
  ([`c63d37d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c63d37d168bc236d2c0770321ed337a2d446e0cf))

- Updating documentation and tests
  ([`32c6014`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32c60146f491a646f3e2507b329bc46dd21b9a74))

### Features

- (WIP) add more test cases
  ([`9b4110d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b4110da58341c139c4d13f85919442ca7ea220d))

- (WIP) add test for PPO weights
  ([`d152339`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d152339b66dd2219b36fde08c6a191bad11a981c))

- (WIP) added tests for rotation angles and checking all single ops in the lookup
  ([`5b5d609`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b5d609499e4ae1cbcd54c09bfdbb982a39ec156))

- (WIP) remove PPR buckets for clifford/non-clifford buckets
  ([`937da33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/937da33b6d41b8ce5175e14ccd31a4abecd06adb))

- Add all the missing fields except the ppo average weights and aggregates
  ([`43377b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43377b6893d7d72aaf5d064ccd3277914cb31e9e))

- Add in ppo weights
  ([`8b70dc4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b70dc4cdd24b06f6b91beeeacf3cc22ca1b10f5))

- Add passing tests for av count and bucketting
  ([`0ae45ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ae45ecbdd9bd67fce418d8b393a8f176b5bc09e))

- Add support for variable length argument lists
  ([`31a9952`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31a99520641e90632733930412617b7dca1175c2))

- Add support in bit-qpu for print_state_vector
  ([`fc91882`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc91882d1acd8e42bff29a83d138860dac35529b))

- Address reviewer comments
  ([`6f7ca5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f7ca5f9680f222608852e97279ad29239f259fe))

- Change relative imports to absolute for consistency
  ([`57c42ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57c42bacf197919929c1068488363c8a9669e712))

- Delete commented-out function names
  ([`65283fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/65283fe43848d5b9ccca64ac2c263152e5620eb2))

- Deprecate unused args in metrics
  ([`902d278`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/902d27848bf237a3d7967094727487f71079664b))

- Discrep. tracking for sqre/nqre mismatch
  ([`6751618`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/67516188602a00954c2a83569a1454b8a4e0d756))

- Document average PPO function
  ([`21314f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21314f56f9d8b344cebc8d623db27a82d6bb4d56))

- Fix incorrect typing
  ([`cd8890f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd8890f373d6e4c36e56fa7972ac40a59d2371e8))

- Made buckets for AV counts
  ([`6e43dc7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e43dc76a6d46992269269d8547b85583d1c3008))

- Make non_strict_av_func private
  ([`d8a110b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8a110b78342c57ad26125a87c0fb5694ba7effd))

- More tests, now covering all Dylan's use cases
  ([`7a75d05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a75d05b2ec4b8020ad2ab914493c013994f3937))

- Remove reference to checking old values
  ([`78f98f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78f98f59a16e008e2d1d1eaa61882703982343eb))

- Remove single controlled rotation from cliffords
  ([`9a2460c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a2460c294950c7340e28a31269ba6ded53a7d57))

- Remove support for direct AV evaluation of multi-target Toffs
  ([`14b7a37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14b7a3742a633c8edbc3318c6d6596749860944c))

- Remove unnecessary num_targets_check
  ([`accd993`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/accd993f11225c85daa47cdaee0652d2cd1143d1))

- Reorder imports to avoid circularity
  ([`269c39b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/269c39beaf829d3ab7458d19fceefb1760e923e7))

- Simplify metrics logic
  ([`c223e40`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c223e4099944e707b3022d19c8403b23e8e8167d))

- Symbolic filters further progress
  ([`1ac0a0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ac0a0ceb2d899761a4d28c91c1971f76af73501))

- Update the documentation to make the PPR bucketing clear
  ([`3652799`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3652799ca22abcb6b374fafa072c424595fb3b52))

- WiP version of symbolic filters with new AV
  ([`7647175`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7647175e70084c5e66536e72378dfa79307239c3))

### Performance Improvements

- Change bitstring to num calculation to python builtin
  ([`b3f7721`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b3f77213bb2c27916931bff4f91a07a2deefc74c))

- Optimizing pull state on a reigster by reimplementing pull state filter on a particular register
  in C++
  ([`20ded72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20ded72b51a6f76b8acb67acc51323a78604c9a1))

- Rework print_state_vector when there is only one amplitude to improve performance specifically
  with bit-qpu
  ([`c2799f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2799f020d880275f6b178a8e1d5de04bccda2d4))

- **mask**: Additional speedup for the most common mask() cases for #1183
  ([`e1d60fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1d60fd6172f08abc52376f0c068245471e430bb))

- **mask**: First-pass speedup for Qubits.mask() per #1183
  ([`9519e98`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9519e9882ab09304ddac493cd06cbd08e4b8928c))

- **rotations**: First pass of optimization in #1106, with a speed test
  ([`b7efa2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7efa2f155fb9e41ace8d1679aa5d11bd91e1a49))

- **test**: Activate this optimization carefully
  ([`3aec7b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3aec7b3787a36d58eaa6d03a13f7eaafd1c1e69f))

### Refactoring

- Added explicit checks on kwargs
  ([`b529a5a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b529a5aaba33bb0bab112457becd50c8a8b467cc))

- Cond_reg to cond_zip
  ([`ffe5750`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ffe57506a7b4228adf648108f532dfc9bd78b657))

- Fix argument order for `ConditionedGateBase` and derived
  ([`7846519`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7846519e438dc4c288d2022b6e8b277f26b43419))

- Further cleanups
  ([`7e68c36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e68c3688e55d83db478f9e063aa06f9af349df6))

- Further refactor in symbolic filters
  ([`d8b9b53`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8b9b53091fa14be98cb7b2f71f19ab2259b3498))

- Further refactor in symbolic filters
  ([`12e688c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/12e688c3dcd094b5cba2b53b489ce3e693f4d0ea))

- Making dataclass frozen in registry.py
  ([`05a7c94`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05a7c9415b6a5dd0b118adbe13611b8dae384706))

- Minor cleanup
  ([`69e104c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69e104c1a8190c1516b6c8bf7cea9a75ea224ff2))

- Moved to pydantic dataclass
  ([`fc85399`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc853998cdd6eee4c39d2c94094f3c063401aedc))

- Remove redundant import for qubrick discovery.
  ([`7599f7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7599f7a399f97a44b83035a255179b37792ed937))

- Removed relative imports
  ([`597fe47`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/597fe478cd8e279387bf7e7c1c300686981edef5))

- Simplify membership check for dataclass obj
  ([`68f8d95`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68f8d95c02d958829554cada0e13eae9ceb7061b))

- Simplify symbolic compilation
  ([`24b8a0a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/24b8a0ab94f9c88dfb08271e12c262b8d1dcb2b2))

### Testing

- Adding test for the transitional error messages
  ([`9bdf691`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bdf69159ffc9fd3a8a37dd07f92066a82f75526))

- Adding tests
  ([`d38609c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d38609c7dc3f5a248ca55ebdd0ae3512583986e7))

- Adding tests for optimized pull state
  ([`2c929cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c929ccf5b217de0a58e15acbe74b5bcbf5a4948))

- Adding tests for QASMExportFilter to fill out coverage
  ([`58324c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/58324c51e3187363aaf92911be796f5ac448c426))

- **ladder**: Add a failing test for #1155
  ([`a461074`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a4610742b6e76ebbd5e2b3790fb11255d9d7c921))

- **old_vs_new**: Comprehensive testing and comparison of the old vs. new methods
  ([`5a0b011`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a0b011eb0ae3bf515c71ee4a38cd7522eba211e))


## v4.28.6 (2025-09-10)

### Bug Fixes

- Add missing seed
  ([`6893776`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/689377654afac6db5b4be5836a6b9e90d35b01a3))

- Add phase gradient via catalyst circuit oracle
  ([`3b07ef3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b07ef3004d4963e962c819c05ba068c160736c4))

- Address bug in QFT using phase gradient qubrick
  ([`b145af0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b145af0f2792289a8d6675c0c65246d90cae74b8))

- Apply Dylan's suggestions
  ([`81cd571`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81cd571f648a6bb12f4cc24a3afdd8d73bfb2253))

- Catalyst syntax in example nb
  ([`5b9dc5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b9dc5e6d9e8124db0b541bce9ad8ba1e58741aa))

- Change adder variable name
  ([`cebe049`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cebe0498997601cc4d1b19d14117f0b08034cf43))

- Deg unit import
  ([`0f6e103`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f6e1032f0019305aca4acf2d80d944fe365812b))

- Delete unused helper function
  ([`d35d6a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d35d6a8d3aa56be5c077fb5268ffe70c83689944))

- Delete unused import statement
  ([`84bbea6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/84bbea6967992a8d46e7ac058d79630201c9c52f))

- Reorg phase gradient example notebook
  ([`781f80a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/781f80a587c6340f5fc8a9fbdd1bf9ba2d80b0e0))

- Reverse QFT class back to the original implementation
  ([`d82ed22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d82ed2288973031b0cefeac42b4841dd7d71f48b))

- **coverage**: Remove autogenerated QASM3 Parser from coverage
  ([`d980607`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d980607e49f08d0aab755b3915608f080743b7be))

- **docs**: Remove link to deleted Witness Counter Deep Dive tutorial
  ([`3c19737`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c197377694e8b60bf8eef8f11e6c16a1b86127d))

- **error**: Improved error messages for phase gradient
  ([`c7ef8d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7ef8d52d8dc8c8862d106c7efb769489c1c05da))

- **highwater**: Fix for highwater witness bug in #1164, bug introduced in !667
  ([`a308988`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3089889a9c72e96fa97682d5721e020ac7676c9))

- **lock**: Re-add a line which got merged out
  ([`d847fe0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d847fe03160081057434e24493bea89184d17366))

- **phase_grad**: WIP fix for Schwinger part 3 #1158
  ([`8eae603`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8eae603c1adc2b83b628d756f5c39195748c994c))

- **witness**: Fix error in #1164 and ALSO update test #1004 so it fails before the fix
  ([`8f37502`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f37502bbfc7879b1025c5133c49a1a865aa5420))

### Chores

- Apply review comment
  ([`4e35bbe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e35bbecc046d7b276d1cbadcbc9fbb576e72524))

- Bump version to 4.28.5
  ([`e272605`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e272605442acb0d08511d64ecb2cc6013ff53fda))

- Merge master
  ([`4ac5f57`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ac5f577f42c27a83749608fdf915843bedb98f8))

### Continuous Integration

- Pin poetry version
  ([`56c05fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56c05faa3a9fb8638005c185cf58304ac51ac25f))

### Documentation

- Address reviewers' feedback
  ([`f2fca88`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2fca88aadfd2e333ac1611b84ba7f93f128f0ee))

- New 'Testing and Debugging' tutorial
  ([`007d37d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/007d37dafb5a2b0fad0659662f0091a8df61bcf9))

### Features

- Add test and example for sequential phase gradient
  ([`0020aa4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0020aa42a69cc95238e091a71da760f548be21a7))

- Allow QFT fallback, simplify for loop logic
  ([`1f5da38`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f5da38ac11622a4e8ba7fd1f665fb94b5ad89bf))

- Include more abstraction for phase gradient via catalyst state
  ([`aef14b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aef14b560df91107f9d0d82f8ab9772cecff86e5))

- **locks_and_docs**: Some minor tweaks, and better function call documentation
  ([`0e696e6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e696e60a8c21787303913a03c56870a9a4510b4))


## v4.28.5 (2025-09-04)

### Bug Fixes

- Add unstable marker to Parameter class
  ([`414c92e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/414c92e2693947c6f9d2b7f6d6ff204111ccdf5a))

- Catch warnings when using QubrickCosts at module-level
  ([`8daf1ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8daf1cab06550ad03f3cf3d48171a7e48c7a98b0))

- Improve error message when formatting stream that is None
  ([`2a26374`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a263744bf82273b6e3b3741fe32f75cbb5ffea7))

- **coverage**: Moved old_conversion_code into archives for #1154, adjusted tests, all tests WB
  pass, and WBA QApps still pass unmodified.
  ([`741490a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/741490a330a87f2886800abeab3db8338ec3081f))

- **MR**: Fix for #1147 per MR feedback
  ([`56db9d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56db9d517f814ca9b6c23cbcdb85aa6d5bb8a65d))

- **qubits**: Fixes for qubits release detection, per #1147
  ([`e1afbd3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1afbd32cc38d6036e4e23b006443aae5aa1ab06))

- **synth**: Fix for synthesis filter issue in #1142
  ([`69012ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69012ae3672f031b761e3b7a733bb582156cae00))

### Build System

- Added examples dependency group
  ([`77a3aec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/77a3aec81433fb45c2ab779567b58add80b8f1ee))

### Chores

- Adding gate costs back....
  ([`0593d62`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0593d625c3aa54ad161deee64cd95be4e683df0d))

- Bump version to 4.28.4
  ([`63d590c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63d590c6849db36e9189a57f4fa5c7dde345dd57))

- Moving compute_circuit_volume_arbitrary_unitary to get_av_from_op
  ([`fb5f349`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb5f34918f4e8331ecc2a76e0df61bd203b3dba3))

- Remove accidentally committed basquiat file
  ([`0b9076b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b9076b1662e33c353cf26a0d76d458c40aa84bf))

- Remove old av notebooks
  ([`08dddd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08dddd2667bfd63091f737b7270da4cdb5b7dabe))

- Removing deep dive notebook and gate_costs.py
  ([`b890838`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b890838d52adfe73c4b61ea6a54f5a955a498895))

- Updated bartiq dependency for examples
  ([`66aab20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/66aab2037e9fcdcef0bf1eda06c932155a4f9e3d))

- Updated poetry.lock
  ([`3a51245`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a512452f3f703623b8a9d9f4f060399229db0a6))

### Continuous Integration

- Add examples test job
  ([`a3f1b88`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3f1b8871cc4ae2295af2ab85535211b7573de0d))

- Added graphviz installation to examples job
  ([`392205a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/392205a161c63b5d94e6f1043ef9b70d9161e86e))

- Allow most jobs to be interruptible
  ([`2bcb634`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2bcb634a4d75004b927b349bd1e826205484ff6d))

- Ensure poetry installs right groups in test jobs
  ([`e982b1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e982b1d0eb9cd4b93ab8bdffc58dd673249574d8))

### Documentation

- Address reviewers' comments
  ([`90735df`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90735dff62cf89520cd1bcb2de5ab8662742e971))

- Fixes/removed old example notebooks and scripts
  ([`777bdf1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/777bdf17e0e3a5407ff9c0505a878ff778ecd39f))

- Moved broken examples to examples_on_hold
  ([`6c350fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6c350fdbd4f6cefbf173c15e48914d7ad83b84fa))

- New 'Simulating Workbench Programs' tutorial
  ([`77dcf5d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/77dcf5d9dae1c1c8f0dca80481552402bd3062bf))

- Removed unneeded notebooks and script
  ([`f9e4de8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9e4de8fb938c291bb1c4e70ab7100a2fba9c94c))

### Testing

- Remove bare call of shor_sample in test_strdemo
  ([`c4d45e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c4d45e9383e414cb0246c35e39193f0cb4d6fc16))

- Removed test_strdemo.py
  ([`6ea01a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ea01a5a56415287935dda5399f5e28909992e73))

- **examples**: Added ability to run .py example scripts as tests
  ([`de5ad32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de5ad32c629926d7e74f76cd2153a63dfad8b069))

- **examples**: Fixed simplest issues in example scripts
  ([`407167f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/407167f9554e07cfcf0c4563c55312b78012a277))


## v4.28.4 (2025-08-26)

### Bug Fixes

- Fix handling of zero-target Z and phase gates in >>unitary>> filter
  ([`fae78aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fae78aa1edeb3b99e8c76333befba427e9fc3584))

- Reorder imports
  ([`80b7be7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/80b7be75368b7628f348300e895eed6e27be3544))

- **cicd**: Skip over intermittent crash in rotation synth
  ([`0da1626`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0da16262139ac1aaaf3bb18dfc2b74757657b7a2))

- **cicd**: Streamline build more
  ([`04aabb1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/04aabb1e0d7ddef444b3894e875575c0ba17e67b))

- **cicd**: Testing CICD synthesis crash
  ([`ac714f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ac714f9830c6ca7328c6ffe6828871c3508568f2))

- **testfiles**: Move output files from #1122 to ./output folder per #1135
  ([`b84783a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b84783a209bcfc41bd1da919973bd876cdd6b754))

- **yml**: Restore the yml to the main version
  ([`f9e381b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9e381b660b635948e2728e1f8659dc735675a24))

### Chores

- Bump version to 4.28.3
  ([`9902e7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9902e7c3b57dbcaa02b085ca73a69368c37f7b34))

### Documentation

- Address reviewers' comments
  ([`2adda0f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2adda0f84cdb81a4bb60b7729e6293819b897dd8))

- New 'Configuring Program Execution' tutorial
  ([`675af9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/675af9d1881ef203e74b4ccd1841e041b74902e2))

### Features

- Add need_basquiat_adapter helper
  ([`b4bda2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b4bda2f14d0d2f113836b0bf54d3c325ef8f49a2))

- Split Qubrick labels in circuit diagrams into two lines
  ([`9bf44b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bf44b3a0a1d747580469d9121e932b7cbd394c5))

### Testing

- Use need_basquiat_adapter for tests of symbolic resource estimators
  ([`ecc8c0b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ecc8c0b96807b4527c256fc258a0c704d3c67bdc))


## v4.28.3 (2025-08-23)

### Bug Fixes

- Failing qapps test
  ([`4047449`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4047449a537db3fb473a64b063977b18828e4819))

- **av_ops**: A few small fixes to the AV witness counter
  ([`325c213`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/325c213d66f3c0b8bd1099f770ba7fbe03c4b929))

- **jump**: Fix for jump opcode checking
  ([`2c3a2e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c3a2e29a5f348c825973772ddb0e09f2f66a0f6))

### Chores

- Add wrapper function for get_av_from_restructured_op
  ([`b38a748`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b38a748a7a9c9630dea8516bb6836c38567b4f14))

- Alter simple to gate_counting for cost format
  ([`b50ea23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b50ea230d6fe29dbaf5839370e4f544a30fb7ca8))

- Bump version to 4.28.2
  ([`d40fdb2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d40fdb2fc3d4aed24324a185f89083969e71156a))

- Do not suppress warning in non-strict case.
  ([`94c7dce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/94c7dce55a4d137e447ef2012f6b6fdb2519fedc))

- Refactored the optional Basquiat import
  ([`c86a30d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c86a30dca05a68b11ebe02c9c6df3feb2b16c808))

- Remove need for cast function for baquiat
  ([`c8d5534`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c8d55348172ca7893e87906a3442a96888471903))

- Update decomposition rule
  ([`8bb029e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8bb029ec23d82e2fc98b22e5f8d8b74152a6fb98))

### Continuous Integration

- Fixed macos build issue
  ([`1371663`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1371663f47c5b35a0facbcafdc7848e51f6d6d79))


## v4.28.2 (2025-08-21)

### Bug Fixes

- Avoid import to pytest in needs_xxx decorator factory
  ([`f2f6d57`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2f6d5792fba793103d542bb403d753c6f08fa56))

- Do not yield av warnings if no av is requested.
  ([`dcb3b13`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dcb3b138452052fbea7900aa99a785d62c52c947))

- Previously failing tests.
  ([`9e9b04a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e9b04abf3213670ea18515e9fb8fdff20ec4f78))

- Turn off av counting
  ([`f966848`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f966848dae7c8503a6ca7f23e7610d6b4e8631f1))

- Witness counter warnings for toffs
  ([`e5fcaff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5fcaffec72a92833d5716379daeb03103884aca))

- **cicd**: Add scipy to the CI/CD build for docs
  ([`c67d730`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c67d730b22d3f62fe29b3f7c3e946f7e4d1b0fa0))

- **docs**: Fix link to getting started
  ([`8d1bb2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d1bb2e9d72d788432feaa3f643d60f8e3042ab9))

### Chores

- Bump version to 4.28.1
  ([`b471a25`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b471a258890ae80efaf3d2744206ffd41b5e4afe))

- Merge master
  ([`3d1a381`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d1a3818b4b74c058a661e52c48d50ffc3f1516d))

### Continuous Integration

- Add explicit image specification for macos jobs
  ([`d2fbc1b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d2fbc1b6994f4cf33b6ca9b8d276e35f7d7fe51d))

- Stop calling different python commands
  ([`1bdb6ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1bdb6ac63eb02f9427d64826158bd5e9caa82477))

- Updated dev-ops/common include reference from 0.0.6 to 0.0.7
  ([`971f5ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/971f5ec7fdc1b4bc3a57bbccb6b6177c3f065b8b))

### Documentation

- Address reviewers' comments
  ([`26d866f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/26d866f29984191635b7425ed345edac317fa191))

- New 'Uncomputation' tutorial
  ([`3439071`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3439071f0a1b3b0413235e455a118305da5010d7))


## v4.28.1 (2025-08-20)

### Bug Fixes

- Adapt column counting such that when there are non-consecutive qubits in the operation, it counts
  as a use for drawing purposes
  ([`bde4ddf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bde4ddf18fe1624a824d30649288fb66b82653c0))

- Add check for whether the space between qubits has been used in a previous operation to determine
  the latest usage
  ([`c367e96`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c367e9628fd29141d73087db11cb7df65404d9f1))

- Adding tracking for more full column, but no direct qubit addressing operations
  ([`5708152`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5708152826f64d844921531d9ef07a97eeef3f80))

- Allow multiple phase gradient
  ([`1e206b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1e206b020202dfc63c527d7478578bd3fa76a300))

- Change start gate to z, reverse bit order
  ([`b07c144`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b07c14498341ae2bd766babd148cdcfae660de18))

- Changing the padding factor and labels with no operations are removed
  ([`38d23b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38d23b18a246bd1911ce6927f20ab41b8c1d34bf))

- Ensure empty labels at end of circuit are not expanded
  ([`23a1cf2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/23a1cf235518fb2fa397037bea9a93f90cc5e42f))

- Fix indentation that was excluding some instructions, rework logic such that operations on
  different qubits don't artifically expand the width
  ([`1f5387a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f5387a42177d339663fbb64fc0e0672dbe04080))

- Formatting
  ([`5d43fc8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5d43fc8a78827fac869803ab3e1f333e84c5b551))

- Make sure nops get counted in the operation width
  ([`2900170`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/290017074319fe7d93650430ec18b6336bfdee92))

- Minor edits for test file and lint
  ([`637db52`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/637db52173bfdb501fbaac3eb6a2fa9b7b2f02df))

- Modify naive phase gradient and phase gradient via catalyst state classes
  ([`ba4b33e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba4b33e3751923311ecfe6f3f38a216fc9e1340f))

- OP_qc_swap is not being used and yet not having it imported somehow broke the docs. Nothing makes
  sense.
  ([`cdccbff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cdccbff39e5dbe981aff7caa125d0a75e0f612f2))

- Remove print statement, fix assumption when getting all_qubit_mask
  ([`a35cd0d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a35cd0d9b97b51b473efeaee0008adc0a560ce6b))

- Reorganize conrolled naive phase gradient test to include checks on the entire matrix
  ([`f827467`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f82746712a4f43d4c4640f4900f4a3c0c11bdb95))

- **assert**: Per feedback, require assert for overlapping |
  ([`f41f881`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f41f8811769d9144c67ce0c9054c076d82d314c3))

- **assert**: Re-add overlap assert, per collaborative feedback
  ([`245c020`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/245c0206e9381a456613b88cf8fcbf9f22d093fb))

- **cicd**: Add basquiat-adapter to extras to fix test:coverage job
  ([`08654f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08654f58b4d88e148ab94300bd1c7ff1edaf0d39))

- **cicd**: Add more optional references to basquiat-adapter
  ([`5200123`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5200123cc9bc36e443a0cda4943a57672d2b2c20))

- **cicd**: Add pyyaml as a non-optional dependency to fix builds
  ([`3a38fff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a38fff0b87cc4a3d53eeb757667c0a44e2bdab9))

- **cicd**: Allow mypy lint to fail gracefully
  ([`dde7427`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dde74274dc739a7a674376a13a10df5e13b4b220))

- **cicd**: Attempt to fix poetry issues
  ([`45e3fec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45e3feca5664aad18351a2f3c987e10f9b269f81))

- **cicd**: Minor fix for docs build in cicd
  ([`9e2a4a0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e2a4a06fca07a7df1e1b9e02ecd2d37dc835f93))

- **masks**: Minor fix for mask overlap checking
  ([`be5e37a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be5e37a3dfc15ba8ff89357e8f536d426dd38ae7))

- **MR**: Tiny fixes per MR feedback
  ([`048b133`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/048b1335c28ab800715258a88660842e3b2652c5))

- **operators**: New tests and substantial fixes
  ([`099637c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/099637cd686840b259feaebbdacd3b5a731f5b8e))

- **poetry**: Update poetry lock file
  ([`4c90935`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c90935f989ef9957bc8840df4c2cbbb4cf0c043))

- **test_name**: Rename test to issue number
  ([`b3d2d2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b3d2d2ec1811d70103bcd283e0e7b34954ca9a7c))

### Chores

- Add -p no:warnings flag in coverage job
  ([`d93622c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d93622c51274874e263d82f1f7221466fb748b8f))

- Adding additional tests for _get_magnitude_approximation_av_from_bits
  ([`6046061`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6046061c595b651df25e7e0913a2d161eddcc95b))

- Adding get_av_from_op to ims_transpilation.py
  ([`80665ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/80665ecde4d2fd36783578bdccf8bbda3c4ac84a))

- Adding test with wrong extension.
  ([`2bec703`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2bec70330e6393bba3fd717ea5b357ab9311c16a))

- Bump version to 4.27.1
  ([`3f49bbd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f49bbd357e362132e728dda7d24caef99320281))

- Fix lint
  ([`c95a71d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c95a71dcc83573d5d989e8a0a4f23946b4a575d1))

- Making get_magnitude_approximation_av_from_bits private
  ([`4a7f6ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a7f6ae8eac623fcf481bad53fc0be8baae66966))

- Moving imports to top of file for test.
  ([`62b856f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/62b856fe0ba051b81922cbdd16abf3659fea1927))

- Remove active_volume_lookup_v2 from
  psiqworkbench/resource_estimation/witness_counter/witness_metrics_functions.py
  ([`8f27c0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f27c0e0e84e3818ea33be6f563baf695c3ea1af))

- Remove old count av logic
  ([`78f1794`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78f17942db09dc4eb76a95974f2d6baa05b6ce32))

- Rephrease comment docstring for PPR magnitude function.
  ([`716a155`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/716a1554272127a9b72afbd74e28774b497fde73))

- Responding to MR comments.
  ([`3d14279`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d142798c70428a0823bfe04c643bdd449072198))

- Revert function to not break api for magnitude approx.
  ([`2f1fa71`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f1fa713d63295c43f74c628d1d33735f012a262))

- Simplifying test and clarifying docstring
  ([`390a6b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/390a6b2cb7bc3bbc852431696b536f59c30481a1))

- Split magnitude approximation av calculation.
  ([`121ce12`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/121ce121fbdeaa99f037cd34739a0c285b52b28f))

- Update comments
  ([`73109c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/73109c7ff3c3f9943f3960df1940efba9d35bb9d))

- Update psiqworkbench/compilation/filters/composite_filters/ims_transpilation.py
  ([`df6b6b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df6b6b0d5f7f1d15ab45dc91bddc0b6b99edf5d6))

- Update tests/test_912_debugging_witness.py with updated av logic.
  ([`be1dd5d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be1dd5dabfee2bd3ff93e0a92fb13ed7cc7c8339))

- Updated poetry.lock
  ([`37a1ba3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37a1ba33bc61f0c5663473b5ebc3f408aed8110a))

### Continuous Integration

- Update docs:deploy:prod dependency
  ([`2a97095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a9709535e65378a52a81a4767ea1c04ea0f4f75))

### Documentation

- New 'Qubricks' tutorial
  ([`445bc02`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/445bc026716c5dd4394e6b9c0be69284eb90d8d7))

### Features

- Add controlled naive phase gradient unitary equivalence test
  ([`dde9ff9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dde9ff93979e93a5e82994b81025e60aef773900))

- Add helper function to classically compute catalyst state
  ([`ddd9293`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ddd92936628e7c59621cb99c99f2905849047040))

- Add new names for simulation filters
  ([`52bcd8e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/52bcd8e1517650c42420bef1de3d5877430dcefd))

- Add padding to fit long label names if needed
  ([`3b2c688`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b2c688cd57e0315ce7fbdc5faa4d2167e875948))

- Add phase gradient example notebook
  ([`0af6273`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0af6273f6f6e5a4fed50e26a57b5701c0d883775))

- Add test for phase gradient circuits
  ([`dde827b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dde827b31d51d1f1a39f1e0134b46fc2346e373e))

- Draw format for qpu obj
  ([`0989359`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09893599812b84d424e15806d0de1864224f66c8))

- Implement phase gradient via catalyst state class
  ([`53d8c5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53d8c5b84a7d53f9e8c9c5fae02cdb5e1cd32043))

- **operators**: Adjust overloaded QPU operators per Sean suggestions, just to test. All
  back-compatible, all tests passing
  ([`cfe842a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cfe842a93b229c745e6fa1bdd9d86fc3b5ae4072))

### Testing

- Added WBA as explicit test dependency
  ([`066e0e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/066e0e2675f417391fedbde84514cad8b307103d))


## v4.27.1 (2025-08-14)

### Bug Fixes

- Fix needs_sympy import
  ([`bfb2a50`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bfb2a5033851352b9f0de29a794a4513d53733a2))

### Chores

- Add generic warnings to check_warnings.py
  ([`f1cd09d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f1cd09d8cea03b1a4798348bfcde3b111d8ec28d))

- Add install lxml to gitlab yml
  ([`3add090`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3add09069c64d59a53882ff0b9f5e6e4454a7227))

- Add statistics to mypy report
  ([`158a037`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/158a0375487d067060eb147b0b2826110020a415))

- Add txt-report to mypy output
  ([`90119be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90119beaba6ff03597fcabe0480a9c17b148c890))

- Add || true
  ([`d9d8d64`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d9d8d6459c81d8e0254201be02cf836226dd2126))

- Bump version to 4.27.0
  ([`6f3fcc0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f3fcc0b1ca0fb92f8ae3a84fe88450853bc3356))

- Fix artifacts section
  ([`bac457f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bac457f2f8a4092a5de15f0af84a7939dad82e17))

- Fix pyproject
  ([`97b3c7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/97b3c7c44d08665bc0fc957b9dc037ade5964a65))

- Remove &&
  ([`37e6620`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37e6620f9bbc3fa94244151f277bdf64b5e064db))

- Remove backslashes
  ([`00b06d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/00b06d70a3a14bab50fd3a9fb16f469043569635))

- Remove conftest left over after the merge
  ([`ab00ede`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab00edee200dc352cf5a23280a40df372749d6f2))

- Remove level reports and fix rules
  ([`3b8353e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b8353e621cd286d77071a4a2af6459e9b4ce3e9))

- Remove statistics in mypy
  ([`92c95d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/92c95d0b9de0316b973beaac7aad268d3d5d0191))

- Update Adders to match interface
  ([`9bc3d87`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bc3d8721c7d2938de27a45880aa78fad0fc4e45))

- Update lock
  ([`5099b14`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5099b14af29d2fb543befb9e1b7569a14b25641f))

- Update lock file
  ([`5f0403a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5f0403aa57de38eafffc2376fa37fc0b6d1e1f13))

### Continuous Integration

- Add mypy to gitlab ci
  ([`01b0a1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01b0a1dd745ad2d688af9c92a7868d205e9d4104))

### Documentation

- Address reviewers' comments
  ([`eb07c3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eb07c3e5841cd65105f7ce4ea7856342fd9548c6))

- New 'Controlled Gates' tutorial
  ([`d12aada`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d12aada6ea74c67402b6b7ae9c4ff25e27b1b662))

- Publish new tutorials and deep dives
  ([`1a418aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a418aadabfe137e5a68c04ac15361ff10a6a7f1))

### Testing

- Adds needs_sympy and needs_bartiq for simpler test skipping
  ([`3ea591a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3ea591a870e6cab3a30556b6e3c2b25d8b70bdbc))


## v4.27.0 (2025-08-12)

### Bug Fixes

- Restore import of compile_symbolics_costs in test_helpers
  ([`922453e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/922453e8226924c19ab99c07cfa245b269a30eed))

- Use "active_volume" key instead of "total_av"
  ([`af14b2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af14b2fadce14986de501b9292f3281ce35940a2))

- **ppm_functions.py**: Account for parity in y weight for av
  ([`f6f659e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6f659e599e1096cc7dbd654111b131211e6225b))

- **ppr_functions.py**: Account for additional Z weight in ppr injection.
  ([`77ff868`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/77ff868f31472d845d6d41b4269452702ba95a5b))

- **test_994**: Add y parity to rotation av checks
  ([`b821783`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b821783c3dc83e2aebdefc2f4eaa759fd4d8cc80))

- **test_native_dialect_numeric**: Update PPR and Rotation AV costs.
  ([`bb6fada`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bb6fada88688e391fce9687e0380042e3f0d7b85))

### Chores

- Bump version to 4.26.1
  ([`b7a4bc9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7a4bc961b2c1d95d289c07dab38c7c766232685))


## v4.26.1 (2025-08-11)

### Bug Fixes

- Add handling for more arguments in class, but must have defualt. fix adder interfaces to have the
  same name to satisfy the conditions of the interface checker.
  ([`c222445`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c222445e6dc654059916a95f22a125399d50c582))

- Fixing qubrick injection demos
  ([`b1e2e64`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1e2e649436131fe7d6ae7b09b3fee479378a5ac))

- Grammar and spelling
  ([`dde8005`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dde800561ba6931dd8d63422fb2ac88c5d6fb276))

### Chores

- Bump version to 4.26.0
  ([`1f5ca73`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f5ca73df63f6872ec3d6dc3ba5f54ad9ded9dbc))


## v4.26.0 (2025-08-11)

### Bug Fixes

- Add CompiledRoutine to except block
  ([`ba92e7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba92e7b76f6c9ff2b2bc8e03f12a192e81925b94))

- Add missing __all__ field to resource_estimation.qre.__init__
  ([`be84eb2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be84eb254d35308f27746412f28615eb3794f287))

- Add missing Any import
  ([`9a09b92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a09b92c2066e6d4c5d878cf45ad7575e553177a))

- Add phase gradient qubrick to QFT qubrick
  ([`2f43499`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f434996f552c50861b392c0e59479c9c29aab87))

- Add resource_estimator to __all__
  ([`0ba734a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ba734adad3c315a52196c719702746d163a856d))

- Adding lelbow and relbow for av lookup in tests
  ([`af22902`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af22902d74f011500595f628ede1192c3d6b71e4))

- Allow docs to build when bartiq is not installed
  ([`ab8ce72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab8ce725e5ff18e795577cace8602c2bcb3af2d1))

- Attempt to fix pipeline
  ([`af1f89d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af1f89d551ace782fb3978a9ff3247094307f482))

- Broaden the class of warnings ignored in tests
  ([`606e36a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/606e36a07f228fb573d9a525fa7919b0cc876d6f))

- Docs build adding placeholder function
  ([`8f3e924`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f3e924638aa05ad40eab5d8a05ab119f375693b))

- Fix broken docs build
  ([`04aceda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/04acedaf2eab111ed155054bfd251d64223bf1e4))

- Fix lint errors
  ([`d2a6a83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d2a6a832c9d23c8a2c6c78e687385352d15a2fb0))

- Fix message pattern in ignore_unstable_warnings
  ([`149f826`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/149f8265faaf5de29fcd4e2a6b659cdfaee3bb66))

- Fix module name in rotation_utils deprecation warning
  ([`74095ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74095ae2e2b822c1ea70531b4fafd85383c13e5d))

- Fix typo
  ([`e4eeeef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4eeeefa490d32b034fcd0107f7d911f158fa432))

- Fix typo
  ([`eb4801c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eb4801c1dbad70092a0cb2dfc01d13c1fa509abc))

- Fix typo in import
  ([`cdf40e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cdf40e4b91e5fdadf83258f85d6badcf21ecb864))

- Get_total_costs for witness counter now has desired behavior
  ([`9e628b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e628b1a1aa0f03a5cd59e78fd711f31a40e5de6))

- Improve how registers are filtered out in QREF conversion
  ([`1789181`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1789181a5c645641ae33a095ab2c6f64e939328f))

- Invalid variable name
  ([`cb383ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb383ec5cda653816c6fceb68ca1071cf1aa697c))

- Lint
  ([`573f18d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/573f18d50cf749aa777827c40ec1e9c19113c187))

- Lint
  ([`f1f7d3a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f1f7d3a0c85076cf72476a2ad0b96d4013bfe5cf))

- Lint copyright
  ([`90f5115`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90f5115315a3390def7753db2702ddb0e80654ae))

- Ommit message in ignore_unstable_warnings
  ([`93ff4df`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93ff4df7f2f6803e0b16dcc2dce43388f1fe165d))

- Place import-related try-excepts near top of the file
  ([`c1f3e09`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1f3e098ae3e3b9ea7ae312320566cc53cbc6744))

- Remove duplicated ignore_unstable_symbolic_warnings function
  ([`59fe22d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59fe22d8f49f957aa416ffd468e620706cf383d3))

- Remove extra whitespaces
  ([`e4cd777`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4cd77745438bb00de95045b2b90ad0f91596244))

- Remove filtering warnings from gate_costs_v2 module
  ([`673f70f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/673f70f7d5b7d6a03093a84e1cf8995de2d121d7))

- Remove trace output.
  ([`78fae84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78fae84538ad55c58896f788ccba263feecee5a0))

- Remove unused imports
  ([`32bfef4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32bfef4d67e135ca1a04f42c8727e7b80dd9696f))

- Updating non-intuitive behavior in get_total_cost and fixing add bug
  ([`54d2955`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54d295575ea3a85fb988699c2b0b3dc193f48a48))

### Chores

- Add docstrings to public methods
  ([`d1353fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d1353fcd75907f1acf94c6899fa1971017800058))

- Add error_param per rotation
  ([`6bf5670`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bf56703adf9ad880b72820f8aa87cfe20df1d54))

- Add xfails for ppr tests
  ([`f95e9ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f95e9abfeb0774140645dae1dc6eddacfa2b922a))

- Added minus sign cases for PPR tests
  ([`c49631c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c49631c5887ae8ea98f1e2ad6ac5909132dd455d))

- Added test to verify PPR with same angle but negated yields same AV
  ([`6a5f7ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a5f7ec2bec8011df0fff043596fb14dda0a9679))

- Adding all AV tests as described by Dylan
  ([`11693e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11693e970a9c8d21b165fc7654714ec9cf43359e))

- Adding av tests
  ([`0e35248`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e352481e1e07e9e628713b9da7f4ca4cccd22cd))

- Adding docstrings for Op class.
  ([`c1d40bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1d40bb4f9b681877bef73b564fc62fcf435e918))

- Adding test for ppr neg angles.
  ([`d6c402a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6c402ae87dfc31f05df6518a273d0646c169290))

- Attempt to fix check_project_configs.py
  ([`c405194`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c4051944d724efc5683cb3a684baa4804ef9dd2e))

- Attempt to fix check_project_configs.py
  ([`59975f6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59975f697960885866da87a7083e7167ff74c0ce))

- Better exception handling for try/except block in notebook
  ([`47575fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/47575fe00fcaf1534e2726211e314dc2ccd76439))

- Bump bartiq version
  ([`fcac378`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fcac378f14c01554183cd104424a30c978f19fb4))

- Bump version to 4.25.2
  ([`3556bcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3556bcc281d80431b42d9694be136c4c51c638d6))

- Clarify arg_sig to argument_signature
  ([`f7b9dc1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f7b9dc1dbbf61bcb718f984cba3e67ad085ccd2a))

- Cleaning up tests in 1042 test file
  ([`45f591b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45f591bcd76441bd7d41bb8a235e1b2b60dee8a8))

- Deleting commented decomposed_witness
  ([`3e88423`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e88423e66b3f8408197737d2c05b5eeeb2e0a20))

- Deleting non-functional code.
  ([`bc338a0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc338a096c45ad4c5054cdcabcd0d74d9c6f4b2f))

- Globally disable warnings about unstable symbolics in tests
  ([`8121b18`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8121b1886cf8d7553c669740f3a4c86c20053ad0))

- How in the hell does changing this break tests in completely unrelated places
  ([`ef7dd81`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef7dd81396e2b14ab860bccde202eabc1ef21763))

- Import * changed to explicit import
  ([`909ffda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/909ffda5f8d85f001227d4094a68469276770b68))

- Import Callable in notebook.
  ([`85d5536`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/85d5536cddf8cc28c1745919dd04d112c579f02b))

- Made op.py to _op.py and moved all to init
  ([`ce36399`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce3639997ae34706c7caf1990ffab7821390aad9))

- Putting if flag counts back for failure
  ([`b73b2fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b73b2fa5945cf2bd13d48ce534d6521557ba212a))

- Refactor default metrics functions
  ([`f7a93c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f7a93c12c0ed9a69d0e01653dfcf04330b726ef7))

- Remove comment psiqworkbench.resource_estimation.witness_counter.witness_metrics_functions
  import... from tests
  ([`5b20195`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b20195607fe5ac16ba5214abdb728e50b8afd18))

- Remove commented out import.
  ([`068b87c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/068b87c326d1c83a0f5bb561b46bad7bca901fc9))

- Remove commented-out needs-compilation message code
  ([`1736294`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1736294e614c3a32a0e683f84723d84dc2f96c01))

- Remove dangling comment
  ([`ea34754`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea347548db36b4030c1d5aa74b6eec99cd7ffc40))

- Removed imports from test_771_independent_metrics_counter.py
  ([`070ba5a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/070ba5a81195f4f480f7891fb9b416a35fc490f4))

- Removed validate_witness function in favor of witness.validate, added some TODOs to be addressed
  post joint review session with @vrusso, @acaesura, and @ssim
  ([`1fb7aae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1fb7aae3699f646e28642625e05210e330f78711))

- Removing assert false from is_cost_event
  ([`ab88aad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab88aad341c362edd4bb01f1dfb5f08ad4d14060))

- Removing assert false from is_cost_event
  ([`38996bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38996bd4b5e77e8d106521d131bacbd1a893b0eb))

- Removing commented out line from witness and highwater function from EJ note
  ([`e8516ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8516eefc52892a153c9bdba4b0c0f0eec32fcab))

- Removing commented out resource field
  ([`f87db32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f87db323eaed28cec7ccc540a3de783a6060a3d9))

- Removing commented out resource field
  ([`24ba40e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/24ba40e19d5ab2159d55699bcdce2e482663dea6))

- Removing extranous cells from av notebook
  ([`ca3bffa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca3bffaf2823459014f84ae4ad7b46b0d96cca92))

- Removing something that is not used
  ([`47a011c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/47a011c2cf1bbd75527520b1ff50099e30c03d29))

- Ripping out anything with an if_flag in lookup.
  ([`08eac97`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08eac97949c84d2e5bdf16a2dd0e18a1741f8268))

- Throwing all into init for witness counter
  ([`5fc4c5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5fc4c5fc89fb8401152ec69d29fcc16e96e73177))

- Update av tests based on comments
  ([`37e8ff9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37e8ff9fd2b10a350ef3029432a966e7e1fee7a2))

- Updated test 914 to use new AV functions
  ([`78a6498`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78a64985f70a9a4048e27df4aeaee0b182746775))

- Updated tests in 1042
  ([`e6aece4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e6aece4c94f91d895a5982c5b898effd66b49bfe))

### Code Style

- Tidy-up imports, fix docstrings and add type hints
  ([`630b6bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/630b6bd6306fc1a24aedb8bf76debc62b4afe2eb))

### Documentation

- Add docs on QRE interface
  ([`c64f414`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c64f414faafd432b0db55a29f31a18f4b2fde492))

- Add docstring for resource_estimator function
  ([`f3ad8c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3ad8c9653125480392c935a416bbe51d1f94325))

- Add docstring for SymbolicResourceEstimator
  ([`0da34e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0da34e2e7f5d33bc5cda6e0e9aa22998597894b3))

- Correct info about default backend in docstring
  ([`f513071`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f513071cc3be8fb8f34d98eb32899288f0ba9abe))

- Fix typos in docstring of _SymbolicEstimatorBase
  ([`9a28ccc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a28ccc3e13b25915b7c825f04269546fc0bd9fb))

- Improve docstrings and typing
  ([`dfb7d8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dfb7d8fd9fa938ac43dd3e453ac1e8309cb591f1))

- Improve docstrings in Numeric estimator
  ([`aefda9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aefda9b9d2e434b10cbe1f3ec8d4b0993c9f231b))

- **readme**: Added pip config instructions
  ([`ae50522`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ae505226167824c3870fce85f2b6fe29f298bf54))

### Features

- (WIP) add black box counting to the metrics witness
  ([`afd7c84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/afd7c84af7857729c40ced2c5d542aaf41e42740))

- (WIP) get QREs working with the witness metrics
  ([`fe1f2a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe1f2a40b755cffbefd43e6053bbf6075555f91e))

- (WIP) making some changes to the underlying framework
  ([`a2e4fce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a2e4fce1c342b2bbc02d4dbeff84e0064a9ed77c))

- (WIP) most of the tests now working
  ([`2c24298`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c242983074383d8c95dbea9319a4a9d78ce537d))

- (WIP) updates to witness counter and tests
  ([`ac05464`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ac05464aba19dc3be5c286afcf91a607c14743c3))

- [WIP] better formatting for metrics witness
  ([`b512b49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b512b490debd050e91ee64d8add87cdba0850056))

- [WIP] trying out a new idea
  ([`de16de9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de16de91d66427e229e94979107bd3cc282d58f2))

- Add active volume witness
  ([`7d461a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d461a8976786e39acf0b8652cd58827a6e2376c))

- Add aggregate method to symbolic estimators
  ([`609aedb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/609aedb4fd81ae0da982de93ff813dbdb0f99dfb))

- Add assert_resources_equal function
  ([`3cf986f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3cf986fe733bdd93598998879ceb2fd0922ebfbd))

- Add basic implementation of numeric resource estimator
  ([`098c546`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/098c54609c78b92e526b8e5ea706c5f1c3b81020))

- Add default metrics functions
  ([`918b87f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/918b87fb5ffecf49dae8434de4cc00b0221a2e29))

- Add demo notebook for AV witness
  ([`67af669`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/67af6695eb70e4391e22e8579fcc2af5888ac55f))

- Add filename option to some resource estimator methods
  ([`561c50c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/561c50cd0e16dbd7a77a3103976d802afc12164c))

- Add phase gradient qubrick
  ([`0d2e547`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0d2e547cf8a4c9902c67649cdf1a901cb3102033))

- Add ResourceEstimator protocol
  ([`c2bf82c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2bf82cacc63e2b5d489bc4df79da3bd10fad990))

- Add support for multiple metrics (WIP)
  ([`1425a7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1425a7bf7a67494b78d0b6a5999366588454b464))

- Add test helper for disable unstable API warning for symbolics
  ([`661086e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/661086e677caeef2e60f9c4adda856885102a9ff))

- Add unstable feature's name to unstable API warning
  ([`55fe8d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55fe8d5e0199d582e02e29e6466290b5d75ec407))

- AV black boxes now working properly
  ([`10faf60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10faf60a96ac99f1c4eda4036691eacd31476044))

- Enable importing resource_estimator from top-level package
  ([`7f6ee57`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f6ee57439892f0c622223bd5984031505b99afd))

- Get all tests working
  ([`2809a33`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2809a332df8f8712a4c3e299ab080a6b3c3355e0))

- Get highwater integrated into the new system
  ([`d447d6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d447d6f50be05817b2fed28acedc0e588e7c647b))

- Implement creating Basquiat graphs from symbolic programs
  ([`9006e8e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9006e8e3d413c4d32bb644922f6986b894366e2d))

- Implement ResourceEstimator protocol for symbolic qpus
  ([`e237bab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e237bab0edfa74577386c0be5570e784f4d1aae6))

- Inlclude pprs and ppms in numeric resource_estimator
  ([`be943fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be943fe530450c44b6a50e9759a06ab98ec6b58b))

- Introduce separate protocol for symbolic resource estimators
  ([`159c4a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/159c4a65618540f5b97de89b8f0f8af106c70e97))

- Make numeric estimator resource name match the symbolic one
  ([`a6e4af5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6e4af566b3fc49ed6a614856ffc460174773327))

- Minor fixes to the witness counter (WIP)
  ([`769d020`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/769d020a67bbdaf5f4a2c600efee33191d1e532b))

- Remove ActiveVolumeWitness from __all__
  ([`b616bf8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b616bf8ce2b1e4baebecaf0be2728cc93dd07ea4))

- Support QubrickCosts and symbolic comparisons in assert_resources_equal
  ([`5189a9c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5189a9cf9f2028c7ddf025b2e1343d931d538e7b))

- Update native dialect tests
  ([`29408c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29408c378bc02f22d59758f4a7d1edaad21b91b8))

- Use resource_estimator in test helpers
  ([`5cb90e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5cb90e196b4c1dae8ed95e6804785402f16b83b5))

- WIP updates to the general cost witness
  ([`e85c6d4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e85c6d44c957207b46138934ef2b6ffeb3569448))

- **get_av_from_op.py**: Improve op handling
  ([`a158b24`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a158b245e67c9fcd81f8ab02345c6a1350322c50))

### Refactoring

- Move AV calculation from sympy backedn to resource estimators
  ([`1f54026`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f54026fae3fe1ef0e96237cd03819f244642a4f))

### Testing

- Correctly skip symbolic res. est. tests when Bartiq is unavailable
  ([`9722c23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9722c23223d613c0586b667dca573cd413017b73))

- Move skip_without_bartiq and bartiq_only to test_helpers
  ([`c3580d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3580d64c17032c50ac0fb50b12916100a5a3bde))

- Replace usage of pytest.skipif with skip_without_bartiq
  ([`63c8938`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63c8938ce052db62980bfa9a7f7718bce90db0bc))

- Use assert_resources_equal instead of deprecated comparison
  ([`6c141fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6c141fba96596dbc2a8441e112c80f3327b813b2))

- Use Bartiq resource type instead of looping through ADDITIVE_RESOURCES
  ([`34a547d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/34a547dc8484cc0f7ac1157f3895f107ed655f83))

- Use expanded=True in swap tests
  ([`e929fd0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e929fd0ee0bf76ba1dceee21c60a6f165493cf96))


## v4.25.2 (2025-08-06)

### Bug Fixes

- Add missing \\ to awk command
  ([`c8dbd66`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c8dbd66ce3996689d4fccdf8e1ec35187eeb6631))

- Add version bump to pyproject.toml in set_version.py
  ([`474ebcd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/474ebcd3fc8ea65c7246de0765f88e67adb588f6))

- **catalyst**: Add ability to suppress gate playback during qubrick recompute
  ([`3cd8ea2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3cd8ea2fd8a0a52222027198317f132acfbe4a95))

### Continuous Integration

- Make coverage job non-blocking for MRs
  ([`5a1fd4c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a1fd4ca0aacca85e9aadf436eb9ba5c6db58397))

- Only run qdk downstream when pushing to default branch
  ([`d1ee6fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d1ee6fc1065ec4f0483ea2ab5f4249fd14418b72))

### Documentation

- Address reviewers' comments
  ([`1bf1f06`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1bf1f06cbe988b5fe5a13620f6460db26855b5ff))

- Address reviewers' comments
  ([`ffe8c42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ffe8c42c3f6805411deca079d1d592cb0b024e22))

- New "Basic Gates" tutorial
  ([`3c8cfcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c8cfcceddf76b80734dcb954d98c62225d82c76))

- New "Measurements" tutorial
  ([`7fc09de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7fc09dee7227563336d18f2917f1654de72145a7))


## v4.25.0 (2025-07-31)

### Bug Fixes

- Adding Qubrick inheritance to the test classes
  ([`5bd608d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5bd608d4b56acdd430c1a06940acb7b351364cd9))

- **color**: Gray change per MR
  ([`ee4a161`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ee4a1615f242b353658edc52b4bff9689d4faf85))

- **get_dag_from_qpu.py,test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**:
  Renamed qubits_engaged to active_qubits and qubits_removed to inactive_qubits.
  ([`cdc6790`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cdc679006602dc6867ab6112be37aa44b8309d6b))

- **ppr-color**: Fix for PPR colors per #1114
  ([`d60aaea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d60aaeab37806bf0a5c3804642c26eba26ed33fc))

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Removed comment out code,
  updated doc strings, updated attribute names.
  ([`86e4b0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/86e4b0cfda8a4b79515c72a83075811d39f9557c))

- **version**: Manually fix pyproject.toml version.
  ([`7405871`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74058718407ea69516a8f5b9d483133add18e207))

### Chores

- Bump version to 4.24.0
  ([`219cc53`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/219cc539ccaf22c82b66f1b0ae7f110ba55d88f3))

- Change USP to universal state preparation
  ([`f36c9cf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f36c9cf55ba0346ab5ee9619580b0ef7b20e2afc))

- Cicd permission issue
  ([`1c6d281`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c6d281d5ef47836d376f9c9f10f1be0288b7099))

- Fix griffe error
  ([`dab416a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dab416ade22ab09df54dd24ce382a3bce7b73e50))

- Fix griffe issues
  ([`ba67416`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba67416c8f16c6b10ea261975486572a919f85e7))

- Fix review comment
  ([`9eda9a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9eda9a3d31574f450b51490d6799eada72141254))

- Fix review comment
  ([`e9ffc7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9ffc7a46bbb31546019627d592de0a5ebccff9c))

- Review comment fix
  ([`4e1d10a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e1d10af5cca8b4993e7b5b4c081dfb76367c194))

- Update merge request description template
  ([`6d76e49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6d76e499c7d8e7e9e3e4e36dd58be7a8fa9b4b8d))

- Updated MR template based on review feedback
  ([`aac3b11`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aac3b1192f90dbd7d2a1d6e8199146a98df36d3e))

### Code Style

- Typos
  ([`a8800f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a8800f0380d0bd3e9a073a3d2cbc94d821f44b0a))

### Continuous Integration

- Added coverage reporting to test jobs
  ([`389c978`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/389c978b5020baf3323bbad0c151893dfdb28f11))

- Make downstream:psi_qdk manual for scheduled pipelines
  ([`61e06e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61e06e322d75bad5386707884dce3bc44de2a410))

- Updated dev-ops/common include reference from 0.0.5 to 0.0.6
  ([`b85f512`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b85f512415d6ba2eb86979e58dd19d09d475fa0a))

### Documentation

- Add development workflow to README
  ([`fe00931`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe00931eef68348fda68f8b06dbf9bf36873a4d9))

- Add private members to qubricks and show source to all
  ([`aef9b26`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aef9b264c296c76b551adb1f7303a938df24353f))

- Add specific qubricks to python api
  ([`3f5873a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f5873a8189aed6318142522a1b1e25baa4fd846))

- Address review comments
  ([`83553d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/83553d5ed3c5f46a3dde794544604191d8fe4fd2))

- Address reviewers' comments
  ([`383cbe6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/383cbe6e222e3a84f058c71fea69ec609b1a0a84))

- Make private members show in python api
  ([`feb6d84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/feb6d8440344e2e521890f9a83da7400a94a3f6a))

- New "Execution Model" deep dive
  ([`94394f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/94394f5fd7a048f42df666927a9ffa253d8b1ab8))

- New "Qubits Data Type" tutorial
  ([`dc451ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc451ecb9c28e8cdf6fe784351ea5f626c6ee515))

- Only show _compute out of private qubrick members
  ([`9632027`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96320270c62d67189c5a5d00419b1d1abc3fbc6c))

### Features

- Add error when class does not match its specified interface
  ([`818962d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/818962d14b7f048cf7af786ef5bc94c96e2b5919))

- Refactored code in get_dag_from_qpu.py and avg_qubit_estimator.py into a function in utils called
  get_active_and_inactive_qubits_for_op.
  ([`72499af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72499afcbf5e3b43d4b23f7a273f2010c3b66aa2))

- Removed count_1_bits function and replaced with python function .bit_count().
  ([`2fc2529`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2fc2529e61bd19f0eec55aed14431b990b331938))

- **get_dag_from_qpu.py**: Adds activated_qubits and removed_qubits as attributes to vertices in the
  DAG.
  ([`5222178`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/522217869f10ecebb27403390939f1dbffd5e5f5))

- **get_dag_from_qpu.py**: Improve code quality and updated attribute name for qubits_activated to
  qubits_engaged.
  ([`1561638`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1561638b068738ac2c67af468bd878864579f248))

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Added tests for the
  assignment of the new activated and removed qubits attributes.
  ([`3a933e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a933e547bec2ee4987c8f164c89a91293f6f1ec))

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Made try optional based on
  igraph import.
  ([`22517e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22517e5b709619023e361b982c69e3f77d3e259d))

### Testing

- Adding initial suite of tests for interface checking
  ([`102c544`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/102c54404c192a01e04527b24a4ca19d767c2ae7))

- Adding test to handle multiple paramters and multiple interface with different methods
  ([`d921b49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d921b4949bfa5bac76520a8e4b28334affb4f3da))

- Fixing how tests are structure to pass CI
  ([`9d9a6d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d9a6d3092a5cb51980a6ac0f912bce29fe5f14f))


## v4.24.0 (2025-07-21)

### Bug Fixes

- Add copyright header
  ([`ce2b640`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce2b6404c0eddd691db3549369521b594aca59d1))

- Better error message when missing filters required for drawing
  ([`51b04f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51b04f0f611e4534dd1da261b3dfaad7e9394808))

- Broken test
  ([`4b1b21e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b1b21e34895a5c5a994813542e8c11e02a66edc))

- Modernize matching in check-warnings script
  ([`917fd0a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/917fd0aa0bb98df3d7475f760b4c7fe638d95f0a))

- Reduce warning count for negative value
  ([`57d0a0d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57d0a0d1f73eddf74212625d55af736607ac6856))

- Remove get_trace
  ([`2450435`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/245043530f25d93e5c34b26475a23efef496120c))

- Remove rs-synth-filter from witness counter
  ([`4df596c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4df596c6cb310411e18da8d29a38f9f1469dbdfc))

- TestQbk warning trigger
  ([`28d804a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/28d804ae71d289c970f53e5c6e86465dc494f06f))

- Typo in pyproject.toml
  ([`6a0030c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a0030c76ffcbeca7f4b4ad56da093cfec75f70b))

- Use built in typing
  ([`1d98774`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d98774cbdfe7bca2ecb21c565b995c8efca38e2))

- Using QUInt over QInt for optimized multiply in test
  ([`6beb315`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6beb3153018023c282c681f34399b0109730b466))

- Using QUInt over QInt for optimized multiply in test
  ([`6723370`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/67233701e59f1964071d3c3e674a38375b853ffa))

- Using QUInt over QInt for optimized multiply in test
  ([`900800a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/900800af927f6114f92d2b24e1e6338860ce4a1d))

- **allocation**: Fix for TLB reallocation bug caused when alloc and free are not in the same
  instruction set
  ([`0ada4fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ada4fed324827891284793d2f3e57545a0cc6b7))

- **build**: Fix legacy runtime dependencies
  ([`7e816c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e816c1b00b24cd72d3511d71ebcdd1f2002b304))

- **cicd**: Cleanup loose testing structures
  ([`f25f67d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f25f67d8331678387976cd8a0b104f8983d564ba))

- **cicd**: Fix error in psi-liqtr import, and also try adding wba
  ([`1d5c8c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d5c8c18153abf4b1182057f1721b9c14088558d))

- **cicd**: Fix punctuation error
  ([`7f4bdef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f4bdef89ef03e7049d2f7a293e280867f86dea3))

- **CICD**: Minor tweaks to finish off #1098
  ([`671d923`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/671d92397d8f41b8aa0dfc8455fef08b4adae8a3))

- **cicd**: Remove check for WBA install success
  ([`1d8bbaf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d8bbafc6a45ea896c0f05fcaf23036466329a34))

- **cicd**: Testing override of env vars
  ([`a2595f8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a2595f87f6cbc0e95a8139b384b447d7366449cf))

- **cicd**: Testing Shelob's new pip.config file
  ([`6bf2f90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bf2f9016601ddf590c3860a21e4241b2710afbf))

- **CICD**: Trivial blank line added to try to bump the CICD system
  ([`d5b3a1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5b3a1d58963a7db2eb69908b552d88d1f2fb99c))

- **cicd**: Try overriding PIP_CONFIG
  ([`431a902`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/431a9028690e397a353b0088c8a783b89b39ff8c))

- **cleanup**: Remove debugging tags
  ([`f8e2dee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8e2dee99f9edade707ec7e4e7ba4006caa7dd69))

- **cleanup**: Remove unnecessary diffs
  ([`49cff63`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49cff6338e07dd838bc4d89da7d91ca3f6bb8ef3))

- **lock**: Poetry lock
  ([`42b6140`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/42b61403317420c9c1bef8a372e646f75fcf4f56))

- **macos**: Try generating the missing file
  ([`e878e4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e878e4d05d5076d4f63bb3eff063bba9aa52a4fe))

- **pip**: More debugging prints
  ([`ef10fea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef10fea88cd0f246ca7cfe053fc99834d7cea1e7))

- **pull**: Fix for #1088
  ([`931c85b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/931c85bbf5f18320afd6e35934b88893b3d80774))

- **stale_state_count_lookup.py**: Fixed sqrt T stale state count.
  ([`53a8c4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53a8c4a87e1ff3bb4ae119979a4ca4ce52915a4c))

- **test**: Cleanup the the old test_hydrogen()
  ([`d170cc0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d170cc073930f30cc0a11bb29e89828823eae548))

- **test**: Cleanup, remove unused imports
  ([`3352924`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/335292432445a03a381b2260546e4403283ecf49))

- **tests**: Add WBA and QApps tests to extras
  ([`3a70237`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a70237f92f3aea67506dbf71f6b89b13eb4265d))

- **trivial**: @sam Added a space because commit-lint forced the tests not to run, and I can't run
  them manually.
  ([`d5d00fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5d00fed21fc62ca5b6c38532630e91dea5ae506))

- **trivial**: Add a blank line to force the pipeline to build
  ([`138435d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/138435dbe286a78d445281112c7b3c57bd73cdd4))

### Build System

- Add psi-liqtr to setup_legacy
  ([`61953eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61953eb4e844bdaa921645c10b45a1a025c9b556))

### Chores

- Accidentally removed metrics_stack.
  ([`21153e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21153e12de4b4daabbe7389eeb406e39908d5bf9))

- Add additional op name checks for test_catalyst
  ([`3da4860`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3da4860249760242e34da159de45a5157e381eca))

- Add additional op name checks for test_catalyst
  ([`9393a5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9393a5be7b9578ad91ccde37e3eac8e3b6fc9cfd))

- Add check on instructions op stream
  ([`c39a4b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c39a4b2e8c592f2270316abc0a7cf70198d09ec1))

- Add copyright header
  ([`9c6f67c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9c6f67caec56cda3f9c6964367f44eca19416fb2))

- Add debug line
  ([`0ac66aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ac66aa249a31640817d5407dfea6b1e1f9cbc66))

- Add dependencies in ci
  ([`c6b1265`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6b12658100447fd3aff7238c3372742d1218c3d))

- Add deprecation warning for QPU.set_zero
  ([`8fe0e61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8fe0e617f29c58539db0e6640e3c8847b11c7275))

- Add print instructions to Qubrick notebook
  ([`06f289e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06f289e9cc49a69217579e6bc820e29050eee5eb))

- Add requests library
  ([`c631a22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c631a223ac479ea3cccade5521cbf548a8df91d4))

- Adding test 760 back
  ([`7d4c2f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d4c2f91ba9258b18795ffc10d9ef1a03bb40d90))

- Address bitwise not for Python 3.16+
  ([`d670766`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d670766ab6372c287abc1086936b18e95696763d))

- Bump version to 4.23.0
  ([`5c150ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c150ba6f448d3d4559241052d38d1ea00d8de98))

- Change psi_pyliqtr to psi_liqtr
  ([`39b3466`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/39b34664318bbcf7ee713903b2042b898c091594))

- Changing name for Parameter for sympy register size from N to reg_size
  ([`f43c7b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f43c7b157de1aa053e65b4fd8c3a9102a715d963))

- Fix gitlab ci
  ([`63d03a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63d03a364506c6b9155de87599cd5e38725243fe))

- Fix macos reset fail
  ([`c6c111a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6c111a6b816f19e8ab52f2de0d31e0f8411ad9f))

- Fix mkdocs.yml
  ([`5a87b59`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a87b59ade492053b63657c7358c7f12fce3bb34))

- Fix pipeline failure
  ([`607e3f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/607e3f5ddb18ea083e494ee78f6d20c8c09698fa))

- Fix pyproject.toml versions
  ([`40a79ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/40a79ab2ba7d8476ddde573781afb971b6263cf5))

- Fix radix round warning
  ([`9820eac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9820eace159696d00c8b7c8aef76677e503b0ced))

- Fix warnings for alloc_result
  ([`ca4d6c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca4d6c4b1800651b06c18a192906c9d053224f63))

- Fix witness stack warning
  ([`27c4a7f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27c4a7fb4fd8095d90ff0ffcfee6f55fbc123636))

- Fix witness stack warning
  ([`f680433`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f680433a64ae98c25325677cc19646c3447a2d93))

- Fix witness stack warning
  ([`a7b34de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a7b34deb82ad49c480dadcc06cb043a6bb6a1cea))

- Fix wrong name
  ([`e77693e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e77693ebfbc556c8a9868f53fe415e037365cc22))

- Putting unused ops_asm2 var back in test.
  ([`e2adb9c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e2adb9c0198a2949639cbebbf0d9ddf44eaf42c8))

- Qreq compare warning
  ([`7447e9a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7447e9a21eeeec33ce969a2e99f9ad6f56d4cdc8))

- Release ancillae deprec addres.
  ([`c596797`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c59679795e7f828813e7b6d000c3cfc81289c04b))

- Remove allow of negative for unsigned input for Madd
  ([`91a2a78`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/91a2a78872a6fa71f99c9e7068cca08951114391))

- Remove cross-validation scripts
  ([`35c79d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35c79d31d89b7f1d60d4a9be7d55841f78f78e75))

- Remove other unneeded functions
  ([`1349299`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1349299301f86a1234210ea34b462e2c92587336))

- Remove other unneeded functions
  ([`385101d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/385101d7a95dda6d7b3a73d5733d39179328eb54))

- Remove other unneeded functions
  ([`b1b782a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1b782ad4643315bdaf8d29f8fd5ded87ba8f337))

- Remove other unneeded functions
  ([`5580b40`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5580b40416558cf371e944422fd6264ab50c5ead))

- Remove other unneeded functions
  ([`7230dad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7230dad6978631295b6d3c419103355daeb40b40))

- Remove other unneeded functions
  ([`9854e58`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9854e589f686b3fdbf8bf89b8fb2da7155aaa968))

- Remove profile_mode from eccshors test
  ([`1febba3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1febba38da00ee006141b8b7074844a65bdb7413))

- Remove remnants of get_trace
  ([`6ebd0f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ebd0f18a6b43ecfb0158f6c79c03f1a7dd34f72))

- Remove remnants of get_trace
  ([`16aa90b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/16aa90b876124d30ab035a826f0cc95eb1463f12))

- Remove remnants of get_trace
  ([`608736d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/608736d10756573dc0b1bc7a07f2ae33388969ab))

- Remove ResourceEstimator class
  ([`0915c14`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0915c14987c1fdd1e501518644b5bf504a481213))

- Remove speedscope and export trace functions
  ([`64ee6db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/64ee6db8bfde96b2e93ceacc0c67713968d6e7a5))

- Removing notebooks for tracer
  ([`b4e9430`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b4e94305feee24adf5e00f6f3c6f1fb427f87284))

- Responding to diff comments.
  ([`1b64124`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b64124c813715255d63f2333f97f1df7dcb89e2))

- Update psi-liqtr dependency
  ([`ea39194`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea39194332a0e0ae3f66d6de635c5a4d1d9ff291))

- Update rot count check for test in res_est_tweaks and cleanup.
  ([`1acd77a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1acd77acc5028d7c4862eb4bc811561c04c66c62))

- Use print instructions for test 423
  ([`ad5b842`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad5b842054a9c202ff8e762ad95f54cd8e5cf87a))

- Use qc.metrics() for print in test_440
  ([`7d8d6d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7d8d6d25eb6dfa84d4381f053d36e1a9ac292813))

- Use qc.metrics() for print in test_440
  ([`e8d73db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8d73db2f90f73f9ba56df3db4073795af7823b4))

### Continuous Integration

- Add check warnings to gitlab ci
  ([`8f1b0b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f1b0b514df41d88ff1187e087fcb87dc6edfe86))

- Add image link check
  ([`345ef4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/345ef4bf544ca1df5a07df1ac7891f90ffb63b3a))

- Add script to check for broken links
  ([`e1dccba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1dccbada03aa15dc6a68e101fe4c632d7b745a8))

- Added downstream test for integration test repo
  ([`285ef9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/285ef9bc64e26792293b82088f93285061df0fe1))

- Make check_links new stage that allows failure
  ([`96771a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96771a86536fd72ba296e1ede6babd54bc46fb99))

- Make warnings check allow failure
  ([`19e282b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19e282b016d6bd38f8bb3f861d8cdd6336120186))

- Move docs-warnings to docs stage
  ([`96c5e21`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96c5e21d0bbe4f047939d85f027adf12db31885b))

- Remove old downstream trigger jobs
  ([`e923c23`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e923c232501d33a81cde4753a3a30a318e8589c6))

- Update downstream:psi-qdk rules to run on main and scheduled pipelines
  ([`1ac9d37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ac9d372b05db52a9e69536bd824761e2ed7c636))

- Updated downstream psi-qdk trigger branch target
  ([`06f7a2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06f7a2ab8b3954b43e714dba4cde17ff2d651488))

- Updated psi-qdk downstream job for new project location
  ([`fcf0eb2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fcf0eb29fdc8caa6bdb00b4363479a10e8c66215))

### Documentation

- Add new page to the navigation under Private
  ([`af1cebf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af1cebfe0229d281ddba73c8781730376fb4a7a3))

- Add note about num_qubits being upper bound, not exact
  ([`bda797b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bda797b7fdf445dd8dc08d5c483228c2ee3d1935))

- Address Ian's comments
  ([`c18fd55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c18fd55e34d7e5733f4854224474a6ad5b9ea946))

- Apply 1 suggestion(s) to 1 file(s)
  ([`413f05f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/413f05f1a026fe9195db4f138bf0ba0c3d0b0aad))

- Clean up unused images
  ([`d496a17`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d496a171713192bf24c48f703becf9dd7d211b01))

- Fix broken filter pipeline links
  ([`853a13c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/853a13c666cd86eb3b336592050da282ac9387ba))

- Fix deprecation warning
  ([`2136016`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/213601614f20cf5ca7c79e1860834584000dcc32))

- Fix SMS's comments
  ([`e939a6b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e939a6b9e1201df655f7c76ab4c4b152de41c3f9))

- Fix syntax warning
  ([`c02e305`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c02e30567e0878845cdb9b9df6de7ac527d47925))

- Fix typos
  ([`1a9fe8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a9fe8f66bfa0c761a502423697db592de9e11b3))

- Get rid of cpp warnings
  ([`1b99da6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b99da6ee7610a2f36370e0752632e4cc2aeee33))

- Get rid of unnecessary outputs in notebook
  ([`e893d13`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e893d13974bb3b48ca113d6dc4ecd48c250595ac))

- Move check_links to scripts folder and add max_retries
  ([`ddd6568`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ddd6568d51b4d0335d274bb01a2f97515c676646))

- New "QPU Object" tutorial
  ([`239e5ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/239e5ac3c160b312f370d7bc45eb3614517d6a7c))

- New "Write your first Workbench program" tutorial
  ([`bbee621`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bbee621b2a4b90cb24445a60240a0a7977d6099d))

- Quantum engine -> quantum processing unit
  ([`48ed258`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/48ed2588df81b84852cbe3124e7e86f85da46a97))

- Remove duplicates in stream_ops
  ([`29a4b36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29a4b369ee54d983b03afdf107ef7a0003c021a4))

- Remove explicit reset call
  ([`efc81ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/efc81ab35c39fc02698cdb7bc1ff63fea1f942d9))

- Remove many warnings and move make_symlinks.sh
  ([`2d0aff2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d0aff20d4e165ab64c19b94e95a97fd09f3bea1))

- Update installation guide
  ([`adae41c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adae41c4fb13eabdfdb53cf68317cbcb8103df5b))

- **heap**: Add docstrs for all heap methods
  ([`2c31ca1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c31ca11671a6d1bab11b66a5c408be1dbf8478a))

- **readme**: Update release doc section
  ([`8e5a134`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8e5a13403d9de4feec47915051cc36ea26c2a928))

### Features

- Add script to detect warnings in mkdocs
  ([`1b7b1db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b7b1db1e3bf9f85a71c98b4699ce26a421d5b5c))

### Refactoring

- Changed pyliqtr dependency to psi_pyliqtr
  ([`2eb7f84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2eb7f8423b47c31f01a18b6cba48612114b0a199))

### Testing

- Add failing test
  ([`89f57a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89f57a6db1388d48c2ed82868754ab02af6bc872))

- Fixed test broken by new error thrown
  ([`f4238ed`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f4238ed87729135b5411ee30b779936cfab59d48))

- Have fun debugging this one guys
  ([`9319f75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9319f758015fac2464014c74fa0dc0e193caff19))

- Remove use of sympy.sympify
  ([`11d4cff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/11d4cff78c1fd58c885d8603240deb936e6d9f96))

- **CICD**: See if the psi-liqtr. This is only a test.
  ([`689b807`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/689b807d7ac8be1536c2c8efbe3ea717c4aed566))

- **MR**: Add requested test which fails without #1088 fix
  ([`2a4264c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a4264c181911a89017a994309ef3a6849c993c5))

- **poison**: Add a failure to show that WBA is being tested
  ([`4be69ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4be69ee0df4e7e76c9f6a880d468afe3612bc687))

- **Schwinger**: This code catches the double-free bug BUT ALSO passes our entire testsuite
  ([`adcc406`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adcc4062e59820cc5450b504dc26a0ac2858e219))


## v4.23.0 (2025-07-01)

### Bug Fixes

- Added a link to a note that explains stale states.
  ([`8082e35`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8082e35d9031a5d79fc844bd3f0bdb2a4f2f9816))

- Change instances of .cnot to .x
  ([`016eea1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/016eea1f6b4caacdbad56a9e5af8daef563f15ca))

- Cherry-pick qft_increment deprecation fix.
  ([`535d48c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/535d48c0c312816d00d4636ad90b73cab8ae2b05))

- Minor typos fixed in notebook
  ([`0014daa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0014daacdc19ade3fc505cdfbbc264eb03ac1a4f))

- Refactored stale state counting code into a seperate folder. Also make all stale state count
  import values set in 'stale_state_count_lookup.py', and added
  '_get_multi_target_stale_state_count' to the init file in stale_state_functions.
  ([`7973bbe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7973bbe91747f005ffe3edae6be3fdbdd862c0bb))

- Test in 319 qft compute
  ([`b12c42d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b12c42dda46bdd4da507cff0c51ee20cdc45cd7d))

- Test in 319 qft compute
  ([`54e5587`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54e5587a5d5e5077248288eb91889f4edb66c13d))

- Typos
  ([`b17d471`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b17d4716a0b85077aa36ff2cf871050cb6876509))

- Update check_zero_fields to have a parameter called property_name, and update tests and code to
  supply this parameter.
  ([`c61130f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c61130f9aa78c061d853b5f52692230083c709a5))

- Updated name of _unsupported function to _unsupported_op.
  ([`47e8872`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/47e8872c1cf0d379a496008b560d4bf2bea06398))

- **__init__.py**: Added default_ross_selinger_av to init file.
  ([`3a317ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a317ca526a4f1b47db912b9f71f72e32725c587))

- **av_functions/__init__.py**: Updated _unsupported_av to _unsupported.
  ([`8923f20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8923f202ea83ab6a4633ef4205683e1ec5ef3f98))

- **avg_qubit_estimator.py**: Add copyright
  ([`02883ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/02883ad26a02eadf79f421886df320a43a567e9e))

- **avg_qubit_estimator.py**: Add formula to docstring
  ([`ad5a335`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad5a335c29a830f11c4367c31d29d1b61d724469))

- **avg_qubit_estimator.py**: Add qubits.release thread to docstring
  ([`06e6b84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06e6b84bd625904fadc2650cd8ff0b029834c36a))

- **avg_qubit_estimator.py**: Delete unneeded functions
  ([`4fd6be7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4fd6be74bb9f2655671cee91f73237732f4ed315))

- **avg_qubit_estimator.py**: Format with ruff
  ([`375b20f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/375b20ffdfec478e2f0d4296906fbfc2ae694954))

- **back-compat**: Fix for backward compatibility
  ([`e27044a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e27044a0eade64cde77a782a81b42c1e65df183a))

- **catalyst**: Fix for cases where catalyst qubits have been released
  ([`8cef6a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8cef6a34fcd6df568ab26663a728f75bd39a0619))

- **catalyst**: Simplify catalyst release-check
  ([`936882c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/936882c763789571fa2504fb0257545b08b7debe))

- **docs**: Remove :math:text$ tags
  ([`c495f43`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c495f43c393975f69a8adf806827d307fe368f6e))

- **draw**: Remove stray dots from targetless ops
  ([`4ffc9b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ffc9b30ab3057088a55c9fd7d23e05bf0e4ce93))

- **example_avg_qubit_estimator.ipynb**: Allocate -> activate
  ([`6ed25ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ed25ab985e9d4305966fdc8f6700c927a265420))

- **example_avg_qubit_estimator.ipynb**: Define \bar{w}
  ([`91d0764`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/91d0764c0cb65f89611199d2a30b37ed27a835d7))

- **get_dag_from_qpu.py**: Change strict = False to True for get_dag_from_instructions function.
  ([`82ea135`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/82ea135a06e40384b6553e89d6099f53fcb8abb7))

- **get_dag_from_qpu.py**: Fixed import issue for get_av_from_op.
  ([`bcb8ae4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bcb8ae4eb1788c9661583fef5fc19d2d5f7cf800))

- **get_dag_from_qpu.py**: Remove igraph typing
  ([`572a92a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/572a92a4491b530191e7a8fcd314d6bee4513af3))

- **get_dag_from_qpu.py**: Removed debug print statements.
  ([`f451a90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f451a90546b406c8355cedea0fadf85813c4fc71))

- **get_stale_state_count_from_op.py**: Now import NON_CONTROL_FLOW_UNPHYSICAL_OPCODES and
  QPU_OP_OPCODES from get_av_from_ops
  ([`bcc472b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bcc472bd3b77a4291952f10c54d6a2ae22168abb))

- **get_stale_state_count_from_op.py**: Remove uneeded comments in
  get_stale_state_count_from_restructured_op function.
  ([`ba2b0c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba2b0c8f5dbf208dc587621a1a55658d8a19e019))

- **get_stale_state_count_from_op.py**: Remove unused import.
  ([`cd8c644`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd8c644e151048b9e05be8f328dbb5d053bc6c18))

- **mask**: Mask fixes wip with mariia
  ([`a43af5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a43af5f2ba9ddcf5615ff7c372c1e9eda29884d4))

- **merge**: Fix merge for #1004 and !668
  ([`4b6541e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b6541e11571ff1f7c170e412cc909ae89f555c5))

- **MR**: Fixes per MR feedback
  ([`e4cb843`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4cb84352abc62d04f288126b5add25242920d31))

- **MR**: Forbid qubits types for x_mask and z_mask, per MR feedback
  ([`e72312d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e72312d6f82b06bbadfaaf45ad3ff4ba4d97b42c))

- **MR**: Minor MR changes
  ([`c3bdde3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3bdde32e3abf996c558024e58dc86a703eca3c3))

- **MR**: More changes from MR feedback
  ([`95d5f5a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95d5f5a2e255bc9594f179da1d15c421fc59cfb1))

- **MR**: Tiny MR comment
  ([`a78c142`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a78c142b54030c101e4d08d84c957c72ae6dbee4))

- **MR**: Undo MR change to fix lint
  ([`78da9d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78da9d55327c97147ffbdf18fafb1fad844ea217))

- **qpu_op_functions.py,utils.py,get_av_from_op.py**: Change name of _unsupported_av to
  _unsupported, as this is this function is used in get_stale_states_from_op and so should have a
  generalised name.
  ([`d1b9bca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d1b9bca9566bd139a753625808186d1d31d23369))

- **qpu_op_functions.py,utils.py,get_av_from_op.py**: Refactored _unsupported and check_zero_fields
  into the utils file under resource_estimation, also added a parameter to _unsupported to indicate
  which operator property is not supported.
  ([`d6ba6f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6ba6f43e9ef9cbd0a99a7cca556358f0e807207))

- **reaction_limit_estimator/visualization_tools.py**: Added check for optional matplotlib install,
  we through and error if a users tries ot use draw_dag without having all necessary libraries.
  ([`6c996ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6c996aefbfaea2e57729b5a118bc9e2601f7a355))

- **resource_estimation/utils.py,test_1063_create_get_stale_state_count_from_op_function.py**:
  Reduced repeated code in unsupported_op function and added tests for it.
  ([`e5b385e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5b385e1129633f7615126e54b1b7859899cea83))

- **resource_estimation/utils.py,test_994_create_get_op_av_function.py**: Fixed _unsupported
  function call in check_zero_fields, we now have a property name for failing the zero fields check.
  ([`675c4db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/675c4db0475ec5407aec85249dc8833bb90a8530))

- **stale_state_counting/__init__.py**: Added an init file for stale state counting.
  ([`b5531d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5531d2f09ddc8357948e3e160cb87248f7d09a1))

- **stale_state_function**: Added an init file
  ([`572a92a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/572a92a4491b530191e7a8fcd314d6bee4513af3))

- **test**: Fix failing test #844
  ([`36613bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/36613bd2122803aa34c76dbfc1c03a3963812e36))

- **test**: Fix for test after reflect change in #1048
  ([`8fed65a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8fed65a7dcf66e5aa3e3ca8f8a231fdeb9b06d4d))

- **test_1063_create_get_stale_state_count_from_op_function.py**: Removed ross-selinger tests,
  remove 16.5 degree rotations from common ops test, added pi/16 rotations to to tests.
  ([`31a51d4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31a51d4f94740546e79c9273962c78ef5ab581dd))

- **test_929**: More tests
  ([`bab6229`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bab62297db9477f905a12e3373ae39ae0ddb0aa4))

- **tests/test_994_create_get_op_av_function.py**: Restored test994.
  ([`e3ff239`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e3ff23906ba04dff56744215c6a0384cf483d555))

-
  **utils.py,test_1063_create_get_stale_state_count_from_op_function.py,test_994_create_get_op_av_function.py**:
  Improved robustness of _unsupported_op function and updates its tests.
  ([`df5712b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df5712bfdb724d6b0e7321c0228e48c202ece67f))

- **visualization_tools.py**: Removed unneeded comments.
  ([`6e728ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e728ad5c7857132a0cc1032b74b06427944021a))

- **witness**: Revert witness metrics change for this MR
  ([`5333362`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5333362acbafac0067ec3a585bfeeca3a3d8be80))

### Build System

- Fixed validation issues in pyproject.toml
  ([`82c1b71`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/82c1b717af6e9a6e55e2923383dcf139986bc8d8))

- Move extras dependency specifiers to project.optional-dependencies
  ([`da12607`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/da12607a82e3fb08ef583cc0f2715392a2ce362f))

- Update poetry.lock
  ([`99564b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/99564b63037e01a8634e0e123e4649621508c2e1))

- Updated build specification for poetry v2
  ([`c3f563a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3f563a4796fcce0b0462d3c13e074b6a10e88cc))

### Chores

- Change double to single quotes
  ([`2aff914`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2aff914d3cef62e7bd09fa40e8877073bd81866f))

- Cherry-pick test changes from test_319_python_draw_svg from SMS.
  ([`15c6aa8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/15c6aa82bd95871a1e020a285ab25d0ae1a942a8))

- Cherry-pick test changes from test_347_print_qubits_state_vector from SMS.
  ([`a28d724`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a28d724318ecbb7f0a7574d2e38ce92cd6725be6))

- Cherry-pick test changes from test_408_xv_api from SMS.
  ([`9022f59`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9022f59433226bcbaff252e59bc2f5faff6ae197))

- Cherry-pick test changes from test_catalyst from SMS.
  ([`032cffb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/032cffb4f779fd7d8d2f8b2c6f38a8e577081866))

- Cherry-pick test changes from test_composite_filters from SMS.
  ([`b5ec8bf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5ec8bf2e3d254e45fe3f9428ef1d36f0877e20d))

- Cherry-pick test_519_builtin_add_and_qft from SMS.
  ([`b21e13e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b21e13e2a10d33cd0f30dec31a6c0175cd456bc1))

- Cherry-pick test_847_skeleton_window_filter from SMS.
  ([`047b82c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/047b82c887b380462c12abac1a058a9d48fafdd5))

- Cherry-pick test_cross_ops from SMS.
  ([`1a60bf1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a60bf1ca5356cd53772458e699e9abda294da17))

- Cherry-pick test_cuquantum_export from SMS.
  ([`3cfba0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3cfba0c99fcfe371bdfca0912bd77da482fabb7c))

- Cherry-pick test_hydrogen from SMS.
  ([`a1db3a4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1db3a464529b38378aa5b9ee23c4f1dda0cc846))

- Cherry-pick test_qint from SMS.
  ([`abdb9d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abdb9d007de66dd67a159e00cc5a133866ee3e3e))

- Cherry-pick test_shor_compile from SMS.
  ([`780cfaa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/780cfaa6dc4a9b98cfe9ede1342224c01dff99a9))

- Fix gitlab yml
  ([`90ad000`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/90ad000e3e32c2d0cc2331a3222ddbc027cfc656))

- Fixing downstream variable handling for doc building
  ([`81bfb22`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81bfb22fe3ea5749f0ffef2671f44a39c890d24c))

- Remove test_helpers deprec warning.
  ([`202088a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/202088a0827eb9024d1d4e447b5dca3df30f92ff))

- Test_qft changes for most tests
  ([`22d8994`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22d8994b3bbf12d7f170eb272f6fcbb4ba6b4ec3))

- Update import for numpy utils
  ([`c11ef8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c11ef8f0fc9de846193f0716a9d8df5b446600e7))

### Continuous Integration

- Make error message more clear
  ([`bb1a2d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bb1a2d62a49f9910c5b8bbc57c14c7d3034f8bbc))

- Pass reference as input to included dev-ops/common script
  ([`c011ab8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c011ab8ba3729ac6ee6a11bd554e2a9bbdb6d988))

- Update GitLab CI to fail on markdown_exec warnings
  ([`64158ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/64158acaac1a1abce84540c3470d1a8bba7d88ee))

- Updated dev-op/common reference to new release
  ([`756a157`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/756a157f3e61534e22483d2ec5afd5d91033d43b))

- Updated dev-ops/common include reference from 0.0.3 to 0.0.4
  ([`de0a630`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de0a63082129c535cb3174417295ac01fb3b67ce))

- Use pre-release dev-ops/common branch
  ([`eae7b1c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eae7b1c9b00b5f2b0f39d3ff94e4bd1c1b8ee44f))

### Documentation

- Add markdown-exec
  ([`6b658ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b658cab64e160e694bcbba5a98fed27b942dba9))

- Updated README for poetry v2 usage
  ([`9b2f5b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b2f5b4d57bc8cec77b4bcefcf391dc23d35fbde))

- **qpu**: Add Returns to print_state_vector and detect_entanglement docstrings
  ([`25fd327`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25fd327d68224c25b29e91afe8badd70f4386d89))

### Features

- Change the DI controller and selectors to pydantic classes
  ([`8b95eac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b95eac92cdbf6e2acab18763f2f28c58867f577))

- Removed support for arbitrary angle synethsis but added support for pi/16 rotations, also merged
  in updates from main.
  ([`14e363f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14e363f9329c31aaf2029cfed29017f6b9c37448))

- Support reset in OpenQASM
  ([`05c7f4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05c7f4a7dfa22a89cdef0649509b1be0ded38c8c))

- Update check for generic class to work on python 3.12
  ([`d209f5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d209f5b904d391305f3abf810a054d2e66a72090))

- Update pyproject.toml to add pydantic dependency
  ([`fefdac9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fefdac907bcbbdf39519b7900b8f1d56d2c430b2))

- **__init__.py,get_stale_state_count_from_op.py,stale_state_count_lookup.py**: Added comment to
  header which explains stale states.
  ([`2aa6084`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2aa60842726d3d3d522319c5bd39f0ccb32e84a8))

- **avg_qubit_estimator.py**: Added average qubit estimator
  ([`a5017ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5017ac22955dba9930701a3fe4fc66f0394e743))

- **cz-cphase**: Implement Qubits.cz() and qubits.cphase() with tests
  ([`51b2f4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51b2f4b3bf55f9b4d4c0338af1f3fe57f1299e09))

-
  **get_dag_from_qpu.py,visualization_tools.py,resource_estimation/utils.py,get_stale_state_count_from_op.py,stale_state_count_lookup.pymqpu_op_functions.py**:
  Added code to get the number of stale states produced by an operation, we also now attach and
  display this stale state count on DAG graphs.
  ([`dd947d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd947d0d801de8ab238163e52c9df7da9c0bb02b))

- **h**: Add h() as alias to had()
  ([`8a31ddd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a31ddd145206a8f4a5141cf5390792eaaea12e5))

- **h**: Add h() as alias to had()
  ([`9d9b3af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d9b3af3921262d3705acbb094f8811380abe10f))

- **MR**: Reflect implemented per MR feedback
  ([`64ac532`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/64ac532e380fced8954c475472e40d0246101468))

- **qpu_op_functions.py**: Added a note for a future update to the code.
  ([`45bc12c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45bc12c8b305e3bce6660de2ff3ee9bfb0279604))

- **reflect**: Add Qubits.reflect per feedback
  ([`aa054c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa054c9d6bff19f4f7f49e6a00cee6e29147cf73))

- **reset**: Implement automatic qc.reset()
  ([`e109330`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e109330387ffe5dcb9fcbc65639d99eb4c9592ce))

- **stale_state_functions/ppr_functions.py**: Added functions that return the stale state count for
  the ross_selinger implementation of a arbitrary angle ppr.
  ([`cbb7afd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cbb7afd17ac277686704719d8ea9b7d625ceb0a7))

- **test_1063_create_get_stale_state_count_from_op_function.py): added test file for
  get_stale_state_count_from_op. fix(utils.py): added missing line to raise and error for
  'stale-state-count' case. fix(stale_state_functions/ppr_functions.py**: Removed op parameter from
  various functions are it is not needed.
  ([`ab8e654`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab8e6542c746fe50b5befe74a851a55a08cb7f23))

- **visualization_tools.py**: Added a colour bar to the DAG graph.
  ([`76c244f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/76c244f2fd8ff4f1987f8369a6068df7ca902de4))

- **visualization_tools.py**: Added colouring to nodes based on relative AV cost.
  ([`43a7efc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43a7efc99599925bcce4523c0f4c2c684105fc8c))

### Refactoring

- Suppress Expected Warnings in Overflow Tests
  ([`98ec41b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98ec41b654460fbea8ec1f1845da9847d63249f6))

### Testing

- **cz**: Adding tests for the new API
  ([`0818c44`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0818c442bd81e521e5d1757d304c4af9f6db2b04))


## v4.22.2 (2025-06-20)

### Bug Fixes

- Add back removed truncate_angles function
  ([`4182bad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4182bad804636aaf6d6545e90a5c057d23d99906))


## v4.22.1 (2025-06-19)

### Bug Fixes

- Add fixes for proper rounding
  ([`c108797`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1087973f03d4c7ab4f10530df055a986f9357f4))

- Add numpy cover to lower_bit_index func
  ([`cabcc61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cabcc616944d0dd57ea685e878f28754fb2d2c41))

- Broken macos tests
  ([`db4a7bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db4a7bd51417ba1e6d30681eacd74b14398cfc94))

- Fix failing docs
  ([`9fb191b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9fb191bdf1fa742f1af4e49cc0079e40b47a907a))

- Fix how the requirements are constructed in setup_legacy.py
  ([`298e63b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/298e63b9340c0b900a465143bd58b00e42e60ad9))

- Integerize_truncated_rot_angle around 360
  ([`1f8f16d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f8f16de55fd3d91611b182a036e8b49c015d7d9))

- Remove `ig.graph` from typing as it was causing failures.
  ([`f04577e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f04577eeb9f89b24395568819ff597a1c254e1e5))

- **cicd**: Bump dev-ops/common version to 0.0.3
  ([`b79cbc0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b79cbc0ddf4e41e63cbef0534611b2ce9b9dc17e))

- **debug**: Fix leak-detection printed message
  ([`b27f3a9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b27f3a92cb3ca74eca11052be05cf95794df8ea2))

- **docs**: Add missing tutorials to mkdocs.yml
  ([`09b647d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09b647d95f420452a54494d12ed1b6a3629e326c))

- **draw**: Auto-expand for partial circuit drawing
  ([`3a9c6bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a9c6bb68ebc8c75d933538bda67346ce9fa636d))

- **heap**: Fix a heap allocation integer error
  ([`f6486ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6486ae6a072848b942e2211716e0a4286776de0))

- **indent**: Fix two indent errors
  ([`cec77d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cec77d5b3015a10c14e56fea0e0f450d322c65ca))

- **lint**: Fix lint error
  ([`86c4344`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/86c4344fd6c2d153460fa61b98146e96e2fe2210))

- **MR**: First round of MR fixes
  ([`4fe4e37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4fe4e37287ecba1e447c4bf8c7dd0611d014d0df))

- **MR**: Fixes per MR, with test adjustments
  ([`6f8f0cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f8f0cd074ce959608e45bce953b04519619bae0))

- **MR**: Handle rotation catalyst in #1041
  ([`81e372e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81e372ed8e4a38a429151e1ca6f8254ce95cd770))

- **MR**: Remove unneeded test
  ([`dd432a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dd432a8372e751c77fbac48540fe40b1f9940944))

- **MR**: Tiny MR feedback item fixed
  ([`f9a7952`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9a7952fb61c7b68509f18251dc6b653e5ef1228))

- **names**: Print angle units sensibly
  ([`16edbdd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/16edbdd2e4ded50e1a54948e7bdb7d645189a2c9))

- **poetry-lock**: Recompile with reaction-limit extra
  ([`a79d0a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a79d0a8bfa21edbde8e04bd93d6763df2f3baba7))

- **ppr/ppm**: Fix for bit mask values in PPR and PPM
  ([`d924f92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d924f925a9f9b30195b196c194926ccb0206c17e))

- **rotation**: Fix case where rotation catalyst qubits are deallocated but not registered as
  deallocated
  ([`4612b49`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4612b490a257f5b31b2d11c4fff1fd6d084c7abc))

- **serialize**: Fix tree-crawling issue
  ([`91148ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/91148abd9433830aa10639f89d66c3a5afcfe9a0))

- **test**: Fix a test where a qubrick op label is zero
  ([`68c9cba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68c9cba8ee5c5599199847b5f0d0ce272547ed44))

- **test**: Fix for valueerror raised #1007
  ([`a88c53b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a88c53be693a2b5999c6c2860ec2e6302c971440))

- **test**: Fix test dependencies
  ([`7ebf367`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ebf367c4c6cad8aee889b390f062315025c8fff))

- **test**: Moved set_random to after Qubits initialization
  ([`753f58d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/753f58d6c01481c9e31d06b53c528efeeb7772cf))

- **test**: Remove old test
  ([`67ae1e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/67ae1e45015883058414f045d7f30fd84f5c1ee1))

- **test**: Remove old, unnecessary, nonfunctional test
  ([`b347758`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b347758649b41e1df2d54ec93089f434a35dbaf7))

- **tests**: Allow comparison with 0 in #1041
  ([`89000fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89000fb4d5d9d36b248740f86cfb2a774ebcef85))

- **trivial**: Better test name printing
  ([`f81a92c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f81a92c469e93f37531b0ad532fc9f91ee3e2394))

- **workaround**: Disable AV for this test
  ([`1986b25`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1986b2565e1ee76b1f32feded735327e69aab63a))

### Chores

- Add accidentally deleted function
  ([`d5d3230`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5d32300a1dc47eb4a96f04ece045b2fc6955bdf))

- Adding ntz to special functions
  ([`0710d4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0710d4ddeaaf8a81278f6d213623e18e81fb5f35))

- Backward compat for num_leading_zeros func
  ([`c704a8a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c704a8ad739ec9c29bf3223021d419a6dbc158c7))

- Bump version to 4.22.0
  ([`94ecac8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/94ecac87a0c1a24534455b7de4f6a43d18a8f56a))

- Changes to reduce number of warnings while running tests
  ([`f0db0ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0db0ecadc1bba3a077c086c62ae0c6d7031cf8d))

- Deprecate theta_bin
  ([`93c354c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93c354c6558ea786aeb656d3d242dce52cee235d))

- Deprecate theta_bin in tests
  ([`bea5fef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bea5fef9013d34fbe4ba515bf53c04818ef1ff7d))

- Fix tests
  ([`27d3095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27d3095a7bc76e0c93fd17e3331e123bcde8f7d1))

- Json file ignore in tests directory.
  ([`e4b300d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4b300db131547b8bff3f166717d0859fa5c773a))

- Json file ignore in tests directory.
  ([`78ee96b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/78ee96b65f19cfda2449444084a6b8b851312beb))

- Nlz to ntz
  ([`fb35ab3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb35ab33a4de9a93d344605464a3efdbf13275ae))

- Remove deprecated function from test
  ([`5099a19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5099a196f2a4cf72f10dcaa452aed796025c0a8d))

- Remove extra test
  ([`e0db616`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e0db6167146c5fa1749c4a15a3ee64cd6e129a0e))

- Remove old functions in favor of hardcoded values
  ([`c3436a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3436a547732a778380fa189e1fb88ce7a9ff89a))

- Remove truncate_angles
  ([`0b65cee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b65cee83817ef7d1605182a944b75d10f9f22b4))

- Revert test_qbk_rotation changes
  ([`681542f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/681542fbfc1887601edb89f7f02c743866522afd))

- Rework implementations into older functions
  ([`2efecde`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2efecdea55ea3a0c92dfac8a10e5a5d88830f0ce))

- Rewrite inefficient code
  ([`41d0580`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41d0580a9c23b814b74a9d025ab5600cef731cc7))

- Update to non-deprecated function.
  ([`d25c95b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d25c95beec4bdc278f572d976353f94b99d1d458))

### Features

- Added another test for QFT
  ([`c29d4c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c29d4c1b9c939b3ea3924dd414e74d9ca26cb3ef))

- **nqre**: Nerge stacks in witness counter for #1004
  ([`130102b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/130102b58d7a81a482b7238520691ead184073d5))

- **push_state**: Finish per MR feedback, remove the old implementation (moved to the test file),
  provide docs and exceptions
  ([`3b04bbc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b04bbc9f3d3031462c5214c98da38dbdb7bd322))

- **pyproject.toml**: Add reaction-limit install
  ([`5e4dc61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5e4dc6118e1da36f0172b1d96a7b9efc479feb85))

- **WIP**: Adding stacks to the witness counter, added a serialization comparison test
  ([`21014c0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21014c0bff92f4fc3ac1df948b2f86658ae7f585))

- **wip**: Stacks for witness counter WIP
  ([`160e1ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/160e1eeb4538c54db31a43e2ab8e0498d6e4ef4b))

- **WIP**: Witness counter stacks for #1004
  ([`7dc7193`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7dc71931c381d19bc6ecd34361bcfb87436e270e))

- **WIP**: Witness to Basquiat WIP
  ([`ca892c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca892c2e4d5600fb0ab17e320fc7edec5d448cd6))

- **witness-stack**: Success! Saving Basquiat files instantly
  ([`31b17b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31b17b88ca5053c1298c5bcbae4d8dfdde4453d2))

- **witness_export**: Integration of witness-to-basquiat and serialization
  ([`cf5fe0b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf5fe0b8cc88f98e0ce9f68293ca1e3cbf813b72))

### Performance Improvements

- **filter**: Massive performance fix, avoid duplicating QPUHeap when it's not needed
  ([`50c7f8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/50c7f8c8925b7d3c6e5aa56cb77513a9d27ae167))

- **push_state**: Complete optimized implementation of push_state for #1007
  ([`3362a8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3362a8f9194174448759c5df20cce00896209631))

- **push_state**: More setup for optimized push_state() per #1007
  ([`c031a82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c031a824e6ddf1518b3780d77f45141c625a95f6))

- **push_state**: Setup for C++ implementation of Qubits.push_state() per #1007
  ([`e1c46b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1c46b4643a46b064c3d6152a057923c44426c6c))

- **push_state**: Switch over to the optimized one for #1007
  ([`3da9bce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3da9bcee4a8ec9101cb2e5c5f6153d857c0622bd))

### Testing

- Add new tests for 1018
  ([`106599b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/106599ba161e8ebc76c47c7d03fac7f68f6d42f2))

- Correct eps in rot_qbk test suite
  ([`2d882e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d882e002228f7217a5b18669597541647e61dc7))

- **cleanup**: Add easy switch for existing serialize
  ([`01e6e31`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01e6e31d25f7bc1f4889b56ea8da8bb889a923b5))

- **push**: Add a test for push speed
  ([`daebdc0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/daebdc0be983ca6450ef35b648ceb437b8e17406))

- **speed**: Speed up test
  ([`4efdba1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4efdba1b34ddf32ed21c794bec61a1fd37ea7809))

- **validate**: Validate tests against normal witness for #1004
  ([`1f5bfcb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f5bfcbc5a4a69c785534c6f9ae8bbb9ac6eb70f))

- **witness**: Test witness counter export to basquiat per #1004
  ([`0e54481`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e5448135b8641b679ec9d279f06c8b6e6fab612))

- **witness-basq**: Adjustments to the test file
  ([`91beb02`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/91beb02936a0e6e9249535703ca4d84a968c3d3a))


## v4.22.0 (2025-05-30)

### Bug Fixes

- Add missing rotation catalyst events
  ([`6fb9411`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6fb9411b1028b946a82db992f6030bff0a7d64ca))

- Catch qubit numeric names before qasm export
  ([`e45f94d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e45f94df0514572c95b338afd2fb1bd9663396cd))

- Convert used_symbols from set to list to allow for JSON serialization
  ([`ba25b57`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba25b57a3d5ec2bcbd38e618613e93dd1a76c247))

- Correctly handle input arguments to uncomputes
  ([`75a81cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75a81ccebf28e7924a950abe3f50a072806d6104))

- Correctly handle symbolic PPMs and PPRs
  ([`43fd212`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43fd2124410527c6a092b8207d1288c7f5939f2e))

- Fix Bartiq compilation flags for numeric QPUs
  ([`a0fb012`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0fb01294096dfe29af62def6518ad3b69e1d480))

- Fix circular imports
  ([`e79da10`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e79da106d581b8d2423951b9a0d8e3e18ff9f235))

- Fix minor issues with new bartiq version
  ([`5dc1e90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5dc1e9042b2ccef5ef24dc2d7bf675e893ea871d))

- Fix storing of input_qregs_ids when some regs are lists
  ([`7e6fe92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e6fe9210b294070b86ed57bdf26466e9100f476))

- Fixes in serialization
  ([`1c71252`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c712524c48f3b7961ba7967dec1c5ef4226b0ad))

- Further fixes in serialization
  ([`a222db5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a222db5508807d880362ed8bd013167ffd7a08cb))

- Make name of repeated ops wrapper match the old implementation of symbolic serialization
  ([`7f4c936`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f4c9364abd9aeb674a67afd820865a207acc7fd))

- Minor fixes from code review
  ([`13c7e83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13c7e835bb21bfe288d8dbca896c19e397a46c26))

- Propagate qc.used_symbols to serialized output
  ([`9427621`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/942762102997fd53a42d8e7cd4a6ffcf6573764a))

- Remove an invalid test case
  ([`5e5da82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5e5da82ba792249f554218de873810b10abca736))

- Remove debug if statement
  ([`c6af2f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6af2f441a0877b5a0e6f860c2eb47b6d8e8c72e))

- Revert unneeded changes
  ([`19b004e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19b004e0a2eaeccb625c19949ee216bdd15155cc))

- Revert unneeded changes
  ([`9e916c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e916c8caba60aaaf7194398f719d297db758cda))

- Standardize how masks are stored (namely: as ints, not registers)
  ([`c20f0d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c20f0d30892275860b9d7333a1b8c54c0f14f005))

- Swap in QFT and _get_symbolic_costs_from_gates
  ([`598bbb3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/598bbb3bfa83443d483c79c0c6441f1e517316d7))

- Update .gitlab-ci.yml
  ([`d73abb0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d73abb0deb51333d6839bc22d1bdf8d455e26d39))

- WiP work on unifying serialization
  ([`eaac1f2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eaac1f2bc95dee74335205583946f2ffc1dd465b))

- **active_volume_lookup.py**: Disambiguate property 2
  ([`18365f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/18365f554c3e3a95824095e89590011df76920bc))

- **active_volume_lookup.py**: Fix comment
  ([`f7e3e3d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f7e3e3dbe4354ee5ce093dc85378cd53bccefbac))

- **active_volume_lookup.py**: Point to av_counting folder in warning
  ([`e4adb27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4adb2793dea00ed06568e56a8037df0ea9a6f80))

- **active_volume_lookup.py**: Remove bare z gate
  ([`35df552`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35df5528cb5140cc960442139881f96296597955))

- **active_volume_lookup.py**: Remove cx
  ([`041ca04`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/041ca046f05dfb32cc5c29a72f3961f474fc45b7))

- **active_volume_lookup.py**: Remove phaseless phase gate
  ([`68fa90f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68fa90f7b9ed898eb8299b1c86c9d8cdeb867961))

- **active_volume_lookup_v5.py**: V5 -> v2
  ([`0570663`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0570663d1ba7347e427c441084881bf50261fcee))

- **arithmetic**: More tests and fixes for #1041
  ([`2c06aa4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c06aa40d22b494e6a2bf5439f6ad51157cd1604))

- **av_counting**: Import sorting
  ([`2f7ba2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f7ba2b531554e5b8233ca1131e572e4ae1eeef0))

- **av_counting**: Update comments
  ([`c2fdfad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2fdfaddfbdd9d14ed6ec09babb94077ad4715f5))

- **check_ops.py**: Improved documentation for is_physical_op
  ([`8e280f8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8e280f8b736ce77cf95a208f022032d0d08a33ee))

- **get_av_from_op.py**: Support more types of cz gates
  ([`ff7d18b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff7d18b297c0820d6a406b339cd6e1390a0877bd))

- **lint**: Fix minor lint issues
  ([`88dafc7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/88dafc7e47b74002d17cbd18d0cf41d8cb1a5921))

- **mkdocs**: Fix broken link to tutorials/QPU-Standard-Setups.ipynb
  ([`b6c78aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b6c78aa24f649f2655ba3341c5dcc85905889f16))

- **output**: Restore outupt files
  ([`5633e8e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5633e8e204bb342aa772d6b92319f9bf13541fa2))

- **qpu_op_functions.py**: CX->CZ in multitarget CZ comment
  ([`5bb1d76`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5bb1d765eec2c93d8b0f10d51430bdd25000bc83))

- **qpu_ops.py**: Attribute of QPU_op_write restored
  ([`aab09cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aab09cd997af649eaacf6a1e2f3266e48a5820bf))

- **qpu_ops.py**: Get rid of extra space
  ([`ae843a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ae843a2323367f0e0fdf819c574c60a86ae0b9cc))

- **qpu_ops.py**: Get rid of extra space
  ([`570ad96`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/570ad96165a879bf4fa27c64aaad5a490ebf1856))

- **qpu_ops.py**: Undo formatting changes
  ([`d411150`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d41115027c00c777a45e93a1ccd5a3b4fca56991))

- **simple_av_counter.py**: Added deprication warning
  ([`96528e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96528e28f710869066635683a3ca3242c6a6e687))

- **test**: A fix for the testing code in #1041
  ([`17e5927`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/17e592701b026cfec45f19174a6bc1f93f08b20e))

- **test**: Minor fix to a test in #1041
  ([`4530ac2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4530ac242a6005072bebf9125f06c1777c0e5fc4))

- **test/output/out**: Unneeded test files
  ([`4f6515d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f6515d4f554fa2084fa8d7198033104f583a690))

- **Witness_counter_deep_dive.ipynb**: Back to new metrics functions
  ([`effed2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/effed2b6b1dfa0e278919c8ed115c19ff7689ce8))

- **Witness_counter_deep_dive.ipynb**: Back to old metrics functions
  ([`4453438`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/44534384a9bfff59d63ef7bca270d3503c13ff68))

- **witness_counter_deep_dive.ipynb**: V5 -> v2
  ([`cc584be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc584beb0afd7d8a98f53f0bffbb9d009822b2f9))

### Build System

- Added deployment to codeartifact task to ci
  ([`adc1ed4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adc1ed48a90860c027a06c9b38b52c9a327ed13b))

- Added docs publishing
  ([`a9b45ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a9b45ba13d67369ba7c357e230ec6533c0b7bde5))

- Added docs publishing
  ([`60a03e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/60a03e008635c558875b2d10bd964e7678d9e282))

- Adding yq for docs build
  ([`72eea83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72eea83b809167ef8c12487cc84a6a593d0baa58))

- Centralizing docs publishing job definitions
  ([`2ca6492`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2ca649213fedf19c172f1fad6c269ea33a3ea8d2))

- Changing image for deploy job
  ([`a2483af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a2483afdbf0f2bce43b5f1df145db600ed8975a5))

- Corrected ci task rules
  ([`f3032a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3032a2cfdfde247d60f615020b95fe79e90dd11))

- Enabled overwrite in codeartifact
  ([`0af00c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0af00c408c884922e2640423dbbae1a5d9c206aa))

- Fix gitlab doc publishing job
  ([`b6033b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b6033b691097e3c8ed7dfee699201fc5891a3439))

- Job logic adjustment
  ([`9317d55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9317d55725042f45e51e04cd27868c5e44daf631))

- Made optional publishing steps non-blocking
  ([`178d853`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/178d8534d576bfbfee834d4eb0097c293fbfedd2))

- New flag req in yq
  ([`5743dc8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5743dc8f3712938a6927f3e319fd48fb4ea24ca2))

- One final test with actual docs publishing
  ([`519c52a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/519c52ac26ecc0855a7e929a1e19712ee72a8c55))

- Reducing merge to only deploy packages
  ([`e9c1d2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9c1d2e051c66e9d352e7eb222ea490996c3f74c))

- Renamed job to clarify what it is
  ([`aa3057b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa3057bd1f77da4eb082a2c8d4d71252722b2b4b))

- Speeding up docs build
  ([`86b914b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/86b914b95a2adc12f747740cf11fddc3deaafe78))

- Trying twine skip existing
  ([`a0a1f44`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0a1f44590ac99453db615ea3abcfec35e43dd58))

- Typo in product name fixed
  ([`6b293c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6b293c209d4797d5c877d6ffee90a75bb9d1f8b7))

- Update python range in pyproject.toml
  ([`b3d4dc1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b3d4dc1a9c61f103a7da8c582dfa2645da32fdb6))

- Updated logic for construct docs publishing to only run on master commit
  ([`cb81988`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb819885ee7e5c69dffd09b90ffc87de7817b9f1))

### Chores

- $$$ -> $$
  ([`af5e116`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/af5e1166e64c528f43b8d27d0f96a1350c80b60e))

- Bump version to 4.21.3
  ([`a3f995e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3f995e1309e8a2d9644c27f3ddd7bf1fb70d2e0))

- Fix poetry install
  ([`dcff3ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dcff3ce24276fe1d92b778beb71405142d3f1975))

- Fix qasm2 test
  ([`d57b2d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d57b2d170dcc2a41e4526a1a620cd0b16755dcbf))

- Fix tests and add special case for ctrl
  ([`bca6d44`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bca6d4460f6de6ace202675664c76cd89896740b))

- Rename test file
  ([`97b2d01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/97b2d017b1fa3db7f53cbec0e74836cc07e6d9e9))

- Tidy up imports
  ([`7baf168`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7baf16875a96743c8cb9e0bb823e3064f4b3177f))

- Update bartiq version
  ([`b2c80f3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2c80f3bc31ebaf52342a14f03a66c9b3ea7527f))

### Code Style

- Blackified native.py
  ([`69b341e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69b341ed9a449a5ffe7912138362881c183ccb53))

- Mark children key in native format as NotRequired
  ([`131ed0a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/131ed0a38e571f415cc054207ea94e4afd37ee54))

### Continuous Integration

- Changing image to python 3.11
  ([`e8e4041`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e8e40416b43aac9bc551affe9e25fff7ba200909))

- Deprecate wheel upload to old pypi index
  ([`5b9ff7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5b9ff7b2d2f09d172915dc2f74b7e24ec64a2db8))

- Minor fixes to deploy_external job
  ([`552f551`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/552f55167045b9b059c25ef2f3a279273bfeddc7))

- Refactored gitlab-ci config
  ([`f1edca8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f1edca80fec769d1bc798ceff4e523d1f590d5bf))

- Remove aarch and DARPA builds
  ([`2956bf9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2956bf90255054756aa4690c31248bdb0754033e))

- Update dev-ops/common dependency to 0.0.2
  ([`bd1212d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd1212d88c233486274917c9196e9f7b2ec9c831))

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2
  ([`dfc1a6d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dfc1a6d68b4e78f4fc9f6eaf7142ee3c4d4396e3))

### Documentation

- Add print_state_vector docstring and fix detect_entang.
  ([`6894aae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6894aaed51d04f522eb21fb4482dd2a76265ecbd))

- Moving c++ api docs to top level and filtering for external build
  ([`5aed98a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5aed98a9bfd9948277868d4a5c31a415f82e340e))

- Privatize C++ API
  ([`273b80c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/273b80c564d8b168f0e2fc4c080c575f4d26690b))

- Remove :meth
  ([`1abb17c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1abb17c66d324529021c00be6982f15602650913))

- Replace :math with mkdocs math strings
  ([`c2b067e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2b067e05c30546479872458c879bf25793733ff))

- Update docs on symbolics
  ([`0079c7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0079c7ac8176c24b391f83bdd2be60a8eda0a546))

- Update sqre docs
  ([`bc6abcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc6abccfc9a3cb7a6711e3f1657202545ebadcc4))

- Update sqre docs
  ([`491058a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/491058a756c02704f61dc66064547e0c017281c5))

- Updated docs build job to support both internal and external deployment
  ([`54b334a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54b334ad4564d53b3ebafbcd42490d5c5a4bb67a))

- Updated logic and naming as for wba
  ([`0cc9a2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0cc9a2a93108d0da4ae67615d88f848c78337c77))

### Features

- Add checks for more special chars in qasm export
  ([`d5fcc1f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5fcc1f0a3f4bad4416ec8e953a7a741dd968394))

- Add support for qc.read in new symbolic serialization
  ([`1b608d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1b608d664f5719ae8ffed3534c1de6e07b563923))

- Automatically register parameteters associated with new SymbolicQubits allocation
  ([`ae7816f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ae7816fefeccdd2da4cd6a8d246b5083f82ce55d))

- Implement new algorithm for infering symbolic input/output registers
  ([`d2a2b4f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d2a2b4f0d39b520f2ec6de7180dfd92aaf0757c2))

- Implement symbolic version of _infer_registers
  ([`2cefe0b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2cefe0b109eb658c857aeaf19bb9f5fba891cc41))

- **active_volume_lookup.py**: Re-add CX as it is a special case
  ([`e95a761`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e95a761698b99e812b29559a69cd3ef615eeb2b8))

- **arithmeic**: First implementation of arithmetic for rotation units per #1041
  ([`c54963a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c54963a4617e91b9b7e58f678a538c3cd7e9b004))

- **get_av_from_op.py**: Update old comment
  ([`66e1868`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/66e1868f4abe5f6523776f5fa0f30d2fc111b82f))

- **ppm_functions**: Disambiguate _get_pure_ppm_av description
  ([`480ac1b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/480ac1bd8987b9280fd684443a97f7a17f02ab39))

- **qpu_op_functions.py**: Add optimized multitarget cz gates
  ([`e5e31af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5e31afeda77da473d7cc56efa18fe45649cb266))

### Refactoring

- Clean up serialization code
  ([`a3c7fdd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a3c7fdd322c92845b266bc61d744ab95cc226b6c))

- Get rid of some commented out code
  ([`d6c7ded`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6c7ded79dd0ce7e5c4044d7a9e7595d407d043f))

- Simplify how input qregs ids are extracted from target_mask and condition_mask
  ([`d79c124`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d79c12425e39ef93222b26448f3242c841c38ed1))

- Simplify how registers are normalized
  ([`6aea253`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6aea2538eabec54a5f4c2a3ff08a47f7945e2836))

- Unify symbolic and numeric registers
  ([`9bd62ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bd62ecb55b9e8ac9bc86174e43026ad092c1bd1))

### Testing

- **arithmetic**: Simplify tests for #1041
  ([`c8f10da`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c8f10dae1c375a2879c842c12abb436803955640))


## v4.21.3 (2025-05-08)

### Bug Fixes

- **active_volume_lookup.py**: Add v5 version
  ([`8f61077`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f610776b5e9f97560934c38d8007470730e39fd))

- **active_volume_lookup.py**: Improve comments
  ([`bc38bd3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc38bd38092377b4ba4aa7ed931fa9a994624ceb))

- **av_counting**: Ruff format
  ([`7f13fe7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f13fe7f70926e6ad62618b40f7062447d421ed3))

- **poetry**: Un-pin poetry per #1022
  ([`b710768`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b710768e6d4c9cdeca74173760f883b50e339378))

- **setup.py**: Passes ruff checks
  ([`7dff246`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7dff24668bf5d5c61490dd81206e4a202936f90e))

- **simple_av_counter.py**: Circular import
  ([`992950f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/992950f3893e6f2b12d06c6a6a88cbbafedcda02))

- **simple_av_counter.py**: Match witness av counter
  ([`7aa3599`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7aa3599876578bf1ad6e042fd27c90762151185b))

- **symbolic**: Flip the symbolic workaround in #998
  ([`5070b07`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5070b070556e07afa9ab0108eb3367d29041da9b))

- **symbolics**: Revert prior change, keeping the symbolics workaround in place
  ([`6386578`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6386578eae0f4ccb98f7fdf72049e8063c260287))

- **symbolics**: Workaround for symbolics issue in #998
  ([`5241124`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/524112449afbecaa77fb9111800f1984a50428e3))

### Build System

- Added "all" extra dependency for installing all extras
  ([`07003dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/07003dd6804765070e9ad6353e4176b4e21b5fbe))

- Fixed missing extras in setup_legacy.py
  ([`7327780`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7327780e2a4382bfcf4c8dde12dc6a6042e87913))

### Chores

- Add doxygen inst. to readme
  ([`bcc8834`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bcc8834305150b65f707a40361b793205adde41d))

- Bump version to 4.21.2
  ([`0626979`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0626979fb96908cd86b7d064361db2c9b5e0d2b2))

### Continuous Integration

- Add doxygen install to page runners
  ([`b1dea19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1dea1984c947e72f6099bcab60301b5696abd19))

- Adopt default settings for python jobs
  ([`f0b598f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0b598f88c66e187cb640e37f709712d9db6c9ee))

- Fixed remaining bugs in macos jobs
  ([`de3f95b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de3f95be358e9ced4e65233faddf62f3d5cb8334))

- Refactored .gitlab-ci.yml to reduce duplication and remove uneeded commands
  ([`69eb05f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69eb05f4fa22833dc52e6197758e22f5e8ce584d))

- Updated poetry.lock
  ([`95559c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95559c4028514f393d99779a1b87fca41d02a907))

- Use poetry>=2.1.0
  ([`59da911`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59da911cbf26d5f860b6410445f159eaa223fa17))

### Documentation

- Add doxygen comments and api overview sections
  ([`676f728`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/676f7289cf6ef2177a18d851e6e675468845ac56))

### Features

- Add comparison of two numpy mats
  ([`ddbd849`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ddbd8494d513b6d1a11220a148f4c7224863b6ed))

- Add doxygen support to mkdocs
  ([`0c5ec1e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0c5ec1e9e4e36e76b758f1e24ad50b014421c1ae))

### Performance Improvements

- **ram**: Massive memory usage improvement for #998
  ([`bad5bbc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bad5bbcb7b7bb919600658526b218e56218d98f3))

### Testing

- **cicd**: Restore TEST_ON_LATEST_DEPENDENCIES to false (it seemed to have no effect)
  ([`b65e698`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b65e6985584699b29bf8201f44737ca087a33ea0))

- **cicd**: Switch to test-latest
  ([`072d238`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/072d23895914c91ec4403d9801a46a63c663a5f5))

- **MR**: Test added per MR feedback
  ([`0151ff2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0151ff2ad112b893902af93284431add644e7256))

- **ram**: Add first RAM tests
  ([`9236226`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9236226a2dbf698298301c135d972e2fb560da7c))

- **symbolics**: Testing a fix for symbolics in #998
  ([`2b43e82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b43e8208344e03b973ee6119d1e1281dd9a1db0))


## v4.21.2 (2025-05-02)

### Bug Fixes

- Fix import
  ([`6190627`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6190627598f6ffaff836857eb9339dd9e94ef83c))

- **warnings**: Fix all compile warnings per #1003
  ([`22c4cba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22c4cba08b1c69adb7e584bcb470689c40b462ec))

### Chores

- Bump version to 4.21.1
  ([`74e53c0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74e53c0e9b05efeef394c84194f5307c427fa4dd))

### Documentation

- Update Witness Counter deep dive notebook
  ([`b8cbd77`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b8cbd77fdb54dd41335c1273a3562d4c92281dc8))


## v4.21.1 (2025-05-01)

### Bug Fixes

- Remove explicit pytest dependency
  ([`43ab820`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43ab8202a5026796057cfcd4d210f3f8ce2b28ed))

### Chores

- Bump version to 4.21.0
  ([`630e5b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/630e5b55a118a8d3c7e328f9e7ae6fc6cdc24224))

### Continuous Integration

- **codeowners**: Removed C++ sections
  ([`ba6da66`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba6da665e04355281a60a54ecc10d1ebaa7b8515))

### Features

- Delete unused warning filter
  ([`151a6c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/151a6c74ccb3bc5f07b626f6bd44c014f04dbd5c))

- Remove pytest entirely
  ([`47efa68`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/47efa68a6a3a50e9fdb32c0bbec1815cceb86213))


## v4.21.0 (2025-04-30)

### Bug Fixes

- Allow conversion of nested sliced registers to QREF
  ([`43234e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/43234e0c49e08bba452daf0121b52259c47796b2))

- Fix how the input and output registers are calculated
  ([`a5a1f83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5a1f83847b5b9c5281353dab215dd601aca5cf5))

- Fix problems with serializing nested access to rotation catalyst in uncomputes
  ([`53dec5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/53dec5e810cdcd39b1feed2b4385d7f2f59249a5))

- Fixes issue where pprs and ppms are not counted correctly
  ([`8b0e00f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b0e00fe1171f2d61c6dee44e2688a3cf28f16ed))

- Melt registers before stripping children
  ([`1860584`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1860584ab4b4e89d747a37d3e1f51493622bea95))

- Start re-adding rotations
  ([`670e748`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/670e748fdccf159894e5fc1ed494f349ba6aadcd))

- Update how AV for arbitrary unitaries is calculated
  ([`f042187`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f042187956d5915bdbf98d9949a384df84103553))

- **active_volume_lookup.py**: Allow universal import
  ([`8cd9be0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8cd9be00b98ccc845dba5fbb9ed687068f4c0ba4))

- **active_volume_lookup.py**: Depricate old version
  ([`7e2d983`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7e2d983e484e1228b2dac865919b8697921ab2af))

- **av_counting**: Formatting and sorting by opcode
  ([`435d515`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/435d5153163cdc65c16d4c3800d3ba6273db5eee))

- **av_counting**: Privatize
  ([`3bffc3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3bffc3ec66479da01af6fa3527218e8a23cd6e89))

- **clifford**: Fix for the case where z() has no target and 2 conditions, per #1010
  ([`7a707b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a707b6dbd63b0ca90ba9773d25a50c10fe9e536))

- **deprecation**: Warning and test, but warning doesn't work
  ([`e59e844`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e59e844b00c21ee22f9ea3d980ab7d013ed8847e))

- **docs**: Add Setups doc to Tutorials
  ([`f314d81`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f314d81b274e0b6e2f74f8743bfeca29c2084e15))

- **docs**: Docs tweak for #816
  ([`0d785ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0d785cac3e49521fbd515ff2133b4350458f4bfa))

- **get_av_from_op.py**: Fortify multitarget CX
  ([`142a853`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/142a85379a4a2cba11a2c207bbf2dc21f5faad3c))

- **get_av_from_op.py**: Improved reactive gate handling
  ([`0b4f62e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b4f62e567cddf285e9b5d0dd1a61fe825af4b29))

- **get_av_from_op.py**: Passes wills common ops circuit test
  ([`e458192`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e458192e3917b1b49a87b6789fbd2301de55508e))

- **lint**: Fix one lint error
  ([`dbe96d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbe96d7f0d1c9b9fff3b0dc2dd073333f1b305b3))

- **macOS**: Attempted fix for MacOS builds
  ([`9e9cbec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e9cbec20e5f5fb588c63784bb6a5d976a5d0e6d))

- **macOS**: Modified fix for MacOS builds per #990
  ([`b854ffc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b854ffc5074645b3a79c95f8ebc41ee301fdfd4b))

- **macOS**: Remove extra version check
  ([`fe2679f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe2679fdea9ea20ec2e820c01f5745a147bf7b7d))

- **macOS**: Revert macOS install lines
  ([`e951920`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e9519202a6882c502247d5c363e0a049a8e1dd40))

- **macOS**: Some prints to debug versions
  ([`b7131a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b7131a276cdfab94f2400b68d3bc18fc3ce2ee10))

- **MR**: Changes per MR feedback
  ([`5676529`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56765291474c9317a24ca5ad02091ceabff785d0))

- **MR**: Fix MR feedback items
  ([`ff1e86a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff1e86a8887f4fc4e0597ca76fdac6494d4869ee))

- **MR/back-compat**: Fixes for backward-compatibility and MR feedback
  ([`874c542`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/874c542be61780be35d135910454626dc300ff26))

- **setup.py**: Deleted old version
  ([`def7a1c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/def7a1c390a340ca66d452a5b23b632bd2161889))

- **test_994**: Add Op_qc_phase test
  ([`225f346`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/225f346131aa952a1a58be80f876b3fd45fccec3))

- **test_994**: Added tests for rotation synthesis methods
  ([`1fd849d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1fd849df84433674a33ecefb8fae5cf0d853795f))

- **test_994**: Re-add accidentally delete test case
  ([`5a89d60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5a89d60a948f6f0b01f3efbd0104d7ffc478e775))

- **test_994**: Ruff checks pass
  ([`564d00b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/564d00b455ffc6b19e8c324661728434c52839ee))

- **tiny**: Fixed a variable name in a notebook for #983
  ([`7fa89f7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7fa89f75fe74d878cc4a4d527a0dfd602bfbaec1))

- **warning**: Fix deprecation warning #816
  ([`f22c985`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f22c98546992146406b07749aad3ecba70c43608))

- **witness_counter.py**: Fix reverting back to normal Op
  ([`705582d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/705582d6bcbdab9a53880338e07c8c7eefb0dba2))

- **witness_counter.py**: Revert some formatting changes
  ([`6f20cc0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f20cc09dd95d2866408eaaa42e4539e7f03e4b3))

### Chores

- Bump version to 4.20.5
  ([`3236858`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/323685838c713fc1b2bc2f36bf9afcb7a92af748))

- Fix CI settings
  ([`767b3ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/767b3ee73e0d6fa3c1a65a3c5dff17d6e83ff879))

- Replace QPU.cnot calls with QPU.x
  ([`d766df9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d766df9f352ce129f7e5d5d3835f4d11fbd1ee3f))

- Replace QPU.cz calls with QPU.z
  ([`412cde7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/412cde79793e969a08641a1cecb53a00eb9efb64))

### Continuous Integration

- Add WB crew members as default reviewers for bumpversion MR
  ([`34bab46`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/34bab46a2d40116934193ef1d66254b3b77e20d3))

- Stop pages and wheel deployment running if previous stage fails
  ([`f2fde5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2fde5c517b5c4d0703e7a68bc34ca81ffa54311))

### Features

- Add data type to circuit labels for qubit allocation
  ([`394529b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/394529bea0d4c6efdab100531654f8bdf729d43a))

- **filter-sets**: Adjustments per design doc feedback for #983
  ([`9e2e5af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e2e5af4d0100a3759a66078a790fe9becb5d7d5))

- **radians**: Specify rotations as radians or fractions of pi, per #816
  ([`c23df89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c23df8924332b88b74e1b0425c21666d15b1fbdf))

- **rz**: Testing new variants of rz()
  ([`93c64c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93c64c7ae67d219fa08b5c013e00a7c67e4b707a))

- **test_994**: Add test for multitarget cases
  ([`2d6c174`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d6c1744158f540203628a4b4aeb6cd7940b6f61))

- **test_994**: Added 337.5 ppm test
  ([`3738e1e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3738e1ef05db2bf294d36c6d90a0557135e82319))

- **units**: Add rotation unit tweaks for #816
  ([`db78c41`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db78c41457a95899ce6116719b1e99f325b69c40))

### Testing

- Add bartiq skip for pprs test
  ([`9e707b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e707b88e2a6067b018d15f0c4c3831057bd5751))

- Add test verifying serialization of alloc/dealloc pair
  ([`c3b4f39`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3b4f39cc7b2036148a5f59b1b25df0736557d6d))

- Update test for pprs
  ([`3f63e08`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f63e080bf66bdb797468014c026e3cc6f0b317d))

- Update test_916_numeric_black_box_qubricks
  ([`a9a71dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a9a71dd95b6d01097f5ad1fde1e330f3333686e5))

- **cz**: Add more test cases per MR feedback
  ([`86a7b10`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/86a7b104cd2fe7f80a8aba2574f62a7d259040d7))

- **macOS**: Switch to clang++ to see if it matters
  ([`9116741`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9116741e91bb23939026787d8a93713001e78b99))

- **macOS**: Testing MacOS update probes
  ([`8f71c57`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f71c576b4306b97f0eae5162711e346a176909e))

- **macOS**: Try separating -arch from arm64 etc
  ([`80aca78`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/80aca78a6522b2b9aa1802db34d53636a5d4034c))

- **MR**: Add test per MR feedback
  ([`08e8071`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08e8071cb63e8e457c2d03b7669b9cdc7286715f))


## v4.20.5 (2025-04-24)

### Bug Fixes

- **cleanup**: Remove extra assert
  ([`45fbf2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45fbf2b3fe42ba7a343c181684be3759449cd78e))

- **matrix**: Fix a very terrible bug in the matrix code which caused const_gates_2x2 to be
  modified, per #1000
  ([`744b706`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/744b7068df584c203fc655a919e3f94bcffe74e9))

- **ppr**: Fixes to PPR matrix and draw code, per #1000
  ([`813fe5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/813fe5b9bddd59566617f4243497cb4989faa2b6))

- **random**: Random seed for #1000
  ([`aac79a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aac79a8499dce8e708663e1eb4b0e887e21f5c7a))

### Build System

- Increased floor for pyliqtr dependency
  ([`65c3f71`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/65c3f71a00c719e6d719ee7e76f5d39748faae4d))

### Chores

- Bump version to 4.20.3
  ([`a1bceeb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1bceebe4842d81d2791115ff4957f42a1e79403))

- Bump version to 4.20.4
  ([`2e5b894`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2e5b894790ad67ccbf3f75f619128c1d54dd80b3))

### Documentation

- Made all edits suggested by Sean Greenaway and SMS
  ([`210ec0f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/210ec0ff87b020978096614184419e95c30da999))

- Removed vector-register from CompositeRegisters-and-VectorRegisters.ipynb
  ([`9f0c534`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9f0c534f09133ac7f207d5d863864a5cf214e6a3))

- Update How-auto-uncomputation-works.ipynb
  ([`b69096f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b69096fa4bf4945b45ec8bcddd1112a49174eec8))

- Updated tone and made changes based on QA feedback
  ([`df85483`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df85483787b11e339f3e539531f48047d7c9bb05))


## v4.20.4 (2025-04-23)

### Chores

- Sync ci with master
  ([`4bdfd1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4bdfd1ddcae7e2ecac718a5463083aa7b21711d1))

### Continuous Integration

- Updated CODEOWNERS for version bumping updates
  ([`b91b555`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b91b5550d490174ca8074605d1773594d970bbc0))


## v4.20.3 (2025-04-23)

### Chores

- Bump version to 4.20.2
  ([`b592cb0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b592cb03fc5f197a740656367990590250173673))

### Continuous Integration

- Add wheel upload to new artifactory
  ([`ba464f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba464f0879fd466c830607e3c9508183f50131cc))


## v4.20.2 (2025-04-21)

### Bug Fixes

- Docstrings + added option to choose b/w decomps and am testing both now
  ([`f833115`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8331153277e2a23d283c9d33fb8794bef4baa5b))

- **capture**: Fix for capture buffer overflow in #997
  ([`62ba96f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/62ba96fe21c859f41520e323b2dc333c6b44172e))

- **test_991_qasm2_string.py**: Add qiskit install check.
  ([`56cb761`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/56cb761e89caddbee991802bd9f10407587ae0b6))

- **test_991_qasm2_string.py**: Added copyright header to test file.
  ([`aec7a79`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aec7a7974ad0e831df737e65338038d22d30867b))

### Chores

- Changed tabs to spaces indentation in PPR test file
  ([`49068aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49068aacb54a2ee922fd07e56b90d419d46d3751))

### Continuous Integration

- Update include project ref to 0.0.0 tag
  ([`733ecc9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/733ecc9dbd4900c9de939dcaf2847d182ed97a7e))

- Updated CODEOWNERS
  ([`6091ca5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6091ca5eef89afe74920208ec048d56086264d72))

### Features

- **qasm3_export.py): added get_qasm2_string function to QasmExportFilter class.
  feat(test_991_qasm2_string.py**: Added tests for get_qasm2_string.
  ([`dc97d6c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc97d6cf3bf40ba7b4777cacbcc4f7347297d214))

### Performance Improvements

- **2x2**: Speed up 2x2 matrix ops with not-conditions
  ([`693bea4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/693bea4af5599f5f27f2eb8d7949a2e0df9c51c3))

- **cz**: Speedup not-conditions for CZ gates
  ([`08ade2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08ade2ba759a28a37ed521114f6aca4b77aa9344))

- **hadamard**: Speedup for had() with not-conditions
  ([`25f77c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25f77c1dc1438f004d242528df73910ce8ac5e51))

- **ppr**: Optimize not-conditions for PPRs
  ([`fa0c292`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fa0c2925825ca33388caee9579f866016a19e5ef))

- **sim**: Massive speedup for cphase when not-conditions are used
  ([`4e8fe2c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e8fe2ca81519113a5545ddbfc272ca036da5de4))

- **sim**: Massive speedup for not-conditions on X and Elbow gates
  ([`c62919f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c62919facb3065a0ffb5240ed5e4fa30c8b93b77))

### Testing

- **rename**: Rename test script
  ([`29d9e60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29d9e60d50efce7a4da4bd554d34331141eeeda3))

- **speed**: Add test for not-cond speed
  ([`47dd46f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/47dd46f5ccffb648e92dcb4717a38c66578df496))


## v4.20.1 (2025-04-16)

### Chores

- Bump version to 4.20.0
  ([`66db837`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/66db8370c5f94855009a9c985e6a27c87f9d58a2))

### Continuous Integration

- Refactored .gitlab-ci.yml to remove duplication
  ([`6d3b1c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6d3b1c789092accd387024a84366aceb3247dca8))

- Remove test template extends from mac osx extras job
  ([`3db0324`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3db0324ed883354c631fd76b3287ef560e09bcaf))

- Run default job rules on tags
  ([`3f19b1d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f19b1d961db6ddbf40dc755d863fc109fd4cf12))


## v4.20.0 (2025-04-15)

### Bug Fixes

- Add copyright
  ([`63a70ba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63a70babc3d006c780c242a7b7c8866ea3c64c68))

- Add site to gitignore
  ([`7ad5977`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7ad597740c9502ec67176907ca88ab8ea37ad342))

- ASIP-1195 Circuit label for write uses data type
  ([`ff221a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff221a6cf5891275c5cd2cc7688ca0c960e83354))

- Clarify restructure op is for av
  ([`6faf099`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6faf0993d63e8955a23b0a0092f743da1e95a15f))

- Delete dag stuff
  ([`ef60501`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ef6050103235b6fcc9b6465315aec80e96f521c3))

- Fix for another failure mode with AV of read
  ([`95191a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95191a82c1ddf3fdf00281141e92893bd9d5bc51))

- Get rid of av specificity with restructure op.
  ([`310693d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/310693d45680362a0781d07aaa623887a73dcb4d))

- Makes costs in QubricCosts to be None by default
  ([`670b263`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/670b2637e762b8304412bcf42f0355ac13eace5e))

- Update av calculation logic for symbolics
  ([`c41b4f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c41b4f07f0e2a81b4d61336f3e0a014ee4ca7a0f))

- Update old parameter class to handle None values
  ([`4e04129`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e04129e5c70d0a5591dbf18cf69ffde10e9240f))

- Use the value that's actually written
  ([`875c451`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/875c451eb6b6f7e77eb8b5a093aeb1de834b4efa))

- **active_volume_lookup.py**: Get rid of unused compute_av_multitarget_cx
  ([`27c1fb6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27c1fb67f98131955081b650eb2a450d05085f55))

- **av_counting**: Account for CZ gates in targetless op
  ([`2d60847`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d6084759be3592f823a050788a6fc4c456697ef))

- **av_counting**: Add copyright tag
  ([`fd4bff5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fd4bff53b3a66009bec771a761612f15cbe99f0f))

- **av_counting**: Add typing
  ([`30c35b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30c35b3f316491ef508872dd07346e7ac0018d3d))

- **av_counting**: Clarify ppr costing function names
  ([`00f9a01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/00f9a01c96d1e5ddd3aa0604c69d5bf300941a4e))

- **av_counting**: Delete duplicate get_ppm_av function
  ([`32d2cc3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32d2cc3988d35a736bf7a849eb633eaa1cf280b6))

- **av_counting**: Get rid of get_av_from_witness dict
  ([`df1df5e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df1df5e29e1574b202f109dd891ed006f17bde44))

- **av_counting**: Get rid of serialization
  ([`37c740f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37c740fd78362c02a034043efdf074e50da3cff2))

- **av_counting**: More Selinger spellinger
  ([`f469bea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f469bea2a314628d5df70895d7e716b6611b95a2))

- **av_counting**: Pass ppr av counting method explicitly
  ([`851c4c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/851c4c1b0298f95e0169d4886bba12e0f6887c86))

- **av_counting/utils.py**: Improved documentation of strict option"
  ([`2767484`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27674844905aa0094ad8933e830927db5994325b))

- **av_counting/utils.py**: Update typing
  ([`e1de9b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1de9b93c755558c690bb4788be6c4df6bdcc22c))

- **cicd**: Revert #970 per #992
  ([`f648093`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f648093dda94c388a99cecdc3a0466f0047bb3bf))

- **create_simple_av_lookup_table.py**: Delete dead code
  ([`bc41bf5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc41bf50a25a90e791dbe4970d8b197f0df4a89c))

- **create_simple_av_lookup_table.py**: Delete improvement comment
  ([`c4e8078`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c4e8078a1ba579371e8e66eeb4d487802c0dd04d))

- **get_av_from_op.py**: Delete double import of restructure_op_for_av
  ([`1bc93f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1bc93f42f1bbc0a5c43e670a8aa2afdb019c5d9c))

- **op_av_function_tests**: Ensure all adder operations are supported
  ([`d902fd7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d902fd702485365d952f8315474406feb431cd1b))

- **output**: Delete unneeded json files
  ([`1076a91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1076a9117f39ab7aefb25f55fc2c78858ecd5051))

- **output**: Delete unneeded txt files
  ([`99ad61d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/99ad61d98c26fb1755d8642f8dd4960468ac90a2))

- **ppm_functions.py**: Get rid of type annotations in comments.
  ([`20c554b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20c554bf64ba8fca780f1967ccb351e95689945d))

- **ppm_functions.py**: Specify meaning of pure weight
  ([`b0d15c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b0d15c78228877391846a244e0623f90a42a1db9))

- **ppr_functions.py**: Add comment clarifying half Y state costs.
  ([`adbe4b0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/adbe4b00b71c517c1ecba7261df9b75cd907568a))

- **ppr_functions.py**: Add default case to RS
  ([`647d2e3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/647d2e367c5c54a4839705af5bcffdfac842a8dd))

- **ppr_functions.py**: Improve function description for arbitrary angle PPR
  ([`614361b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/614361b6ac61437a8dcb9b6a4881afc91e745228))

- **ppr_functions.py**: Make default rotation synthesis case more explicit.
  ([`e067601`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e067601a26558ab67b78e551154f917d2450a5a1))

- **ppr_functions.py**: Selinger spellinger.
  ([`9304853`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9304853e4859029a617741c91610c806e8f89f87))

- **qpu_op_functions.py**: Delete unused import
  ([`d87a43b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d87a43bc2975066e6b1cdc5ec52e94d6877d7f38))

- **qubit-mask**: Fix for #996 mask error
  ([`256de91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/256de912d13e83cca1a5bf3fdc03cd08cff9ce1f))

- **serializtion/native.py**: Revert imports to master
  ([`4f26008`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f26008b0b567511524b5b2d60e86889b551dcbd))

- **simple_av_counter.py**: Add copyright notice
  ([`86bffdb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/86bffdb96d43c886e891169d526c44987e8d48bb))

- **test_994**: Add ppr tests
  ([`79bcc84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/79bcc84d2437288582e8bf5c28ec7dfda7418de1))

- **test_994**: Adder verification tests
  ([`14c47cb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14c47cbc11eda50326fd8f2463c39366de2b6073))

- **test_994**: New default RS imports
  ([`51ff745`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51ff745fb5b9db39607d69dd1a0b0cb1149fbff5))

- **witness**: Finished include y weight
  ([`b2a0cfe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2a0cfe2e44c12e7a2f598e78c4707fb1fbe8128))

- **witness_counter.py**: Faster hashing
  ([`964ec21`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/964ec2188f34364e224d842365ed464eee4d49b1))

- **witness_counter.py**: Simpler hashing
  ([`8f53e38`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8f53e383bbab88eadc4c34b46e9ebb654d3809d7))

- **witness_counter.py**: Y_weight excluded from x_weight
  ([`6e8a05f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e8a05fb3e946fbe089495540c3258c908817389))

### Chores

- Accounted for factor 1/2 in PPR angle convention
  ([`9354f20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9354f202d4b7282ad60e8a0dc04f2435f097e89e))

- Bump version to 4.19.0
  ([`585d095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/585d0953b668fcec5339de46656a34dd725153d5))

- Bump version to 4.19.1
  ([`a71cd5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a71cd5c76b06bac8e5f830a40c0f5301f9972ea6))

- Bump version to 4.19.1
  ([`ff575b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff575b189dc8a5da9a8bda477a0c3eb4dedaec16))

- Fix test
  ([`498b804`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/498b8049317037111b097290f911236d5115251d))

- Remove references to >>knifey>> filter
  ([`6f03c85`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f03c8509803d157a361f55ffeeb4623cea803bc))

### Features

- Add set_random() to Qubits
  ([`7a95c59`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a95c59bb616ca2ff3e202d08296fccb72729d65))

- Added dag
  ([`81ac696`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81ac696a4131e218481ab5060bef6951f4b20530))

- Added PPR into PPM + anc decomp as well
  ([`6e4b133`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6e4b1338dfe856a0aa555f83aed2ec883aa01f79))

- Added tests for RS synth for PPRs
  ([`a0ca577`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0ca577400b3a51336a746c203122a783214322a))

- Adding some code to convert from PPRs to RZs
  ([`b92d9d7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b92d9d710facb3e3a1aed5f741a0751665356df9))

- Av lookup table
  ([`771215e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/771215e3d29b59dac7bec57348ffd5a8fa83d45b))

- First version of PPRs with RS synth working after pairing with @ssim
  ([`def1c0c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/def1c0c239c90efd5fbcf6c6bfa080a194b50f34))

- Paired with @acaesura, made some updates
  ([`b475180`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b4751805818df8f35ca19a1d84c01797e717be9e))

- Simplified decompose_op, now calls ross selinger qbk
  ([`215f8ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/215f8ec633ca729712e60f30944c5890807c7847))

- Small fixes, looks like PPR examples are working
  ([`962b118`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/962b1187e60e76ca7a112671d57c5113fbd56fac))

- Updated test to use new qbits.set_random method
  ([`49d321c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49d321ced648ad5261f74652c62bba76dfc75f2e))

- **av_counting**: Add safe av counter
  ([`111ca6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/111ca6e0d1868acf779cc39e825b09cc30fd531a))

- **setups**: Filter setups for WB users per #983
  ([`68d9020`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/68d9020ba72e596cb0f2d263240f06c40a16f7ec))

- **simple_av_counter.py**: Create simple AV counter
  ([`2601061`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2601061fe67e120d76d309b22ce3be85ae3344e9))

### Refactoring

- Apply 3 suggestion(s) to 2 file(s)
  ([`a5e1acb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5e1acbc08e0ff47709e4bac96f1dc8be99b724f))

### Testing

- Add missing "requires bartiq" decorator
  ([`1060f7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1060f7c53758db68d77806dfdd8120b674584ae5))


## v4.19.1 (2025-04-10)

### Bug Fixes

- **cicd**: Revert #970 per #992
  ([`b272ce6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b272ce6b171101718bb3b50c93111bafd5fec7eb))

### Chores

- Bump version to 4.19.0
  ([`49bb5ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49bb5abfde59d7d368998e7ba0dec243d1e57635))


## v4.19.0 (2025-04-10)

### Bug Fixes

- Add types to resource map in native.py
  ([`1bc9684`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1bc968489990500ab7bf54e5a82c56e5b1a823fc))

- Allow for setting the QPU RAM limit via environment variable
  ([`f8e99d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8e99d6c209f0fc22327599a29f2c780cde7dd64))

- Correctly handle integer sizes when constructing remainder ports
  ([`1bab6a0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1bab6a04f687beb14f247624f28adbed346c011b))

- Fix split-merge pair cancellation
  ([`de300bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de300bb45ca52963e8344508b6e86a5de92fe0d4))

- Fix tracking unique names in native serialization
  ([`aadcef5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aadcef5c4c75da555c523c6d220d19a0a71abcf7))

- Fix typo (again)
  ([`a5b1e64`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a5b1e64396cf50e589d88f562a52f3bc9f81b63f))

- Further improve performance of split-merge cancellation
  ([`e923a44`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e923a442164522d8e6dd7641df4af83be5187d2e))

- Handling measurements and elbows in numeric serialization
  ([`96cd4f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96cd4f0914233962f1b67bdc4730501d153ba68b))

- Import BaseQPU for typing purposes instead of QPU
  ([`87af295`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87af2958f1ca34cd9a1d8ac7bc178fa926511db7))

- Improve performance of split-merge cancellation
  ([`d6d5095`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6d5095248fe524fc4c4b52b4d2c55ac49d17219))

- Make tracking unique names more performant in numerical serialization
  ([`13dcd2e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13dcd2ea48af1736c07184d4b60d2430dc3e2fa9))

- Remove left-over breakpoint
  ([`c6abed2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c6abed290dc3804fbe023084e993a3f670bf9935))

- Remove no longer needed is_based_on method
  ([`63560c1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63560c14d4ca08c50ac853aa132a092233b3a940))

- Remove redundant call to qc.to_serializable
  ([`7bdd1ed`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7bdd1edf7dfbeee3240899133d93c794eb8ed200))

- Remove unnecessary case in _numeric_precursors + add docstrings
  ([`f331ef3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f331ef33d62216a9faec252773da244363d523f1))

- Remove zero inputs in qubricks as well
  ([`932389b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/932389bcee81e46ad1583009d2fc881d186449ab))

- Restore resources to repetition wrapper
  ([`2f0ba13`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f0ba13e5a28f91dbb5e3fc5731689cb84ea7583))

- Skip zero masks from all outputs
  ([`75ea5da`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75ea5da3acfbe61ff020a13eef874d49c2028a5e))

### Chores

- Add CR notices
  ([`9ab407a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9ab407ac1ea1ce958558f978fa683c7900c0c151))

- Add note to docstring and more tests
  ([`270cb74`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/270cb7473208ce14cdbe8e2ff612784a0c0149f6))

- Add typing_extensions module to dependencies
  ([`aae4e08`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aae4e08acdd75d6d011f1d94ac2b5f7d76fac9c3))

- Bump required Bartiq version to 0.12.0
  ([`8a2ab55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a2ab55de156b309b7e9bcd00058de63d87fe8cb))

- Bump version to 4.18.1
  ([`0158b72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0158b7287fe975d866541c287e5bf9d8a4c23243))

- Fix failing tests
  ([`ad41d8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ad41d8c5c5b5828aa1686121557dfc178491f92f))

- Fix random seed and use fidelity
  ([`680c164`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/680c164e3190856e928130f1defaab49ff6c3f7b))

- Fix weird corner case output
  ([`d4e1e9e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4e1e9e967cd355754c5e63cec24d7bcc8064fe1))

- Redo with faster method
  ([`abb6f3f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abb6f3f51cec4a6925da886c2739777515312132))

- Remove comment in docstring
  ([`e958c82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e958c82e0fcb0a964bf61db9f14e970707247d3e))

- Remove references to >>knifey>> filter
  ([`794e555`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/794e555e7cde3fce1e40841c83010c9d25c4c553))

### Code Style

- Improve type hints and formatting
  ([`4effe07`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4effe0760f9672e6d90edfe1f24bf175f8c5fcd9))

- Remove extra spaces
  ([`0bd6bce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0bd6bce93989b24158df708cb9fa0eca4d7c7ae8))

- Typing and style fixes
  ([`8d09cba`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d09cba419b40548b19a770f8f820ace32a0be5a))

- Typing improvements
  ([`df63dd8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df63dd893219535d072536c361b4759a2a505892))

### Continuous Integration

- Always run extras test job
  ([`4e6d82b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e6d82bd911fea4dfadfce21b59d37b18e6fe606))

- Downgrade extras test to 3.10
  ([`01d75af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/01d75af38d76862df52c836a90572d35e524a299))

- Move sast to own stage
  ([`cc0c28d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc0c28dd3c26abef24cd351d22fc8149f3618842))

- Only automatically run non-3.10 jobs on master
  ([`6529d08`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6529d085b3c225ca6479c9e8ae947d6b666d9302))

- Remove lint:ruff job needs
  ([`f761768`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f7617685df8c27ade768de3f65ab808ac04015bf))

- Run sast ASAP
  ([`e17be2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e17be2b65d58d11c998449b3395736040dcddd13))

- Turn off manual pipelines and ensure everything run on master
  ([`c54c68a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c54c68a13942d3f4369ad9ec6cb3cc7b0afb8f42))

- Use poetry to invoke ruff
  ([`0ee0e72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ee0e72988d0d21f6403c351e20fcb6837a3133e))

### Documentation

- Add docstring for _symbolic_precursors
  ([`2cb6618`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2cb6618c7814c0c6d15d7b29f9145d9e678af587))

- Add docstrings to register getters
  ([`fe89ec3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe89ec315b0c5988758188cf1f37550f31991841))

- Document the algorithm for inferring input/output registers
  ([`4907e8b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4907e8b65d5e2e50d69fa902cad44d1ea1cb709f))

- Fix docstring saying that Wb -> QREF works only for numerics
  ([`7f63a09`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f63a0973ea59c79d98434120a878ee92012b956))

- Fix missing docstring
  ([`84e2e90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/84e2e900671ab59632502c17fb20910353093538))

- Make qubits pull_state doc raw string
  ([`0d42949`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0d42949f830177c8464e8b736286bb0e3d5364df))

### Features

- Add extra step constructing splits and merges for output ports
  ([`7f75e69`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7f75e69615b4eb9ee7c529981114964b9fbef95d))

- Add information about QPU type to QPUDict
  ([`2c10667`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2c1066781527cd7dafc33cd47d6c57dce43b900e))

- Add pull_state() and entangled() to Qubits class
  ([`498f5e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/498f5e0c35bee8fa0deff63f2ab5a6d754d53ae9))

- Catch malformed env vars and add tests
  ([`c743b2d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c743b2da64c7e3fda923fae1867fc1bd3cda0d10))

- Implement initial version of numeric WB -> QREF conversion
  ([`5d29fde`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5d29fde0c29552f6258f2d7b9865be9e82dcb534))

- Implement new algorithm for infering inputs and outputs
  ([`98901e8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98901e8e98af243852c14cb773a87d8f67fe693c))

- Remove reference to env var in (user-facing) C++ error message
  ([`c131cdf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c131cdff29d612c1f91bc44ba0361c558282f4f2))

- Update exception class in test, fix exception hierarchy
  ([`2051300`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20513000b910108115af958ec229140d75a8fb3c))

### Refactoring

- Introduce common base class for numeric and symbolic reg dataclasses
  ([`74d0f94`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/74d0f940360418656e3bda657817bea366e1ef7f))

- Make WB register interface more flexible
  ([`bcb1d7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bcb1d7a49fe26ed2b4f4e89c7fd329f55c2b2a3e))

- Move functionality from source_registers to _precursors
  ([`dc49ed5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc49ed5368ea6ac9da8f3214bb9523a5b4841155))

### Testing

- Refactor tests for symbolics and testing utils
  ([`7226626`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72266265ba952c880777007881494e7c65a0785b))


## v4.18.1 (2025-04-03)

### Bug Fixes

- Add check for same qubits in target and condition
  ([`336d4af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/336d4af8799a236841a2531ea301e26606e110cb))

- Add runtime error
  ([`ba74b99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ba74b999ed8efcbc1ffb4ffacbe441f381c95c08))

- Add test cases per reviewer comments
  ([`440c7bc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/440c7bcbf652eb1e91e30c19ade2dbb95277f24a))

- Add test for cond_reg per reviewer comment
  ([`60c821a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/60c821a9968b89469fb67e1ed0e469b2518ae487))

- Add warning for the case with duplicate args in compute.
  ([`2b0d0dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b0d0dd5b854d8f4bfc61a28509c4c8f530ad616))

- Change to qubits and add error
  ([`505fdb8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/505fdb81c66b85e54feaa77fb3a24258d6ec585f))

- Decouple native serialization code from symbolics module
  ([`944b7a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/944b7a3f4b5adcc22a9d3023d43f2c6d38f824ec))

- Fix bugs in witness and vector tests
  ([`921f74b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/921f74bb90276c4b304a1b6e6cc77701eb77db13))

- Fix construction of random test cases in test_rotation_utils
  ([`a0009af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0009af58e4f1da6ac80fbccb709d298f67c6528))

- Fix copyright notice
  ([`8324198`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8324198b873f95df734eefe380b8d4b15d861517))

- Fix issue in how compute_args are being calculated
  ([`31bd67b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31bd67b5fb3444bdb243abccc1bba53ff0011523))

- Fix native serialization plugin path in setup_legacy.py
  ([`502f0f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/502f0f5b89e1c4db9f62191ec7ba3871dda46c64))

- Fix numeric serialization for deallocated qubits and default args for compute_args
  ([`3942abb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3942abb5c4b0b2a714d67a5302d391e799f7b471))

- Fix numeric serialization test cases once again
  ([`190ccc7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/190ccc72d750391f938276f4bf9f805a9da2b80a))

- Linting
  ([`8952afb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8952afb65bfb76e60941aa00f82856a94c54c9dc))

- Make witness counter (and metrics) work for an empty QPU
  ([`87ee892`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87ee8921933c1586c3ff6419c01901f39a4ff7f6))

- Remove old names
  ([`4b6183e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b6183eb0c28fbb595e3ba6fb227e8903497441a))

- Rename MatrixV2 to Matrix and delete MatrixV1
  ([`8d3b9a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d3b9a2d0f47d238efc25b412022f6e87ac0d51e))

- Rename square_engine_v2 to square_engine and del v1
  ([`b35392d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b35392d5026bde134ad4f84ef4ad6cd1a1d65022))

- Split pages into test and publish
  ([`bf8f80b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bf8f80b816ea764995c41922ea52ad2cc3c784da))

- Treat x_mask and z_mask of ppr as masks in witness counter
  ([`cd801cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd801cd2a07b130753b19bc0f613992535c86a15))

- Typo in quint docs
  ([`51fb9fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51fb9fe9ca92608d8cfd50c903f4b4e6715ce12b))

- Update WitnessCounter demo notebook to match updates signature of metrics()
  ([`55399df`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55399df6258b205683c8900e34488c1db76737d9))

- **cicd**: Step around failing qiskit CICD tests
  ([`10095a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10095a8e7434d1ed95d7b12617770f18442b91c2))

- **deprecate**: Deprecate Grover per #575
  ([`9bb2ed2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bb2ed2ad5266c68f8e05b195f4f4d4d15d3fa9c))

- **MR**: Changes per MR feedback
  ([`f496c19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f496c19b6ed0ad58a8ddd71fb16d684160e39ebf))

- **MR**: Changes per MR feedback
  ([`34154c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/34154c49bbf5a1e31f378681a955116dc948ed74))

- **MR**: Fix examples link per MR feedback
  ([`5534dc6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5534dc66f88bbac7a7afcc818ce74d2479f05977))

- **MR**: Fixes for MR feedback
  ([`5389bc5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5389bc57cc1b0690aabe3d3026f2c39b0122e756))

- **MR**: Rename notebook per MR feedback
  ([`8225867`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8225867b5b80245f2f3d41e0c32973ce07ed799a))

- **op_filter_clifford_qpu.h): Corrected copywrite info text at the top of the file.
  fix(test_958_add_clifford_qpu_gates.py**: Removed logic that triggers the entire python test suite
  and tidied up test code.
  ([`4bb7bff`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4bb7bff11ddf34ccacf3f7b39c4c7b8ae8c2a9f9))

### Build System

- Bound pyliqtr python dependency range and update poetry.lock
  ([`702dd9f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/702dd9f56fc3c194cc9e9c79b492ac53321459f6))

- Replace wildcard dependencies with specific bounds
  ([`6229fb0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6229fb05d39432a4c756da2285b69eed20e12738))

### Chores

- Add dependencies
  ([`9c05b88`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9c05b8839c8d31c25394866d5d763dfbb0ad1240))

- Add more qubits to test
  ([`821c041`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/821c041ee3c280d3d3b2b02165c755d8340f04ea))

- Add skip to pytest
  ([`b62af70`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b62af70c2877ec12860652eac96c1bb4c4932989))

- Add small fixes to make work
  ([`5adf28c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5adf28c91915e4b78ccda3c085638b35480988ea))

- Add some improvements and more tests
  ([`2a84fcd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a84fcd886d1db16028542715f58f130543f0a47))

- Add tests
  ([`483fee9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/483fee9fd8e8c8b5ef03d9b2ef14e93a12b50eac))

- Add uncompute
  ([`118ef58`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/118ef581355a9d5580403c298e50891e678ca1c0))

- Bump version to 4.18.0
  ([`3d7847e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3d7847e7cccc80fac9e71b8640ba308461999448))

- Clean up not used stuff
  ([`091a79e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/091a79ec176ec373a8167d858ab33b9dcc909639))

- Fix stage
  ([`733b267`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/733b267c31c7690b6bf7808bfbdc660845431619))

- Fix tests and add detect entanglement
  ([`aad09b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aad09b7950919460cb845864b7edb9a76484ffef))

- Move import
  ([`7a34091`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a340915217cf44dadb81372af5f445ff89ea7ca))

- Recheck composite tutorial
  ([`6ccaf86`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ccaf86bb2e6f0ea235ea5b47091c8de1aea8d56))

- Remove dependencies
  ([`1ce57ea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1ce57ea9e156d7647b7bf3b6ef4601ffd46c82ff))

- Remove dependencies
  ([`49eca21`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49eca212261a5c4d37a6c35bdc7cf53d250dfab7))

- Remove entanglement and rename MatrixV2 to Matrix
  ([`16822a7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/16822a765e468cb9e73d678343b2a6e9fe37ea5b))

- Remove import
  ([`44c5555`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/44c5555f54836d6b6a5ec3ff43884871b8bc4b89))

- Remove period
  ([`783001b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/783001b7505679348248a1f43f48955ddea55b7e))

- Removed old cruft files
  ([`49fcac0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/49fcac05a67808e5f30218ae854a63361a7b2577))

- Rename qubricks in tests
  ([`4852404`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/485240485ea99fc9af7642a70bb8a874ed0bc080))

### Code Style

- Simplify imports and improve typing
  ([`3c272ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3c272ab41a4860c20124ac76ca77cd54e443e22f))

- Tidy up imports in native.py
  ([`b208156`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b208156929e579828cab10fd5fb336aabcef078f))

### Continuous Integration

- Add CODEOWNERS
  ([`a80466c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a80466c7f7da1398d1188c74ad56abade635b3cf))

- Added directory-specific controls for cpp and cuda
  ([`2b00d0b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b00d0b56dcd05f439a9cfa4d28843909e155ac0))

### Documentation

- **compilation**: Add compilation filter notebook.
  ([`bf93093`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bf93093e5ca67a4cd139ca2239fdc6972482178c))

### Features

- (WIP) add unstable API
  ([`a95db68`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a95db68ab357996c263974ba46a0faa059beb13f))

- [WIP] Add option to turn off warnings
  ([`ab89b02`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab89b026394ba19dfcf62b2d45fc9ebc5b7b4af7))

- [WIP] integrate DI framework with existing tag/interface framework
  ([`ecd8faf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ecd8faf5beaf1cceb079ef3e08ca56647b687fa0))

- Add arithmetic QRE notebook
  ([`187c749`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/187c7492e755be9bd2a52bab8c93e38fb68e07ae))

- Add back used QPU aliases
  ([`f5adeea`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f5adeea405b51bf884619c7598cd2d933bb120a1))

- Add Cassandra's demo directly
  ([`2f394ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f394ac491e1bcf516503ccfcc87207a641f1930))

- Add DI framework notebook
  ([`ea19b01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea19b019c43f170dafad2b6f900362d91df8fb6c))

- Add initial implementation of serializing resources for numerical QPUs
  ([`8eb665f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8eb665fe63a7034a57925b74b6b802589e74d38c))

- Add numeric primer tutorial
  ([`e4e906b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e4e906b981ddd3647c09389f437ea246760d8525))

- Add push_state method to Qubits class
  ([`cb2e34c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cb2e34c7c1a0b19a7eb018d5ecdd03043a28635f))

- Add rudimentary save/load functionality
  ([`c7ed03d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7ed03d4f72571e746462846877a0af898858eab))

- Add support for Qubrick specification via dicts
  ([`bef603c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bef603cbff5b026a398d17165e9d2236099858db))

- Add symlinks
  ([`df002e6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df002e6b8252df1d7f45ead8a04f2ac321d9e9b5))

- Add utility functions for use with numeric serialization
  ([`46250de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/46250de4aa863c659a6491eea2f81ef1d0fb32d6))

- Address reviewer comments
  ([`c916cc9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c916cc9c34ffff0ed87f676f378e34bcc4382d33))

- Address reviewer comments and lint
  ([`a0300e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0300e99865067a055179d0df21f07bc01265139))

- Address reviewer comments, update symlinks
  ([`5ab98ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5ab98ca0dfb3cbdb3db0e4cf8095307ea6ceac91))

- Change private QPU methods to use underscores
  ([`e96c632`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e96c632224554bf1797d0ee568f22a3fda78e618))

- Defined api for qubits and qubrick, removed old unused functionality in qubrick
  ([`b389bcc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b389bccd86aedbbd0eedd7dc0ffeedf0c2223564))

- Expand DI tests
  ([`b0c6312`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b0c6312f6421124659ed97d00fe096579de37644))

- Expand test coverage
  ([`33b83cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/33b83ccffa9fade19b68f4536fe8eb21a251fcc0))

- Fix one missed API
  ([`6ac7387`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ac73871a7ae970ae6b0a660bd2efbd2a6db7d39))

- Fix singledispatch typing
  ([`7aba915`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7aba915a991e0f7ac33a045c0e03d987be7c3dac))

- Fix the linting
  ([`2396d8e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2396d8e3737e2b526baeea3f48b1ebf6aa80c10d))

- Fix type check to get tests passing
  ([`025811b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/025811b6a5f1ef119ed931fd167b35e55d93bd01))

- Fix warnings filter test
  ([`35ed057`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35ed05753b0dc5043214820a02112aeee38b3320))

- Flag symbolic, baseline arch and counters as unstable
  ([`a74992e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a74992e172993867826a4437f9623f55a1dd0516))

- Implement native numeric serialization for PPMs and PPRs
  ([`5cd0f3c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5cd0f3c34bd1d90389758584940d1b9787912694))

- Lint fixes
  ([`673410a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/673410addc17dbbe20fc2c70e96c86812b12ab20))

- Remove dead code, add functools wraps
  ([`4ba362a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ba362aa788797772523a6a1ccd9a2672d25f1f2))

- Remove standard gate counter and AV counter
  ([`e01b524`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e01b524f4982d8f92f71fdea938466e2f828c535))

- Remove unused aliases and deprecate cnot/cz for now
  ([`2b4ad51`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b4ad51550edb8f97974168d39961de2bbb42ee7))

- Remove unused symbolic cost helpers function
  ([`bd0ff60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd0ff601e3e289336841c4d34011e89fcc9684a1))

- Rename numeric QRE notebook
  ([`636dab1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/636dab1bb4b9ca26e0a3836b9c2bbeebbdcfedc5))

- Revert fail tests on warn
  ([`d4489de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4489de2b8a0b630cc4ed4e5a50d83eb201926e7))

- Update DI controller to support non-optional arguments
  ([`32fae48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/32fae4833613366fda79cf4f7163e7213953e745))

- Update DI demo notebook
  ([`a497e21`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a497e21ebf90d8bd41985bd266712c546b8f8d5a))

- Update documentation
  ([`ab8cb27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ab8cb2728e475ce95d0c21c165e1ba31c2afb647))

- Update framework to accept lists for registration
  ([`e47eaad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e47eaad14932da34d3a6fefb126c803ef21d6e89))

- Update mkdocs.yml
  ([`146dbd8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/146dbd808e2da9d841f6d587371c5dcb4374067a))

- Update qiskit and qasm tests to not use old API
  ([`1c34bfa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c34bfaf1906f3bddf87b131359e056f8e4d1b0a))

- Update sym link to docs for tutorial
  ([`e5f4f5d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5f4f5da455d22a7e10dffe0339f7551c12c9e47))

- Update test to remove check for failure on warn
  ([`106455d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/106455de0603d5849ec1a42b52c5d91f67c8bac7))

- Update tests to not use old API
  ([`b18730c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b18730c423eb58cae233df6a15197a83d1476c19))

- Update tutorial to not use old API
  ([`8b1932d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8b1932d9805132a3016f54bbac7f613d61ca31ca))

- Update unstable decorator to handle classes properly
  ([`95b64dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95b64dd19bdc9974acbd41069a51a2ebd9737ae1))

- Update warning message and add docstring
  ([`8ae5b38`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8ae5b381dad24699c9ccf39caae10bb1375be1c2))

- Update witness demo notebooks to no longer use standard AV counter
  ([`a0d95e4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0d95e42765b41e21268d7b6f37b2ae9050f8593))

- WIP add arithmetic tutorial notebook
  ([`818fe60`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/818fe60d97abb58fc0d157d01794b8520b178735))

- Workaround for python 3.10 typing
  ([`f989d2c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f989d2c23318598a1572b90fde194c1abec9b2e2))

- **op_filter_clifford_qpu.h, test_958_add_clifford_qpu_gates.py**: Added control handling for Z
  gates in CliffordQPU. Also added a test to check it works.
  ([`a044463`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a0444633d0142aa20689b4a12759034c1122f8be))

- **tutorial**: Add simulation notebook per #964
  ([`0591684`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/05916841dcff929e6baeb621bb4940be9719e66b))

### Refactoring

- Get rid of invert in QFT
  ([`75edcd1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75edcd15567369ce96ce9fc4fe6fa86a45a90532))

- Make some functions in witness_counter public
  ([`55b725c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55b725c2bcc84dc243af0b9566363d2e02ec529d))

- Minor logic simplification
  ([`17ac7bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/17ac7bb29cf36a8fe1375031210b0f6aa70a0ed9))

- Simplify how the cost format is determined
  ([`8a3bc6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a3bc6ec8ad4ca7b605ad34841f95c0a7ca34b54))

### Testing

- Add (currently failing) test cases for witness counter PPR problem
  ([`5dd97f6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5dd97f68c49161d690a1cf4c79f7e3976a7d3fad))

- Add test case for serializing PPRs and PPMs
  ([`f56fcd1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f56fcd1c8118c8afd399ad7a1bfe9f66b157154e))

- Add test for serialization of program with deallocation
  ([`df0b7e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df0b7e195b541bd000718a78126213e370e021bd))

- Fix some numeric serialization test cases
  ([`89e81ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/89e81ecb1c27f8b150a29b3769ea9e23933478aa))


## v4.18.0 (2025-03-25)

### Bug Fixes

- Update av calculation for symbolics
  ([`dbcde27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dbcde279208171d08c7bcd13f4b54964feb8a946))

- **merge**: Adapt optimization to new witness counter
  ([`22efe4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/22efe4eefae9f030bbc59ad88c0c8dd875caf07c))

- **merge**: Another fix to the very complicated merge
  ([`16c62ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/16c62eebeca56fabf1166b9edb4b34025d228956))

- **merge**: Minor fixes and cleanups
  ([`193c3dd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/193c3dd252b51dc7fb46775881cce82188d16503))

- **merge**: More merge fixes for #767
  ([`acfa8a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/acfa8a8d99c62f056e66a3626a3bde1dc505cb69))

- **merge**: Working on merge for #767
  ([`08cb21e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08cb21ef39d32adf83cf672ac727b2b20325c88a))

- **MR**: Changes per MR feedback
  ([`d16d232`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d16d232ce12a2f76bde0c8857b21edac916c3abf))

### Build System

- Fix python dependency range
  ([`4c16462`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c16462ace113d3e7cdba6a86bc692ded072e08d))

- Updated poetry.lock
  ([`db49bb2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/db49bb23a7a31ee89981d7086857c960a31e08c6))

- Updated pyproject.toml to adhere to linting requirements
  ([`187e2c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/187e2c2c4c1bbb16e8fda91665bccfc5f9df7251))

### Chores

- Bump version to 4.17.0
  ([`3da18b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3da18b440f1f547c8374f3148c5bfbcfb01cc59a))

- Update bartiq version
  ([`a19f0ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a19f0aeaea21b63815d6dd418e6ce07c53336401))

### Continuous Integration

- Adopt common ci jobs
  ([`4601468`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4601468101985c52a48a91bc84ffeefdd01fc090))

- Refactored linting jobs
  ([`d7d803b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d7d803b788dc23d2385228fcf9aa73aaf46554fe))

- Require lint:ruff to pass
  ([`edcc178`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/edcc17818d88e126541428aa07fa9a8966f15c0d))

### Documentation

- Fix CR headers
  ([`2a37f04`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2a37f0415689fe17b1292382dbb35139a94b2afa))

### Features

- **loops**: Add repeats to witness counter for #767
  ([`03e82ac`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/03e82acff395147c2642eb4b52cb5d86b8902a3f))

- **repeat**: First pass of #767 using jumps for qubrick repetition
  ([`da68cc4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/da68cc4f68a34e0c8a57ca65933a28f1284c1c1a))

### Performance Improvements

- **loops**: First pass at the real optimization for #767
  ([`d5145b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d5145b8333676c73cb42e7bc50635a46791afc74))

- **ops**: Optimize conversion of oy ops to cpp, per #959
  ([`2095680`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/20956804d2bbaf96f92cf72f9a976cfd1ccba8b4))


## v4.17.0 (2025-03-25)

### Bug Fixes

- Add fixes to ensure backward compatibility
  ([`f94d3f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f94d3f47b949242f15676694a2456b06f6550dbe))

- Add friendliness features to box and filters
  ([`23614e9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/23614e925c42746cc0488a8ef58fbf9f6a6ca00d))

- Add logic disallowing release of vector register slices
  ([`e38efad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e38efad5ce89aa33c51db2c03dfb2b05b769239d))

- Bump copyright hook version.
  ([`8d8bb48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8d8bb48a0891c4c1f992287d74ea2de2c582c8fb))

- Convert assert statement into proper exception raising
  ([`be57fb1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/be57fb14a93233923491942e3844c99742bc0706))

- Correctly account for the case where bit_size is a sequence
  ([`3cd91eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3cd91eb4b8b86c1e8012cbf7a2f21d8e95127418))

- Correctly set name of sliced vector register
  ([`c228adb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c228adb1e4f4f4d869337635beff17a55a6f494d))

- Enable concatenation of symbolic qubits with vector registers
  ([`41a6177`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41a6177abc83e9cfd2669da4d2c28c369a75b7c9))

- Fix >>unitary>> filter and update tests
  ([`5e7b7f8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5e7b7f8d352a59da1ab68dd3cd9f9ec9ae5e9002))

- Fix melting of composite registers (and corresponding test cases)
  ([`f4962e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f4962e5cef13b9396d06c4c740bc5f4a3c0a026b))

- Fix naming of vector register-related classes
  ([`63c17c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63c17c9e109b578942611f547b9fe546eee5ddb8))

- Fix notebook
  ([`790581d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/790581d8f633459865634bf94974f23d76ce9368))

- Fix return type in VectorRegister.__getitem__
  ([`068f39f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/068f39f739e15d84f93e94e8ecfb4c51f2aa9eff))

- Fix slicing of SymbolicVectorRegister
  ([`6842337`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6842337074f0e59fc1c0e8b9cdaf62ff2eba63eb))

- Fix test for vector register
  ([`2ecb407`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2ecb407e5ceabbd296566f69d6b6b4bb21c2f867))

- Fix typing related to QPUType
  ([`54ded6a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54ded6a53190714cc463c155804775ba47118c26))

- Fix typo and reword error message in SymbolicVectorRegister initializer
  ([`36f3a19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/36f3a19efdc319f4a7155d95c7a0c7f931a2f533))

- Fixes for vector registers
  ([`efea38c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/efea38c565f9638eca420568923ce5b6149ccba7))

- Improve handling of slice assignment
  ([`08430fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08430fecd920fd3f6b9f5157ac306363c2bdb401))

- Make _list_to_mask compatible with VectorRegister
  ([`25734c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25734c75d7c2bb8de3a9168a932b1fb40b8db02e))

- Make `mask` method of vector register conform to BaseQubits.mask interface
  ([`e045b75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e045b7551717a0c81a40a503381d67ca7159d5e4))

- Make inplace addition and subtraction work for iterables of ints
  ([`f952444`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f952444431e136761326e5b6075b5ccdbc1acb10))

- Make Qubits.__or__ work with VectorRegister
  ([`5742154`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/57421545f149fd9ff781d88955b1f893ab56f1bc))

- Make single dispatch methods in VectorRegister compatible with Python 3.10
  ([`61acbeb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/61acbeb459b192c60c23457b343de6315fa1b752))

- Make VectorRegister.is_allocated work reliably
  ([`826eb3b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/826eb3bf15a7e93c33d81b2d31f2254faae2ecae))

- Make VectorRegister.swap work with vector registers as targets
  ([`1216ab6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1216ab64f0d314e100a20951a17bbda74303ff79))

- Missing import
  ([`2d7d78e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d7d78e351b47b1f66da1239a539fe145486d240))

- Remove pytest as dependency
  ([`c5a7e2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5a7e2f67ff703dd78c560e16c674654d02f8047))

- Track allocation ownership when constructing SymbolicVectorRegister from bitsizes
  ([`7753fe0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7753fe0f3d10fd6d7c8daec2bb434be9539c95f3))

- Track atomic parameters used for constructing SymbolicVectorRegister
  ([`0675ed5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0675ed5f924601f6dd374337f15cc2ff55bac15f))

- Update composite register after __setitem__ call
  ([`726f163`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/726f163a4ac8c0cf8f484291f33e4fad7ea21b53))

- Updated old .lan URLs for new repo path
  ([`5855c3e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5855c3e457329939c7d7522494d25530e51633e0))

- **cicd**: Disable WBA to see what else fails
  ([`1a8e796`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a8e79699e5a3a78e2917ffda0f647a308e86878))

- **cicd**: Fix antlr4 import check
  ([`a413197`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a41319704a7575b0217c033bc2f7c7929d935e7d))

- **cicd**: Fix capitalization of pyLIQTR
  ([`0414142`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0414142b2423f4c2470e89d6ba07c62097e13a09))

- **cicd**: Fixes to import checks for #954
  ([`b956baf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b956bafb0f25697a6a6425d1cfab34aa3d4a443a))

- **cicd**: Remove internal extras, leave externals
  ([`c73eedd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c73eeddb88d174001ea51a80c4cd829004c78d55))

- **cicd**: Remove unused darpa target, install extras
  ([`ac15cd1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ac15cd1876a116697fb395d90608a7c7fed8ffad))

- **cicd**: Test extras on latest
  ([`3238caf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3238cafa4695e2f74ca4d1af19bf139b55e0c8a1))

- **cicd**: Verify that extras are installed, per #954
  ([`3087420`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30874205dcc257394a584d5491afe40da6742c09))

- **CR**: Fixed missed .cpp, .h, and .sh copyright headers
  ([`596f83a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/596f83aea7180dc7d26e9ec2a117810853424c9b))

- **MR**: Comment added per MR
  ([`ce6990c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce6990c794566bc9e24558a405d0ce67454ce694))

- **MR**: Fix per MR feedback
  ([`da4b8c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/da4b8c35e6d5370a291dc7c96fbc9ad883a58768))

- **qubitmask**: Fix for an issue in #945 where numpy contaminates `int` variables into `np.int64`
  ([`fb5e538`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb5e538e77829cde2f19d9b5313fadcce7626f7d))

- **security**: Medium security items per #709
  ([`f84e735`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f84e7355a0ccd52cc38c8477ebb6b1d400e7c7a3))

- **security**: Remediate some vulnerabilities per #709
  ([`edcc2f5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/edcc2f53f9a6f48c9b92312b372bb2615dbc170b))

- **test**: Fix test #771 by removing rs-synth
  ([`9b76b8a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9b76b8a8a631042f23ca5db0d76eff422b53876a))

- **witness**: Witness counter isn't working with RS synthesis yet, so remove the rs-synth filter
  ([`0340b50`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0340b500ff674a7771d2956a5532de61e57c4f5f))

### Build System

- Added pre-commit config for CR notice linting
  ([`2ae7ae6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2ae7ae66abbe35f909d9264258c4710bd917cb3c))

### Chores

- Bump version to 4.16.1
  ([`19f2577`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/19f25774b1cc908fe0f5e9121a1ecb613d7cc189))

- Fix kernel
  ([`f4b9495`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f4b9495c447ffa71294e37b8997356cc7bd74ef2))

- Fix kernel
  ([`e063bfc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e063bfc2a2d03fd1d1ef4cd62d471d7a2b2f5ccd))

- Fix kernel
  ([`d7a1cd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d7a1cd2e23f8df313390d9382760f0d71a902edd))

- Fix toc in multiple ipynb
  ([`95db22e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/95db22e5d36ce24855808e6dbd159f3acb777e17))

- Remove Notebook prefix from notebooks
  ([`55aeaf3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55aeaf3fc31f0d6d729f1f702d1fa693389e42d3))

- Remove pytest
  ([`7dcd68e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7dcd68e12bf15a8c65cf47e45ab1a2f7abf6e703))

- Style and minor typo fixes
  ([`94e2780`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/94e2780a4b6845d84aab40555d0723bf26782a9b))

- Update bartiq version
  ([`6f16538`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f16538cdc2ec59014dec9d8942572a87865fdd7))

- Update dependency on bartiq
  ([`5573dd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5573dd2ef57882b3c20e6565ad07b1cd6935fc65))

### Code Style

- Adressed @sgreenaway's comments
  ([`83c2319`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/83c2319c946541f868420024adc7eb70698fd333))

- Make method names more readable
  ([`e91af85`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e91af853bda9944929ab711b51dcad95701d5c74))

- Minor formatting and style fixes
  ([`45e195f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45e195f1c907464d27811efcbaf55c1e19fa4df1))

- Minor refactor of vector registers
  ([`29cf3b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/29cf3b674cc7e75d0a67a4756cd1a8127ad90d88))

- Remove unnecessary backticks
  ([`d7c25cc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d7c25cc5cd3b6589503538194516a48ce89a3e52))

- Sorted .gitignore
  ([`2845419`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2845419b7aecc4efefcebc084778adba8c47e8bd))

### Documentation

- Add missing operations
  ([`52469fb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/52469fba8ba2fdffe1ea6cffb63e20920db3735a))

- Added CR notices
  ([`1c3c600`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c3c600393f09dabac9d24775c5a030030d755b8))

- Removed ruff format section of README
  ([`80e9b0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/80e9b0e3ed3af26aa0904b69cb5c8cb14b3d0d91))

- Update CR headers to conform to standard
  ([`1e86d4f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1e86d4fd3652ed9b3c2395281a2536d3e69ec2da))

- Update docs of VectorRegisterSymbolic
  ([`df052b8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df052b8d17fb86147cf103be93b49a39fc82cce9))

- Update vector register example notebook
  ([`4a5e4a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4a5e4a83fd6b8f9b0546d9ebed82cc89dcd15096))

- **readme**: Added section on conv commits
  ([`5c50ae6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c50ae65ef3e04e2d6d8da2a7bd8860e227bebd9))

- **readme**: Linted
  ([`a62f647`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a62f6474959a57f6e91d5f68b617fa5c87427fea))

- **readme**: Update developer guide
  ([`f9d9c91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9d9c91f55c2a20fe02046f97144cf0e8e454fde))

### Features

- (WIP) VectorRegisterSymbolic
  ([`677db76`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/677db769197b2ad47b1976c2bca68f2430bc12e9))

- (WIP) VectorRegisterSymbolic tests
  ([`637d97a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/637d97a1a88db327d4a89f9a424f6508ab42361d))

- Add allocation ownership tracking to SymbolicVectorRegister
  ([`242be78`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/242be78df09bcec1c16dddf02a449cecd704bcc8))

- Add index property to SymbolicVectorRegister
  ([`134c324`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/134c32448f0080d61a50b293634923c7426d05f2))

- Add index property to VectorRegister
  ([`f1a2876`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f1a2876c369b21af08fd914bb7a6b6d5c620e0dd))

- Add missing methods from BaseQubits interface to SymbolicVectorRegister
  ([`71f4aa3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71f4aa35f403dee29aadc6417f70bb2ee3710557))

- Add search bar to offline docs
  ([`f58da7a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f58da7aca1c693ef9af511579a7ced1716181ebd))

- Cache composite_reg in VectorRegister
  ([`92d0929`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/92d0929aa0f78e619b93623ddc96a211efb573a1))

- Fix test for VectorRegisterSymbolic
  ([`4c8f494`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4c8f49472b36392778e75eaab56ca3bd40d2afc9))

- VectorRegisterSymbolic
  ([`8bb7f8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8bb7f8fde36a036aca63b543414a52a21c80d2b8))

- VectorRegisterSymbolic (address @sgreenaway's comments)
  ([`5aaf1c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5aaf1c56dfc0d85ba35ca967a5faa62e4c5595c7))

- **py3.13**: Add py 3.13 to CICD per #809
  ([`1dbf34f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1dbf34fc7b135bde658306a72af44e1f9fd1cb0f))

### Refactoring

- Add qubits_type to VectorRegister
  ([`45c7b7e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45c7b7e1d0baea805ba28a39c968cf7e6e51bff9))

- Move some attributes of vector register to properties
  ([`7c6f3ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7c6f3ef4447ff8fbc8d481ec3d6b4a46e7ed441e))

- Refactor VectorRegister and its symbolic counterpart
  ([`e26414c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e26414c606dd9562b9b1d3017a9d2128e7f20522))

- Use single vector register type instead of separate classes for numerics and symbolics
  ([`c95cae0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c95cae0a7d630fc5d5ed613b45b1717cb983cb55))

- Use singledispatchmethod for different cases in BaseVectorRegister.__setitem__
  ([`239b405`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/239b40500f328befedd5fe4b2907e878a7ef7191))

### Testing

- Add tests for manually constructed VectorRegister
  ([`a6625d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6625d24df3c5f0d33ca2beb83cca2fc202d9ad8))

- Add VectorRegister tests
  ([`77d515b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/77d515b20fa988acdbb4bda028a1f8f872b22627))

- Clean up masks used in vector register tests
  ([`87a9827`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/87a9827952a67832896828849bb510c7ae28b11c))

- Consolidate tests for all flavors of vector registers
  ([`df90868`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/df9086828053429471350b650f6782a77669d7d5))

- Move test utilities to test_helpers module
  ([`38d815b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38d815b6fdfd7461fa5b0e57862adae266dd1ccc))

- Remove obsolete test
  ([`71cd04c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71cd04ced73167d2a3bdf5fc5f13c93ef055c6aa))

- Remove unnecesary 64 bit filter
  ([`99db54b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/99db54bb9be86be848ba8973a27e242a3160102a))

- Rename numeric_qpu helper function to bit_qpu
  ([`fcf7cd8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fcf7cd864205b01a41f4ba59d769df6616f4c594))

- Skip some vector register tests if Bartiq is not installed
  ([`9309c84`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9309c84f58e284f082933962188e8b9fbcbe24fe))

- **change**: Added a test for #945
  ([`704849e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/704849e189216724091bfc14818c339030462a1a))

- **extras**: Check to see if extra libs ever get used
  ([`5407157`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54071571d7c636f6fe2b2086e7f13edf59c68cd5))

- **extras**: Remove test for extra installs, as it's not part of this change
  ([`f47fc2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f47fc2faa682e64e7f70aae28dc413eea4293e7c))


## v4.16.1 (2025-03-12)

### Bug Fixes

- Ammend bumpversion cicd commit message
  ([`72e3d16`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/72e3d16b3151e1faa56002654eb2fe45d3946818))

- **witness_metrics_functions.py**: Mult by num repetitions for AV
  ([`795ede8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/795ede8d86bae0c67161d6fe9f4f284f7b7fd341))

### Chores

- Attempt to fix yaml complaint
  ([`09f6d83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09f6d837765ff2f88994dedf53c1bd6cf698b8d0))

- Attempt to fix yaml round 2
  ([`ed87b05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ed87b0580df76cb31d6dff5e39f11f35967f21bd))


## v4.16.0 (2025-03-11)

### Bug Fixes

- Corrected bad pages URL in xv_utils.py
  ([`f40c4b6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f40c4b615fea72a550313d8bfdfe5105ead99b80))

- Fix == for Parameter
  ([`b62d799`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b62d799d4aa2c77204a2912c2b4481d27196d35d))

- Fixed symbolic log function
  ([`81a9304`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/81a9304a8eaf08d85b7b53a72cc1c40e7a051095))

- Modified log function to use custom log2 and log10 functions for those bases.
  ([`c9ac16e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c9ac16e2d474aa2af74866f6d0c8af8321679008))

- Old arch URL
  ([`4e13591`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e1359120fb72a49bef79049310943717d5573f6))

- Reinstantiated _condition_deprecation_warning
  ([`0a80b9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a80b9d8b28ad5367ee8afc8b82623114bdf8781))

- Updated references for new repo paths
  ([`b5d9f6b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b5d9f6b774c413441dec4f9271267178d8a2779c))

- **docs**: Fix documentation link after repo migration #937
  ([`c3380ab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c3380abfd514c3aeffe8dee8952abab665d45eed))

### Chores

- Linting
  ([`733c15e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/733c15e31bb0559e9f70a9c9f24f48ffd2948adf))

- Remove commented code
  ([`2f94fd0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2f94fd06d2374dadc81a43833288327259b509a5))

### Continuous Integration

- Avoid annoying emojis in slack notifications
  ([`885be15`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/885be1528859eb6c5de0b434dda94b423f099065))

- Remove pauli docs deployment jobs
  ([`a741120`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a741120b953f6edb8762caea4e2668a9503a5d2c))

### Features

- Add adder typing
  ([`2bc7b7d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2bc7b7d71dcfb0f4b868d767378a89e50cc5845c))

- Add demo notebook for tags and Qubrick registration
  ([`6a74eec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6a74eec0f16add70ff0a9d8abc94b374fa817482))

- Add tagging and qubrick registration functionality
  ([`9228fb1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9228fb1a96f7fe5d4067764cfdd6a9d2f3049821))

- Add test for generic adders
  ([`dc92ded`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc92ded4ed90a761ba19bd2a4d4aecee700232c5))

- Added blackbox AV test
  ([`4f796f3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4f796f3f3d8e5bcce1aa32de8e23ee3883db3757))

- Expand tagging functionality
  ([`6f906b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6f906b4ba5e3f056755dc587ad40446248f7a718))

- Expand testing
  ([`aa67fdb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa67fdb4bbe20780b7467d976828f4ac65e2b1c2))

- Fix for Generics interface in python 3.10
  ([`ee961b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ee961b4b059edae6a5d71f1315ac97572d5114e2))

- Fix measurement bug causing WBA tests to fail
  ([`f3ab6c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3ab6c32d53bbd5bdfec32d9f69ce79f12793da1))

- Fix test and linting
  ([`ff00c9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff00c9d3514b7e00ce376139b086762cdf8a3227))

- Fix tutorials, lint and fix PPO issue
  ([`eba36b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/eba36b7e4fa0ea649ca8cfcdd0ba0da81e75816a))

- Improve performance by using defaultdict instead of dict
  ([`353c2db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/353c2db87286a324244c0cb0d72829953eb3f2fc))

- Linting and moving tutorial to docs tutorials
  ([`504c0bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/504c0bd50881b0ca1a0e1fd396dc546167cee404))

- Made changes to metrics functions
  ([`c2d14c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c2d14c5aacc925b35290289da617ec455aecd44e))

- More tests, update demo notebook
  ([`c1c3cee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c1c3cee2cc63039be07f03be5e196057a41c045a))

- Re-add buffer to notebook
  ([`cd60cd2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd60cd2a8023bb75e583331dc2a72a4ed7615a63))

- Re-organize cost functions, allow custom cost functions to be passed
  ([`46792a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/46792a8a8f8eaa160c215ec0cd70d9f7caddd6bb))

- Remove symbolic_metrics=True kwargs from metrics calls
  ([`2b0d846`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2b0d846b434b6381381163c9a7dc8a3ac59b6c51))

- Respond to reviewer comments
  ([`30da84e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/30da84ef1d6c397783e17af069b0f1f4bb167f02))

- Restructure tags and add unit tests
  ([`2dcd639`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2dcd63964c9c8245e0a60182a8c19920f6005202))

- Speed up runtime by deferring witness build until qc.metrics is called
  ([`d7fa957`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d7fa957ba6878d8fb15761de62a93aab615868c2))

- Support more robust aliasing for rotation args in metrics functions
  ([`d6759a6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d6759a68e4314e91fbf078f741dd1667cbf5abb3))

- Update demo notebook
  ([`f821b27`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f821b274bb0ed845b10d23d124bdeef44a682f41))

- Update generic adder qubrick tests
  ([`6ad9d3a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ad9d3a210809d7cdc1fb960a38ab63e73c55819))

- Update interface for metrics calls
  ([`bc033b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bc033b7cdf20f73291430d95f2f2931c528efacf))

- Update metrics to point to new witness counter
  ([`c8c7f5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c8c7f5be6c0c2a25ba588164e2ab64ce1657b511))

- Update PPR calculation
  ([`7042b85`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7042b850cf008149e7d57b007d3a439423889e0d))

### Refactoring

- Decouple symbolic and numeric code in qubricks
  ([`b0da7aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b0da7aa038e39bc54a078c5feb646df24b806971))

- Minor changes
  ([`06e6a7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/06e6a7c60603cc6cafc3648b0e2b2f2ee84f7180))


## v4.15.0 (2025-02-25)

### Bug Fixes

- Fix creation of multiple issue labels
  ([`08498eb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/08498ebadc1b7703627185decc26bbd5ef51d3ec))

### Chores

- Add private notebooks
  ([`b2cf304`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2cf304baaf59fbd857f6ab66e3940036946f5f9))

- Bump version to 4.14.0
  ([`45f174b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/45f174bf679b9ac0465535a85625c36993cbf6c6))

- Fix AV calculation for symbolic Qubricks
  ([`f8a4a01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8a4a01ad10abc0250b766a956db24d428a25650))

- Fix deprecated link/statement
  ([`586bd46`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/586bd460596a775eaa20c5f5d4136417bc9cb202))

- Fix index and getting_started md
  ([`96da63c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/96da63ca7c3ae1f0e5087b8ea5df8ba45808dd3f))

- Fix index.md
  ([`4b4a76c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b4a76c2536537dd7cef2028cc301190eaf8e246))

- Fix symbolic links
  ([`abbaf51`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/abbaf5184f46da7b878a333ac223aa9fde0cda4e))

- Fix wording in index.md
  ([`d48876e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d48876eaef8bf5194b6c21c90f67311061ed67fe))

- Move AV calculation to Bartiq post-processing
  ([`8811fab`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8811fab51e30aa0423feeb45c62438a0c40e4133))

- Reword older statement
  ([`422190a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/422190af6ca0a3a1360f86d17cc1dae2028b864a))

- Small fixes for mkdocs
  ([`7a849ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7a849ada4569e97b8a53575a5f1ae027158dc3cf))

- Various small fixes
  ([`cae0b9d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cae0b9d60f5dc0b1e9d7732526e01d3b326cfdca))

### Code Style

- Linted .gitlab-ci.yml
  ([`6668a39`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6668a39845818fb9c88578feaa5ed23d7802a7ce))

- Update imports
  ([`ddf4751`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ddf4751165a1dbd1a07503671f060feef7dca2c8))

### Continuous Integration

- Added slackbot notification for failures on scheduled pipelines
  ([`e59c3b7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e59c3b77b9e4262a99086329ab56a3fd45ff392d))

- Added variable for testing latest
  ([`75e4f37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75e4f375d7fec325592c05818a466dbfe10957cc))

- Updated gitlab-ci.yml
  ([`692c223`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/692c223d01bf862893ccffa64d505b404e354ad0))

### Documentation

- Rearrange mkdocs structure
  ([`642f270`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/642f270e1cc50336de057a5d4da265104a9b4a07))


## v4.14.0 (2025-02-21)

### Bug Fixes

- (WIP) ctrl logic SymbolicQPU
  ([`cf3a332`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cf3a3326b4a2d7b30db97909fa22b69526c936ca))

- Add estimate variable
  ([`6fea366`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6fea366f37c7d0c98e0b73f8c570cd4dc37c4908))

- Add estimate variable
  ([`647d486`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/647d4864a0db8f1ac061d9d54d7e5c4d8ca74529))

- Add failing test
  ([`cd53452`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cd53452ddd568721eca9ed20d772234de3312936))

- Add issue number to pytest skip
  ([`b2bbf46`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2bbf46e791178867e857e4bebae078109a7ec63))

- Address reviewer comment for clean ladder qbk
  ([`c5e3e1c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5e3e1c0f290f4f18411204f6a30bd9a7003633b))

- Avoid circular import
  ([`0a7d493`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0a7d493ce5f480f274c731a34c2e291ec44c3c33))

- Ctrl logic for SymbolicQPU
  ([`bdd775b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bdd775bf5fac31b8216598fc2441bdc017f8f450))

- Fix assertion to reflect change in register size
  ([`b61ef90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b61ef90329055ad0273cd017803f761033bce38c))

- Fix deprecation warning in qpu classes
  ([`dfae974`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dfae97460e9d791bd63c765ecfb51e4ec6e76b16))

- Fix PPR lookup and demo notebook
  ([`312fc0e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/312fc0e9f362922fd5e87761eaed9ada4fe19ca3))

- Fix symbolic av calculation
  ([`a60d293`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a60d2933104f336e6486293e06afbcecb8a89930))

- Fix test
  ([`c7c06a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c7c06a809cea5a6ee461dffc5ab55ae5ed00bcf5))

- Fixed circular import
  ([`269049c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/269049cfe9a50e12dc89d6f65562f04ff3eb47f7))

- Misc errors
  ([`329ef2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/329ef2a6987ceee4cd1cd5bd78a64a0582c732b3))

- Not sure why I need to commit?
  ([`37fd829`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/37fd829578efb82aadb54224aaf46a3d49d7d4a3))

- Properly connect children with through ports in repetition wrapper
  ([`3a57998`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a57998c063b917abca7541bc2b31fabcb3ccd14))

- Removing some files to make MR smaller and moved to a different MR
  ([`903fb42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/903fb42dcc4589a6da451be893c396f11de90fff))

- Removing some files to make MR smaller and moved to a different MR
  ([`056a9f9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/056a9f90a9fb82889a7dca08075648e829a87a9f))

- Simplify logic
  ([`10392bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10392bd78e839ea846114ab9dc317e08f19a251e))

- Update imports in the other CC example notebook
  ([`38d784c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38d784c1aca725f80cfb8f6a805af6baba374f10))

- Various changes related to symbolic filters refactor
  ([`ca5d4fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca5d4fe3ca6811b40f5c2c8e893285390d60ea07))

- **active_volume_lookup.py**: Error in T count
  ([`e13ab90`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e13ab901a7e62388ff8bd5f3ddf4cdbc8742698d))

- **active_volume_lookup.py**: Fix docs for PPR AV function
  ([`3fc0e1f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3fc0e1f3911913c257edc8da5b906cd114d9003f))

- **costs**: Costs events fix for #916
  ([`ac96efc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ac96efc61dd1679eb905d3dd65532f298ad66e12))

- **lint**: All ruff issues fixed
  ([`101bf56`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/101bf5668196e5e94f59fb7fe27ad3ce59d3c7d2))

- **MR**: Fixes per MR feedback
  ([`31e5138`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/31e51380f6aff7f4306c272ed6b60f0ce4d0cd52))

- **poetry.lock**: Revert to master version
  ([`675a42a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/675a42a205183aa47f634da6b681b4a2b8bf85f3))

- **poetry.lock**: Revert to master version again
  ([`122735d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/122735d8fc1f8778e505108d34b89956f094ef7b))

- **qasm3_export.py**: Unique qubit allocations
  ([`10e5e48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/10e5e4840b42c96b91b1d55bcb3166faa11972cb))

- **qiskit_qpu.py**: Don't declare helper functions when qiskit isn't imported
  ([`8af4f4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8af4f4e168c38234af01dc0f158b094e3857702f))

- **qiskit_qpu.py**: Move import to top and docstring improvements
  ([`9291cee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9291cee2d2a2a8c4c5bd971360b72325420a0f93))

- **ruff**: Semicolons and == None
  ([`a8da2ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a8da2adb68069d858cc2a3acdbdedb43c3930713))

- **test**: Fixed a test which was using 3.5 GB of RAM by mistake
  ([`9e91b99`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e91b9931a6ee57db0f5a024cfd909126a6f1ec1))

- **test**: Fixes to the custom uncompute test for #916
  ([`c916526`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c91652659d17cdea8dd9379e16d992c05035aba6))

- **test_861**: Assert allclose instead of 1 for fidelity
  ([`27aece2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27aece283b6f0066f9896593edad34a41960bc1c))

- **witness_metrics_functions.py**: Missing 1q clifford AV bucket counts
  ([`a50e69c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a50e69c6843df4ea158445a3c5cae15d65ab22dd))

### Build System

- Added linting groups to pyproject.toml
  ([`1a17778`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1a1777838f5dd9b0438094462765e4c5c0d12811))

- Removed unneeded semantic-versioning poetry group
  ([`55b07c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/55b07c8e120c15bf8e56acae56923de3e5357cd8))

- Updated poetry.lock
  ([`b450080`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b4500801628c1275c198052ab3bf4579f11ce6eb))

- Updated poetry.lock
  ([`b11d572`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b11d572b657e24c872adcd70d50dcee2c3499602))

### Chores

- Add debugging print option to witness
  ([`3a75f55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3a75f5513eb8b1e36f0eef55bd663084d79ab3e0))

- Removed spurious jupyter notebook
  ([`6c55bae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6c55bae2c3317620759dc781af369a6b4624c778))

- Restoring do_warning in convert_value_to_type
  ([`83a6500`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/83a6500e650c06d21ca7106dca0c438476813112))

- Reverted elbow cancellation filter files to current state on master (with updated CR notices)
  ([`6257ea4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6257ea48ea354a926338734ead51d12ac580e8a6))

- Update docstring
  ([`404ca9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/404ca9b4b34c172a2adce26ed4f9cf29281a7072))

### Code Style

- Update imports
  ([`058df29`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/058df299999a45fea2be5e536c993a3ec78d3aa6))

### Continuous Integration

- Added commit linting job
  ([`38b0e21`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/38b0e2158e4bff4087e47642618152df724a2e66))

- Added commitlint config
  ([`4d4e608`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4d4e6087d2c53a8ccf98c9459cbcc908b1ad4940))

### Documentation

- Add more docstrings in the AV lookup
  ([`cbc7211`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cbc721182399e9b9204944aaead22a23076a2f90))

- Added readme section for contributing, including pre-commit hooks install
  ([`d30b158`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d30b1580895f26b2ecd8f55db4bd8230240b6324))

- **licenses**: Updated all license headers
  ([`a1b9583`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1b95838670d9aac56bf65a2249672024ed97a7c))

- **pre-commit**: Updated CR notice
  ([`b2f8c9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b2f8c9b1cdd1d027fd9847df2d83981dac24554e))

- **readme**: Updated conv commit example
  ([`0e5dd6e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0e5dd6e4832da88bbcaa158f0fdfd45c2085a9d4))

- **readme**: Updated instructions for pre-commit hooks
  ([`e73b416`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e73b4168c60819ceb5bc41a3838bbe38abd7b28e))

### Features

- Add numeric black box functionality for Qubricks (witness almost working)
  ([`4fb2782`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4fb27829fa81878039fa4798d31b1bd63ea9abae))

- Add support for composite registers with optional parameters
  ([`0b10887`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0b10887f27fed8daf31dc66ece1754c5a9fe28c6))

- Added test file for conditionally clean arithmetic, added docstrings
  ([`bccb4b5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bccb4b51533af25df65cef765dc5e1688644fa64))

- Fix bug with decomposing gates with black box qubricks
  ([`7270d66`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7270d6611783f8458c28b7c10b3ecfd96c0633fb))

- Get old metrics functions working
  ([`1008e00`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1008e00cff2d3bb1279053c74f208b6c71a14628))

- Implement native serialization for numeric QPUs
  ([`4ecffb6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ecffb60b7484cb4eb64e913771664b144899e9b))

- Moved cuccaro adder tests to separate file... seems to not work...
  ([`ec89730`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ec89730a4fbe55d2baebe93a17bd9565fa146a03))

- Re-wrote example notebook demonstrating conditionally clean decompositions
  ([`2802384`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/28023848386f5033afd9e2c1d62ff494e3389ce9))

- Removing various files, addressing reviewer comments
  ([`b99899a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b99899a490d5b5c8b3f1ab1b0dcbd8c25134ceff))

- Restore active volume calculation for symbolics
  ([`c55116a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c55116a127ad5be20b7bbae96d18731dd53af883))

- Unravel composite registers for purpose of serialization
  ([`6ab4a2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6ab4a2be94a38bb59f99a61e7032fa6c0a50f47a))

- Update cost events to use start/end
  ([`4ef25e0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4ef25e0961a3e403340d1f784ce463ef489dbd20))

- Update tests, add av functionality, add demo notebook
  ([`5296692`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5296692ea4a8b95c76b47ac307f6d0a924565dce))

- **qiskit_qpu.py**: Create clear error messages for when qpu is not provided.
  ([`d3f17aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d3f17aaa7d603e75cd8b1ded838e5362227ddca8))

- **qiskit_qpu.py**: Speed up MPS simulator and add debugging features
  ([`25510d6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25510d6660bc74bcec9b3b28b290a346fb8370b1))

- **test_861**: Use existing fideltiy function rather than custom
  ([`50a3697`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/50a36978c95030badb1315575f1f43a607cc13e8))

- **witness_metrics_functions.py**: Add PPR/PPM AV counts
  ([`2110964`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2110964226faafcdc0f689a518c3085c21747e6b))

### Refactoring

- Minor cleanups
  ([`93541dc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/93541dc040e6dced3e1bc5bd87e2ccb7efa7ca4e))

- Minor fixes
  ([`3f827a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3f827a53c0c4f89a4f58b3ecf72ac72b8a4f71e9))

- Remove highwater calculations for symbolics and rely on bartiq
  ([`c9b5674`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c9b567417eb82503e02670e3d0549af090e14e4b))

- **examples**: Moved experiment notebooks to /examples
  ([`f2110c4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f2110c448777d8bbd5c77acf5b5f57300df2ea6d))

### Testing

- Add 2q cliff tests for av
  ([`2d63bb1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d63bb1c6653c051602b0c5a0955e77131b76c8e))

- Add test for counting PPRs with same weights, diff angles
  ([`c5f1c5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5f1c5f7d0f06e8c1ba78add24b3405e340b7b38))

- Address @sgreenaway's comments
  ([`4339011`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4339011f1e2e0fd9d56c01f11930447d8849caf3))

- Address @sgreenaway's comments
  ([`6bbc16e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6bbc16efc90c3643165f49140f703729380e4afc))

- Cleaned up pytest config
  ([`ce44f4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce44f4aac675b8b98db5cc8b5ae6fedf07a072d7))

- Remove set_repetition_env where unnecessary
  ([`12c1c7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/12c1c7bca1c71753f5fcb1237e37b1af0078ce99))

- **test_771_independent_metrics_counter.py**: Add test for no PPO circuit
  ([`3209a8d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3209a8d43290a18327ffbafcdb256df3a0bd90c9))


## v4.13.1 (2025-02-11)

### Bug Fixes

- Fix logic in equal_compare_engine_symbolic
  ([`335e2fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/335e2fd178e6083850d67f20a95a3a2d23832a9a))

### Chores

- Add missing import
  ([`9bdffd9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9bdffd994282e3764be1eeb0aef304b09b74cff3))

- Add set_version for .whl files in gitlab yml
  ([`a4d7f2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a4d7f2af8bbd094ad7c97ef34b94efe3587b11a7))

- Extract pyproject.toml version in setup_legacy
  ([`e63e93c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e63e93c734b4434644630e36f2a549386d2206d6))

- Get version without toml
  ([`a1103fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1103fc13a8c5d0b694a4a87450fa9d25fbc1f24))

- Only check for v on release tag cicd runs
  ([`2405be8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2405be8e7293efe89d5fa8b83c04a4244b6bc526))

- Remove unnecessary poetry install
  ([`d8d9b74`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8d9b74ae61106e7b7b2dab163955a589c01261f))

- Remove update_versions() function
  ([`bd27063`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bd270639d7f6d868ca5f1d9aa0734171ce8e5892))

### Refactoring

- Remove qc from decompose_op
  ([`436fa2b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/436fa2b6d18e1b3fae20b19bccb72aed72137407))

- Update logic in equal_compare_engine_symbolic
  ([`982e503`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/982e503cb8291220a5abf99915bf6e8b434e4490))


## v4.13.0 (2025-02-06)

### Bug Fixes

- (WIP) Symbolic estimate method gidney adder
  ([`237cc89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/237cc89473de6a242fc7122bf28b6c05a7e1cb80))

- Add test from issue 718
  ([`aedcb3b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aedcb3bd87b7fa8166e16f99641cd2d756a15efe))

- Remove unused mathjax.js file
  ([`3aa309c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3aa309ca18f37d37ae6812a63eaa7d1ce07423ef))

- Symbolic cost Gidney adder
  ([`ade53ca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ade53ca468aab5f39d12f90bea147f92841180b0))

### Chores

- Adding pip install whl back
  ([`1aa5d20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1aa5d20bfcfabf9172cc34ffe5e3ad7b0b18de7a))

- Adding pybind11 manually
  ([`ec5127e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ec5127ee6a7ba612064caab24cb65a259c2cc53a))

- Adding the test for linux aarch
  ([`f4759ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f4759ec4b29192bb610326c0a777aa66d743060f))

- Fix macos test jobs
  ([`ce8c656`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ce8c65623da1682bf962f43e00763df18347e272))

- Fix qiskit
  ([`fb35f86`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fb35f86fcd27c85b493c6f544d8a2b8f348560ce))

- Fix the parallel job for macos
  ([`8a8e46a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a8e46aa7e6eb95d05d29ba368c87b02ee10fe23))

- Fix the test job for macos
  ([`7780e3d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7780e3da896342ae3e2b8b2c5427d39d7e043aca))

- Instantiate the virtualenv
  ([`fe8e807`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe8e80799518db800577c4301d346beebfd28f0c))

- Made the qiskit macos job even more dynamic
  ([`373beb3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/373beb3416bb81199a44af9cce8672c87394871b))

- Pages need dependencies
  ([`081f930`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/081f930628308b5fed05d0cdf850bde542bd6b4a))

- Remove resource_groups
  ([`d0d63c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0d63c81b4b3d6c8bd64307a6f16bf37d412e737))

- Reverting the macos
  ([`e1f829e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1f829e58a39c73e0d24326741848f50ba0176bf))

- Simplify .gitlab-ci.yml
  ([`3728457`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3728457d2ed9b7ce0bc49f0f507cc2065e5bc667))

- Simplify .gitlab-ci.yml
  ([`c144ce0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c144ce01063acc12d2b479a8df920a5b9a5f925a))

- Specifying the python version explicitely
  ([`0f4f997`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0f4f997c3a315e256c5724c4c9d18f2bb56188bf))

- Testing the new scheme
  ([`161dc70`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/161dc703fa6de5795d86e7960b62d7c512d83c07))

- Trying to tie the test whl to built whl
  ([`f3ca734`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3ca734d0caa35bcf4f86ab72c25ab3dbc250268))

### Continuous Integration

- Clean up .gitlab-ci.yml
  ([`a081cbd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a081cbd16086d5b07e590d53f5ff92bc8ede1f81))

### Documentation

- Add info about emitted event to fetch_rotation_catalyst
  ([`080a05d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/080a05dde39ab8b5e317ffab04adf337c6169b56))

- Add links to notebooks on the symbolic qre page
  ([`366a18f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/366a18ffd3e27db706ecc986d50c9a97fb39b257))

- Improve docstrings for event_start and event_end
  ([`8501eaf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8501eafce7a4b55b7439b2f974f7c5a771544cc0))

### Features

- Emit events when accessing rotation catalyst state
  ([`e95c490`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e95c4906e5fbdf70a6039fe046b9d5e0ecee2200))

### Refactoring

- Further extraction of methods from BaseQPU
  ([`ebdf80e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ebdf80ee70a2d536bc304f0fc4ca71fd83dc3759))

- Make num_qubits property in QPU
  ([`d8e9714`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d8e971467205f3da5f90d93848703e4f76c20c2e))

- Move logic associated with threads from BaseQPU to SymbolicQPU
  ([`94c902c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/94c902c6d5ac5cace1ffc7945191edbc763e2309))

- Move QPU_cpp and associated methods out of BaseQPU
  ([`c0aca92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c0aca925fedcb830a13c0d3000d2a7a2ceb830d3))

- Remove unnecessary imports and count_1_bits method from BaseQPU and QPU
  ([`a65ea1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a65ea1a4ba4b9c35cf1590453bb685bf170bd01f))

- Remove unnecessary methods from QPU
  ([`6874b62`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6874b62183004b966dc450e8e17b3f0c000a40b0))

- Update examples/fh_benchmark.py
  ([`63dc5ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/63dc5ae234d8f1343492e55caac0f7b40c875822))

### Testing

- Add parametrization
  ([`baf9199`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/baf919903a09b0eba374aac35c2622fa1332dceb))


## v4.12.3 (2025-01-28)

### Bug Fixes

- Add default cond value for ppr in SymbolicQubits
  ([`8eb2cfb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8eb2cfbaa024fcfe2d5f6e00a8e527e194ca0806))

- Minor fixes
  ([`147db20`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/147db20700a5fde25bad82326c74acbe2548fe74))

- **cicd**: Lock file and cicd instructions
  ([`d0763c3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0763c3ab52df641979d927e91a9e1a4d5b51ed4))

- **lint**: Fix actual ruff errors (undefined variables)
  ([`c78ffa4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c78ffa416e15ac506c943860e6adcc211cc166a9))

### Chores

- Add missing attributes to QubrickComputeState docs
  ([`dc5bd3b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc5bd3bcccf35024b027728ca9bd3d6817e0269c))

- Fix debug comments
  ([`bfd98d3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bfd98d35add1eb7140f169a06cd95baec4e1cb3b))

- Fix docstring
  ([`ff9511a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff9511ab19ef5f74c83205f0ced1ff86fb181b1c))

- Fix uncomputation filter docs
  ([`fbee800`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fbee8004e7e100d8e7071487d191fd07c7a93915))

- Remove emit_op from qubits
  ([`e7d91fa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e7d91fa030345093ddf3a3cc2d2387b3d863ec44))

### Documentation

- Add initial MkDocs docstrings to qubrick.py
  ([`5efdb26`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5efdb26b8dbd21e1a1ef5823462c164390f264c2))

- Add rendering fixes and move around some files
  ([`3b1ccee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3b1ccee793ad5f11b299180879f38f32264487b8))

### Refactoring

- Add BaseQPU class
  ([`f07767e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f07767e95691428d9bbe1fa80a3da802bc0faaba))

- Remove unnecessary functionalities from SymbolicQPU
  ([`2653949`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2653949b080cdbf1236e857ebb387a822aeea758))


## v4.12.2 (2025-01-24)


## v4.12.1 (2025-01-23)

### Bug Fixes

- Remove metrics method from rsqrt qubrick
  ([`756f28f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/756f28fde104d43d63641cb83576c3b1c87a5fdf))

- Remove stray parentheses causing test fail
  ([`71274e7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71274e7af483da216b571679ef79241ebdb15237))

- Revert back to correct build version
  ([`6574ce6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6574ce6e96089e4a58335cc27a64c0fbe9ba9e0a))

- Sync version with master
  ([`3e19c2a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e19c2af372456009402217426543fa8990a73ad))

- Update how we resolve whether an object is a Qubrick in QubitLogic
  ([`c93f07f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c93f07fa2afc4160049de8ff32f2effe628d1345))

- Update logic to fix circular import problems
  ([`4acfb98`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4acfb980d0b81ef8c7ea62a1057d4de6fc9941d8))

- **.gitlab-ci.yml**: Get rid of qiskit-aer install in macos test
  ([`9d5c25a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9d5c25ad9bb09f95af96d8daecd4f19faca4ef05))

- **.gitlab-ci.yml**: Revert back to original ci
  ([`d4cbe74`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d4cbe745090ed7bc06afb114d75b2145a644f808))

- **.gitlab-ci.yml**: Test qiskit interoperability in CICD
  ([`aa3b25a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/aa3b25a76bdedebb2ec2e75c1cf5103aed001899))

- **dagger**: Fix for dagger ops in #870
  ([`e1616f3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e1616f32851ff0a5a6c4f1d0f8d5dafddac312eb))

- **links**: Updated documentation notebook links
  ([`fc19d61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc19d613e71e04960f29d0f43efde466472dde61))

- **poetry.lock**: Add install extras
  ([`1f4aa29`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1f4aa29e1e8ab37c39ea768023e9d5b3826ee218))

- **poetry.lock**: Regenerate with new extras
  ([`d158976`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d158976ffecba7b7cbbc0f4d24170918c42c687b))

- **psiqworkbench/__init__.py**: Unsort imports
  ([`965be6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/965be6f4d4ba14c9b915c75c2bb6995cdd6c4852))

- **qiskit_qpu.py**: Add legalese
  ([`cee4ad6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cee4ad64840add7e193d7d8793c6043e44f2eb88))

- **qiskit_qpu.py**: Apply isort and black
  ([`33995ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/33995ce9f60a3a4809d6069dfa5514bec943cccb))

- **qiskit_qpu.py**: Ooutput -> output in comments
  ([`ed276f2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ed276f23dc83d2bc7bed52b86408b6b563c79bb8))

- **qiskit_qpu.py**: Require qiskit install for qiskit qpu usage
  ([`2d90907`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2d909072b459dc6aac0098607e25b4f62e667bb9))

- **qiskit_qpu.py**: StreamBitQPU -> QiskitQPU in comments
  ([`0116211`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0116211eb965ab540b50a31a4704d5bcb6fcea6b))

- **setup_legacy.py**: Undo version update and isort
  ([`f969ad0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f969ad08592f5016ff3d78d05324b6a94db0d82f))

- **test_861**: More descriptive import failure message
  ([`d04988a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d04988acf6f3b0f09a275990b2b84299d9856b26))

- **test_symbolic_qint.py**: Don't require sympy install for test_composite_register_symbolic
  ([`b1c2d6f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1c2d6f0f873417f77523f51bc232f3d7857d0d3))

- **test_symbolic_qint.py**: Require bartiq install to run bartiq tests
  ([`0ff53b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ff53b211a0cc1f8dcc9e36c5bf303afd6e4509c))

### Chores

- Redo imports after fixing some circular imports
  ([`54d0dc6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/54d0dc675c1c30f7bcbec989bc1c9d1aacbae8db))

- Remove _copy_internals method
  ([`34cc615`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/34cc6155be2ec700455da18216900887b579b505))

- Remove unnecessary fields
  ([`bcfafe6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bcfafe65689a116322756a28fb19bbc7ac7cb870))

### Features

- **lint**: Add flake8 files for #875
  ([`f7ac4cf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f7ac4cfc1bf5fb72f09a7083f13f4ef94871d939))

- **lint**: First pass at ignore items
  ([`75b7929`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75b7929b983ce60c9289580ace60387f10b5f99e))

- **qiskit_qpu.py**: Add in Statevector, MPS, and Stabilizer Qiskit simulators
  ([`e49a524`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e49a524a68fc731654ffcedb42b4c7428b215b3c))

### Testing

- Add test for #870
  ([`fbc7085`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fbc7085757aa96c30406faeb3ee59fbd4870c8f5))


## v4.12.0 (2025-01-15)


## v4.11.1 (2025-01-13)

### Bug Fixes

- Add explicit exception for symbolics in QFTIncrement
  ([`69c2469`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/69c24695e62790e29ab5966b8968cc6ccf1cbf83))

- Add index to SymbolicQubits again
  ([`52ef213`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/52ef213595ea8c66274763230ed28af2d5ab4158))

- Added QasmExportFilter to built in filters
  ([`2416dc2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2416dc2be6700ef6142d21577fc3c83938bdd41b))

- Minor fixes in usage of qubits classes
  ([`899a280`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/899a2809da8913d07ee76b786705198661ab3d2a))

- **qasm3_export.py**: Add support for elbow operations
  ([`09158bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/09158bb073f86eafffa57c0166c6c6d08621af47))

- **qpu_ops.py**: Re-align inputs to ops decalaration
  ([`44f8855`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/44f885514d4ba04bd36ee42c58a0876eecaa02df))

- **test_811**: Refer to filter by name
  ([`1c121ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1c121ef4d636a6e807f8f10368ffca9814b26567))

### Chores

- Add BaseQubits class and refactor Qubits and SymbolicQubits
  ([`0cba44a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0cba44af2fdb6067bd0237560be331cd1e297428))

- Refactoring parts of SymbolicQubits
  ([`963b8d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/963b8d1078511b46de345ab2c3e8641a68028463))

- WiP refactoring of SymbolicQubits class
  ([`8a1cc4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a1cc4bc6be24e89dd4ae0cfa77b1e816a75370e))

### Code Style

- Fix style issues
  ([`fc18d32`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fc18d32c61f0ad1c82f863ec287c02f35bb9b5af))

- Fix style issues
  ([`d730452`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d730452a5ae1de7346c0de4d71ce42fdeb77324c))

- Fix typing
  ([`9fed0e8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9fed0e86be25cd7af98b6080fc3906fad2345483))


## v4.11.0 (2025-01-10)


## v4.10.1 (2024-12-12)

### Bug Fixes

- Fix compatibility with old Parameter class
  ([`bdb78d9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/bdb78d9e057686b2269214f7550178993f0f9646))

- Update highwater calculation to use Parameter class
  ([`4adbc79`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4adbc79f55cdc1c5796826eb8ecfc3e1c34f9f02))


## v4.10.0 (2024-12-06)

### Bug Fixes

- Fix in serialization
  ([`0ddb4f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0ddb4f14c8df0ec124028074ed56b6d53458f2b0))

### Chores

- Make docs dependency optional
  ([`937d938`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/937d93884c422989096f4c6d14d2d7a7bb73e741))

- Rename parameter_new to parameter
  ([`260a4ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/260a4efbd64ec50b01c66ef3857d26de62e3c825))

- Update poetry.lock
  ([`fe60fce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fe60fceefdfabc60fa0dcc98e540a85523e274dd))

- Update poetry.lock
  ([`2aeda8a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/2aeda8a239e211bbc1115bb7454fd48e79bdfb75))

### Code Style

- Run black and isort on symbolics
  ([`de002d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/de002d1364de3eaec3e31f5f7a998d3fc685c23a))


## v4.9.2 (2024-12-04)


## v4.9.1 (2024-12-03)

### Bug Fixes

- Fix numerical issues in compare_symbolic_total_cost_with_numeric.
  ([`27d537c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/27d537c1ad4074c0ef7c4f3ea7e94de1b0be1258))

- Fix usage of Parameter class when sympy is not installed
  ([`1114c73`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1114c7306a45fc9f2ff21a884bdc5832bd67f9c4))

- Get rid of circuit_volume mentions
  ([`afc8fe0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/afc8fe0f90204fd5d39e4772097ab419c1b2e28d))

### Chores

- Add sympy to docs dependencies
  ([`8aed090`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8aed090b2dd959affd3e5b92d215cf24dd97d69e))

- Fix CI settings
  ([`3fed2a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3fed2a23decc0d8106ad515db3166da10e81d622))

- Minor refactors
  ([`d0f82e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d0f82e2b7acf0b63757e3919e838b58925d2e00b))

- Multiple refactors
  ([`cccba72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cccba7226d1d94053fbca397a755d6c7555abe61))

- Update example notebooks
  ([`ea5b91a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ea5b91a0c08ea6e68b931bac52a1e5289201a60a))

- Update Parameter class
  ([`1d4d223`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1d4d223c3784c1841256a47b76134abf32658ba5))


## v4.9.0 (2024-11-26)

### Bug Fixes

- Fixes bug in Old parameter
  ([`786cbbb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/786cbbb495d7c14d5e068f2c6388e58dfcd99ca2))

- Fixes in parameter handling in symbolics
  ([`d021094`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d021094838823670f2d3b3842e734bffb2187fda))

### Chores

- Make _get_serializable_qubits_representation not mutating
  ([`5809dfd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5809dfd56f92d889cbf88374a9843f8865fd5c28))

- Move Min/Max from classical_stubs to Parameter
  ([`755e090`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/755e090db60c8a289baf0bc1bcfff65904c314a7))


## v4.8.11 (2024-11-25)

### Bug Fixes

- Add support for repeated structures when exporting to qref
  ([`a581b75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a581b75d6ce75c4103a747584e8efcaf55f81814))

- Fix logic for handling slices in SymbolicQubits
  ([`1810ddf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1810ddfee58bc4e69605e6de68bb86426cbba427))

- Update logic for bit_count in new Parameter class
  ([`9a27fca`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9a27fca1a4aabff43b0921797800043343dd689a))

- Update symbolic slice handling
  ([`b1e9e01`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b1e9e0125ba3894c34590295a43fca1527e0ad81))

### Chores

- Further refactor in Parameter class
  ([`da8dc83`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/da8dc839c0efedc642052fba4fdb9a53fd6f86ed))

- Minor refactor in QubrickCosts class
  ([`c5104b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c5104b247ed69d89c5eed81020156a97e045954b))

### Code Style

- Fix typing in symbolic_compilation_filters
  ([`cc92dce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/cc92dceaab9da41afc81140e9b29459554adad8d))

### Documentation

- **filters**: Removed reference to workbench web
  ([`ca2ec4d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ca2ec4d5b605fdd50043338b3f0ea477f0625193))

- **index**: Simplify installation instructions
  ([`13044f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/13044f18ec3c9524cb101538fdf5d94346d94948))

- **index**: Updated docs landing page
  ([`f3ae140`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f3ae140d15b9c193fdae84e06288980a0c20951e))

- **readme**: Fix underscore error in package name
  ([`f9c8ae2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f9c8ae2174fd04c377aade73440cdd2986e655cd))

- **README**: Updated installation instructions
  ([`1e2e779`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1e2e779b02a641418297573918c3b434b232a4d8))

### Testing

- Improve usage of sorted in qref serialization tests
  ([`07041e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/07041e141cfc1cbbd28054f11bd65bf99370f1f9))


## v4.8.10 (2024-11-18)


## v4.8.9 (2024-11-05)


## v4.8.8 (2024-10-31)


## v4.8.7 (2024-10-23)


## v4.8.6 (2024-10-17)


## v4.8.5 (2024-10-10)


## v4.8.4 (2024-10-09)


## v4.8.3 (2024-09-12)


## v4.8.1 (2024-09-06)


## v4.7.11 (2024-09-05)


## v4.7.8 (2024-08-28)


## v4.7.4 (2024-08-23)

### Code Style

- Fixed whitespace and a couple docstrings
  ([`28582e2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/28582e259023ee01820b2fb23ab6c50b5253393b))


## v4.7.3 (2024-08-22)

### Bug Fixes

- Add __init__.py to placate CICD
  ([`239e035`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/239e035a33ac1fa69af84fc3bd7f0a5ae024f670))

- More inits
  ([`806e7d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/806e7d2ed86416bcecb7689b760a0ba23c40090f))

- **psiqworkbench**: Fix and clean imports
  ([`b8f7886`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b8f7886e6c706e508e399de8e14507b3d61cdede))

- **psiqworkbench**: Tests pass
  ([`51b57ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/51b57add5e82fbf5020cf521f8a5adde5d399f4b))

- **qpu.py**: Export_to_json
  ([`75f9071`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/75f9071ce1137eb69765432d1eadf28ccd1a16a9))

- **test_qasm**: Run tests instead of skipping
  ([`f64558b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f64558b9c8a546f1040cac602f5aeab8b11720d1))

- **working_with_qubtis.rst**: Fix placement of QPU in docs test
  ([`b8b6b59`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b8b6b59cf371718dec2616bdd9df992f0b9311d4))

### Features

- Move necessary files
  ([`a1ae4b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1ae4b9a1e67658b5fcf3ba2ae456dddbc6257c5))


## v4.4.5 (2024-08-19)


## v4.4.4 (2024-08-16)


## v4.4.3 (2024-08-16)


## v4.4.2 (2024-08-16)


## v4.4.1 (2024-08-16)

### Bug Fixes

- **reaction_limit_estimator**: Improve comments
  ([`21acc70`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/21acc7041f9653c8a9c0f65a048813be5a1cac75))

- **reaction_limit_estimator**: Sacrifice perfect DAG for speed.
  ([`a6c9290`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a6c9290376b89b379911b4ea5d986ea9e6df8042))


## v4.4.0 (2024-08-14)


## v4.3.16 (2024-08-14)


## v4.3.15 (2024-08-13)


## v4.3.14 (2024-08-13)


## v4.3.13 (2024-08-12)


## v4.3.12 (2024-08-08)


## v4.3.11 (2024-08-06)


## v4.3.10 (2024-08-06)


## v4.3.9 (2024-08-05)


## v4.3.8 (2024-07-26)


## v4.3.6 (2024-07-25)


## v4.3.5 (2024-07-24)


## v4.3.4 (2024-07-23)


## v4.3.3 (2024-07-18)


## v4.3.2 (2024-07-18)


## v4.3.1 (2024-07-18)


## v4.3.0 (2024-07-11)


## v4.2.13 (2024-07-11)


## v4.2.12 (2024-07-11)


## v4.2.11 (2024-06-28)


## v4.2.10 (2024-06-28)

### Bug Fixes

- Use opname in error
  ([`98e207d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/98e207d7267f14ef2d5a334c2f0052bcf5eda426))

- **get_dag_from_qpu**: Don't require igraph
  ([`3e76a1b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e76a1b14e4085a3600a8a52f214043f753ab4d8))


## v4.2.8 (2024-06-27)

### Bug Fixes

- Allow python 3.8
  ([`41d58cb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41d58cbd3d97c49d2ba7479b83852e9a94c9291c))

- Clean up imports
  ([`1745db8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1745db876d5b3c1f09e540c9a832ff394db708e4))

- Double time for left elbows
  ([`961a2ef`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/961a2ef94cdbd354a0ccc4a0fec256adc7bd03c1))

- Ignore I in ross-sellenger
  ([`888882e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/888882e3419cd822caff0ba6cc728759528766c0))

- Images inside image folder
  ([`0201e61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0201e61cde6ec5cf6739ce03ee357bf8834dcbd4))

- Improve typing in operations
  ([`a019448`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a019448e7c65e7e8a2c5defaf84e3fad0a7110ba))

- Indent in ross-sellenger default
  ([`6304e0a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6304e0a566695367f18b166c32f0795eb1653f96))

- Instruction filter -> instruction selector
  ([`8eca647`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8eca64794942a455187b442d716be1c4b9063182))

- Is_quantum_operation -> is_physical_operation
  ([`7dd50b9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/7dd50b94e08cff43a0bf97c13cd850c703e88329))

- Issues with merge
  ([`773a5c2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/773a5c22cc772a540affc43770f7db7d9e030275))

- Make all_op_types decalaration more compact
  ([`25ce296`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/25ce296f497572dcc9ee1638d9b855908c2a9bc3))

- Missing merge conflicts
  ([`e5e1b68`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/e5e1b68553b18f2643fb33721c16ecd73613272a))

- Missing merge conflicts again
  ([`fa1422c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fa1422cb428b2f013194db126a911a2a760f14a8))

- Rearrange imports to after copyright
  ([`fcf2889`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/fcf2889bfa3f6d7c395064acf2081ccb0fc6441b))

- Remove testing output
  ([`4137758`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/41377587e93db04e672f0c47e42aec69ddc51c10))

- Require python>=3.8
  ([`f0e2505`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f0e2505a6dec6c9a5194f7ae0ee74c75231c7942))

- Respond to PR comments
  ([`5933522`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/59335227eb4cd0b430b256f44c6d3544d9d98449))

- Target and condition in example
  ([`c270116`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c27011697683be928b509cf81b35c9dec0a57616))

- Tell users when to install igraph
  ([`b11440c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/b11440cae53e45d55cb4213dbfe42a3b74319be3))

- Typo
  ([`6d5a5fd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/6d5a5fd9afcdeb19e9cd7c0c565873b148fe0035))

- Typo in reaction instructions explanation
  ([`3532842`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/35328429249491b1b580d48dd91782336519e0b7))

- Unify qubit mask getters
  ([`171e50f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/171e50f8ed0d03235c4bac4db7cb24a62661b217))

- Update comments to latest version
  ([`626ac85`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/626ac858bb54d64f80fe3b4a8053fc483e8be2b5))

- **example_reaction_depth**: Add QFT example
  ([`042e8a2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/042e8a2522028671627672f2672914a46d49e2a8))

- **example_reaction_depth**: Will's corrections
  ([`838a784`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/838a784ddfc05b9578c2a5e5149c9a306262a53d))

- **get_dag_from_qpu**: Improve comments on inst argument
  ([`dc5b6b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/dc5b6b11e13372d8247d0cec40dbeb3163720d07))

- **get_dag_from_qpu**: Simplify elbow check
  ([`02f088a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/02f088a02766590a187f7b07035f2a40fcfa3d82))

- **get_dag_from_qpu**: Use num_qubits for reset
  ([`ff5107b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/ff5107bef8f7815a354dbdaaf8cf7c6c862136f1))

- **ordered_qpu_ops**: Self.hash -> self._hash
  ([`4b6d199`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4b6d1996eb1ed16b5c857376fa2b26944482d3c0))

- **ross_sellenger_synthesis**: Bug from I no longer defined
  ([`d78573c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d78573c84375d2028e1e0758c3c2f55bc6e9cdf3))

- **ross_sellenger_synthesis**: Bug from I no longer defined
  ([`9e14894`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9e14894dc1b4d831cd28fe0ae2bdeaea90ca92d4))

- **test_531**: Test adder for more qubits
  ([`8a4dd92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8a4dd92c73c3e5f6bb4f1d106c79a4bef85925dd))

### Features

- Add default to error to ross-sellenger - 1
  ([`038a6d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/038a6d043dd67a63ff9997b2207de3780a33e4b0))

- Add default to error to ross-sellenger - 2
  ([`5c75f75`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/5c75f75df91f7b7a7adc80a1ab2551883c9cf48b))

- Add default to error to ross-sellenger - 3
  ([`f8862d2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f8862d29991e04188d789b08df84bbc1e8bb95dd))

- Catch warnings and explicitly manage queue
  ([`14192c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/14192c90d6284450622c2653aec07a1e33d146a5))

- Changes before cleanup
  ([`0cc7e1e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0cc7e1e0c66235451330927a681fdf4a45bba34c))

- Examples for reaction depth calculation
  ([`f6c07d0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6c07d0132e1989c3a03850ae9e827e72ff7f114))

- Expose number of circuit layers in reaction limit
  ([`3e70b55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/3e70b550d260e20792b1b2a3b0bae43bb0eaf5cb))

- Express circuits as DAGs
  ([`71c1f35`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/71c1f3503fd7ea34d6f94df10b14f05e43443c0e))

- Fast reaction time calculation
  ([`d9fca30`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/d9fca30bd2684dc35fbea99378f49e73ecb56213))

- Jess's idea
  ([`f6ebe43`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/f6ebe4387e4191a9858c0da45ba6456ab64f9391))

- Jess's idea in igraph
  ([`8898ae1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/8898ae148fa4e3ae15661eb2fabc914d200aa72c))

- Minimal graph
  ([`827a8fe`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/827a8fede126a0c1214f8b4cdf45fd9a31a9e08f))

- Minimal graph numba
  ([`9acaa9b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/9acaa9b21bcb942fb247522b96708ae1d9e70d25))

- Organized DAG creation functions
  ([`97581be`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/97581beb9c74f49fd6f2a46edad56dcc5d7f5f06))

- Stuff before cleanup
  ([`c79c081`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c79c0819366fb27f0d19efa88ee28cfb1a09c8a4))

- **get_dag_from_qpu**: Specify get_qubits_used_mask for dag creation
  ([`1effa42`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/1effa424e9e58f6a9c194d1bcaf084b2f4d5faa8))

- **test_531**: Test adders with shared register can be parallelized
  ([`a1fece2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/a1fece28cc07b790948d066c4671505e428276b7))

- **test_531**: Test doubling the sequence doubles layers
  ([`0209495`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/0209495b8b3961284f1e04264c4326a79e07702e))

- **test_531**: Test parallel adders don't add layers
  ([`c262a4b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/c262a4b198d30436fd7dee21698eea8167410b32))


## v4.2.4 (2024-06-27)


## v4.2.9 (2024-06-27)


## v4.2.1 (2024-06-25)


## v4.2.3 (2024-06-26)


## v4.1.16 (2024-06-25)


## v4.2.0 (2024-06-18)


## v4.1.15 (2024-06-20)


## v4.1.14 (2024-06-19)


## v4.1.13 (2024-06-18)


## v4.1.12 (2024-06-14)


## v4.1.11 (2024-06-14)


## v4.1.10 (2024-06-14)


## v4.1.9 (2024-06-13)


## v4.1.8 (2024-06-12)


## v4.1.7 (2024-06-12)


## v4.1.6 (2024-06-12)


## v4.1.5 (2024-06-07)


## v4.1.4 (2024-06-07)

### Chores

- Update the ci pipeline so that all wb and wba tests would be mandatory for each MR
  ([`4e8f942`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/-/commit/4e8f942ccf198cad541ca282d9ba820477ea73df))


## v4.1.3 (2024-06-06)


## v4.1.2 (2024-06-05)


## v4.1.1 (2024-06-05)


## v4.1.0 (2024-06-05)


## v4.0.20 (2024-06-05)


## v4.0.19 (2024-06-03)


## v4.0.18 (2024-06-03)


## v4.0.17 (2024-05-30)


## v4.0.16 (2024-05-30)


## v4.0.15 (2024-05-29)


## v4.0.14 (2024-05-28)


## v4.0.13 (2024-05-24)


## v4.0.12 (2024-05-23)


## v4.0.11 (2024-05-22)


## v4.0.10 (2024-05-21)


## v4.0.9 (2024-05-21)


## v4.0.8 (2024-05-21)


## v4.0.7 (2024-05-20)


## v4.0.6 (2024-05-14)


## v4.0.5 (2024-05-10)


## v4.0.4 (2024-05-10)


## v4.0.3 (2024-05-08)


## v4.0.2 (2024-05-06)


## v4.0.1 (2024-05-03)


## v3.8.6 (2024-05-02)


## v4.0.0 (2024-05-03)


## v3.8.5 (2024-04-25)


## v3.8.4 (2024-04-24)


## v3.8.3 (2024-04-18)


## v3.8.2 (2024-04-16)


## v3.8.1 (2024-04-16)


## v3.8.0 (2024-04-09)


## v3.7.13 (2024-04-09)


## v3.7.12 (2024-04-04)


## v3.7.11 (2024-04-04)


## v3.7.9 (2024-03-28)


## v3.7.8 (2024-03-28)


## v3.7.7 (2024-03-27)


## v3.7.6 (2024-03-27)


## v3.7.5 (2024-03-26)


## v3.7.4 (2024-03-25)


## v3.7.3 (2024-03-21)


## v3.6.10 (2024-02-16)


## v3.7.2 (2024-03-19)


## v3.7.1 (2024-03-18)


## v3.7.0 (2024-03-13)


## v3.6.11 (2024-03-01)


## v3.6.9 (2024-02-16)


## v3.6.8 (2024-02-12)


## v3.6.7 (2024-02-08)


## v3.6.6 (2024-02-08)


## v3.6.5 (2024-02-07)


## v3.6.4 (2024-02-05)


## v3.6.3 (2024-01-19)


## v3.6.2 (2024-01-19)


## v3.6.1 (2024-01-19)


## v3.6.0 (2024-01-18)


## v3.5.5 (2024-01-16)


## v3.5.4 (2024-01-16)


## v3.5.3 (2024-01-02)


## v3.5.1 (2023-12-21)


## v3.5.0 (2023-12-13)


## v3.4.3 (2023-12-12)


## v3.4.2 (2023-12-07)


## v3.4.1 (2023-12-07)


## v3.4.0 (2023-12-07)


## v3.3.0 (2023-12-05)


## v3.2.14 (2023-12-07)


## v3.2.13 (2023-12-01)


## v3.2.12 (2023-11-30)


## v3.2.11 (2023-11-27)


## v3.2.9 (2023-11-08)


## v3.2.8 (2023-11-08)


## v3.2.7 (2023-11-08)


## v3.2.6 (2023-11-03)


## v3.2.5 (2023-11-02)


## v3.2.3 (2023-10-27)


## v3.2.2 (2023-10-25)


## v3.2.0 (2023-10-23)


## v3.1.16 (2023-10-20)


## v3.1.15 (2023-10-20)


## v3.1.14 (2023-10-16)


## v3.1.13 (2023-10-16)


## v3.1.12 (2023-10-12)


## v3.1.11 (2023-10-12)


## v3.1.10 (2023-10-06)


## v3.1.9 (2023-10-05)


## v3.1.8 (2023-10-05)


## v3.1.6 (2023-10-03)


## v3.1.5 (2023-09-27)


## v3.1.4 (2023-09-20)


## v3.1.3 (2023-09-19)


## v3.1.1 (2023-09-19)


## v3.1.0 (2023-09-06)


## v3.0.15 (2023-09-06)


## v3.0.14 (2023-09-05)


## v3.0.13 (2023-08-30)


## v3.0.12 (2023-08-21)


## v3.0.11 (2023-08-17)


## v3.0.10 (2023-08-14)


## v3.0.9 (2023-08-11)


## v3.0.8 (2023-08-11)


## v3.0.6 (2023-08-10)


## v3.0.5 (2023-08-04)


## v3.0.4 (2023-07-31)


## v3.0.3 (2023-07-26)


## v3.0.2 (2023-07-24)


## v3.0.1 (2023-07-17)


## v3.0.0 (2023-07-11)


## v2.13.20 (2023-07-05)


## v2.13.19 (2023-06-28)


## v2.13.18 (2023-06-28)


## v2.13.17 (2023-06-27)


## v2.13.16 (2023-06-26)


## v2.13.15 (2023-06-20)


## v2.13.14 (2023-06-14)


## v2.13.13 (2023-06-14)


## v2.13.12 (2023-06-14)


## v2.13.11 (2023-06-09)


## v2.13.10 (2023-06-06)


## v2.13.9 (2023-05-17)


## v2.13.8 (2023-05-17)


## v2.13.7 (2023-05-05)


## v2.13.6 (2023-04-19)


## v2.13.5 (2023-03-27)


## v2.13.4 (2023-03-21)


## v2.13.3 (2023-03-16)


## v2.13.2 (2023-03-07)


## v2.13.1 (2023-03-02)


## v2.13.0 (2023-02-28)


## v2.12.1 (2023-02-23)


## v2.12.0 (2023-02-23)


## v2.11.10 (2023-02-23)


## v2.11.9 (2023-02-10)


## v2.11.8 (2023-02-10)


## v2.11.7 (2023-02-09)


## v2.11.6 (2023-02-08)


## v2.11.5 (2023-02-07)


## v2.11.4 (2023-02-02)


## v2.11.3 (2023-01-31)


## v2.11.2 (2023-01-20)


## v2.11.1 (2023-01-19)


## v2.11.0 (2023-01-13)


## v2.10.1 (2023-01-13)


## v2.10.0 (2023-01-12)


## v2.9.1 (2022-12-20)


## v2.9.0 (2022-12-02)


## v2.8.8 (2022-11-23)


## v2.8.6 (2022-11-09)


## v2.8.7 (2022-11-22)


## v2.8.5 (2022-10-05)


## v2.8.4 (2022-08-24)


## v2.8.3 (2022-08-23)


## v2.8.2 (2022-08-16)


## v2.8.1 (2022-08-15)


## v2.8.0 (2022-07-29)


## v2.7.9 (2022-07-27)


## v2.7.8 (2022-07-26)


## v2.7.7 (2022-07-26)


## v2.7.6 (2022-07-25)


## v2.7.5 (2022-07-25)


## v2.7.4 (2022-07-22)


## v2.7.3 (2022-07-05)


## v2.7.2 (2022-06-28)


## v2.7.1 (2022-06-28)


## v2.7.0 (2022-06-27)


## v2.6.17 (2022-06-09)


## v2.6.16 (2022-06-02)


## v2.6.14 (2022-05-19)


## v2.6.13 (2022-05-18)


## v2.6.12 (2022-05-18)


## v2.6.11 (2022-05-16)


## v2.6.10 (2022-05-04)


## v2.6.9 (2021-12-20)


## v2.6.8 (2021-12-14)


## v2.6.7 (2021-11-18)


## v2.6.6 (2021-11-10)


## v2.6.5 (2021-10-15)


## v2.6.4 (2021-10-14)


## v2.6.3 (2021-10-06)


## v2.6.2 (2021-10-06)


## v2.6.1 (2021-10-06)


## v2.6.0 (2021-09-15)


## v2.5.23 (2021-09-15)


## v2.5.22 (2021-09-09)


## v2.5.21 (2021-09-03)


## v2.5.20 (2021-09-02)


## v2.5.19 (2021-08-31)


## v2.5.18 (2021-08-25)


## v2.5.17 (2021-08-12)


## v2.5.16 (2021-08-12)


## v2.5.15 (2021-06-08)


## v2.5.14 (2021-05-26)


## v2.5.13 (2021-05-24)


## v2.5.12 (2021-05-19)


## v2.5.11 (2021-05-18)


## v2.5.10 (2021-05-13)


## v2.5.9 (2021-05-05)


## v2.5.8 (2021-05-05)


## v2.5.7 (2021-03-30)


## v2.5.6 (2021-03-10)


## v2.5.5 (2021-03-05)


## v2.5.4 (2021-02-23)


## v2.5.3 (2020-12-17)


## v2.5.2 (2020-11-24)


## v2.5.1 (2020-11-23)


## v2.5.0 (2020-09-10)


## v2.4.8 (2020-07-21)


## v2.4.9 (2020-07-21)


## v2.4.7 (2020-07-02)


## v2.4.4 (2020-05-28)


## v2.4.2 (2020-05-26)


## v2.4.3 (2020-05-26)


## v2.4.1 (2020-05-19)


## v2.4.0 (2020-05-15)


## v2.3.3 (2020-05-11)


## v2.3.2 (2020-05-11)


## v2.3.1 (2020-05-01)


## v2.3.0 (2020-04-24)


## v2.2.5 (2020-03-16)


## v2.2.4 (2020-03-12)


## v2.2.3 (2020-03-03)


## v2.2.2 (2020-03-02)


## v2.2.1 (2020-03-02)


## v2.2.0 (2020-02-26)


## v2.1.18 (2020-02-20)


## v2.1.17 (2020-02-12)


## v2.1.16 (2020-01-21)


## v2.1.15 (2020-01-21)


## v2.1.14 (2020-01-06)


## v2.1.13 (2020-01-06)


## v2.1.12 (2019-12-20)


## v2.1.11 (2019-12-20)


## v2.1.10 (2019-12-19)


## v2.1.9 (2019-12-12)


## v2.1.8 (2019-12-12)


## v2.1.7 (2019-11-27)


## v2.1.6 (2019-11-25)


## v2.1.5 (2019-11-22)


## v2.1.4 (2019-11-13)


## v2.1.3 (2019-11-13)


## v2.1.2 (2019-11-13)


## v2.1.1 (2019-11-13)


## v2.1.0 (2019-11-13)

- Initial Release
