## [1.5.0] - 2026-03-27

### Features

- **psiqworkbench**: 4.33.6 → 4.35.2
  - first pass prototype of fallback measurement generators ([`cf77c128`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/cf77c128d9eee4c9a9cf6ba25a125df9455d03db))
  - Add new fallback scripts ([`a6de0694`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a6de06944b7a648f59ead5e75dc1657b5ba07472))
  - Implement Diagonal Matrix, with test ([`5302ccda`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/5302ccdabd4da288974a399f9ee402a060883773))
  - first pass, with test ([`962c6c19`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/962c6c19fb75ca9b5afaf75176814cfad1de9548))
  - WIP initial functions needed for cudaq filter ([`90dcf7fc`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/90dcf7fc615f9ed5b64bfaeac2f59e009bcd09ea))
  - Add basic support for depth argument in circuit_designer.export ([`31e238d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/31e238d599acc70c48238a73e02494c3e6e7bc28))
  - Add comments and expand to use different core adders ([`c75c1d54`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c75c1d54a22378300ff4cf4d20d118b63a84a2d7))
  - Implement basic circuit_designer.draw function ([`7e8b1ac8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7e8b1ac8e986fe8c9b77db8318105817112da833))
  - Add path tracking in exporter base ([`00f09316`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/00f09316b89aa4a9a34e8b21a69ec2d57cb2c253))
  - Add hash and eq methods to LabelReference ([`4b627aaf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4b627aafb6e5d37c614d11584f5b2636b8c311de))
  - Implement somewhat functioning register placement in WB -> CD conversion ([`bd03caf1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/bd03caf197d2fff1734b6e294a6a83dab16c9239))
  - Implement proper handling of implicitly accessed registers ([`d165ef5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/d165ef5c68c8b3dbf91a01d5df9592f7ada06350))
  - Implement `expanded` flag ([`14b5a3f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/14b5a3f196c55b698b0542d224a8e5b80d3a8652))
  - Sort registers to make output more predictable ([`54532d36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/54532d364d32d85314cbadaf9100ef7e5ad2bcee))
  - draft filter ([`e4e38841`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/e4e388412bf3110e422e5ceee43594415272485b))
  - Early prototype and speed test iteration ([`943ea32f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/943ea32f0ca2297d68b06bc51e13330d56bc5b93))
  - Iteration on Construct CUDA testing ([`252b4bd1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/252b4bd1299885b39a5b507e5d76a2df9ba2b9a9))
  - add native QFT ([`affc1c5b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/affc1c5ba01f610cc4ea89f6d6a265359d58915a))
  - Add mini kernel test, and lots of mess ([`a48bac72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a48bac726e201e605afce610ad0ebf129a6e4f8e))
  - Iteration on the cudaq sim filter ([`ffe29678`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/ffe296782897299fece5a639787d88312d5bbe95))
  - Iteration, integration of filter with static kernel sim ([`aabb6b7b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/aabb6b7b35992f51bf7e009e40ae86e9920234d0))
  - More iteration and fixes ([`487bd1aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/487bd1aa3b9a76b8b573308cb6f07641ef3779ec))
  - Update from car/les to test #1302 ([`9057199e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9057199e5b7928d0c15bcd9bb15052b2716b176a))
  - Implement parsing of box close and box open events ([`9af63b39`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9af63b39905274f3d202c386591ae48ddc1ea217))
  - Support special angles < 45 degrees in symbolic rotation catalyst ([`499b2d72`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/499b2d726906082721f42905ec082e72d81c70e9))
  - enable AV comparison in assert_resources_equal by default ([`4f808573`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4f8085736828a97197fdb622dc9a11c161d67522))
  - enable AV comparison in assert_resources_equal by default ([`fe9cc447`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/fe9cc4478720e0a9f430f61d20bfdf47fcf2c4ef))
- **psi-rex**: 2.2.1 → 2.4.4
  - adding multi-generation wall time plot to REx from AHM ([`0fb603e6`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/0fb603e64c47447ea3b36fce73af85ab7bf73cca))
  - adding observability metrics for usage ([`85ce53b4`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/85ce53b4c7d185f90da201e9c72510876586fc91))

### Bug Fixes

- **psiqworkbench**: 4.33.6 → 4.35.2
  - fix the == compare to be efficient for all types ([`2b5ef8aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/2b5ef8aa05d1557d248ed80b8118afc9ddeddec6))
  - Remove special cases and fix a test ([`50713850`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/5071385007523986721b8edbcbf075aa2646f834))
  - Fixes per MR feedback ([`64dcf2f4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/64dcf2f4d8f9b3dba50f42dfed99a4dfa13078a6))
  - paramaterize test ([`ca36d8ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/ca36d8cec990301509295210738894aab9a697c8))
  - All MR feedback addressed! ([`dfe23a14`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dfe23a141d829f94e271aef4aab9fdd0a9e961a5))
  - MR ideas addressed, first pass ([`343d85f1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/343d85f14704a7ef769fd261290e9ef734ea38af))
  - Fix per MR feedback ([`b04a039d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b04a039d08c0b4d700e80f32b72c64dcc2957a85))
  - Add text per MR feedback ([`2b92b244`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/2b92b2440ca5be5ecb1d1081284c52fab9182b94))
  - Respond to all MR feedback ([`c40b7524`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c40b7524a2b4b7eb4a3d89c34c3f7955f629a0f7))
  - Robustify witness removal pr MR feedback ([`eeba9c55`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/eeba9c55c4077aa1d67a28227e2b713367f7a859))
  - Use correct action when constructing subroutine enter event ([`db8b5000`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/db8b500097ef33d5a5599fe23452637b16256fdd))
  - update logic for subtype specification ([`42c7c1cd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/42c7c1cd7ae63da99dd8b6a7001d31e6803def8b))
  - Make imports from construct_tools optional ([`9a44a478`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9a44a47801fa32b2386964ba7bc482dea7a00dcf))
  - add tests and a missing compute in qubrick ([`7798d99a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7798d99afd1274c4aa77c44ac61083071874ecfa))
  - Add missing type-checking import ([`9227ec7c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9227ec7c23f21db7745ced392dbfd14d692098fd))
  - edit docstrings ([`2496b7a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/2496b7a5d7e4216e8d2a0396b046a13eb7f813aa))
  - Remove incorrect TYPE_CHECKING import ([`dd5269bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dd5269bbb12a6ab6b638e2c06f2276e62e43d8fb))
  - Add type checking import of construct_tools.Circuit ([`fd0339da`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/fd0339da2546d45a0b2b7ac3f9c883e5d3e64a4c))
  - Skip alloc_ref and free_ref in register tracking ([`dfc2612d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dfc2612dca419b1d8f6695e52b1fb55dd83f8211))
  - Fix register sorting ([`59c0a6c7`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/59c0a6c7f08086fb4c0213bd8f4513ba98821367))
  - add test file ([`acdab195`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/acdab195a959c909e07360c8abb8ac132972353e))
  - remove unneeded parents from function ([`65579fd9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/65579fd982e4ff0d519852eed213f9a7d35b8c3e))
  - improve performance of unitary filter and add catch for slowness ([`0991b2b1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/0991b2b1876ec16e93d262d95276f9936186b2d0))
  - just small cleanup ([`419af45b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/419af45b6a423d24a1dd1adaa513fa9ac85886c5))
  - iteration on new kernel ([`796be55d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/796be55daf4c305af916f152c66a8c21f7e19110))
  - New kernel logic ([`bbedf00b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/bbedf00b38209eb1cfde9b51a264dd80bafdfaed))
  - iterative fixes for ops ([`8ee28800`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/8ee28800cfc3c029dc801270f6f18e658a57468b))
  - iterative fixes for ops ([`4a1bd4b4`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4a1bd4b406351a8011db0dc6735148a4c33ea71b))
  - Test now checks the state vec ([`b7133f3a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b7133f3a74482100a461ce705909728c8ea249bf))
  - Small fixes to speed testing ([`05bbd1ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/05bbd1ae2add0367198b1311c6a757f67378e492))
  - Fix per MR feedback ([`7d9473e1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7d9473e19fdca70c7b97a535e44c749b5fc364e3))
  - Kernel and speed test adjustments ([`41941a8c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/41941a8cea9f8df824ca74610afded4247c800c0))
  - Make CUDAQ a soft-import per AST-3457 ([`9d011c91`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9d011c91d4454afd039d6b6e9489bb55e6fb58b4))
  - Make expand default to False ([`3ba2274c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/3ba2274cd6d10a0f71038942181722060a5b8250))
  - trivial change to fix build lint error ([`baf188ce`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/baf188ce22563ffd180cfcfa1bfe1852bc174eac))
  - trivial change to fix CICD lint error ([`a52a2b4a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a52a2b4ab249f48c206915ac3891f62ccd42f940))
  - fixes based on MR feedback ([`5ebbbd82`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/5ebbbd8221e7dca14dfad0327334cd4dc96d950a))
  - Add >>cudaq-sim-v2>> for testing ([`8848d824`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/8848d824edb930ed74ffd11b77b8d03762ffb55e))
  - Comment out second run ([`9964ff5c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9964ff5c7e827a69ec96aa49b8c66163231fc2f0))
  - merge fix for iterative car/les changes to kernel ([`15a689b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/15a689b231105a8b575ea1df1839ce9936a77901))
  - update interoperability code to work with more complicated generic types ([`59c73c3b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/59c73c3b4957ab71cb4efcba6baa3003c12ec602))
  - Remove debugging import ([`cb77aa65`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/cb77aa6571b4bddfd485186fc833ab493f0f65f1))
  - update DI logic to handle more complicated interfaces ([`4aa42736`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4aa4273667e203c2d63f245986c7f976cd12353a))
  - minor fixes in get_dag_from_qpu ([`b5c372a3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b5c372a3c6150465b2ad01f9ae25fcc6b4b21216))
  - remove unnecessary option for dags progress bars ([`0f61c00c`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/0f61c00c8506b77ab9ab9458e09fca30de778876))
  - Fix converting programs releasing rotation catalyst to QREF ([`b9fc7f61`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b9fc7f61ebea5f2414796b464589fa05ad0441a0))
  - remove networkx as default dependency ([`a5b60c2f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a5b60c2f51d0265baa8565fddb10e6c2f8b36627))
  - address reviewer comments ([`c48ce328`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c48ce328e80547aa41048e67143c58b4f951d49b))
  - add support for changing unitary dimension between get calls ([`1f0225aa`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/1f0225aa3e75ecac7cc5b02dda8e06c89df7f56d))
  - address reviewer comments ([`7f1d631d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7f1d631d9c07b02f346d5fe22764214f0e2de99c))
  - Remove unused imports ([`c580a279`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c580a279904ddedda02ea6e24c50f0d0e4d768d9))
  - Make symbolic catalyst QREs more robust for multiplicities of pi/8 ([`7d11b8c5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7d11b8c5d5748e373f3dbec8db97d4d639a66304))
  - cudaq QPU.reset() bug fix ([`30f48fb6`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/30f48fb6f880e9ed82daf6d720986a2ce6fad342))
  - update IMSModel docstring ([`5c7c95bb`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/5c7c95bb80ca83964aaa43033daa96c25b8623f6))
  - remove IP-sensitive QPU Driver model ([`0463ad67`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/0463ad67eea447f78700c37a3f613b6fa7f76093))
  - update logic for subtype specification ([`05f468e5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/05f468e5eb16fde4c5212cd79c491c116bf0739c))
  - Move qpudriver subpackage out of Workbench ([`c5087552`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c50875529907b36d26337a9a017769c4bfde0d17))
  - Fix WB -> CD export for Qubricks with no inputs ([`b66dd639`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b66dd639a7a914f9241f252528d4d59b8128aea8))
  - Fix WB -> CD export for Qubricks with no inputs ([`54c5e02e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/54c5e02edf27c2015d07e56facc11947fdbf0de9))
  - update ci to build all images on tag ([`dac359db`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dac359db78612aa4c3510d84e2c1870e0b9ed4a3))
  - update ci to build all images on tag ([`dd99336b`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dd99336b4ed9bba34b64f204164d473be6f0cf5c))
  - updated build job to copy instead of move from dist ([`7ba12446`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7ba12446be7dcde9ec09d52fdd8cc9ec1713777e))
  - updated build job to copy instead of move from dist ([`3740529a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/3740529a6e38b46781a43b2d320f1b098a23bbde))
- **workbench-algorithms**: 1.13.0 → 1.13.4
  - fix symbolic uncompute in DataLookupClean ([`fd55bada`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/fd55bada0a9795323dd7853ccbef94a4e8af8792))
  - release trigger commit ([`a449ec89`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/a449ec891cad5ed9076de293196be46efbc405fe))
  - release trigger commit ([`dc479c65`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/dc479c6511ac3240af712a435c99bb43706f0dc4))
  - fix bug with numpy arrays as inputs to DataLookupClean ([`6500793c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/6500793c7790da461e189430adb23a8236b51173))
  - fix symbolic uncompute in DataLookupClean ([`2d1e00ea`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/2d1e00eac92641980a1d636d7efb371613deb57e))
  - fix discrepancies for several qubricks ([`555ce853`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/555ce853179873cd573e989f4f18fdfd27f7b8a1))
  - fix discrepancies for several qubricks ([`44094e4b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/44094e4b34a2105185196ac43fbb34e8abb68a8f))
  - Cheby warning in test ([`56bf5f53`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/56bf5f538cefcc36f42c9a3bcba66c66bc68a410))
  - Cheby warning in test ([`35950c47`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/35950c4797f837a0ac85f5a293d2a69fabfd83f3))
- **psi-qapps**: 0.5.5 → 0.5.6
  - mark symbolic/numeric discrepancies ([`67073502`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/67073502a05a8025cff6b8ec9cf3cf5a849533d8))
  - further fixes for discrepancies ([`e161c4a4`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/e161c4a4487ad4e46ae1e2e46fbd157bb211ee46))
  - mark symbolic/numeric discrepancies ([`60035633`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/600356331e86d8fee00485c1766e05d157a39ec6))
- **psi-rex**: 2.2.1 → 2.4.4
  - bump common ref to 0.2.0 ([`fd656d97`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/fd656d97a2669ae90dfe4847038beecb9c11a1ba))
  - label qrep metrics for centralized observability ([`c9bc865e`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/c9bc865e157897b813d06cf020368f5fa1444465))
  - correct Alloy relabel replacements ([`a63d00c2`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/a63d00c28838da74519bd066f153ca62a6a7eaa7))
  - skip notebook imports without examples deps ([`8dfb77b7`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/8dfb77b7538de5fc773ed6f342a10e1c5f36c59f))
  - add construct-tools explicitly ([`1692bf4a`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/1692bf4a228947eec3cd9ff60066339843869e58))
  - convert CHANGELOG.md to python-semantic-release format ([`0ed143db`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/0ed143dbc21a579feb9cc5109fca54fa0b3eb146))

### Performance Improvements

- **psiqworkbench**: 4.33.6 → 4.35.2
  - Add in test optimization from #1274 into #1297 ([`4c3941bd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4c3941bd98417af383f162b0eeb3dcc70c6edd50))
  - Added parametrize ([`e909eda5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/e909eda561375828965f6918e6f6cfbd1e4c7bb5))

### Documentation

- **psiqworkbench**: 4.33.6 → 4.35.2
  - replaced commitlint README section with MR title linting docs ([`23e328b2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/23e328b2a8c944975971204106b2f55560705816))
  - Add example notebook with CD conversion ([`19060856`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/190608563e28a34acc47e9e379ed1f09eedf8ef1))
  - Refresh notebook ([`3460a1ad`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/3460a1adfb81654fd460c92253ca8fea64cc33b4))
  - Update WB -> CD notebook to correctly discuss expand kwarg ([`11c6c3af`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/11c6c3af60e68703938fff49449a30d90487d503))
  - Fix typo in docstring ([`8cc6a342`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/8cc6a3427c6690754cccffc406a9e602d43c47cf))
  - Wrap Qubrick labels in \\text{} ([`76bb7c0d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/76bb7c0d79ad61de6c6de00074891cf18130f96c))
  - Add basic docstrings to QPU ops. ([`cc21252f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/cc21252f5d6b29179c1a3e926e35b3c8c6ba8a52))
  - Place comment about QPU_op where it should be ([`6f2b2592`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/6f2b25926b9e5ae75fa40242c781eb090014b729))
  - add 'Basic numeric QREs' tutorial ([`c40e97a5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c40e97a5fa4edfedf94973a52c7081faf9d238cb))
  - outline CUDA-Q simulator tutorial section ([`a00e1964`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a00e19641371b579c0488ea86f5b6a8dd7ec470f))
  - fix reaction depth example ([`dc4eae05`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/dc4eae0559d3f51301a5e0fd7b3c5bbd38cb8232))
  - remove reference to igraph in example ([`0a0a7c37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/0a0a7c37a222329cfd34e276f3f3cf6bfe1fc67a))
  - add basic numeric QRE how-tos ([`1eef3f4e`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/1eef3f4ec6fa518dbb9feb4d06bc387b93100089))
  - improve API docs for ppm and peek_ppm_probability ([`8d0874ae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/8d0874ae46c7d4bf63c401642184eb379727dea7))
  - clean up API docs ([`9746ee36`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9746ee3690c5ee856d722359e0c10f519e3d7682))
  - Update comment ([`c04a3a48`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c04a3a48622109bc2eee0c07221a5512e365735a))
  - add 'Advanced Gates' tutorial and docs map ([`d0dcb980`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/d0dcb9800b360cc3942c8c33671fe5184d108ce2))
  - outline CUDA-Q simulator tutorial section ([`fd169a66`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/fd169a66f5c0431d34aabe48de9046f4bd21e6e0))
  - add 'Non-standard Gates' tutorial and documentation map ([`b31221de`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b31221de1bbb1113bccbb584a969a05ff45f6c0f))
  - add CUDA-Q simulator tutorial section ([`6a915b8f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/6a915b8f8c776f12a08795e40717ea0076bc6e9a))
  - move items from private docs to examples ([`af4deddf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/af4deddf35a2db143959790112059824355d3791))
  - remove info about private docs from configs ([`df3b33c9`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/df3b33c9e79de3221f5ab59f3dd94045057f104f))
  - move items from private docs to examples ([`b7b53a14`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/b7b53a142d1c6e4f1e674fabc88754d95fe85fca))
  - add instruction about installing graphviz ([`5b10b8d1`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/5b10b8d1834284051b81a984a70001555bae6834))
  - update graphviz instructions ([`a1c3dfb3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/a1c3dfb356cf4054821d157284f0b92c1891e6db))
  - add instruction about installing graphviz ([`c608a635`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c608a635c1bcef9e231a5dc91441aa016432ab9f))
  - update Slack webhook variable reference ([`2d613258`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/2d613258e7dcefde5e2949a75cebc7f47aa852e7))
  - fix release notification channel name ([`21a29a93`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/21a29a93f2087e1b1d2bdc2dea247c18b1b6e4f5))
  - Unify internal and external docs builds ([`be16b893`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/be16b8934b655cc03777e1d972cf760b30c6252c))
  - Unify internal and external docs builds ([`d483881f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/d483881f3c3dbe529c23e4e361308669b906b858))
- **workbench-algorithms**: 1.13.0 → 1.13.4
  - add check for broken external links ([`31aaf3f1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/31aaf3f17b8423ab03c65b410aedf6c8d7992862))
  - add CI check for broken external links (AST-3728) ([`a6b9f3da`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/a6b9f3da0db84c1d7b2f82b91216b45a467949da))
  - exclude CondCleanBuild from qubricks ([`fb48c8ea`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/fb48c8ead932c0c66b23f06123a6fef8eb673532))
  - exclude CondCleanBuild from qubricks.md ([`73f64cb9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/73f64cb918cfd68a71dd2ea1e77dce10aaea7963))
  - update Slack webhook variable reference ([`3f1e9910`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/3f1e99106512276a0ab12df2324b578daff91a0c))
  - fix release notification channel name ([`964f9093`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/964f9093d0bc633f7e840abb10b2c96454b9538e))
  - remove filterwarnings('ignore') from tutorial notebooks ([`89ed6bc1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/89ed6bc100fa440ebd79d898ef733996e877c3c1))
  - remove filterwarnings('ignore') from tutorial notebooks ([`d56348d9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/d56348d987f9e8d9b8b519863a6cec04f48de9a6))


## [1.4.1] - 2026-03-17

### Features

- **psi-rex**: 2.2.0 → 2.2.1
  - backend implementation of the new algorithm taxonomy ([`68d0a969`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/68d0a969b06b039780d9024a6c2e60ffb8970690))
  - support multi-value expansion in array-mode problem instance params ([`f7ba3d28`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/f7ba3d28d7dee7dfd7ff206131fffed7e1a25b0b))
  - helpful exception for bad tag json. ([`c04c43ee`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/c04c43ee9ed7f6d4b26b3bb7a3b59d8f8beca849))
  - raise more specific error in place of UserError. ([`5abd9e8a`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/5abd9e8a03f53f4a162a4c5630345f411cb493a2))
  - raise specific errors rather than the generic `UserError`  user error in `algorithms.py` ([`981c3895`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/981c3895f7930b39affb36a0d0d0fe7df37ad397))
  - raise specific errors rather than UserErrors in `qre.py` ([`0313ba27`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/0313ba27a8c6e71dcc6e45a8ccdd9d714e97ea60))

### Bug Fixes

- **psi-rex**: 2.2.0 → 2.2.1
  - default spec tags are unioned with spec tags from metadata ([`95db6339`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/95db633929de19928d18af648bf8e29e635edc23))


## [1.4.0] - 2026-03-06

### Features

- **psiqworkbench**: 4.33.5 → 4.33.6
  - fixed unc bug in edge case for ltc and included this in tests ([`3e2f4c37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/3e2f4c3763eebc40eeec8405dc00c809a3a2ad95))
  - 18s for CC, 8s for Cuccaro ([`409d6fc2`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/409d6fc2f80342c10348f4649ed91103d048012f))
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - integrated the select and old tests passing but seeing weird warning about release of qubits and need to test ctrl case ([`b2bd20d6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/b2bd20d649ad4af1f0dadc7cb202ae990467ad1d))
  - added smarted ctrl incorporation and all test passing for all Selects updating test to call interface. ([`43e6669f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/43e6669f9e700f8d7557e78bae9fa5b762dfa5d2))
  - pulling out ancilla assignment from test files and pytest parametrising select instance, fixing typos, removing unnecessary init ([`563e20bc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/563e20bc1ac22774e1534cba60261040069ba30f))
  - wrap selects in sorted to allow tests to run in parallel on workers ([`8b280b29`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/8b280b29464787880771a3ef509ccdfed690e00b))
  - adding explicit uncompute test and bumping WB version ([`8b442221`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/8b4422217917674b7c1a9fc08661a328aba5fff8))
  - warnings bashed ([`56d2982b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/56d2982bf2726abcd249b1b4ddd8fe4c4136fd9e))
  - pytest warn included ([`a1e16d4e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/a1e16d4e4a1d086065e14ca0b3cd4e8bc6b33f3a))
  - updated syntax in two qubricks to use reg.ppr vs. qc.ppr ([`a8e99787`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/a8e997879e731a316aafd3cd5ff8e26d93fa8927))
  - removed unused lines of code ([`f0c3eae0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/f0c3eae0170979b8f368753b71a32895e99674e2))
- **psi-rex**: 2.1.1 → 2.2.0
  - support getting runs as a CSV ([`40f78277`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/40f7827725b2e5fd99713c3b9c72fc2ce863e32a))
  - add algorithm metadata and problem registry for lattice hamiltonian" ([`99b4f68d`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/99b4f68d9e756e78e4c2bff08658bfa34339eae9))
  - support case insensitive substring matching ([`458c1c3c`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/458c1c3cad3c7cca95552d6a666fe07fed76ffc0))
  - define new job tag database model and add repository logic ([`a06cc8d1`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/a06cc8d119f5da4c69540809d87cdcd446e0b5d8))
  - update the API and SDK to use the new job tags ([`a51e53b9`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/a51e53b9f265e76456bb1f46735ae2e908d373a5))
  - add filtering on job tags ([`9ee68bf2`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/9ee68bf28d38b6dc9d65d343efffe191fe4a77a7))
  - update example notebooks to use set-style tags ([`53cb673a`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/53cb673ad8ef979ac4a3a8736be71736d8c1fc7a))
  - improve error response for authorization errors ([`cf28575c`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/cf28575c21caf8f3c1a1ed3fa23f3833c58bc30f))
  - make errors for storage problems more descriptive ([`3e8d62fb`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/3e8d62fbf9576d3ce9881c7207cb0fdf19e1f5e0))
  - add an endpoint for retrieving all job tags for jobs matching a filter ([`90cf96fd`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/90cf96fd5d946942c3a9aa5337f66e72819ed616))

### Bug Fixes

- **psiqworkbench**: 4.33.5 → 4.33.6
  - Test building 6 flavors, both pinned and unpinned ([`928b6a89`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/928b6a8999a3e89a7985a3aac4ca4147f67dfc62))
  - Test unpinned default build ([`54259d1a`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/54259d1ae89afb93dd74bfdf2c19192631702e14))
  - Try to force no bookworms ([`1c5b6e74`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/1c5b6e74695c57344a052c76a2434065006a02eb))
  - Again, try to force no bookworm ([`7087f805`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7087f805d49557b96ddf0a7645585ad1525d4127))
  - reduce number of unnecessary warnings ([`760b0cae`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/760b0cae5c53eb3648483d05f1a9ec039b72c763))
  - Signed/unsigned errors and warnings fixed ([`112dd4d5`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/112dd4d5225a463cf86d0bdd55127f484d399e01))
  - debugging CICD fail ([`c6af53c8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/c6af53c87214af28d04287c1eed594d64b05323e))
  - Try to install just the compatible wheel and relax when the incompatible ones fail ([`57c50d0d`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/57c50d0d3e315652bf8d4625669b85a6134c55fa))
  - See if we can autodetect the correct one ([`edc399f0`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/edc399f0edacbbbb150e6e552588d6bc8fa170c4))
  - Try to install just what's compatible ([`d4520c5f`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/d4520c5fef2fa24b173b723768efdd1720c65df3))
  - fix typo per MR feedback ([`81c712b3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/81c712b36de7fb2b179612822bf50dd5b42593f6))
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - Fix a few deprecation warnings ([`f6411850`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/f64118501767a6de173fc50011cf063145af0c1c))
  - fixes for AV in symbolic select ([`042d5d9c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/042d5d9cc53cf16abc258d340a9014c5ba2161da))
  - fix QREs for controlled selects ([`e56f5ad3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/e56f5ad34e0b492429b9017ca88f388cc76132a9))
  - fix trotterization to use Y weights ([`3a3afa44`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/3a3afa44c3c9ef7b00000a669d2e37c26a842f9b))
  - remove warnings by skipping incompatible pairs of register sizes and basis states ([`b7e6d447`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/b7e6d4479c9fdad81dbd909f7db3d7607d60d57a))
  - remove warnings of duplicate flag arg in compute ([`f74f0966`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/f74f096644c39bc824f995191cd70c9a8b1a1b6f))
  - reducing the size of the system to stay within memory bounds ([`41b06736`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/41b067360859695cdc79092d738b878e890de535))
  - only passing in valid tuples of basis state and size of system ([`5d348d08`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/5d348d08cab314942d125cb186591130b9b7b562))
  - changing size of system to stay within memory limits of workers ([`99471e93`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/99471e932dbfedcbd24fd54145d9964eef0c3739))
  - remove warning from block encoding duplicated be_ancillae_reg arg ([`99a9d276`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/99a9d27664cf6cd829eaf6772ae61bbf41b77a14))
  - remove test warning by adding pytest-repeat to pyproject ([`d7a0f000`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/d7a0f00022996d1751d995f9021fe853249e15c9))
  - test release ([`5e55e064`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/5e55e064e6df63e08a51e25d4342011166d37823))
- **psi-rex**: 2.1.1 → 2.2.0
  - include more debugging context for internal server errors ([`44b445c3`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/44b445c3f5cc20ef92c81c99924efcff16a626c3))
  - add reasonable fallback behavior for exceeded job completed count ([`ae370467`](https://gitlab.psiquantum.com/applications/core/psi-rex/commit/ae3704673407b56a599efee255275fe6159fa18e))

### Documentation

- **psiqworkbench**: 4.33.5 → 4.33.6
  - fix issue with broken w3.org links ([`2e735561`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/2e735561dfcafb5d1217272baa978cfc3dc2a32e))
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - replaced commitlint README section with MR title linting docs ([`f9f202b5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/f9f202b5dd9345e7539d0c7edabdd4983227ba0e))
  - updated README.md with release flow and mr-title-linting ([`72dafd43`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/72dafd43688bb3161a1197894f90f754f3364b67))
  - minor docstring changes ([`b1153642`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/b1153642a09ece98f64ed90fb9e2b1b68638496a))
  - replaced commitlint README section with MR title linting docs ([`be1fb50c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/commit/be1fb50cdae52af8357e0fd3758fe75b2890678d))


## [1.3.0] - 2026-03-02

### Features

- **psiqworkbench**: 4.33.2 → 4.33.5
  - all warnings bashed ([`3c0e02ec`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/3c0e02ec07a4ed3ec6e1795819d3357b7dd4bae6))

### Bug Fixes

- **psiqworkbench**: 4.33.2 → 4.33.5
  - fix cswap handing in UnitaryFilter ([`74d41ced`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/74d41ced604bd677831a58d7d7e0a10c5c3aebff))
  - control only the center CNOT in controlled SWAP ([`9887b0ee`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/9887b0eebe1c21b33c07b51483378faa52d669cc))
  - check for catalytic T warning checking ([`4e820fdd`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/4e820fddc580ee5e87f3665d21ea4082fad0b53b))
  - check for conditional RS warning ([`7745c3a8`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/7745c3a829e1b64743a4b0b05e7d7cca26f764c3))
  - get rid of DeprecationWarnings ([`650b6cd3`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/650b6cd3d78de32344a7d6df310780fdcbbe1b67))
  - remove warnings triggered when expected ([`e2a71faf`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/e2a71faf86226ab4a80b29be7416f6da16220097))
  - Remove AWS version file from version update script ([`f4f58e92`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/f4f58e924596ca390109421bdc31f378506b05c7))
  - remove all aws references from build scripts and .gitignore ([`0b752f37`](https://gitlab.psiquantum.com/applications/core/psiq_workbench/commit/0b752f37dc85935e1a52430682c7de3e3f75acaa))
- **psi-qapps**: 0.5.4 → 0.5.5
  - move trivial givens tests to their own test ([`a65f45ad`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/a65f45ad6ea26d7558bf131984055bce4f1331e1))
  - move trivial givens tests to their own test ([`07c19b3c`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/07c19b3cc82369b11572ea7781c3c64aa17ba711))

### Documentation

- **psi-qapps**: 0.5.4 → 0.5.5
  - replaced commitlint README section with MR title linting docs ([`ec13a87d`](https://gitlab.psiquantum.com/applications/core/psi-qapps/commit/ec13a87da7796ea83f580099d9e95b410da08807))


## [1.2.0] - 2026-02-23

### Features

- **psiqworkbench**: 4.33.1 → 4.33.2
  - added Cuccaro and benchmark graphs
  - Implement forward referencing of labels
  - Implement helpers for register-tracking
  - Implement missing details of RegisterTracker and MaskBasedTracker
  - Add utilities for converting ops to abstract events
  - Add base class for CD serializer
  - Add stub for circuit designer serializer
  - Implement public interface for Circuit Designer serializer
  - Implement serving exported diagrams directly to file
  - thinning code examples and other style changes
  - thinning code examples and other style changes
  - Add s and t to gate mape
  - Add support for exporting missing ops
  - Add explicit input registers to routines
  - Use correct control type with phase operation
  - Wrap labels in \text{}
  - fixed bug and added test for >2 ctrl op's.
  - adding list option to get_filter_by_name
  - improving test and removing dead code
  - wrap returned implementations in sorted to allow pytest parallelisation, update test_tags, and separated out adder interop test file
- **basquiat-adapter**: 0.5.1 → 0.6.0
  - make basquiat types public.

### Bug Fixes

- **psiqworkbench**: 4.33.1 → 4.33.2
  - Remove nonexistent LabelType from __all__
  - Remove nonexistent import
  - Fix typing errors
  - Make display label for subroutines correct
  - Remove unused variables
  - Reuse variable instead of calling get_instructions twice
  - Remove unused imports
  - Remove debug print
  - Implement support for PPMs and PPRs
  - fix pyliqtr calc and switch off warnings
  - fix main call in test
  - Make registers bubble up when finalizing qubrick conversion
  - Use cnot gate type instead of plain "x"
  - Fix how registers are sifted up
  - Fix handling swap in compute_args
  - Fix typo making controL_type for phases incorrect
  - Remove unnecessary pass statements
  - removing print statement
  - returning single filter option correctly
- **workbench-algorithms**: 1.11.0 → 1.11.2
  - fix AV estimates for TrotterQuery
  - fix estimate for BinaryToUnaryUncomputation
  - angle type HWP + PhasingCircuit
  - ctrl rz (WIP)
  - reorienting on rotation_encoding
  - adding poetry run
- **psi-qapps**: 0.5.3 → 0.5.4
  - remove KPI 6 references from DF-THC notebook
  - fix typo in notebook
  - get rid of DeprecationWarnings

### Documentation

- **psiqworkbench**: 4.33.1 → 4.33.2
  - Update example names in RotationEvent
  - Fix docstrings still mentioning serializers
  - add basic howtos
  - replace 'how to define routine' example with ReflectAboutMean
  - adding correct capitalization
- **workbench-algorithms**: 1.11.0 → 1.11.2
  - improve docstring
- **basquiat-adapter**: 0.5.1 → 0.6.0
  - removed superfluous readme content

### Other Changes

- **qref**: none → 0.11.0
  - Added new component: qref 0.11.0
- **psi-qapps**: 0.5.3 → 0.5.4
  - Bump version to 0.5.3
  - Resolve "AST-2956 remove references to internal KPI for DF-THC notebook"
  - Fix basquiat adapter dependency conflict
  - Bump version to 0.5.4
  - AST-3294 Fix deprecation warnings


## [1.1.0] - 2026-02-05

### Features

- **psiqworkbench**: 4.33.0 → 4.33.1
  - add discrepancy decorator to comparators

### Bug Fixes

- **psiqworkbench**: 4.33.0 → 4.33.1
  - intermediate stage of fixing AV of PPRs & PPMs
  - intermediate stage of fixing AV of PPRs & PPMs
  - fixes calculation of z_mask with control
  - fixes calculation of z_mask with control
  - add default functions_map
  - fix some edge cases for symbolic ops compilation
  - fix issue with av for ppm
  - fix import problems
  - change idx mechanism in catalyst to using ARBITRARY_ANGLE
  - remove unnecessary logic
  - First pass at a fix for #1249
  - fix issue with wrong defaults in default_functions_map
  - add missing known_discrepancies for GidneyAdd and RotationCatalystHandler.
- **bartiq**: 0.16.0 → 0.16.1
  - correctly handle custom functions in repetition count (#280)
- **basquiat-adapter**: 0.5.0 → 0.5.1
  - test patch release of basquiat-adapter - ignore
- **apps-hardware-modeling**: 0.2.0 → 0.2.1
  - test patch release of ahm - ignore

### Documentation

- **psiqworkbench**: 4.33.0 → 4.33.1
  - update docstring of ResourceTolerance
  - improve Qubricks docs based on mentees' feedback
  - address Ian's comments
  - fix wording in docstrings
  - updated reg issue in releasing qubits

### Other Changes

- **construct-tools**: 0.10.1 → 0.11.2
  - New features: 0.10.1 → 0.11.2


## [1.0.0] - 2026-01-29

### Features

- **psiqworkbench**: 4.30.6 → 4.33.0
  - CC MUX (old and new constructions), CC arithmetic (old) and new filter constructions
  - toffoli window filter with cond clean MUX
  - working CC MUX example with pre_filters to catch x's and toffoli's. TODO compare to recursion version
  - refactored CCBuild and Arithmetic Routines. Resource estimates for CCMUX, DataLoadDirty ...
  - unifying qubricks with abstracted partial compute function
  - Adding more arithmetic routines
  - refactor LessThanConst to utilise parity checks on constant
  - fully tested less than constant utilising parity and early stopping. separating out work and adding doc strings.
  - organising files, adding doc strings, tinkering with recursive mux
  - add test for toffoli window filter
  - fixing test and imports
  - tests working with pytest
  - added all doc strings, all tests passing
  - ej example filter breaking
  - qubricks for cuccaro addition with tests
  - added edge case
  - updated dirty ppm functions to now include the block cost of bridge qubits, also implemented a small cost optimisation.
  - First pass of state vector classical checking
  - added example notebook and deleted debugging files.
  - interface to alter bits of precision for rotation.
  - update pi/4 rotation function to use one of 2 formulas depending on y parity.
  - change get_pi_4_ppr_av_cost to calculate both methods of doing the pi/4 rotation and then return the minimum cost, as this is more robust and has a minimal impact on the computation cost.
  - updated pi/8 function to use X or Z for state injection.
  - added optimised ctrl H to av and ssc lookup tables.
  - added a comment to mention that ppms outcomes must be interpreted differently for y_injections.
  - second pass at auto-clear classical qubits on free
  - added pi/16 and 3pi/16 PPR rotations as well as some updates to the AV lookup table.
  - changed filter to work for any self-inverse op. made partial_compute qubrick to avoid reverse input and utilise dagger. small chore's from MR feedback.
  - added rx, ry, rz support for theta = 90 as this are just control paulis.
  - add docs references, add QInt testing fro incrementer, adder. Remove cond input from CondCleanBuild.
  - added stale state count formulas and logic for 3pi/16 PPR rotations.
  - added carry input for subtractor functionality,  added tests for QInt, added doc references
  - adding QUFixed, QFixed testing pyres
  - adding QUFixed, QFixed tests.
  - Track classical values for warnings
  - adding option to  do controlled qubricks. translated to AddBase but not all inhereted tests passing instantly.
  - Cuccaro with AddBase passing all tests
  - include MAdd
  - borrowing naive adder for quantum + classical value for multiply add to work with QInt
  - added doc to link tl formula derivations.
  - added more tests and fixed test values for new code. CH is not a support op also.
  - added references to AV derivation files.
  - add a comment to explain the location of CX and CZ gates in the test file.
  - transforming adder to AddBase and making ctrl case apparent for incrementer. Notebook with possible bug case in AddBase.
  - hybridising Cuccaro and Gidney for lhs > rhs addition.
  - AddBase versions tested.
  - sign extension and carry-in, slight bug left with combination of sign extension and carry-in
  - final optimisations
  - final tests tidyup
  - add initial typing to print_state_vector
  - Built-in support for pygridsynth
  - Add pygridsynth and mpmath as optional dependencies
  - Allow selectable synthesis filters
  - Add witness_qre-analysis serialization dialect
  - adding sorting for typed register values
  - fixing argument names
  - add newlines and progress bars
  - speed up node removal
  - enhance progress iterator with improved ETA calculation
  - Refactor path checking and predecessor caching in DAG construction
  - rename instruction_dag to operation_dag and update related logic for clarity
  - Iteration on zero-assert in #648
  - Simplification iteration
  - deleting unused file, EJ fix for bug for deferred result
  - deleting dead code, adding more comments, temporary tutorial notebook
  - adding Cuccaro to quantum arithmetic doc
  - add padding for floating point values
  - coverage 92%
  - pragma cases
  - 100% coverage
  - Implement Overridable class
  - cleaning test file
  - Add overridable objects to QPU
  - doc fixes, CC ltc edge case caught, made CC tests more efficient, tutorial notebook for benchmarks (to be deleted)
  - added a comment and a fix strat for incorrect dag construction.
  - Allow computing RS AV when precision is symbolic
  - Implement overriding epsilon for SymbolicQPU
  - Implement overriding symbolic catalyst rotation epsilon
  - Implement overriding epsilons per Qubrick instance
  - Add support for error_param for PPRs
  - First pass of event reporting system
  - Event system first pass
  - wip-stack-collection
  - add support for pull_state_specific to bit-qpu
  - Assert if bit-sim error detected
  - adds payload ancilla when non-Pauli and most tests passing. need to update dirty ancilla version
  - WIP, first pass unhooking the 64bit converter
  - Move 64bit conversion into cpp conversion
  - all test passing
  - removing partial call and adding swap to self-inverse ops
  - adding sparsity trick for CC and edgecase fix for Cuccaro adder
  - adding hermitian-window-filter to docs and removing ctrl (added to work with WBA which is now its own MR)
  - initial commit
  - adding select test specifically for sparsity
  - Clear ops on reset per #1276
- **workbench-algorithms**: 1.9.4 → 1.11.0
  - added tidied notebook from sync. added merging functionality from this notebook to qubrick. passes initial test.
  - added phase merging, issues with amplitude merging (see notebook)
  - added complex vs real coefficient handling and test file
  - add clebsch gordan qubrick and test
  - add test for dagger=True
  - add composite reg for su2 mps
  - add example notebook
  - cleaning and responding to review comments
  - responding to review comments
- **psi-rex**: 1.9.17 → 2.1.1
  - add functions for serializing Job & Run filters to the API format
  - add a new job type without org_id
  - cache user info to reduce request volume
  - add a job reading method to the SDK, and paginated read methods for jobs & runs
  - improve error messages for parameter validation
  - add helpers for defining filters
  - make run counts public for jobs
  - update example notebooks to use job status
  - add filter metadata annotations and a filter metadata endpoint
  - add problem instance params to job metadata

### Bug Fixes

- **psiqworkbench**: 4.30.6 → 4.33.0
  - something is failing with the filter which is only obvious with MUX with grey counting
  - running more tests of filter mux issue
  - fixing me repeatedly mispelling cuccaro
  - update to _get_pi_4_ppr_av_cost function such that we use a more optimised formula.
  - Fixes for invalid cond_xor constructions
  - update entries in the av look up table to agree with the new formaulas.
  - accidently left some bridging cost addition in the table, these may be added back later.
  - fixed the dirty ppm function formulas to include y_parity in the return cost.
  - found optimised costs for ctrl Y and sqrt y, also update other clifford formulas to use the distillation of Y states explicitly.
  - added optimised cost for Y pi/4 PPR rotations. Also updated table cost to use Y state distillation cost instead of hardcoded 3 cost (this was previously missed).
  - reverted back to original function for pi/8 rotations as X injection does not work for T gates.
  - forgot about elbow->x replacements in filter
  - docs misprint
  - less zealous override for rotation
  - qint range
  - qint range and type hinting
  - Check that allocations are returned to zero when freed
  - WIP on the zero-check fix
  - add switches to different behaviors
  - updated reactive T measurement AV formula to be more optimal.
  - updated an incorrect comment.
  - fixed expected test results to match new AV formulas.
  - reorders thetas to be optimal.
  - updated get_stale_state_count_from_op tests to include new operations.
  - fixed the tests in 1113.
  - Start by removing cpp functions we've outgrown...
  - added 33.75 angle to _get_av_from_qpu_op_ppr_symbolic function.
  - simplified some code as t_cost is the same as reactive_t_cost.
  - changed import to t_gate_cost rather than the now disused reactive_t_cost.
  - fixed ppr numeric and symbolic functions for pi/16 and 3pi/16 rotations.
  - fixed 33.75 and 11.25 identification for the _get_stale_state_count_from_qpu_op_ppr function.
  - fixed typo in docs and improved readability.
  - WIP first success at c++ rework
  - WIP on C++ remap
  - updated docs to point to the new note for PPM formula.
  - made lookup table entries occupy only one line.
  - imporved readibility of the _get_3pi_16_ppr_av_cost function formula.
  - reformatted elif logic.
  - reordered lines the _ppm_injection_cost function.
  - improve code readability in _get_pi_4_ppr_av_cost function.
  - improve doc to provide a link to a note and state how classical interpretion must be updated.
  - changed divisors to integer divisor for if states in the numeric and symbolic get_av_from_qpu_op_ppr function.
  - WIP removing pybind11
  - LARGE change: complete removal of pibind11, WIP
  - minor cleanup
  - Set up more functions for external calling
  - WIP on C++ overhaul
  - More iteration on C++ rework
  - WIP progress on C++ refactor
  - WIP for C++ rework
  - removed white space for linting.
  - updated doc to say corrective measurements rather than reactive.
  - updated doc to use or new definition of reactive and conditioned corrective measurements.
  - Cleanup on C++ rework
  - Iteration on C++ rework
  - iteration on pybind11 removal
  - Iteration on C++ refactor
  - properly incref None to fix tests
  - Update poetry lock
  - Fix setup_legacy.py
  - remove straggling refe to the old lib
  - Move exception to a warning
  - Fix warning from mkdocs
  - Complete removal of the license and expiration systems
  - Migrate namespaces form Tau to PsiQWorkbench
  - Remove cpp from docs
  - Very small fixes
  - condition needs to default to 0 not none for interface tests to pass
  - caught bug in calling none ctrl
  - repeated test line
  - Fixes and cleanup per MR feedback
  - Remove unnecessary None case
  - Iteration on #648
  - workaround getting new message in qpu debugging when warnings turned off
  - change to list of messages to allow for mutability
  - remove elbow measurements, which are hiding errors
  - temporarily always enable debugging
  - poetry lock
  - fixes per MR feedback
  - Make default value for rotation epsilon 0
  - DAG should now produce the correct graph and run faster.
  - updated a comment.
  - refactored some code at the bottom of get_dag_from_instructions.
  - Remove capsys from printing tests
  - Remove unnecessary "error_param" user parameter
  - Fix handling of rotation epsilon override for catalyst
  - removed failing test cases from test_controlled_phase_special_angles_numeric_theta as they are not valid equivalent comparisons when written as controlled operations.
  - Remove incorrect changes to active_volume_lookups
  - Remove redundant assignment
  - Remove some leftover code
  - Revert meaningless changes to qpu.py
  - remove references to core_expiration.cpp from build and distro
  - Remove --skip-existing to try to work around a CICD server issue
  - Remove unused arg to get_gate_cost
  - Remove unused default value to compute_active_volume_rotation_ross_selinger
  - Remove leftover mentions of rot_bits
  - improve handling symbolic rotations
  - fixed symbolics for rotations certain angles
  - Fix returning of new array
  - Add simple stack debugging
  - remove additional string append
  - remove all 64bit references, add a test and a warning
  - remove commented-out exception
  - make interface extraction more robust to parallelization
  - Provide a much better user error on non-zero release
  - Simplify measured testing
  - fix tracking when we swap measured qubits with non-measured ones
  - Reduce the set of changes to get this delivered soon
  - further simplification
  - Minor typo fix
  - fix a few test issues
  - Sign-extension fix for adders
  - Fix lint issue
  - fixed per MR feedback!
  - New fail case from Mariia to handle
  - fix debugging feature so it works as requested in MR
  - Minor type fix
  - fix minor op counting error
  - all MR requests met
  - Update an old test to the new behavior
- **workbench-algorithms**: 1.9.4 → 1.11.0
  - now self consistent, issue with fidelity with original qubrick (see FidelityCheck notebook)
  - working qubrick
  - handling of unmerged uncompute
  - change Qubits | None = None to Qubits | int = 0
  - change back to None for HWP qubrick
  - update Givens' interfaces to be accurate to implementations
  - update alias sampling interface to match protocol
  - just remove the old Givens rotations args
  - fix interface registration for phase gradient adder
  - Remove outdated ALU tests
  - Remove outdated `subroutines/alu.py`, all tests still passing
  - update alias sampling test to use new debug tool
  - bump version in pyproject.toml so locked version can access debug qpu method
  - add discrepancy for USP
  - fix USP symbolic tests
  - fix usp discrepancy description
- **psi-qapps**: 0.5.2 → 0.5.3
  - updated tests to correctly count control hads.
- **psi-rex**: 1.9.17 → 2.1.1
  - return qubrick name + module, not python serialization
  - change job API to use substitution instead of re-creating the job type....
  - correct typo "problemset" to "problem set" in algorithm metadata
  - bug that lost job status information when copying
  - param validation logic allows optional params to be missing
  - accept integers as floats for problem instance parameters
  - make algorithm metadata names more detailed
  - use the json serialization for the consistent state when working with page tokens
  - Update test_build_wb_program_too_large_to_serialize for Workbench v4.32.1
  - clean up timestamps that did not have timezones
  - add a missed serialization for AST-2663
  - update algorithm metadata

### Performance Improvements

- **psiqworkbench**: 4.30.6 → 4.33.0
  - much faster 64bit conversion
  - speed improvement for 64-bit checking
  - Quick dive into why the witness takes time
  - 2x speedup for witness collector

### Documentation

- **psiqworkbench**: 4.30.6 → 4.33.0
  - adding outline of compilation deep dive
  - adding more to outline
  - adding clarifications to the compilation pipeline outline
  - adding examples to pipeline deep dive with extra verbosity to be shown during some passes
  - adding text and examples to the compilation pipeline deep dive
  - adding rough draft text for QPU section
  - edits for clarity, spelling, and grammar
  - adding batch filter messages, and more drawing
  - adding conclusion and edits from mariia
  - more edits
  - filling out links
  - remove autoreload, add to mkdocs
  - updating title to match file name
  - adding explanation of register type printing to testing-debugging notebook
  - adding a few fixes
  - adding deepdive feedback
  - adding fixes to docs and examples
  - sneaking in a typo fix
  - updating docs language and tests
  - Add missing docstrings
  - Explain purpose of Overridable class
  - minor clean up of API docs and tutorials
  - change comment about bit-vector simulator
  - update readme
- **workbench-algorithms**: 1.9.4 → 1.11.0
  - added warnings

### Other Changes

- **psiqworkbench**: 4.30.6 → 4.33.0
  - bug: filter now reducing gate correctly with normal but not grey counting
  - bug: ej test file
  - merge with master.
  - tests: Remove leftover qc.draw from adder tests
  - tempy debugging code added to bottom test of test_ops.py
  - commented out print statements for testing.
  - tests: Add QRE tests with epsilon-override scenarios
- **workbench-algorithms**: 1.9.4 → 1.11.0
  - sms checkpoint
  - playing around with more intuitive bit finding function
  - fixup! fix: add discrepancy for USP
- **construct-tools**: 0.9.4 → 0.10.1
  - New features: 0.9.4 → 0.10.1
- **psi-rex**: 1.9.17 → 2.1.1
  - Bump version to 2.0.0
  - AST-2572: SDK supports summary
  - Revert "Merge branch 'chore/incrase_staging_scale' into 'main'"
  - Bump version to 2.0.1
  - Bump version to 2.0.2
  - Bump version to 2.0.3
  - Bump version to 2.1.0
  - AST-2399 fix: ref to notebook path
  - AST-2858 fix: typo in metadata
  - AST-2762: numeric QREs compute without buffer/capture filter; no WB instructions made
  - Bump version to 2.1.1
- **apps-hardware-modeling**: none → 0.2.0
  - Added new component: apps-hardware-modeling 0.2.0
- **spoony**: 0.1.0 → removed
  - Removed component: spoony 0.1.0


## [0.5.0] - 2025-12-19

### Features

- **psiqworkbench**: 4.30.5 → 4.30.6
  - optimize mutli-target lelbow AV
  - added code to restructure_op that catches SWAP gates that have invalid arguments.
  - added tests for new swap gate validation code.
  - add support for zero target T, S, t_inv, and s_inv stale count
  - Mark RotationCatalystStatePrep as first-pass only routine for Bartiq
  - add random.seed() in set_param()
- **bartiq**: 0.15.3 → 0.16.0
  - add support for first-pass resources (#277)
- **basquiat-adapter**: 0.4.3 → 0.5.0
  - Alias basquiat serialization dialect to qre-analysis
- **psi-rex**: 1.9.12 → 1.9.17
  - incorporate the job association table into runs queries
  - script for backfilling qres with no job
  - add export to basquiat for symbolic qres"

### Bug Fixes

- **psiqworkbench**: 4.30.5 → 4.30.6
  - move lelbow tests to test_994
  - accomodate symbolics in lelbow
  - allow for no symbolics
  - simplify logic for get_gate_cost and fix 0 for s or z angles.
  - get rid of sympy
  - is_symbolic
  - we now only trigger validation logic for numbers, i.e. symbolics are fine. Also allow for target = 0 so other tests pass.
  - changed double quote to single quotes due to issues with f string.
  - lint
  - bounds check Nonetype
  - adding rel and abs tol to validate to prevent WBA upstream failures.
  - symbolic qres for controlled adder (and other qubricks)
  - move to tests/qre folder
  - testing downstream qdk triggers
  - fix bit length calculation
  - imports in qubricks.py
  - tests pass
  - rename to exclude number.
  - add symbolic tests
  - specified conditions
  - fix test_elbow_av_calculation_from_get_av_from_op_symbolic
  - fix lambdified resources for assert_resources_equal
  - update av costs for symbolic comparators
  - update QFT to give correct AV counts
  - add fix for old parameter
  - fix av cost for 0-target lelbow
- **workbench-algorithms**: 1.9.3 → 1.9.4
  - update n catalysts
- **basquiat-adapter**: 0.4.3 → 0.5.0
  - Remove child ids of ignored nodes
  - Correctly adjust total resources for repeated ops
- **psi-rex**: 1.9.12 → 1.9.17
  - change the SDK to only print the message about copying spec tags
  - add temporary debug lines for pagination
  - correct some spelling errors and fact-check the readme [AI]
  - include filters for algo_id
  - change server startup from poetry run api to python entrypoint.py

### Performance Improvements

- **psi-qapps**: 0.5.1 → 0.5.2
  - update df_thc_qre_runner to use lambdified resources

### Documentation

- **workbench-algorithms**: 1.9.3 → 1.9.4
  - removed installation instructs from construct for external users
- **basquiat-adapter**: 0.4.3 → 0.5.0
  - updated readme instructions for poetry v2
  - updated release instructions in README.md
- **psi-qapps**: 0.5.1 → 0.5.2
  - update notebook

### Other Changes

- **psiqworkbench**: 4.30.5 → 4.30.6
  - fix(get_av_from_op.py); delete redundant tests
  - fixup! fix: add fix for old parameter
  - fixup! test: fix tolerance for av in comparators
  - fixup! fixup! fix: add fix for old parameter
- **psi-rex**: 1.9.12 → 1.9.17
  - AST-2520 - 6 options for DFTHC
  - Allow VPN ingress for RDS in dev
  - Accept a "project" on job creation
  - Add a `run_filter` param for the `GET /jobs` endpoint
  - Bump version to 1.9.13
  - Translates job filters for algorithm
  - Bump version to 1.9.14
  - Postproc metadata
  - Hotfix/sql tests
  - Bump version to 1.9.15
  - Always include org ID in job filters
  - Numeric summ bug
  - Bump version to 1.9.16
  - AST-2378 feat: QRE constructor; applies cartesian product for list of params;...
  - Update dev-ops/common tag reference in .gitlab-ci.yml from 0.0.6 to 0.0.9
  - Bump version to 1.9.17


## [0.4.0] - 2025-11-25

### Features

- **psiqworkbench**: 4.30.3 → 4.30.5
  - updated _get_av_from_qpu_op_ppm such that single qubit x and z ppm have no AV.
  - added test for new single qubit and 2 qubit ppm optimisations.
  - Characterization notebook, second pass
  - adding verbose option to kwargs for qubrick to use
- **workbench-algorithms**: 1.9.1 → 1.9.3
  - temp fix for RZ and two adder version of Givens
  - bug results from unnecessary assignment of  PGA state and an issue with open control and phase fix up
  - got rid of extra qubit allocation for two adder Givens
  - fix bug with open ctrl
  - removed spurious qubit from RZ Adder
  - Add feature to __all__
- **psi-qapps**: 0.5.0 → 0.5.1
  - address reviewer comments
  - update notebook to use latest Bartiq functionality
  - Update notebook to remove resource explorer

### Bug Fixes

- **psiqworkbench**: 4.30.3 → 4.30.5
  - fixed the cost of single qubit y ppms. Now costs 5 av instead of 7.
  - single qubit Y measurement cost 3 not 5 as bell measurements are free.
  - moved new case logic from _get_av_from_qpu_op_ppm in get_av_from_op.py to _get_ppm_av in ppm_functions.py, this solves an issue with symbolics and a testing issue.
  - all resources except AV working
  - updated test for 1113 to use the corrected AV for a single qubit Y ppm.
  - updated hard coded AV in test file such that test passes updates to AV costs.
  - using preset instead of filter pipeline
  - Some fixes for USP, and the characterization notebook, first pass
  - AV working, code needs refactor
  - Fix for not-conditions in rotation synthesis, and re-run notebook
  - Handle error_param=None in reflect Qubtick
  - fix issue for handling specific angles for rotation catalyst with symbolic size
  - remove atomic attribute from Parameter
  - updated from deprecated function call
  - updated another deprecated function call.
  - fixing bug in roll_left and adding verbose check in qubrick
  - Coverage and cleanup, removal of unused stuff
  - Coverage WIP for #1236
  - Increase in coverage per #1236
  - Restore reverse_bitsa and add coverage
  - More coverage updates
  - More coverage improvements
  - use parameterize, per MR feedback
  - Fixes per MR feedback
  - Push expiration to Dec 2026
- **workbench-algorithms**: 1.9.1 → 1.9.3
  - fixed RZAdder case
  - slice PauliSum
  - raise Error type
  - updated symbolic estimate for phase gradient adder
  - cond_xor will only actually work if ctrl is first qubit in register, plus reflect handles all special cases
  - import
  - number of Ys
- **psi-qapps**: 0.5.0 → 0.5.1
  - migrate THC tutorials from on hold
  - address trivial review comments
  - minor changes per MR feedback
  - replace symmetric z-gates with reflect
  - bump WB version and lock
  - remove qc variables no longer used. That's sweet!
  - Update PGA catalyst pre-allocation to be compatible with new phase gradient adder
- **psi-rex**: 1.9.9 → 1.9.12
  - increase storage and add monitoring

### Documentation

- **psiqworkbench**: 4.30.3 → 4.30.5
  - Remove accidentally added link to QRE reference
  - Add 'Controlled Qubricks' tutorial
  - add allow_multi_qubit_ctrl info
  - add 'Built-in Qubricks' tutorial
  - address reviewers' comments
- **workbench-algorithms**: 1.9.1 → 1.9.3
  - add _compute to API docs
  - clean up warnings in _compute API docs
  - fix docstrings
  - fix documentation
  - minor cleanup

### Other Changes

- **workbench-algorithms**: 1.9.1 → 1.9.3
  - paulisum to sparse
  - doc: fix documentation
- **bartiq**: none → 0.15.3
  - Added new component: bartiq 0.15.3
- **basquiat-adapter**: none → 0.4.3
  - Added new component: basquiat-adapter 0.4.3
- **construct-tools**: none → 0.9.4
  - Added new component: construct-tools 0.9.4
- **spoony**: none → 0.1.0
  - Added new component: spoony 0.1.0
- **psi-rex**: 1.9.9 → 1.9.12
  - Bump version to 1.9.10
  - Bump version to 1.9.11
  - Bump version to 1.9.12
- **openfermion**: none → 1.7.1
  - Added new component: openfermion 1.7.1
- **pubchempy**: none → 1.0.5
  - Added new component: pubchempy 1.0.5


