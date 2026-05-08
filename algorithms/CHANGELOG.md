# CHANGELOG

<!-- version list -->

## v1.13.9 (2026-04-27)

### Bug Fixes

- Transient error attempt 3
  ([`5e0c4fc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5e0c4fcf8bb815b526b1cbee6d4b54ee32a9813d))

- Update logic for paulisum weights to get better agreement with numerics
  ([`934bb24`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/934bb24ed44954f019c7a38f67dd0eef287872d6))

- Update random pauli sum and use symbolic pauli sum in qpe test
  ([`02cfb0f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/02cfb0f5951b12c779e5ca3942be035030bded05))


## v1.13.8 (2026-04-24)

### Bug Fixes

- **ci**: Mark deployment and key reporting jobs as non-interruptible
  ([`a6e2428`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a6e2428bb3a921bd212c9a662689834e6a55c5fd))

- **ci**: Mark deployment and key reporting jobs as non-interruptible
  ([`082d536`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/082d536c79044f8232a399b9d0edc4127dd3397c))

### Continuous Integration

- Allow docs:check-links to fail
  ([`ba17a10`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ba17a10723e437de58c7e0e0b43bb74823aee0bf))

- Remove poetry.lock and add to .gitignore
  ([`f8a029c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f8a029c380f7d862e456ba6aeaa66d6d6bb3ef50))

### Documentation

- Add agent guidance
  ([`ac1383b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ac1383b8ec9c4b2682c9e39fdef869911550eeae))

- Add agent guidance
  ([`35cff21`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/35cff21bb507ec5cc1e809bb8ab56a446fcff139))

- Replace poetry with uv in AGENTS.md
  ([`2551daf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2551daf530a586abfb4840c1b72fc9d40ba98296))


## v1.13.7 (2026-04-23)

### Bug Fixes

- Compare deprecation deadlines with numeric version tuples
  ([`6276e7b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6276e7b074c7091ebb850b30e463579e2135396f))

- Compare deprecation deadlines with PEP 440 versions
  ([`6fa959d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6fa959dd46baae0e054bc2d59d35d25b4539bad0))

### Chores

- Fix bug in warning handling
  ([`370387b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/370387b397ffdd3de1061e87c05c87e2e5cae35e))

- Remove su2 qubrick and tests
  ([`5a0f539`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5a0f539801afc3c4590721557e4787477b2fb1ad))

### Code Style

- Fix lint error
  ([`fb25fe0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fb25fe0ef50dbb0e9832d1410b32e1499b2b2d34))

### Continuous Integration

- Align notebook stderr warnings with PYTHONWARNINGS filters
  ([`2f15add`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2f15add5fe6b10ff8062bfb2a1daa5219d73db31))

- Simplify example warning enforcement to notebooks only
  ([`d7f2090`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d7f20901fc9872c80b22b263dadb4a69f81d4d09))

- Treat example warnings as failures
  ([`dd4046a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dd4046a0ba7bd1251cdbf9feaabb6839dc3499b5))

- Treat example warnings as failures
  ([`be5c89f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/be5c89f1ce26b01b9dacbc9dacab7d014658f5a1))

### Documentation

- Add Documentation Map
  ([`0e7cb9a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0e7cb9a4a2dfc47e9f303c47b552ca1ed36b4289))

- Explain the role of 'experimental'
  ([`f9a87e9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f9a87e9e09fd608dce258b8daac81a3fc51c360c))

### Refactoring

- Parse dotted versions with a single regex
  ([`74ac6e8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/74ac6e8ec1d62047744d54ff25548a3d63b93a37))

- Parse leading version segment with int() prefix
  ([`b09e3cf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b09e3cf6f788bc659d85f7b5a25596a3e2c44e83))

- Parse version segments with regex
  ([`70c390d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/70c390deeeb4d1ee2cb96bc142e29774bcb5674c))


## v1.13.6 (2026-04-20)

### Bug Fixes

- Resolve "Update AV in tests"
  ([`865767f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/865767f9081e88a6b0923654a9a3621241ca2fdc))

- Use FutureWarning for deprecations
  ([`9a1da61`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9a1da617c08fc60b0facdebd08faa932893adb90))

- **test_select_symbolics.py**: Increase the bounds on the av for tests.
  ([`2e1cb11`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2e1cb1149df43b5f68e755420dab0ad671827e50))

### Chores

- Bump ipykernel version
  ([`f9f88e3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f9f88e349c77db447cbf27a94190e879f5fc7f17))

- Bump jupyter version in examples group
  ([`ba4af2c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ba4af2c9dbb61bd34bffe4a6ac6007c3eeb8e795))

- Emit FutureWarning for deprecations
  ([`ca7433c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ca7433cdd62ea866a9dd0021e31f9f16dfce08bb))

- Migrate WBA to uv
  ([`64052d5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/64052d57e7609979220932344954663ba259e068))

- Migrate WBA to uv
  ([`eaed3bd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eaed3bd625cfc5341bf3fe80a00bf9773a372904))

- Remove dependency on ipykernel and contrain scipy during tests for Python 3.13
  ([`bafcb01`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bafcb016b2255cee15c4d103d507dfdcd1884bb5))

- Remove direct dependency on ipykernel
  ([`518b348`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/518b348bb9e28d092ed34ef44cf74bc41640acad))

- Restrict scipy version to >=1.15.0 for tests group
  ([`a6cce6d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a6cce6dc10d78c224e99eead606345ca7b7810ad))

- Temporarily lower jupyter version to trigger failure
  ([`a353b2d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a353b2da86a2d98cf16938119d4a4e7a9765eb06))

- Update tolerance for qpe qre test
  ([`b06809f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b06809f2f777d711e98e55d7d8afda5bf099e6b3))

- Update tolerance for qpe qre test
  ([`245526d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/245526d68f8d05f4a7e99d553eac8f1a9b8fa37d))

### Continuous Integration

- Fix semantic-release GitLab domain and merge commit parsing
  ([`884bb81`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/884bb8192daf55e05c3c1da8afa805c9e7181560))

- Fix semantic-release GitLab domain and merge commit parsing
  ([`723a422`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/723a4229afa7c924e7850f9e5008ea0bd7096884))

- Increase number of pytest workers to 8
  ([`9bb186a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9bb186a08ceec64da01268fb3a582196517ac7e5))

- Increase number of pytest workers to 8
  ([`b44f8ba`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b44f8babd8576dc546a81aa6d1f96bd7897a950d))

- Streamline uv sync and uv commands
  ([`a624481`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a624481c3db0b050429432f5a6c9408a3a15ff5f))

- Streamline uv sync and uv commands
  ([`b7260b9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b7260b912028ad42c57f4e89060094d4212154b1))

### Documentation

- Update Data Loaders (QROM) tutorial and API docs of mentioned Qubricks
  ([`694ec65`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/694ec6562f0c7d3818fdf9333da55c108c66f571))

- Update Data Loaders (QROM) tutorial and API docs of mentioned Qubricks
  ([`f2f8f22`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f2f8f2254d5bef45b24f7d723cb05d84740dafa0))

- Update SwapUp + InjectOp tutorial
  ([`b524aa5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b524aa5c8e57cea336f5404ef910ee5831acfa67))

- Update SwapUp + InjectOp tutorial
  ([`ce17e47`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ce17e474097e5c20f633de486d4b30e51c893c8f))


## v1.13.5 (2026-04-13)

### Bug Fixes

- Set random seed in qpe qre test for deterministic behavior
  ([`56d271b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/56d271b8f2352cf0dcddc0ef01e8d45c9479337f))

### Chores

- Fix regex syntax
  ([`e630bb0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e630bb0d6c857ed6e5667090f157e38247e4eb64))

- Isort
  ([`0a87c9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0a87c9bc4ea53e61b828d291e5d18285bd8b492a))

- Rename google selects
  ([`7e00602`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7e00602cd22d37c7997badc06cfba4247940d89f))

- Switch over selects to new class name
  ([`aa29f1e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aa29f1ecc7a17d37f7f1431329e20fdae8215a0e))

- Update documentation to remove deprecated functions
  ([`9468f31`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9468f31ea391857319c2a6db31faa08cc38c34c4))

### Continuous Integration

- Added project-specific webhook for release notification
  ([`01f0fdc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/01f0fdc3e125955169b079195c9e73ecd4cd6acf))

- Updated dev-ops/common include reference from 0.2.0 to 0.2.1
  ([`3a3d8c4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3a3d8c48e424b755cbe29d51b97122a4a50ecf41))

### Documentation

- Add tutorials to mkdocs nav
  ([`287b785`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/287b785712b2ed1298f4e5b7ff819109ea823655))


## v1.13.4 (2026-03-24)

### Bug Fixes

- Cheby warning in test
  ([`56bf5f5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/56bf5f538cefcc36f42c9a3bcba66c66bc68a410))

### Chores

- Deprecate CODEOWNERS
  ([`5399906`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/53999067936de0ea023b81eb04168c3484877d78))

- Remove source code from API docs
  ([`e94cfc0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e94cfc073a642abbd0c3b91a767f0b4339492fd2))

### Code Style

- Fix isort
  ([`adbc4fd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/adbc4fd2e089b4a74d103f89d339e109a1614a4f))

- Fix style issue
  ([`958ce3c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/958ce3c8dd34c190158ff7c123166cfa7b2c0339))

### Continuous Integration

- Deprecate old webhook URL variable
  ([`1831cfb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1831cfb067aa8c930f429515592857655827735d))

- Fix error in lint job rules
  ([`c8428c1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c8428c1732738fa0807fe93a8b135c67cec5a105))

- Remove .gitignore file sorting
  ([`5f4347f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f4347f115898e71c230740681655a6b7b785ecc))

- Updated dev-ops/common include reference from 0.1.6 to 0.2.0
  ([`d3c895e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d3c895e46dba802b820dbd4b29d8f118052e046f))

### Documentation

- Add check for broken external links
  ([`31aaf3f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/31aaf3f17b8423ab03c65b410aedf6c8d7992862))

- Exclude CondCleanBuild from qubricks
  ([`fb48c8e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fb48c8ead932c0c66b23f06123a6fef8eb673532))

- Fix release notification channel name
  ([`964f909`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/964f9093d0bc633f7e840abb10b2c96454b9538e))

- Remove filterwarnings('ignore') from tutorial notebooks
  ([`89ed6bc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/89ed6bc100fa440ebd79d898ef733996e877c3c1))

- Update Slack webhook variable reference
  ([`3f1e991`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3f1e99106512276a0ab12df2324b578daff91a0c))

### Testing

- Add discrepancy for AV in QPE
  ([`37bfb7d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/37bfb7dc4f21d71144003f94b55469f6de0b4da4))

- Minor changes in alias sampling tests
  ([`7eef123`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7eef123b76232b59b8bdccc87f7721a0de7038f2))

- Test_alias_sampling_symbolics.py
  ([`12cdef8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/12cdef899ff598657c8b3e110bbb06bd37aa2a7d))

- Update tests for PhaseGradientAdder
  ([`07ffde7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/07ffde710ea2b4f2532d705d456c78cf2ee905ca))


## v1.13.3 (2026-03-13)

### Bug Fixes

- Fix discrepancies for several qubricks
  ([`555ce85`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/555ce853179873cd573e989f4f18fdfd27f7b8a1))

### Chores

- Fix known warnings in examples
  ([`49e45ec`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/49e45ecc5b64c0ccad094054ed2155e45d80096f))


## v1.13.2 (2026-03-10)

### Bug Fixes

- Fix bug with numpy arrays as inputs to DataLookupClean
  ([`6500793`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6500793c7790da461e189430adb23a8236b51173))

### Chores

- Bump WB dependency to 4.33.7
  ([`5360d95`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5360d952b53acaad7f4c4ee34a106d9dafb61a19))

- Update docstring
  ([`395ef93`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/395ef93f4836892431c21819a5d6695d784a924e))

### Code Style

- Fix isort issue
  ([`62ce322`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/62ce32217c8e71be3d7aeaa61aaf90b90d67a0fa))


## v1.13.1 (2026-03-03)

### Bug Fixes

- Release trigger commit
  ([`a449ec8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a449ec891cad5ed9076de293196be46efbc405fe))

### Chores

- Remove psi-liqtr dependency
  ([`62743e0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/62743e09111b888382cf1f2d51c0faeae8bbe746))


## v1.13.0 (2026-02-27)

### Chores

- Remove unneeded commitlint config and pre-commit job
  ([`8c20210`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8c20210cd2e87d060e396ed2f9b2526c8e5a5a9d))

- Remove unneeded commitlint config and pre-commit job
  ([`c8d346e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c8d346eeb6e411cd805963c1192f32060ed60191))

### Continuous Integration

- Bumped dev-ops/common dependency to 0.1.1
  ([`cc362e3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cc362e3c56d1fa21ff5726e3a45e18291c25c5cf))

- Delete set_version.py and merge main
  ([`c2f12ea`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2f12eae5f2b15c278c5e7dd96aa50165b6b55b6))

- Implementing central release jobs
  ([`622d4a7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/622d4a7906b6541dc210b1d54db395f43147c134))

- More fixing of central jobs
  ([`5b7219b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5b7219b2265d7fe4244e0cbb9999e50e2ae93b7c))

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0
  ([`2270a47`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2270a47598cd52ae98b62659b1b2088df65797c6))

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0
  ([`50b6f1d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/50b6f1d7f7663f0096904c5a580fa3575c9ec1c1))

### Documentation

- Replaced commitlint README section with MR title linting docs
  ([`be1fb50`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/be1fb50cdae52af8357e0fd3758fe75b2890678d))

- Replaced commitlint README section with MR title linting docs
  ([`f9f202b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f9f202b5dd9345e7539d0c7edabdd4983227ba0e))

- Updated README.md with release flow and mr-title-linting
  ([`72dafd4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/72dafd43688bb3161a1197894f90f754f3364b67))

### Features

- Removed unused lines of code
  ([`f0c3eae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f0c3eae0170979b8f368753b71a32895e99674e2))

- Updated syntax in two qubricks to use reg.ppr vs. qc.ppr
  ([`a8e9978`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a8e997879e731a316aafd3cd5ff8e26d93fa8927))


## v1.12.0 (2026-02-26)

### Bug Fixes

- Changing size of system to stay within memory limits of workers
  ([`99471e9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/99471e932dbfedcbd24fd54145d9964eef0c3739))

- Fix a few deprecation warnings
  ([`f641185`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f64118501767a6de173fc50011cf063145af0c1c))

- Fix QREs for controlled selects
  ([`e56f5ad`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e56f5ad34e0b492429b9017ca88f388cc76132a9))

- Fix trotterization to use Y weights
  ([`3a3afa4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3a3afa44c3c9ef7b00000a669d2e37c26a842f9b))

- Fixes for AV in symbolic select
  ([`042d5d9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/042d5d9cc53cf16abc258d340a9014c5ba2161da))

- Only passing in valid tuples of basis state and size of system
  ([`5d348d0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5d348d08cab314942d125cb186591130b9b7b562))

- Reducing the size of the system to stay within memory bounds
  ([`41b0673`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/41b067360859695cdc79092d738b878e890de535))

- Remove test warning by adding pytest-repeat to pyproject
  ([`d7a0f00`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d7a0f00022996d1751d995f9021fe853249e15c9))

- Remove warning from block encoding duplicated be_ancillae_reg arg
  ([`99a9d27`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/99a9d27664cf6cd829eaf6772ae61bbf41b77a14))

- Remove warnings by skipping incompatible pairs of register sizes and basis states
  ([`b7e6d44`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b7e6d4479c9fdad81dbd909f7db3d7607d60d57a))

- Remove warnings of duplicate flag arg in compute
  ([`f74f096`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f74f096644c39bc824f995191cd70c9a8b1a1b6f))

### Chores

- Change over the angle truncation in LKS to non-deprecated version
  ([`105c29b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/105c29b9c18a20d75c43b8d58db692734415c028))

- Move psi-liqtr to non-optional dependency
  ([`52da2d3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/52da2d3631a79ef023955ba66270e28cff46d0c1))

- Sort imports
  ([`20ea5d3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20ea5d366c1ef85d2b08af83b1fa2841d9ccf199))

- **review**: Apply 2 suggestion(s) to 1 file(s)
  ([`7e3bcc6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7e3bcc6c046534243bcf603ee3d35a100b6a2741))

- **review**: Minor changes
  ([`453ea85`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/453ea85b659aee74966806b4de1def7189669302))

### Code Style

- Fix isort issue
  ([`961f78c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/961f78cf18058b6ad863aac6630b466803d252e3))

- Fix style issue
  ([`520869a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/520869a68d62bc25636b610edd4d3902f9d1e10e))

- Fixes formatting
  ([`9c0d243`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9c0d243b5645ee7ad68e41e51a844f0cc82b3d97))

### Continuous Integration

- Add duration logging to test jobs
  ([`710e698`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/710e6980bf02d02911cafd29158694a75922755a))

- Pull SMS out as specific codeowner
  ([`27042f1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/27042f16b93bbac367816d2945bb686134a71334))

### Documentation

- Minor docstring changes
  ([`b115364`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b1153642a09ece98f64ed90fb9e2b1b68638496a))

### Features

- Pytest warn included
  ([`a1e16d4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a1e16d4e4a1d086065e14ca0b3cd4e8bc6b33f3a))

- Warnings bashed
  ([`56d2982`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/56d2982bf2726abcd249b1b4ddd8fe4c4136fd9e))

### Testing

- Add cache to worst_case_symbolic_qrom_uncompute_cost
  ([`4148a4b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4148a4bb37ddb235cb398373251c40a9b95573d3))

- Fix bound for SelectOneAnc in tests
  ([`61cbd11`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/61cbd11f3a4b8b975d30361e73f8c24ccab55dd5))

- Fix failing test
  ([`c149ed5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c149ed5bcab3323beb5d4fa675fa6d5595089aa1))

- Fix import sorting
  ([`774897f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/774897f59e6336de648bca8b482b029cff4dd8c1))

- Fix/ignore few UserWarnings in tests
  ([`6591101`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/65911010f932a7a4928c62d12e3fe14292e01867))

- Ignore UnstableWarning for Parameter
  ([`e583549`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e58354952c1e10446015e8c8ff035c103311c89b))

- Improve performance of symbolic tests
  ([`19ab9d0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/19ab9d09acc1e360134f3a3ec700e14660bf195d))

- Refactor tests for symbolic select
  ([`808b53d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/808b53daa1eb4ec68697675e5011af1e5112f880))

- Remove more warnings
  ([`ec05d8f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ec05d8fcd30fbbff37408b2fbe62ae2e95fe5995))

- Reorganize how symbolic QREs are cached in QROM tests
  ([`5af8c35`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5af8c350345ef00b75b329793723137eb851b5f0))

- Set seed in test_random_mps_prep
  ([`a9de754`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a9de754e4a609b8c6b316eff9bf5b270c1f56359))


## v1.11.2 (2026-02-09)

### Bug Fixes

- Adding poetry run
  ([`df3f7c6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/df3f7c6bd05bc7bc4a8c1ce62b063d25c3b262d5))

### Continuous Integration

- Fix broken docs build in docs jobs
  ([`4fb9ae8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4fb9ae802e1b4e8fb3a32346c9e26b485fc7bc67))


## v1.11.1 (2026-02-09)

### Bug Fixes

- Angle type HWP + PhasingCircuit
  ([`4173d5a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4173d5a2fcad8368252d19ce532710bed37ecff0))

- Ctrl rz (WIP)
  ([`4b961f4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4b961f42937a451939b972102a280ac95b56ba3e))

- Fix AV estimates for TrotterQuery
  ([`2cbe6e3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2cbe6e3913f102f8bf1f177ae6a95ad410ff30c3))

- Fix estimate for BinaryToUnaryUncomputation
  ([`1d1a2b3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d1a2b3001e3dbbd9a4c8da88d07f038af3be89c))

- Reorienting on rotation_encoding
  ([`34447b0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/34447b01538bd08000dcfe352c6ad98b5fe0b77d))

### Chores

- Address a few more deprecation warnings
  ([`a291bfb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a291bfbf47bb0ac9e2764f0715102efbd844ba16))

- Bump version to 1.11.0
  ([`c1dab12`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c1dab12f95e094bddc26a8ccc2dcdc3d02f8ee8d))

- Bump WB version
  ([`4287e38`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4287e3801403a8adebb9ccc70e9e879fea0c282b))

- Delete unused makefile
  ([`5960c26`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5960c2605f799f2f4db17c72384cc06ec4b2eade))

- Ensuring test checks for sparse loading
  ([`1abd3fc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1abd3fc454398782b85e0c950560bdacdd2c1e78))

- Removing sorted call as this is fixed in now handled in WB.
  ([`d4b3e11`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d4b3e1147af44905b19e033c97fe53b28e16fcbc))

- Update interfaces to remove warnings on import
  ([`9ee5d29`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9ee5d29526c013cd040ee051314616bb48dee547))

- Update lockfile
  ([`aa5da2a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aa5da2a800cc6823e8e864fc7568d6d9316e3c28))

- Updated README "master" references to "main"
  ([`160d2f7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/160d2f7671738bc37c37b7de940bfdfa2dcbdc37))

- **review**: Apply 2 suggestion(s) to 1 file(s)
  ([`ee67e09`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ee67e093c6587be802a79cd12dae07ad6b8d33c1))

### Code Style

- Fix lint issues
  ([`5f62705`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f62705d3d5c092d6fec2ba631166a94907b2ad6))

- Fix typo
  ([`1d8ac38`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d8ac386b75fdee35306d76275ce27510fd2a1aa))

- Uniformize angle property and add tests for Units.deg and Units.rad
  ([`e8ec29a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e8ec29abd8156c59012687ccc4d87b66e36d7d96))

### Continuous Integration

- Update master reference to main in .gitlab-ci.yml
  ([`90641db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/90641dba98a454ec6b951f585278925db8dfaf5d))

### Documentation

- Improve docstring
  ([`2fbc67a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2fbc67a1e83283c215e381833e2d6a99a1ffe447))

### Features

- Added smarted ctrl incorporation and all test passing for all Selects updating test to call
  interface.
  ([`43e6669`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/43e6669f9e700f8d7557e78bae9fa5b762dfa5d2))

- Adding explicit uncompute test and bumping WB version
  ([`8b44222`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8b4422217917674b7c1a9fc08661a328aba5fff8))

- Integrated the select and old tests passing but seeing weird warning about release of qubits and
  need to test ctrl case
  ([`b2bd20d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b2bd20d649ad4af1f0dadc7cb202ae990467ad1d))

- Pulling out ancilla assignment from test files and pytest parametrising select instance, fixing
  typos, removing unnecessary init
  ([`563e20b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/563e20bc1ac22774e1534cba60261040069ba30f))

- Wrap selects in sorted to allow tests to run in parallel on workers
  ([`8b280b2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8b280b29464787880771a3ef509ccdfed690e00b))

### Testing

- (WIP) ctrl rz
  ([`f4b74c5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f4b74c54d5d7ef258746765e16155657e57bef98))

- (WIP) with @ssim
  ([`c6d1e98`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c6d1e981ede093c71d11249b0c6793f9ea06ad67))

- Apply reviewers comments
  ([`2977532`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2977532ac20a1c6315e9a168c7545992c3a5098e))

- Ctrl rz (WIP)
  ([`59dd768`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/59dd76812bddcb9c6f732ded833c1bb42b09aaad))


## v1.11.0 (2026-01-28)

### Bug Fixes

- Add discrepancy for USP
  ([`2c6c363`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c6c36313cad16ea492272da2712c25e4ba07d96))

- Bump version in pyproject.toml so locked version can access debug qpu method
  ([`17345b6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/17345b69733e96a12f459889cd87f54e0ed9e1da))

- Fix usp discrepancy description
  ([`9a8c412`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9a8c4128f609fc1e04884ed58e025f58e823a221))

- Fix USP symbolic tests
  ([`b54139d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b54139d13fb72314630b01994e034fd6c76bd570))

- Update alias sampling test to use new debug tool
  ([`bcc92b0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bcc92b016fdc3df3b7b6bd13a9d62b8ff142c3e1))

### Chores

- Address a few deprecation warnings
  ([`061357f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/061357fa809771e05921e098811ec62af54d5efa))

- Bump version to 1.10.0
  ([`0a94258`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0a94258740b4120f3abfaa71227606502b5caa72))

- Delete comment with a typo
  ([`2e01c98`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2e01c98453a180546ec85b3c2ee084f1963a4a35))

- Update deprecated imports from psiqworkbench.bit_utils and psiqworkbench.numpy_utils
  ([`9f2cdd9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9f2cdd996ed2d59978d1d139344dc685fcf1824b))

### Code Style

- Fix isort issue
  ([`db3f396`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/db3f396953b7113d5f6be04b7e1b57d942328a7e))

### Continuous Integration

- Added pytest report generation for latest test jobs
  ([`3b7b57c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3b7b57cfb17452fe682daca20c9f9f5ac7f3bc68))

- Make twine considerably and perhaps unbearably but certainly justifiably verbose
  ([`1d3107d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d3107dbab0bbd681728a50f5e52c894667514fd))


## v1.10.0 (2026-01-14)

### Bug Fixes

- Change back to None for HWP qubrick
  ([`43406a4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/43406a429ba5b5026cd03a2b551a8df452da125c))

- Change Qubits | None = None to Qubits | int = 0
  ([`415160d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/415160d97ef46b1e757212d1ed5d12733e4752ee))

- Fix interface registration for phase gradient adder
  ([`53c1695`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/53c1695e7771f7c8789734149a83e1df9c3860aa))

- Handling of unmerged uncompute
  ([`baabfb5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/baabfb5efdb69af5a159b78155a15f427f87c0b5))

- Just remove the old Givens rotations args
  ([`bf26f73`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bf26f73dd6d143d1c1a726b4444eb508ed7eb08d))

- Now self consistent, issue with fidelity with original qubrick (see FidelityCheck notebook)
  ([`f381047`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f381047e2d3306799c1bf53510d6c89e55a9ad88))

- Update alias sampling interface to match protocol
  ([`741f86d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/741f86ddc518537cf5d855409c9b5e104312feb6))

- Update Givens' interfaces to be accurate to implementations
  ([`8455047`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/845504757fb4e21143b6674eea7bc91da12e3930))

- Working qubrick
  ([`c3771f8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c3771f8c4f578d9a408e77f443e4fe17a5fd6501))

- **simplify**: Remove outdated `subroutines/alu.py`, all tests still passing
  ([`ab1f468`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ab1f468d0a125c128223e96699e2b541991cf3eb))

- **test**: Remove outdated ALU tests
  ([`2dd7be8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2dd7be82d72dcb941394570597580c25510afa35))

### Chores

- Add naive test to test larger sites for phase qrom merging
  ([`c0fa97a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c0fa97ab1664d41bdfcb39a59466635c7ee228c3))

- Bump version to 1.9.4
  ([`860ec12`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/860ec12e340a78ca6df2da1df723dbaec44593fe))

- Clarify notebook with lesley
  ([`53d7b54`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/53d7b54ed180ac0e8a23eea7cd4cf4f279c1f7f1))

- Delete example scripts
  ([`fda01bc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fda01bcafe21d6a87591df020b23a36a27a59b03))

- Expanded docstring
  ([`e9b22be`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e9b22be52857971a7264a5a0744aa27bde859fff))

- First pass on notebook
  ([`58aac20`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/58aac205709d1a662654f381f4d6aa430811fe0f))

- Fix comments and delete dead code
  ([`e416f85`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e416f856c5a697a241a15b6873fd250983f6971a))

- Fix naming convention for u_state
  ([`fc9505b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fc9505bd38898576b4c7fa4edb83fba571df32cf))

- For lesley
  ([`3aebfd0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3aebfd0dd07190baa721f49995149a3f348b5a93))

- Isort lint fail
  ([`648689d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/648689d4f00674a570fcc274171a4cb87971152f))

- Notebook clarifications
  ([`c231838`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2318382904a25e99fc207bbce1355ef6bf3b4e4))

- One missed isort fix
  ([`2d9ec2a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2d9ec2ac00ced060829399c2e4061ac9e76424a9))

- Replace deprecated angle truncation function
  ([`e4b6040`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e4b6040f6f707ac6059b1ca7674f0bbaf6365cf8))

- Tidy up code
  ([`99682e9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/99682e96cbda9d1844fc005ff4b9133fb7d37324))

- Update notebook to work with updated code
  ([`f6e7ef1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f6e7ef1da45683d760b22a9c55167956e7dd63cc))

- Upgrade scipy to a required dependency
  ([`5ff3dae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5ff3daea426beecef80b8425ac0c4a4bf36139ed))

- **review**: Apply 3 suggestion(s) to 2 file(s)
  ([`0886eb4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0886eb442c5f4f535b863f61a34bb99120985ff5))

### Code Style

- Change variable format to snake case
  ([`9f6d1ca`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9f6d1cab019159a995e078abfa63cbafa867b1d0))

- Clean up code
  ([`fc18421`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fc18421b67122ef4db2795625947d8561ec3e041))

- Clearer s_distinguishing_bit function
  ([`193c32b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/193c32b333f2617b55cb2cbacae4d46a5207ae6c))

- Update copyright
  ([`8f41a9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8f41a9b8ca10bdd158a7bf2c9728e69f5fcec84d))

- Update copyrights
  ([`8cc5e6c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8cc5e6c5e22dc473c29adf4f69371e875870a62c))

- Update dataclass name
  ([`90b47a7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/90b47a73cc8ec73f9e0d8c905c53357a547730f4))

### Continuous Integration

- Added release stage
  ([`20760d7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20760d734c6e5701b118e3cf3f18862c55336146))

- Hard code test worker pool size to 8
  ([`1272e4f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1272e4f5e86e8ee85541dd14c51210b13cd496b3))

- Update number of pytest workers for profiling
  ([`a97ab6b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a97ab6bc04679b1e2025989487b4fbedd90ddfe6))

- Update number of pytest workers to 4 for profiling
  ([`5dc881a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5dc881a2e0851b2477b6986a050db2648ae36ba9))

- Updated dev-ops/common include reference from 0.0.8 to 0.0.9
  ([`9fd34b9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9fd34b9074b46431c09e3dd1bb41819fdc4c1f3d))

### Documentation

- Added warnings
  ([`7b38ef6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7b38ef61daf9e0ce60a352308764df26df5a10cd))

### Features

- Add clebsch gordan qubrick and test
  ([`f98e6dc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f98e6dc14aaf45850726728d64d8e10de95472ea))

- Add composite reg for su2 mps
  ([`eb4b7b8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eb4b7b81ed4428295991680f061d85e78b34fc65))

- Add example notebook
  ([`32c049c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/32c049c58bc647e07d8fbc3992494157fb4592ed))

- Add test for dagger=True
  ([`fe1c567`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fe1c567e14f91346bb551dcd70731e7129ac76ce))

- Added complex vs real coefficient handling and test file
  ([`9fec534`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9fec5347a68687936245b074961d9dfcec7d5db0))

- Added phase merging, issues with amplitude merging (see notebook)
  ([`2afebb0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2afebb03844734d0f64f16d7d16ec5b28c93c7b6))

- Added tidied notebook from sync. added merging functionality from this notebook to qubrick. passes
  initial test.
  ([`b3ec9a8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b3ec9a8c7f55378b612fec1f40f1dd91d17cedfb))

- Cleaning and responding to review comments
  ([`f997f36`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f997f366a71dceab2d24c901e4e5877d49999a53))

- Responding to review comments
  ([`4486492`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/44864921b3b26dc162c34b73369bfaa9ac56b944))

### Refactoring

- Make uncompute of s_distinguishing_bit a function and clarify variable names/docstrings
  ([`11b751f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/11b751fb06dd026b7446b78e654dec1e3e012eaa))


## v1.9.4 (2025-12-02)

### Bug Fixes

- Update n catalysts
  ([`8641416`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8641416f9fbbaa8b96c4537497f9789f9dd18578))

### Build System

- Update WB dependency to v4.30.5
  ([`a90939a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a90939a7fb36db73cc45bb91efadddb327e8c9d5))

### Chores

- Bump version to 1.9.3
  ([`6667b5d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6667b5dcce9b0f23f743617e21b2d9659cf5ef2a))

### Continuous Integration

- Allow docs and install jobs to start immediately
  ([`d768252`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d76825282994a2472b1c093b04399b7f7d4d0b28))

### Documentation

- Removed installation instructs from construct for external users
  ([`ca561ea`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ca561ea5b0c1075631ae9ce0cd7689eb404aca23))


## v1.9.3 (2025-11-19)

### Bug Fixes

- Cond_xor will only actually work if ctrl is first qubit in register, plus reflect handles all
  special cases
  ([`4f3870b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4f3870be9424e4ebc0dae977258b8b6d285dc539))

- Import
  ([`8a41776`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8a4177678b7e323473c56fb47295d4953ed81eec))

- Number of Ys
  ([`6f328ca`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6f328ca292bf8bea89955fed98a7c7e8262f1428))

### Chores

- Add special angles to test
  ([`901c8c1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/901c8c149610d7e2e556695230cdd009e0bcc763))

- Bump version to 1.9.2
  ([`a9ef073`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a9ef073dd1a7ad3904e7b0214d7e3835e2ef26e0))

### Continuous Integration

- Run examples in serial
  ([`501ef39`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/501ef39ff83d8fee4757e7b0d7dc4d2ce0b1467b))

### Documentation

- Add _compute to API docs
  ([`9b81902`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b81902b038f96dd69b925c7165fe365734827e3))

- Clean up warnings in _compute API docs
  ([`436e4ef`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/436e4ef0d80cd77a60df8605ef75c98b1f84997f))

- Fix docstrings
  ([`08c0650`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/08c0650f1331d077bcae47343073b8032b53436a))

- Fix documentation
  ([`250c5b0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/250c5b0c62e19b85204ccf807fe47e35470d58bc))

- Minor cleanup
  ([`a18d1bd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a18d1bdc83afbb7f483730a23924b65398b664af))

### Features

- Add feature to __all__
  ([`9b61927`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b61927097b2299b19de9527ba31749489dbaadd))

- Bug results from unnecessary assignment of PGA state and an issue with open control and phase fix
  up
  ([`36f95b9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/36f95b9aaacdfd4b261c70c2e088c748604d25a3))

- Fix bug with open ctrl
  ([`b205a9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b205a9b14f89ef8445d38a6f0c9533e4911cfa12))

- Removed spurious qubit from RZ Adder
  ([`a25c2cc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a25c2cc2d73ecff0be028678f677209d7a991aa4))

### Refactoring

- Change holevo variance calculation method
  ([`20f7d8c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20f7d8c7d2f7ec85338dcf8271f793eddfdf37b6))

- Import order for lint
  ([`fb9244b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fb9244bdb988eadc7751514e40a23207fac68458))

- Move holevo variance calculations to quantum_phase_estimation_utils
  ([`67a6724`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/67a67241a7030ae2d085848aea10ccfd5f787c45))

- Reduce rotations in _compute_partial_optimal_state
  ([`cdd9753`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cdd975332dc8ca31df4ca99046f3befebf0933d3))

### Testing

- Add test calculating Holevo variance of QPE
  ([`25b6fd8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/25b6fd8f78dd6083b62b13a9b4b4c83b0b7d86dd))


## v1.9.2 (2025-11-06)

### Bug Fixes

- Raise Error type
  ([`99c5485`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/99c54859cb4a009bed21a0c27b03ccaf2bd622fa))

- Slice PauliSum
  ([`c8ba338`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c8ba33846b0eaf6041ff55961fbe75a5bec71cbb))

- Updated symbolic estimate for phase gradient adder
  ([`66b05e0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/66b05e06488f941ad63ddd9f1ea148060c26b9be))

### Chores

- Bump version to 1.9.1
  ([`795a2a2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/795a2a24c8cef7ca3aa4962a66fe9acccf2c910f))

- Updated docstring with a note
  ([`4ed2124`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4ed2124284a9ffb37f20a862a90866a766a09fbc))

### Features

- Got rid of extra qubit allocation for two adder Givens
  ([`e6c6a29`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e6c6a292f00f05cb25085ddec3c4fd44557752e9))


## v1.9.1 (2025-11-03)

### Bug Fixes

- Add blackbox costs; need to validate
  ([`e2e4113`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e2e4113b9190412b561895ae1e157895d96149cb))

- Add workaround for failing MPS notebook
  ([`a98f667`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a98f667834a00bca11bc8ade8c84bc96a3588e16))

- Fix ruff errors
  ([`e3149f6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e3149f6c9e9a36253771ad6d837a9da26d462bec))

- Lint
  ([`b8ac37d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b8ac37d439370baa135b0890729df307f2b6678d))

- Notebook tests
  ([`e3f8f67`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e3f8f6745617ebafb4e5c2e84cfac83d20f3aca5))

- Release anc
  ([`a3b5fe3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a3b5fe320a42577b934855f664dab7db5fe770d1))

- **cleanup**: Remove unused qc vars, and radians setting
  ([`7d07867`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7d07867b9919c27bb81ae99697252e14ef3e4300))

- **MR**: Fix two MR items
  ([`7b6e54b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7b6e54b533389d57995c6d8a9079c02bcc66e70d))

- **PauliMask**: Fix off-by-one error in PauliMask get_pauli() for #371
  ([`34725da`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/34725da4be0e23c9f9c135eb098d7baa6b3c1934))

- **poetry**: Bump WB version and lock
  ([`b797eef`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b797eefcdf847a28f51961174fe0f16fcd371a09))

- **reflect**: More reflections added
  ([`d8ccc6f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d8ccc6fa3e04ee64d1d60c1dc47af49c5eb907ca))

- **reflect**: The first few reflect fixes for #368
  ([`b82d5df`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b82d5df9a26bd402ef6d009884a267c89deb2f81))

### Chores

- Account for controlled case
  ([`0b0b65f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0b0b65f33f2523c1470442fe374cc0ba40d18bed))

- Add other costs
  ([`a4fcbf3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a4fcbf3f99bdb68326535080c8a6e80a70bc74c9))

- Add tests for batched HWP
  ([`2ebc22e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2ebc22ea9787d186462c65ba185804e7f401dd57))

- Address Michal's comments
  ([`23eb6dd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/23eb6dd948b834741445a31318ad37f768e81d3e))

- Address Will's comments
  ([`da99337`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/da993374f0bc6faa05415ad35304452d918cd841))

- Apply to batched HWP
  ([`618a092`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/618a09244342df9c3f519e5e694525ab373dca28))

- Bump version to 1.9.0
  ([`95893af`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/95893afb192cf983f9ca255e1b42191f3e433e02))

- Lint
  ([`828b36d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/828b36de7ecd23a85686dd8c841788a930ab13b2))

- More comments
  ([`c78938f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c78938fefd7500db9519e8472f998a8a86b9eff5))

- Remove testing notebook
  ([`ea211b7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ea211b724164c90100126acddcf2692e90481898))

- Rerun notebook
  ([`4259e47`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4259e4751d7684c2519b925b1ae8e0e4a7dc503c))

- Ruff
  ([`6dc44a0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6dc44a0362808b8053ef5937664577ec63db6939))

- Use lookup table for C_CCZ
  ([`542934a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/542934adc4ba35b5c44210c14220f317d1da87da))

- Write test for other resources
  ([`24e6931`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/24e69315240fe82d7d932b48395c1431dc9c60a3))

### Continuous Integration

- Run test coverage job in parallel
  ([`00462b4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/00462b4a66acd9274247f9d05ad175f9f6dae8ed))

- Updated dev-ops/common include reference from 0.0.7 to 0.0.8
  ([`a4289c6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a4289c66a58406fffb49ba30897190d19207f2ab))

### Features

- Add zx costs for HWP
  ([`90a9f40`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/90a9f407892a99539ad5b7d16f0dd2a47c1da020))

### Refactoring

- Replace old filter names with filter presets
  ([`08d407c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/08d407c74e9baf77cd1525c3d8db47aecafbe3b5))


## v1.9.0 (2025-10-16)

### Bug Fixes

- Ej's speedup
  ([`e18cb9e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e18cb9e3a894a4b570d4cd0b7eacf8959fca5f2b))

- Fixed RZAdder case
  ([`cbd31bd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cbd31bd9c7e922c40e5fd1b5c47c097e2ab9a82b))

- Remove process_output
  ([`9638595`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9638595892687f9f8c6a4000a2e0da22e354fb09))

- Update poetry
  ([`d57ecb0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d57ecb0bc09ffe4c6c3590dd7f6acaa531db467f))

- Update to work with changes in WB for ast-2308
  ([`6047c98`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6047c98a06db6901ba16b6dba90c26942def59b1))

- **cleanup**: Cleanup per MR
  ([`c2afbb8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2afbb85a6d9c2017a83aec7f36df9102339256b))

- **lint**: Fix isort error
  ([`91e2ab4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/91e2ab4a57f6dd75b45ab61bb8ca75bb42549b02))

- **test**: Adjust a test to accept equivalent but non-identical tables
  ([`e350957`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e35095723cb6a5432cc5af52f18a37bfa84c79f6))

- **wb_version**: Update WB required to 4.30.1
  ([`dbd695a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dbd695aa93ee30ce531cf5c7685aa266486998b3))

### Chores

- Add docstring to constructor
  ([`56dc065`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/56dc0652935fe6cc6d51c73f35829de8010ef280))

- Address reviewer comment
  ([`e062af0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e062af030a5a5d19cf3fcaef5289be3faa1776dc))

- Bump version to 1.8.3
  ([`3fd9a4e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3fd9a4e6f647a194bea1a7c4f4eaa6ae3e1c25fc))

- Isort
  ([`238f61a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/238f61ad04c0d0030330e15caf9b32666cef943c))

- Isort
  ([`cb94c0c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cb94c0cfe306d14a3460c8e2d11999e46df227a1))

- Isort
  ([`1435644`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1435644f3a72d613a72503e12d290addb9fb3907))

- Linting
  ([`2c373e9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c373e994d64482d0262f8bd30849546cfb9c3ef))

- Linting fix
  ([`9ed0da6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9ed0da607babfd54f4a57302ad708349443306b8))

- Update test to have less repetition
  ([`36c805c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/36c805c84a6bf9f7f91c158f067e970428debe99))

### Code Style

- Change _Ul function name for consistency with other funcs
  ([`0f38e8c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0f38e8ccaed3b8bc1678b0f79c016d1aa8dbd483))

- Linting
  ([`57a466f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/57a466f9de93f7b1e4bb19f07b2714b74e61e244))

- Linting fix
  ([`f52ae05`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f52ae050178aa05b408bcb1e320e34951e17ff63))

### Continuous Integration

- Parallelise jobs using pytest-xdist
  ([`4c0837a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4c0837aa8f6c73e2b8333857f44d5d192acc9015))

### Features

- Add ctrl to u_l function
  ([`87c4f11`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/87c4f11fac8f5f66e1bea6bbeca2eb6ee2fa0533))

- Added symbolic test + equivalence test between phase gradient adder and qc.rz
  ([`5e4dd1d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5e4dd1d3aaf4bab6381e1efacdc56ab5bbf1fe82))

- Added Toffs to cost dict, updated helper to calculate all resources and return QubrickCosts
  ([`bba31a3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bba31a3e38a84bcb315aec981579f58fdcacdb66))

- Addressing reviewer comments
  ([`64b7656`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/64b765674ac4868668849444cf21cf3e7af03dec))

- Changed ordering of some lines in a helper method, added a link to a Jira ticket
  ([`98d946b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/98d946b7a95f3cfcbb26f2c9b574de83c8a3db3c))

- Temp fix for RZ and two adder version of Givens
  ([`7cb69bb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7cb69bbc62fcaf17081ad1edcf4eefefa277943c))

### Performance Improvements

- **alias**: WIP first pass (still needs cleanup)
  ([`87e0529`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/87e05293507843b7a6db4a519425e5f07567d553))

- **alias_sampling**: Speedup in alias samplinggenerate_alias_table(), and also
  discretized_prob_distribution()
  ([`3f490dd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3f490dde54a25556d72eb9c26e55fd581558e0c1))

### Refactoring

- Change phase gate to s_inv
  ([`b8f7cc9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b8f7cc941d6901f9b4184e8af50112e034fdb3b1))

- Move hadamard and s gates to _compute_Ul function
  ([`d080e3d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d080e3d465961a9b4a1dd5a521943fbc48866dc8))

- Rename compute_Ul, remove unnecessary line in test, add typing, and check for n_qubit, sign inputs
  ([`1c70ce6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1c70ce62e3b8a7832ded5b78c37aebc8fd459f83))

### Testing

- Add test for ctrl
  ([`d7bcc6e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d7bcc6e4207fc10c1a6f147e99151adf780649da))

- Added test for uncompute and real amps case, deleted example script, linting.
  ([`466aba5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/466aba5436990dc1ca313fc8c451e45802c5045a))

- Replace QPU.set_random with explicit state pushes
  ([`c646676`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c64667670a87e28b55f39673777a832dda4ffa14))

- Set seed in test with random instances
  ([`372a70e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/372a70e226f0ef3b46990503d8bf6f00fdd6ef2c))

- Updated set_random_qpu_state to use QPU.random_seed
  ([`48213a0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/48213a01f67df705aa74da35d21d5460a553d230))


## v1.8.3 (2025-09-23)

### Bug Fixes

- Adjust protocols and implemented qubricks to match the specified protocls
  ([`40e36f5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/40e36f5faeb55647056f8a1882302ce5c6cfc0b3))

### Chores

- Bump version to 1.8.2
  ([`92ef813`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/92ef813d2c4aed2a67b45d49017614b0f4c98850))

- Linting fix
  ([`e722db0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e722db0ca9e17194b933592119cfc89f69b9e5bc))

### Documentation

- Updated docs sidebar color
  ([`980a416`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/980a416d7e493f87f2f7af1033095082b895d299))

- Updated release instructions in README.md
  ([`baaccdc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/baaccdcbc9b34dc5829b1049ef08e164e8715f4a))


## v1.8.2 (2025-09-15)

### Bug Fixes

- **utils**: Added try clause for scipy import in dyson_utils
  ([`12c9f2f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/12c9f2fe2f265b9408012535d5a2627953a0e7d3))

### Chores

- Bump version to 1.8.1
  ([`6e2fa68`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6e2fa681c8b24d6cf0b8bee878711e0558334468))


## v1.8.1 (2025-09-11)

### Bug Fixes

- Add better instructions when user is missing scipy
  ([`db97dc3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/db97dc3d18b7e19144bbcda2d9ffeb689cb307c8))

- Add docstrings
  ([`a03dd05`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a03dd0531ea4f7357e852a4354f5913e526f5999))

- Adding more comprehensive test range for d > n
  ([`2c037c1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c037c1f341026af26fc63b4fc0dc40b88aca853))

- Address Jess' comments
  ([`a439f73`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a439f7325141641eaa8303316699ef58f8058d04))

- Address sms' comments
  ([`f21c8c9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f21c8c9737be8972527179c9ce9efea2082b4c06))

- Apply 1 suggestion(s) to 1 file(s)
  ([`8873c3f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8873c3f893c75bfa750630badcecab12d5c9f40f))

- Change junk version map index to target class name
  ([`6ab589f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6ab589f2893e3776eae5c49b88664db0ca05b529))

- Clarify use_ctrl in tests
  ([`10269e6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/10269e6b527321ba80723fc4f54e4878944e3563))

- Copy amplitudes in data
  ([`372f16e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/372f16e5339be72c32f7f1bf411a8210b32d9af5))

- Enforcing kwarg usage after wb updates
  ([`5c4c009`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c4c0091a8bb998abc9e97383884aec33efbad39))

- Fix set_version to adjust to new pyproject.toml syntax
  ([`c1def9c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c1def9c1f7498e7e0bedc3b1ced2b1f5be48614f))

- Format
  ([`a140d12`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a140d1222c210fc06a948fa9c8c3a62ac0a78c5e))

- Hard code lambda = 1 for now, need to fix this in the future
  ([`8a46293`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8a46293a756aeecb0bdee2dcaad55c7bb8c3b5db))

- Isort
  ([`357f7c8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/357f7c8f7f1f0428c54110b1b23ab11b33e153b5))

- Lint
  ([`3c9c78b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3c9c78b3e2523495fb946dc0294a796368db15b2))

- Make output reg mandatory
  ([`8a5518e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8a5518e1188b95458467c4628976a885a4b6a1b7))

- Ran isort on rotations.py file
  ([`590657c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/590657cfd72692d14dcaea0566c280e2dc5ff110))

- Remove release index reg
  ([`89faa67`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/89faa67478af713bf596f6df3e8351e6e48e4327))

- Set_version.py sets version in pyproject.toml
  ([`3a2175d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3a2175d1278601f4e190f800540b2be02b54c61c))

- Switch ordering of c-state prep and c-write column
  ([`b07a348`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b07a348d213f585be5651329c7cf493f95d8e282))

- Typo in example notebook
  ([`d8540f7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d8540f7e72926fdb01538db38f5a3914eaf94520))

- Unique positions (sample without replacement)
  ([`c4ce4e5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c4ce4e5dc1bdc2605cd1f1fadc693083e1467a38))

- Wrap up some output updates
  ([`5541223`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5541223d8f9ca30e5ea62ff2f1201f8c4760a064))

- Write to_arb_state_prep_data
  ([`852da6b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/852da6bc3b0f98e4835abdb07677007843ee7f44))

- **qubits**: Fix release of hamming weight phasing qubits per #351
  ([`63fcda9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/63fcda9d14eaf3c620b05cfcb6a9d2f1b48cbabc))

### Build System

- Updated workbench version to latest
  ([`9f5ebad`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9f5ebad09a6db0f6dcd157631b5d21f321e03cdb))

### Chores

- Add issue number for amplitudes copying in dataclass
  ([`8c37eaf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8c37eaf1b1e3c5b1cc1163a0cc206ee931f3f725))

- Add typing
  ([`f8d5e07`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f8d5e07562936a4fa22c299b1597b78ddf1384b6))

- Added reviewer suggestion
  ([`9538298`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/95382983d07d1048e9a9f06dd7abdf262d494eeb))

- Address reviewer comments
  ([`6dd7620`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6dd7620c2a6a1547091639252ce8372f3e9f3f84))

- AliasSampling Qubrick included back into the StatePreparation protocol
  ([`ff97c39`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ff97c39f2ddfeda1b5795ae4d3ba190523e443e2))

- Apply isort import sorting
  ([`028a0d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/028a0d12627e1a89921332ae62b55428e6d5f0a0))

- Changed crtl argument default value from None to int=0 for GivensRotation interface.
  ([`2155e58`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2155e580d62e2d05cb18e44d9dbb89366263d532))

- Changed crtl argument default value from None to int=0.
  ([`bb4fb83`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bb4fb836b6dbe42834621eb3db98bb14707b34c3))

- Changed qc gates to qubit gates
  ([`e2881b8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e2881b8f8f7c12d49944296e1567f0a224b3236a))

- Changed the default ctrl to accept Qubits and int instead of None in compliance with the Qubricks.
  fixed Assymmetrization import issue.
  ([`fec252a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fec252abd22569e70daa8426fc32d88c9187a01b))

- Changed the default ctrl to accept Qubits and int instead of None in compliance with the Qubricks.
  fixed Assymmetrization import issue.
  ([`6218068`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6218068c6490580f1bb1a8acd2466ef567df0558))

- Cleaned up LCU interface import and other dependencies.
  ([`8784921`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8784921d8a20150815aa12c69913d7ed4360307a))

- Corrected and add CompositeRegister
  ([`d74fc66`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d74fc6636a43761a246a156e4e93b26ad91a3f02))

- Fix lint
  ([`5f091d4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f091d4e115a10c23f0c83cfe286b5a489083155))

- Interface temporarily removed from AliasSampling qubrick to reconcile arguments of
  StatePreparation interface and AliasSampling qubrick.
  ([`f50dabc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f50dabcd4dd30f4e5ed56bdb99aa9e32fe31bda4))

- Lint
  ([`c724717`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c7247174c8426392328dd078891ffb0e6337f4a9))

- Minor spelling error in tutorial
  ([`551819f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/551819f5672c508fa5b933c6a1c25769fad3aca9))

- Modified compute to _compute in interface.
  ([`8cf0042`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8cf004236f04ba0464898e58b6fe57337bc402ee))

- Modified pyproject.toml to use test against workbench MR branch 1868-fix-interface-checking
  ([`d922b55`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d922b5555314b41f5a8528a21f975c873583cf7d))

- Modified pyproject.toml to use test branch
  ([`9bbf94d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9bbf94d8f121c0a51f4033cd785582fc28c66d07))

- Remove unused part of tuple
  ([`d7a1f7c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d7a1f7cdc082d37cce3573f7c172c9f1712f2890))

- Removed `None` return type from StatePreparation interface.
  ([`a6721a5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a6721a5f313a38ed18fe63fbf53f1abe7aa95138))

- Removed LCU from Interface.
  ([`8418ce9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8418ce9a22faf0b76e6f03ee21ca7f15c8711993))

- Removed return type for StatePreparation and AmplitudePreparation protocol interfaces.
  ([`94e5463`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/94e5463ec6c510a57bd33ab30afd7e2830e94d81))

- Renamed angles in GivensRotation protocol interface to rot_reg.
  ([`6de68a3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6de68a347ed9e9e184d2d01350787513d5dec2f1))

- Renamed argument psi to qbits for StatePreparation and AmplitudePreparation.
  ([`7ef26d5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7ef26d555a058c8810ece1009e54c7352442957d))

- Renamed psi argument in ProgrammableRotArray qubrick to qbits.
  ([`b4ee697`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b4ee69779d2c6c8f8e0126c37290b0302a8b15df))

- Renamed psi to qbits for ArbitraryStatePrep Qubrick.
  ([`9e033bc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9e033bc3b8ef580c7b567e3d5ef5a995d2f2b886))

- Resolved Andrews review comments.
  ([`36d147f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/36d147f4f432b9bdfdbb34f2475bce08871c99b4))

- Returned the naming of the first argument to 'psi' for ProgrammableRotArray. Renamed the 'qbits'
  argument to 'psi'.
  ([`08cc53b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/08cc53b894477eb6eee19a748fb9001fecb6cf76))

- Reverted ArbitraryStatePrep back to the main branch argument implementation.
  ([`f171939`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f1719399adc4937046b597811269c4a80cd5a996))

- Reverted GivensRotation Qubricks to the main implementation
  ([`11b9887`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/11b9887c9e60a7cd63fe11e38e29fb73cf7e0d75))

- Reverted GivensRotationTwoAdders qubrick to original main branch implementation
  ([`54b427b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/54b427b6de32507765111244bc0a2b9fd67fc2d0))

- Reverted StatePreparation protocol back to the main branch argument implementation.
  ([`d5bcdd1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d5bcdd1fe32c80e9a4f050efdca174d66bc85c74))

- Separate out mapping
  ([`4bdda3e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4bdda3e26badcbca5194e4e517246f7844061e7f))

- Simplify sparse state prep
  ([`18b32d8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/18b32d87886c22151dee4ba9342a4f878bb3f2fd))

- Sorted imports
  ([`c3aac7b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c3aac7b549dba9ab3a6e2d563cee856bdea8091d))

- Temporarily removed AliasSampling. Argument different from other qubricks using the same
  interface.
  ([`5c931c3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c931c303a9823cb162f3df765a8d0483703cfa4))

- Updadated argument types for Multiplexor, Permuation and BasisTransform interfaces, and
  BitonicPermutation and PhasingCircuit Qubricks.
  ([`4e545db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4e545dbd364133ddae0320d974a9d4f1c3ee9e23))

- Update the interface and qubrick arguments for Antisymmetrization and Antisymmetrizer
  respectively. Also, updated the spelling for Antisymmetrization in design doc.
  ([`ace42d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ace42d1b5240af770f3560fe4a9550de415ea74a))

- Updated AmplitudePreparation and PhasePreparation interfaces to use the same arguments since they
  are both used by one qubrick (ProgrammableRotArray).
  ([`3b0ec51`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3b0ec514b594da880b87dacf9f477af8cb8c1d8d))

- Updated argument types for Multiplexor protocol interface and BinaryTreeMultiplexor qubrick.
  ([`e6b62f8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e6b62f89987867a6bbe325a607a272820b4d2997))

- Updated argument types for OneAncMultiplexor qubrick.
  ([`20de2d3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20de2d3a1937eb5d735ff259b0bdca3893fed8a1))

- Updated BinaryToUnaryUncomputation qubrick argurment types.
  ([`080cd69`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/080cd6956c18269541dec8a0384ed87978afeddf))

- Updated ComputeHammingWeightBinaryRecursion qubrick arguments types.
  ([`a80a1db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a80a1db60b2ccdb09b7ffd405ad88d4a06acd9eb))

- Updated ComputeHammingWeightGroupOfThrees qubrick arguments types.
  ([`0e890bf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0e890bffb0fa890b4c931dd16ab3c51007366f49))

- Updated DysonSeriesSelect protocol interface crt argument type and the DysonSeriesSelectUnary and
  DysonSeriesSelectBinary qubrick _compute method arguments.
  ([`4644abf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4644abf54ddf1546a7f41c8330bb1e58253e28c1))

- Updated HammingWeight interface arguments.
  ([`fc1cf4d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fc1cf4ddea28f20a9e04f7d315370d873e607707))

- Updated HammingWeightPhasing qubrick ctrl argument type to default to 0.
  ([`063dacd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/063dacd84366a797567105df34df3b8fb08d5f40))

- Updated InjectOp qubrick and protocol interface arguments.
  ([`5347674`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/53476747675b5f669171a979858ff2c4bf11f2ae))

- Updated MultiplexedSingleQubitRotationViaQROM qubrick ctrl argument type to default to 0.
  ([`e8ab2e8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e8ab2e8a02d39aacd0ace9d0d5b35603480df806))

- Updated poetry.lock
  ([`4b1c430`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4b1c430c79d2778d06778419dea7a898b8204af8))

- Updated StatePreparation protocol interface arguments and return types.
  ([`34c74b3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/34c74b39fab142e5e777e454c45320a4d236ee72))

- Updated SwapUp argument types.
  ([`64630d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/64630d1815f6abbbf29221d59a02029ed1fdcd76))

- Updated the argument type for FlagCollisionsUnary qubrick and FlagCollisions protocol interface.
  ([`ceb9a43`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ceb9a433c18abbf3ce3b6f44fc150242dda0af40))

- Updated the argument types for Contiguizer qubrick and FlaggedQPEWindowFunction interface
  protocol.
  ([`ba39db1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ba39db1285b0468649655526dfc11a0bd94f3e5f))

- Updated the argument types for FlagCollisionsBinary qubrick.
  ([`703d78b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/703d78b52658eb558273a5837329e2fc27f2cf52))

- Updated the argument types for MajoranaFermionOperator qubrick and interface protocol.
  ([`06fcd59`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/06fcd59b7987cc8845d4b934b8ee73529fdd81f0))

- Updated the argument types for OrthogonalDotProduct qubrick.
  ([`b7c264f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b7c264f89d0e595927e45fea994ccccebf6d92d7))

- Updated the argument types for RectWindow, CosineWindow, and WindowStatePrep qubricks and
  QPEWindowFunction interface protocol.
  ([`415c4db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/415c4db9d4b144c6918b92d8df800a3cda08318c))

- Updated the argument types for SawtoothMultiplexor qubrick.
  ([`801bebd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/801bebdda50eea71d7eab5f76bc1a2b20e54aeaa))

- Updated the argument types for SelectOneAnc,, GoogleSelectUnoptimized and GoogleSelectOptimized
  qubricks.
  ([`969ee59`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/969ee59dac3caaf141e4ea3e45b5652579e101dc))

- Updated the argument types for SineWindowPhaseCatalysis, and SelectNaive qubricks and
  FlaggedQPEWindowFunction interface protocol.
  ([`f8dc5d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f8dc5d114a41ec7bf419b9504acf9719e27b0c3c))

- Updated the argument types for TrotterQuery qubrick and Trotterization interface protocol.
  ([`2ffaea6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2ffaea68646fc6acefb0a069d5e1d5af97f99dbf))

- Updated the argument types for VectorAddition qubricks and VectorAdder interface protocol.
  ([`5c45206`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c452063c3757563ba04e43868b9a1bb313f817d))

- Updated the argument types for ZeroAncMultiplexor qubrick.
  ([`2f47fc3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2f47fc3a1a9ea87942769f2fe8f2254ffc527c29))

- Updated the argument types of PrepareWState protocol and PrepareWState and PrepareWStatePowerTwo
  qubricks
  ([`fe0be34`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fe0be3466a4d01eae7d39f020003dfb26168647c))

- Updated the arguments for HammigWeight interface and ComputeHammingWeightNaive qubrick to default
  to int=0
  ([`1bba6fd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1bba6fd4c9523f58c7121c47342b668f7b473338))

- Updated the arguments for HammigWeight interface and ComputeHammingWeightNaive qubrick to default
  to int=0
  ([`62527f6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/62527f6e261522276766572c85c0a4e8d03acce6))

- Updated the arguments for SwapUp.
  ([`3cd2597`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3cd2597c766415e57ea5134ef7b011b75f9d792b))

- Updated the mux_data argument of RotationViaPhaseGradientAddition to rot_data to be consistent
  with others and the ctrl argument of SuperpositionRotations interface and the Qubrick its
  implements to default to 0.
  ([`ac38b7c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ac38b7cdbf91e8f85ac949c2acfcce9406d88d2b))

### Continuous Integration

- Updated dev-ops/common include reference from 0.0.6 to 0.0.7
  ([`386ef4c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/386ef4c001927a01faf7d07b7d689a51d90c20ff))

- Updated examples testing in CI to be compatible with PsiQDK
  ([`50a8409`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/50a84090221123bee02b8526fe8ae1c774f43e7f))

### Documentation

- Move docs images from lutim.psiquantum.lan to the repo
  ([`dd1cf7c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dd1cf7c43907650c22f4a3f1753fa530a17e193f))

- Temporarily deprecate broken example notebook
  ([`ebf1c54`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ebf1c54e3eb11f26091aced17726b860ef80bcfa))

### Features

- Add additional explanation for QROM lambda > 1 problem
  ([`3881c39`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3881c3968d55071f15dd38948be97b0e66e2bfaf))

- Add example notebook
  ([`9b555b7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b555b72f3b81a2c06f243c65368f57e2c72fc13))

- Add Jess' state prep, controlled and refactored
  ([`1a86968`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1a86968ac3674a34e915a2dc3903bfa042d65986))

- Add sparse state prep with junk
  ([`8ed63d9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8ed63d98223f5090ef9da09ffcc79fe0d189a42a))

- Added BinaryToUnaryUncomputation to the BinaryToUnaryUncomputation Protocol Interface
  ([`08f1a9d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/08f1a9dbf7970b202d5a58fa5a39dc2d824b4d97))

- Added BinaryTreeMultiplexor Protocol interface
  ([`3da93c7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3da93c7d578d37582eae2578a0b436a9ce8cfc74))

- Added BitonicPermutation to Permutation Protocol Interface
  ([`8dd4463`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8dd4463e08b3f2663d1fc4a70fb21e8a9c70599d))

- Added BitonicSort to the Sort Protocol Interface
  ([`8068b65`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8068b65ffddb202f9a1ebf69861d26110e114fa3))

- Added ComputeHammingWeightNaive, ComputeHammingWeightGroupofThree, and
  ComputeHammingWeightBinaryRecursion to the HammingWeight Protocol Interface.
  ([`0215c92`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0215c929e6e58dca6be2469d8cb0f579e65cedae))

- Added ComputeHammingWeightNaive, ComputeHammingWeightGroupofThree,
  ComputeHammingWeightBinaryRecursion
  ([`0e0dfeb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0e0dfeb0e814d5adf756f92182f2b221bab4539b))

- Added Contiguizer to the EncodingChange Protocol Interface.
  ([`8b0d79a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8b0d79ad25cc7eb6b82f635cffe4369990331b29))

- Added CosineWindow to the QPEWindowFunction Protocol Interface
  ([`86b3c2d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/86b3c2da173a5a822c4fbc8667d270118069ed6b))

- Added ctrl arg to BRNO
  ([`a1b8c96`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a1b8c964df655d1377e14779877834c2e79eb15a))

- Added DysonSeriesSelectBinary and DysonSeriesSelectUnary to the DysonSeriesSelect Protocol
  Interface
  ([`20ae59a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20ae59a1aa37afbecc9434a1d1425e2d996bd6d5))

- Added FlagCollisionsBinary and FlagCollisionsUnary to the FlagCollisions Protocol Interface
  ([`ee5519c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ee5519cd65a096d0fedb4dd5c59fd53baa6939be))

- Added GoogleSelectUnoptimized to the Select Protocol Interface. Deleted data types in docstrings.
  ([`52c9b2c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/52c9b2c5595c84a597824524478869daa3b24a0a))

- Added HammingWeightPhasing and InjectOp to the Protocol Interface.
  ([`82eb273`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/82eb273f93908f48eb127709474b96d7018f1390))

- Added LCU to the Protocol Interface.
  ([`efc9571`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/efc9571c465365f83999904d9ea4eae802e57c1c))

- Added MajoranaFermionOperator to the Protocol Interface.
  ([`cb3d01d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cb3d01d3cbbcc2faf4282bd21d7e037f198e6008))

- Added modified GivensRotationFusedAdder with ctrl to the GivensRotation Protocol Interface
  ([`020d910`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/020d91082b024dcf85f0ae797719c48654ad299c))

- Added modified GivensRotationTwoAdders with ctrl argument to the GivensRotation Protocol Interface
  ([`dae00fc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dae00fc99f44e21b1633dcd1b7d48b5753f198d1))

- Added OneAncMultiplexor to the Multiplexor Protocol Interface. Ran lint formatting using ruff.
  ([`09b4cf3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/09b4cf39dff2d84cd79bdcf178b68408fb3bcef8))

- Added OrthogonalDotProduct to the DotProduct Protocol Interface.
  ([`af20072`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/af2007207bafad6eafcfff3ca79aff8f02d348d5))

- Added PhasingCircuit to the BasisTransform Protocol Interface.
  ([`616e3c7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/616e3c7d01e30e094e07ef488a470ff4fbf8499e))

- Added PrepareWState and PrepareWStatePowerTwo to the PrepareWState Protocol Interface.
  ([`33f2f40`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/33f2f40b0b44dc8e5704e92c7f7e19accd50d73e))

- Added Protocol to Antisymmetrization
  ([`1aec931`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1aec9316ec8473a0c154e4cd9ded7f0d5c152e7f))

- Added SawtoothMultiplexor to the Multiplexor Protocol Interface.
  ([`992d724`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/992d7240c900bce32b775d436b961ab5b3b87a5b))

- Added SelectNaive, SelectOneAnc and GoogleSelectOptimized to the Select Protocol Interface.
  ([`c7b853d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c7b853df33dc895f8f22f1c3fc710acdf9a38248))

- Added SineWindowPhaseCatalysis and RectWindow to the FlaggedQPEWindowFunction Protocol Interface
  and QPEWindowFunction respectively.
  ([`6aefca8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6aefca8e5071abf224fb394124f5e6b77cb4af1e))

- Added SwapUp to the SwapUp Protocol Interface.
  ([`a8e6865`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a8e6865165129b19e27038688d6d80cce234a41b))

- Added TrotterQuery and ZeroAncMultiplexor to the Trotterization and Multiplexor Protocol
  Interfaces respectively.
  ([`67dede0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/67dede024337d4c42d9d6a4664526a66220da4fe))

- Added VectorAddition to the VectorAdder Protocol Interface.
  ([`e804470`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e804470c763004a2d23c6baefc5a09678f34f218))

- Added WindowStatePrep to the QPEWindowFunction Protocol Interface.
  ([`52fa5c4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/52fa5c40b890391ca15ef49a9b55dca4bd845c36))

- Adding example for sparse state prep with junk
  ([`79fe6df`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/79fe6df61d6751e472290ea831e708447f051360))

- Changed the design doc for MultiplexedRotations and updated the interface implementation
  ([`b296de8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b296de86ed572efeb2b0369f60ee98a688ee7344))

- Second update to docstrings for interfaces in response to lint error.
  ([`b38795f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b38795f4e73cd1f9dbf66d89c679a4a1858f9974))

- Updated docstrings for interfaces in response to lint error.
  ([`b309235`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b30923533c89af20746571c272926becb9e75605))

- Wip tests for sparse state prep
  ([`f50b86b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f50b86b1d6ec7d18a2ced5bdd8143f3da3d0750c))


## v1.7.0 (2025-08-12)

### Bug Fixes

- Add tests for experimental symbolic alias sampling
  ([`6e48b72`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6e48b720f2a25b8d3a45f287a518427f8e4764c2))

- Add warning and test for 0 bits of precision
  ([`d79dd32`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d79dd325969f1f047892486aafa3614c3157f854))

- Batched_hemming_weight should allow batches equal to register size.
  ([`9ac392f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9ac392fc8b25e7524bb00289fa6d78c008b56774))

- Break valid+trim into two functions
  ([`6ae60ad`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6ae60ad3e9987a4dbfff3effbc803ba8e684a06a))

- Correct logic flow in alias sampling data handler
  ([`eba5cb8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eba5cb8d38f0ef653710c01a8ecd224c1a387e4e))

- Fixed control structure of ComputeHammingWeightBinaryRecursion
  ([`4eb9206`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4eb9206c21876c5d343d7f6b69dcd6b4b50f93b2))

- Qubit_highwater key is not accessible
  ([`6f80c4c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6f80c4c92e2133b412c4e7665d86784b6bf13113))

- Split PrepData into Symbolic and Numeric
  ([`94f58d3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/94f58d3f37b176b5cce4ddacd9ff9a1cb38745c6))

- Typing error
  ([`482cc8c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/482cc8c9d2f00be6c02464bd85891fcfe02722cc))

- Update docstring
  ([`80700db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/80700db634dc641983ee01ec2e54e21f383e3938))

### Chores

- Added unit test checking the number of Toffolis in ComputeHammingWeightGroupOfThrees
  ([`4968c9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4968c9bf65de5cf62eaa1a4f1da92b7a24e15302))

- Change .compute() to _computer() in interfaces
  ([`84d803e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/84d803e52c1561b73203ebf034e1d74bcb402b5c))

- Fix blank space
  ([`b89738d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b89738df303fdd7fe9fe99b69d43be33e39d5317))

- Fix isort
  ([`f069d94`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f069d943eab2314ec5fd7df96a4a864dfc993178))

- Fix linting
  ([`7eff818`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7eff818d253aeb6e56aeb6b843139f14f2ece20d))

- Fix linting issues
  ([`3ee5034`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3ee50343f7d26fd98e75e6a15a05e4ecae07abac))

- Improved doc strings, removed unneeded imports, and improved controlled Hamming weight test.
  ([`a3a8fb7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a3a8fb75ed67848e15f8579ed2f2b48f285d4b09))

- Merge in main and update pyproject.toml
  ([`8763605`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8763605ecb053535f311a64c8ebaadba1c5f033e))

- Ran isort on hamming_weight.py to fix lint errors
  ([`0b6f7d6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0b6f7d6e1a983da20357dc437d13d44aaf5efd7b))

- Remove Q typevar in favor of BaseQubits
  ([`d553971`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d5539712618069db22ea32685e15b6b8df0abb16))

- Revert rotations.py file
  ([`79462f3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/79462f33b793569237c3115eed31e8e3e22f2ae4))

- Temporary change poetry
  ([`cbf330c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cbf330c2ac5f202076c77702123297ff1b3c8434))

- Updating poetry to match needed workbench version
  ([`f4d70c0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f4d70c08d41b56a710fba25365feac57c34a46b2))

### Continuous Integration

- Only run qdk downstream when pushing to default branch
  ([`1b23d41`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1b23d417f974ade86043ef70c504317285ff4d72))

- Put coverage check in separate job
  ([`25bd287`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/25bd28771ff8be8827cefceda0b4c315b2cd441b))

- Remove needs clauses to avoid early execution of later jobs
  ([`d5f048e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d5f048e56ba02d0f3efcc2d25cea9c0503e7cb43))

### Features

- Add controls for adders
  ([`a32cead`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a32cead72337674ccd6acbae0bfe043f5164f0d3))

- Get symbolic alias sampling working
  ([`d042e93`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d042e9351b3f81991d4b5317fd68f41c373c6d9c))

- Update to allow for 2 adder Givens
  ([`b74c294`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b74c294ee0bfb45366ad852d649e6341a76a7b5f))

### Testing

- Fixed controlled Hamming weight test. Added control functionality to Hamming weight qubrick.
  ([`115e373`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/115e373c0bd0d103d8f9be30fc6dcd624fd0f7f0))


## v1.6.0 (2025-07-24)

### Bug Fixes

- Add docstrings
  ([`776d35b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/776d35b14a455cb308a0a34ad23b76ca908d4c42))

- Add init to mps_prep
  ([`a211f29`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a211f2952bc4fa75e85203b182defd2927dda6c8))

- Add LKS complex state prep
  ([`47714cf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/47714cf72fb80e4cc01c467548fe8caef932e7e5))

- Add tests
  ([`aae20f2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aae20f2e37f7f05db11b63b9fbf8140fa5c66fb1))

- Add Trevor's suggestions
  ([`09c852f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/09c852fa110971ba334443afa938729b7f0ad927))

- Add Trevor's suggestions #2
  ([`4afcdfa`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4afcdfaf5331c9079003c46b94ba93e9fa04b320))

- Added a check for unary vs. binary QROM
  ([`2cf83c5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2cf83c5da7b47651fdbd55e955c8827a3e5a41fb))

- Adding Will's suggestions
  ([`44bb52b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/44bb52b975f7910ab6f5db6913206959ec96d165))

- Address Will's comments
  ([`86ace52`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/86ace5206b815481a15bd507a71623a4a6221839))

- Broken tests for 3.11 locked
  ([`d731e3e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d731e3e50a412c2221cd70370d90d742019ad5bd))

- Broken tests for 3.11 locked
  ([`8faa502`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8faa50220d1305ad501507afb83e040ccc427b0c))

- Clean modji's notebook
  ([`37400b1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/37400b1f64b7d2d8f4765a4b4f61ba49c05aff95))

- Fix bug in dagger for BinaryToUnaryUncomputation
  ([`2b3abb8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2b3abb87e83801752481c8943f1affdc89e2f760))

- Fix for WB-1058 MR removal of metric and resource estimator
  ([`c419bdf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c419bdfb00fb4f46e88bb32ccc3b16d9a8a265a7))

- Fix for WB-1058 MR removal of metric and resource estimator
  ([`607d761`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/607d761c3faeb855510cec608cae283c31b8e50b))

- Fix for WB-1058 MR removal of metric and resource estimator
  ([`bbdfca0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bbdfca0deea6d18b06f2f2e61fdcc5235528df22))

- Fix lint
  ([`77fc8ac`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/77fc8ac51aca2e21aa06255b3620283c9a3700f7))

- Fix lint
  ([`2c06f4b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c06f4bde12cb3b042b07174b6612ed1659a5a88))

- Fix lint
  ([`70e8861`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/70e8861eaa38e034368931edfc37005faf8a3062))

- Fix lint errors
  ([`eeed5f5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eeed5f51729551309c1c27e1f448007e15bce596))

- Fix lks qubrick syntax
  ([`30f6d4a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/30f6d4a600bf4245150b5841652344b4ceac3960))

- Handle lint errors
  ([`ef54364`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ef543640abca082e6330f5263c588ae59d3b6f8b))

- Include Trevor's suggestion number 3
  ([`0d0b11c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0d0b11c0747db28cc156b43360a4d25a9c643a3b))

- Isort and lint
  ([`c1b25c9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c1b25c9022fba99115eb80518e7a3141d8856ff5))

- Lint
  ([`8c7abb6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8c7abb674c7c6df44d06d99ca488bf7dffb06ec8))

- Lint
  ([`3308b89`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3308b893663cbea999243125ad3e66c18f8cf470))

- Modji's controlled LKS prep used
  ([`0d68715`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0d687150541d2dcb40263170cc646a84b810aaf9))

- Move MPS prep to experimental
  ([`7cbe2f8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7cbe2f878886f595ed4dba7c794ab03b65d70af6))

- Poetry update wb
  ([`15bf562`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/15bf562f8ae9059aa840d5635f64cf0999d90d2d))

- Re-qubrickify MPS loading
  ([`781ff9d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/781ff9dd3388f33da846195c13fd3b8ac4fd9e60))

- Remove bug comment in notebook
  ([`e3a78d5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e3a78d547164d0a7581e5f128ff4c0588bd7f6f4))

- Remove unneeded is_complex
  ([`166dbde`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/166dbdef592f159a30c294be85ac127556eb0699))

- Remove unused imports
  ([`1d78c42`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d78c420e30cfe72573c77a14ad3be6e35748f15))

- Remove unused phase LKS file
  ([`b939a26`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b939a26790efc03c043eb15f89b39b0109aa259b))

- Removed unused files
  ([`f4f9a7f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f4f9a7f325d1fa0a42c91e365dbf0ada58fac8c8))

- Simplify writing alpha part of circuit
  ([`2c3b466`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c3b466d6a0cf97fc0cc3ac6e8b2f0ed7162e150))

- Update demo
  ([`5c4d2a8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c4d2a87d5ccb7a2bca1bf98d18234eb24cc779a))

- Updated docstring of a test
  ([`4a4566e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4a4566e2c1d0ce993e46d60c1333f3825eea76f3))

- Updated docstrings
  ([`e04efe5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e04efe5aca6b5e63dd14fc11ae284deef06932fe))

- Use experimental state prep for handling complex amps
  ([`c94130e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c94130e9d7703a01852ded946e27bc67a39f8957))

- Use temp registers and release at the end
  ([`49c9927`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/49c9927ddd452b1e9262509cdaecafee9cbffc48))

- **holder_isometry_synthesis.py**: Add issue number
  ([`66bdfae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/66bdfae0c80724475eab8dae9ebdf17ef7f2b80f))

- **holder_isometry_synthesis.py**: Simplify syntax for MPS loading
  ([`dbf3e85`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dbf3e855fe71f714eab072ac6261228b694c7cad))

### Build System

- Update workbench dependency
  ([`f8732e4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f8732e46a3ea804e94cb99d05bde60c11497e7b4))

### Chores

- Add 1 test, add more docstrings to process_output
  ([`021f196`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/021f1961b9f58fab3627a32c5cb2b31d3a9b0131))

- Add MR description template
  ([`9b4c57d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b4c57d324c15ebd99e098da267c1216d6296026))

- Add references and minor syntax update
  ([`aaeefb1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aaeefb1e97ec7e55ad0e86f3d6fd05efb3b7073c))

- Bump version to 1.5.1
  ([`2e0643d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2e0643de4920aabd37feee7b1845fc18834e02b4))

- Change jupyter kernel
  ([`0d370fa`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0d370fa525890754f126d2dfbfd7c811c233d57e))

- Fix isort and docs
  ([`f369833`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f3698330a13674f448180a8073232dc64ea32764))

- Fix method names
  ([`7e8759a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7e8759a1f0e846ccc8f870edb83f4100bb6c8af4))

- Got rid of returns in docstring (no longer needed)
  ([`fc866ec`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fc866ec3cb586ef4dda0cc2b6c0a627955904095))

- Initial commit
  ([`4f58a56`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4f58a56c4afc6f1cc8815201dc9ef95e05a9c1b2))

- Isort
  ([`fa6572b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fa6572b7898c53d2ba9e8bbe3f3743115f4cff23))

- Lint
  ([`8540023`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/85400236343aa4b38d89e9071ffba02238646055))

- Lint
  ([`9468a57`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9468a578e0b19a8d13fb45581b464e28e77812bc))

- Minor lint errors
  ([`54c777e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/54c777ef23f8ead017836809a86b0dd30101ab3c))

- Rename notebook to be in docs
  ([`2975813`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2975813244d91255c99a1353b7d346c4ec60b2b7))

- Update bartiq dependency in toml file
  ([`7ad5375`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7ad537512b16b5efa673c7acd4cbfbdac7f9ae27))

- Update to non-deprecated function.
  ([`13e84de`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/13e84de539433aa12e06c6d9b86005e198b0ef8d))

### Continuous Integration

- Added downstream trigger job for psi-qdk
  ([`d931de6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d931de6fef25e1dba3717f50d3dc1b5ca911d4b2))

- Make downstream:psi_qdk manual for scheduled pipelines
  ([`aad26dd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aad26dd0817a00079761d08b73c6a34ce147e22b))

- Remove existing downstream jobs
  ([`90594a7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/90594a72244ec4d2c990a3e55554d506499b99bc))

- Update downstream:psi-qdk rules to run on main and scheduled pipelines
  ([`0fc6181`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0fc61818266d568fd70cfac77c2a0ad99ff95bab))

- Updated dev-ops/common include reference from 0.0.5 to 0.0.6
  ([`b6d4fa0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b6d4fa0677637416c3e50da311e46847a66e417c))

- Updated downstream psi-qdk trigger branch target
  ([`9fa8a59`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9fa8a59f17b0ff77af0e2c285ea63130e2e37fd3))

### Features

- Add additional content for naive state prep example notebook
  ([`3d84f53`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3d84f536a84c812b136b87331f496e380e354f48))

- Add dataclass and add controlled tests
  ([`b6ac074`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b6ac074bc92d6814f730e018c251681f900f9516))

- Added dataclass for unitary synthesis, also moved reg args around for unitary synth compute
  ([`c9aa152`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c9aa152de689687638389b2787021efaf63f6a78))

- BRNO now sets ignore_last_batch on users behalf
  ([`368907e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/368907e8c05db4ad71c4a1f776e5c4eeb0b6a96c))

- Can turn off custom uncompute inside parent qubrick
  ([`db61b28`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/db61b284b605fddfdcdb8bfe2b37b122b4631b73))

- Changed dagger from instantiation to compute
  ([`1d37099`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d37099588e462424cef08c40430cefc93846674))

- Demo for latest MPS prep code
  ([`754e774`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/754e7741a224abb2a783d553a166ef9c7c2d2ba1))

- Got rid of overwrite parameter
  ([`0b0ae24`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0b0ae2486ac08ea98034523fa400a361b2b3faa7))

- Modified muxed rots to allow for batching when used in BRNO
  ([`33399c7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/33399c7a1f7289f13b0dc7731426837e8951804a))

- State prep now takes prep reg, updated tests
  ([`6ef80ae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6ef80ae5d773fd234541756aaa788da4251e636d))

- Updated multiplxed rotations notebook to use new BRNO + get rid of deleted attributes
  ([`92f5434`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/92f54345f8cae9215f088b5e033c71d019d69ced))

- **test_mps_prep.py**: Added unit test
  ([`7c9ff19`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7c9ff190fc18aa25a67bb5da1d87f264adb5a5a2))


## v1.5.1 (2025-07-14)

### Bug Fixes

- Add Rz, RzAdder to init
  ([`bbf8cb4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bbf8cb46c5ef0eb06aace87952198128a33038d7))

- Changed system size to apply Ham onto in Trotter test, correcting a bug spotted by @jlemieux and
  explained by @sgreenaway
  ([`d45f954`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d45f954ec2cbf0d3e38ea7fef7bfc99914c0c126))

- Cleaned up trotter test with PPRs
  ([`8e3862d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8e3862d8459c2da037e739f2dc24ff9dd2e8f2ba))

- Fix broken links in API reference
  ([`4099da3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4099da33d1a383925041a123ed24056bf1d03395))

- Fix sorting of modules and other linting issues
  ([`f1de881`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f1de88151e65841fb22399d290cabdbfe35f9f64))

- Lint everything according to new rules
  ([`2637739`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/263773904e5362fd91e5fedc690b351319e2b321))

- Made sure estimate method passes ctrl=ctrl rather than ctrl=0
  ([`43c2a88`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/43c2a887e0af015057f0b902543fe81b8521f465))

- Remove extra name in Qubrick instantiation
  ([`a086fdb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a086fdb481b5fd7447ad139f501c39bf4c9262bb))

- Remove tutorial symlinks
  ([`e6e0968`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e6e0968df1dd572b3f988a69f155bdb9bc9677db))

- Remove unnecessary noqa tags
  ([`e0e5f67`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e0e5f6755437d29690cdd7ccb39016fc2fc163fa))

- Revert changes to formatting of copyright notice
  ([`0105a01`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0105a01c856a56d0687a5258438e7ee0a0a8f945))

- Undo changes to the copyright notice
  ([`51c4bfb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/51c4bfbe20fa8508fb5e95bbe5079a88aaac07fb))

- **cicd**: Bump dev-ops/common version to 0.0.3
  ([`df2e4ee`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/df2e4eeb588f9c463851f7974ffc75ee50b3c0dc))

### Build System

- Added bartiq extras dependency to psiqworkbench
  ([`eec8431`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eec84316327c5c1a7f816f5447fc1fe21f0b52c3))

- Migrated pyproject.toml to poetry v2
  ([`b674fc9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b674fc9711cabe36a0d6c7c4cfe76613d54366f3))

- Moved python requirement from tool.poetry.dependencies to requires-python
  ([`0a7735d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0a7735d2d4b1e8cafbc1526001a9eb59839ca35d))

- Remove explict sympy dependency and fix bad scipy spec
  ([`3085c3a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3085c3a941927c17c48b4d2173a2969a3766ff9d))

- Update poetry.lock
  ([`02e5161`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/02e51614d2106bde852bcaa0720a7afb904393b6))

- Updated poetry.lock
  ([`02f260e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/02f260e7ac1e36b3af962a6dde5c9a0792c43df2))

### Chores

- "RotationInterface" -> RotationInterface
  ([`9b3a474`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b3a474b644c31588254bb484e4bb860da86c2e2))

- A few improvements
  ([`784c07c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/784c07c07967b2573f415ed31ffb3144a41776ad))

- Add minor fixes
  ([`d376df9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d376df92a0ae0026bce97b56624fac4de2b87ed5))

- Add typing
  ([`00e3382`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/00e3382bc1a4c4079cdb7c5c588b09d0ca4743a4))

- Bump version to 1.5.0
  ([`613bbe3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/613bbe3bdadd74797c48f7f72c90f8c81ed5c583))

- Change data to config in name
  ([`ccf65d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ccf65d1e9fbc4fdbb1504d6d44db95e093a676ef))

- Change kernel in notebook
  ([`cb5695e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cb5695eb88fc12648481fccf4c5a872871de791e))

- Delete accidental line
  ([`eaae49a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eaae49a68c878556661129c199747e7a8b9ed4f8))

- Enforce rotationprotocol everywhere
  ([`ae6d457`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ae6d457214f3d956cec4b9109112500b07f4aeb9))

- Finalize design
  ([`bcc6f63`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bcc6f6324b32b0eafb266ab7035505ba15d589bc))

- Fix docstring
  ([`6994b24`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6994b24a4ccdf42a24a2d54740b54454f256c35d))

- Fix isort
  ([`4d97a39`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4d97a39c7e23f7d234e3a11ce8249cfcaa20681c))

- Fix isort
  ([`baea609`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/baea609aec5141b2adea31c3853ea079e60b6037))

- Fix lint
  ([`04276a6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/04276a660d5fb5ab6ca16cee9b5df12aac609a43))

- Fix linting
  ([`5058fd1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5058fd1791b850ff0b5dfd32333f2b1e22bea08d))

- Fix tests
  ([`138eeb3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/138eeb32e22c06d7d29bbcf6eb81c8968c738b03))

- Fix typing
  ([`7be8c3e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7be8c3ef921b3840709c1628031fc8f166fd1990))

- Lint and got rid of unused args
  ([`a859e98`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a859e9816482c076477f585bcd27ac7fb9426bff))

- List -> list
  ([`4da28f9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4da28f91fce05dc5893ac135a25613e5add07c81))

- Make all rot_qbk have same signature
  ([`06b26a8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/06b26a80dafb9ea95b57ac4d4fabf7be41ef0250))

- Minor updates to reduce number of warnings
  ([`138209a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/138209afbf2038837cedaf25c05e54c4c79dd1ab))

- More improvements
  ([`52ad9cc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/52ad9cc280b3e2cd01dff361d0ea6892e0d88e2d))

- More notebook and some minor fixes
  ([`19f722a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/19f722a02691e13486c814eedcd517c156caf694))

- Remove _str_
  ([`6d6e56f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6d6e56f3d3df31e0ee413d2c07a1dc8a13d38f67))

- Remove knifey filter
  ([`1c7df7d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1c7df7d8c5490cdfcc0271a5246b5022fc07fa52))

- Remove naive
  ([`c5d3d07`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c5d3d0786f47fea309da072f5163895a29caa686))

- Remove other mentions of symlinks
  ([`0b39641`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0b396416bdc3c27fa33e81d5ae5ec2ae84f9f2bb))

- Rename givens loop
  ([`a531f51`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a531f5166222ca833b207013a9617550280161b5))

- Rename GivensAdderLoop to GivensLoop
  ([`0df46af`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0df46af2ee15778d84ff1af639f5f3df7f73d384))

- RotationProtocol -> RotationInterface
  ([`f2cc1e3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f2cc1e30b54b68e4f5c4e903c74720b248871625))

- Small fixes and more notebook
  ([`59e5348`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/59e534820faf66bcc0a3d4cf2e5ac6562c5dd25b))

- Trigger CI again
  ([`3ad3f8d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3ad3f8dbe0f2b50f0f919a9bff415e29c9d04135))

- Update dependency on bartiq
  ([`001915d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/001915d45f9956edfad8db6fd5038c2cc667d85d))

- Update WB & Bartiq version
  ([`f218657`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f2186570562a4d673f3e95ed7843312c19685b6b))

### Code Style

- Fix isort
  ([`476e34e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/476e34e2f9311c6fae3a4b7c0aa594cf4d9a4efe))

### Continuous Integration

- Add default assignees for version bump MRs
  ([`833f6ae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/833f6ae85eb66ed099e7d617b34aa6e656f22243))

- Added the notify stage
  ([`9155ef8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9155ef867025af77184fb3bcd2d722b8c3b5f2b6))

- Deprecate use of old python index server
  ([`7e4441d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7e4441d9a00b8411b50ebe203a6babd1f9688a66))

- Ignore site/
  ([`c874b55`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c874b55a350cd6321914379de30dfc5cdf80933d))

- Pass ref to included dev-ops/common CI script
  ([`0e43dae`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0e43dae34e7040af8d3d2e8e7e679a00446e3a5d))

- Refactored script for more sensible order
  ([`290fd95`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/290fd951c5ad414ea9202e924739df237f908a6c))

- Update dev-ops/common include to pre-release branch
  ([`550b529`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/550b5293bdd16e00d0799ed8535687ce66d81f97))

- Updated dev-op/common reference to new 0.0.5 release
  ([`289dfad`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/289dfad4ed0a54af94384e57d91e76457c61327d))

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2
  ([`caa9de5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/caa9de51a72b109bbbf0032c5c2836e301b2d1a0))

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2
  ([`da020a0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/da020a031e95e06e2899659b2e9294678ddf88b6))

- Updated dev-ops/common include reference from 0.0.3 to 0.0.4
  ([`e0c32e7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e0c32e7864846bec12263c0714a7d5e54223a541))

### Documentation

- Add batching section to rotation notebook
  ([`664f77c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/664f77ccb161000d826528457b0e6dd6d77d8cba))

- Add new givens rotation tutorial
  ([`a299122`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a299122f4b8ce9e3e5ba173b3de76d8f5fb302cb))

### Features

- Add gates.py submodule
  ([`7f9cb74`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7f9cb74c994181cf9f007509d054ab51d207a070))

- Add generalized multiplexed rotation
  ([`322cb87`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/322cb87bd62e3138762190b466306e5f6d61361b))

- Add GivensAdderLoop qubrick
  ([`500d1e2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/500d1e2dc469dad172a0e192d3dc3d8f5b8a6040))

- Add GivensTilingScheme
  ([`20688c0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/20688c094e223e7dfc428c7f4be837648e52a94d))

- Changing qc.ppr to system.ppr
  ([`938fb93`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/938fb939abb8e08827a3d573db908424443ad490))

- Updated Trotter to use PPRs with a control arg
  ([`de4d932`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/de4d932bf03d7cac2b592041a81e969bd576368e))

### Refactoring

- Simplify rotation code structure
  ([`4cf4d69`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4cf4d69b51ae824e448b67a3611a63983e429e2a))

- Simplify RotationLoop by removing sequential mode
  ([`5815105`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/58151059e41c4c67eb25fd3b8408c7ccb6078c55))

### Testing

- Add more tests
  ([`05f65af`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/05f65afabd97f6f2ee01e4d52d248d7295f3db46))


## v1.5.0 (2025-05-13)

### Bug Fixes

- Add back phase_prep to make the interface+controller happy, still need to figure out how to cut
  this redundancy
  ([`823bd51`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/823bd512dabbb829cb1c58e458a0b8608ef1de3f))

- Address linting issues, added missing arguments to docstrings
  ([`6f60339`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6f603393ffb63f79944f19c72c3d89bd16df2e9c))

- Better precision for test with less qubits needed
  ([`5f97daf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f97dafea124b5e4abcaf3d5b7901529264082f9))

- Change gray code multiplex name to avoid conflict
  ([`bc4ab46`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bc4ab468eda612b1a81fb39dc95ca8d50e35bc7a))

- Change grey to gray
  ([`36e5c58`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/36e5c58af365057e099d570aba807782c1cc1a10))

- Change inidivual amp comparison to total state l2-norm bound with eps
  ([`4d4556b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4d4556b1c58a9943a1800fd279a9abdd5ec5f5bf))

- Change name for naive and LKS state prep to avoid conflict
  ([`894fb7f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/894fb7f8ddbac8d18422cbc4b960842f6d7b9f9f))

- Changes for various comments from Dylan
  ([`bff9241`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bff9241e6253585be3fa79feccf35e1301246033))

- Delete MMD files
  ([`253ac9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/253ac9bf9b99ebfd0e631f3d3068c469c95050fd))

- Delete unsupported cases to avoid confusion
  ([`0509e75`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0509e7542677c9a542111f533f97af0a75d38e64))

- Docstring missing
  ([`ef7b625`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ef7b6255aacb592fccfff75eb22f225012f63a5a))

- GidneyAdd object call
  ([`9910a4c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9910a4c4f04f02688354942ad9b360aa1acaf0bc))

- GidneyAdder object name
  ([`b049452`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b049452eecc18a30f75c5be0d5d86bffb1430f7b))

- Isort errors
  ([`3acc1c8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3acc1c80bb1a63cafaf9bcd8d405e59c2840f722))

- NaiveAdd object call
  ([`b972c5c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b972c5c2e67318a6fa9533d074617941a5e7c7de))

- Name change, comment fix
  ([`5a8c848`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5a8c848d69907afaf1fdf7af8fa89a40e1fbdd80))

- Remove check in .gitlab-ci.yml
  ([`d828eec`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d828eec77faaf383223c90cb604ac8f444dc7590))

- Remove commented out line
  ([`6433c29`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6433c2968121a7c682abc4713e8f25814d18d0ee))

- Remove commented-out code
  ([`63deff5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/63deff51612cb92399d0443eeee9fa0d52c82ee5))

- Revoke import
  ([`1f25b64`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1f25b6420008b942a29b32efb5b7ee35fdab29a2))

- RSqrt + GidneySquare object calls
  ([`01bb159`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/01bb1591ca92a4299ecb7280813fea08fe3bf8c4))

- Several changes from MR comments
  ([`bee677d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bee677d8a69a290cd3937eb4494d7d40dc7401eb))

- UML_AS
  ([`a54fa65`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a54fa6554e8c5fcbab162693311a9059c4e00eb7))

- **cicd**: Remove pytest-rerunfailures dependency
  ([`b394ac3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b394ac318e983ca6f344f8259fd850a968c6bd04))

- **cicd**: Remove rerun args
  ([`9eeb18d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9eeb18d43c5d1b5c95b4a2b94a9f9ad96796d0eb))

- **poetry**: Un-pin poetry per #327
  ([`4e6ed55`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4e6ed553b4c3f35a989d592969a6dd56e01a880e))

### Build System

- Add lint rules to pyproject.toml
  ([`ad968de`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ad968de32cdbe5245d1ac579491581189d36e6a7))

- Added codeartifact deployment and docs publishing
  ([`4c62b38`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4c62b38841fbe00328c9652c9b7fdd5b4dc077e7))

- Added missing optional dependency on scipy
  ([`0f96f03`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0f96f03fa0301c7d41772ed0d637c03923a700a3))

- Centralizing docs publishing job definitions
  ([`d15955b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d15955be0cc94bd133b423faf616cda7108d8577))

- Changed manual optional CI steps to be non-blocking
  ([`dcd6c36`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dcd6c36f87619764545a7d113bf29d1c76b284ee))

- Fix python dependency range
  ([`878a90a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/878a90a4cdc4efc859e57e6850c04c9e94abcffd))

- Made docs-build-dev run on every pipeline for testing but without pushing to s3
  ([`ddd2dc0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ddd2dc0227d57694b04a4076cbeff2130095f1c4))

- Pinning virtualenv in beforescript to v20.30.0
  ([`9224f28`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9224f28cc7022e083008d8e82dc66aca21c808f6))

- Refactored definition in docs module
  ([`9232a5e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9232a5edd435e79c5cd4949369395f51df17a3a9))

- Trying previous poetrylock
  ([`e9a6efa`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e9a6efa364667e1529186147bb847147518fab5f))

- Updated pyproject toml
  ([`a5c4fb2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a5c4fb238e4f2d155a78145c26404178d7c5334d))

### Chores

- Bump version to 1.4.0
  ([`d4006ff`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d4006ff81a362f2f52d7025b6ef704d763e1625d))

- Deleted redundant computation of lenght of list
  ([`6a3e279`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6a3e279d1b096b5a80771fec0455e6fdee3d5d13))

- Final_version_for_real_this_time (updates to imports in tutorials)
  ([`b63f974`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b63f9742e376e8afcb4b7f2d5e2ec8bb956c336b))

- Got rid of spurious 1e-10 and 1e-15 in tests... overkill and unneccessary
  ([`a36c13b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a36c13b33c8a8f8ad42e7256e0b56d64a9881c37))

- One (hopefully...) more import fixup
  ([`08ea452`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/08ea45293eff434e2e84d20e07f12c18cafeaec3))

- Update dependencies
  ([`032e6b8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/032e6b84dfee2e96c69c213313d9d7cb191e1da7))

- Update imports in some notebooks
  ([`949bae0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/949bae00e724be03d10b6adfd2198e2b1f0cc8c5))

- Update wb dep
  ([`f51756d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f51756d8af5bff2b9fd7a0ea18354eefbd814816))

### Code Style

- Ruff format
  ([`fe9b2e2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fe9b2e2c746dc880b3380596e813494f7650ea85))

### Continuous Integration

- Adopt default python job template
  ([`143e50c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/143e50c6c173a31d43fbec9e71c2c6bcb9c32766))

- Install all extras in test jobs
  ([`39a0f09`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/39a0f09eaec11cd9d8cbb602fc6d1a5b3240c004))

- Updated before_script config for new pypi server
  ([`4f57543`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4f5754303ba84dcc8fe02e19877a910bd8020344))

- Updated dev-ops/common dependency to 0.0.1
  ([`ccb446f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ccb446fbd2498f93dd23ab376c04f2cd61235a51))

- Updated poetry dependency to >=2.1
  ([`f0899f2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f0899f2b19118dab85f38da9e09f9128f3e8c1af))

### Documentation

- Add math equation comment for test
  ([`2959fd6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2959fd6b07b26a2c3a11c39cf8193523c97bd3d2))

- Better reference + additional clarification
  ([`7a4659c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7a4659c4f35c26a889f2912032dfb9e779072f0c))

- Fix test file summaries
  ([`30d90b4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/30d90b4aa7d6efc16333e615804af6c655c832b5))

### Features

- [WIP] consolidate tests using the DI framework
  ([`79553f5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/79553f5f3b5a624d2b29d3e67d89ac4a41d90ca1))

- [WIP] refactor state prep qubricks to decouple them
  ([`7a3264f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7a3264fc29602c70dbd0f91ead87f2bf36cf2f5a))

- [WIP] xfail failing QROM tests (TO RESOLVE!)
  ([`be9f1d1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/be9f1d15294f0b05e1bcd5bf9d17ae384099ea79))

- Add alias sampling lks interop test
  ([`1be0bf0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1be0bf05a5fb0e438ac701e06b90f483a1b896cc))

- Add experimental features to the docs
  ([`fa65779`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fa65779aa93c698c39e8a8fea26fb41a695740ab))

- Add test for uncomputation
  ([`4200c89`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4200c8973b782de10e474a956f00649e6a45c71d))

- Add tutorial notebook for Qubrick interoperability
  ([`e223fc9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e223fc981d3c3b17d3f07c21a1caf233f11ee9b4))

- Added LKS state prep changes
  ([`62f7e6c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/62f7e6cdb6a56a8829c11e5cc7876556726d9b76))

- Added test to check we need to pass in the coin toss reg
  ([`649420d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/649420d9f951f046f8b42b7bb0afd7eea5e403af))

- Ensure all classes/functions are typed
  ([`0876cd5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0876cd5c3d8cf6624aa53ea60176a3613c1085f7))

- Linting/CI fixes
  ([`4e6e6c3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4e6e6c30c881ee238c20d7542a4599b5521eac48))

- Minor update to test to remove specific qubrick references
  ([`59b380c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/59b380c27d604a82f06db60bc92b19cc27aaf494))

- One more sort
  ([`9cebd96`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9cebd966bc741d0c12929c47cbfe4f89791e38de))

- Re-add complex tests for naive and gray code mux's
  ([`14ac358`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/14ac3585b1e480646230578da0c901d14cd46363))

- Re-organize files to mimic main repo
  ([`614a6d2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/614a6d2e244e8fc1d42e134dbba043e325d7cd69))

- Remove deprecated aliases
  ([`172a4bc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/172a4bcae8fc7adfb17145825951f2f3cd86a1d3))

- Remove gray code stacked phase gate test
  ([`b3a7614`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b3a76147381bc62c923e0e661ff5e6d0c25c3bb8))

- Remove unneeded "experimental" in test file names
  ([`782c1ca`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/782c1ca5e99d3562bb2ab433f5ac959ad8618c67))

- Revert changes to copyright notices
  ([`d316914`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d316914c9a218cac33dbd00b197be37d5cc9ae88))

- Split up tests for easier parsing
  ([`c1421ee`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c1421eeacaf529fb236fb946e600a19f8e795e99))

- Undo changes to init file
  ([`457e8e4`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/457e8e424e64f941e9f45445cabf0904d0821ecc))

- Undo changes unrelated to the features added
  ([`aeaf742`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aeaf7420ed3d971d9ceeedf685b65eb58c77ab2f))

- Undo linting changes in rotations
  ([`f2347b9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f2347b9f174d060bf3199ce866cf2ac282ce059c))

- Undo linting changes to set_version.py
  ([`b073fe3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b073fe36b218579b21536c2ccb01163cd0ec9e68))

- Update poetry.lock
  ([`3c66957`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3c669575144b587be8aafd98d9173f26d0a87a42))

- Update pyproject.toml to drop python 3.10 support
  ([`e6afc4d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e6afc4dd69fb4874b40752b297ceb17d56c0026f))

- Update qubricks in interoperability notebook
  ([`831cfd2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/831cfd217e0152834e918cba47d958255fe3eb23))

- Update test docstring
  ([`b0623a7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b0623a785c7497279c733d45b8c4a7b72977f655))

- Update tests to check for phase and amplitude correctness separately
  ([`c51bfea`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c51bfea186a2a6f07cf618824e0c648315748dcb))

- Update tutorial notebooks to new API
  ([`36295f1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/36295f118047e8817bcae4f036119ce7ea72c78d))

- WIP delete some unneeded lines
  ([`af8e4d0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/af8e4d022487c78264405cddc5ea515cc049e8b5))

- WIP get most tests passing
  ([`c4fd0ac`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c4fd0ac0daf02a74168692701a628db34a125fb1))

- WIP pinpoint failure of tests
  ([`4cb3fc5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4cb3fc5f6da341a310424486c814b21ef5533c89))

- WIP refactoring of the file structure
  ([`b3c0d99`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b3c0d99e96755ad1dd617cc2b8ba471ea2324d3b))

- WIP reformat files
  ([`dba401e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dba401e9eefa68fdcefd5698eca144625ccf7982))

- WIP update docstrings for LKS qubricks
  ([`a191650`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a191650376edc6654653995644e18fd95a9091df))

### Refactoring

- Change test file structure
  ([`f5c1222`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f5c122273beb47500b17c8dabebf3514d06321f9))

- Reorg example notebooks
  ([`c2c5d70`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2c5d70a83434bf15dc9dc4e9b098033b1696968))


## v1.4.0 (2025-04-26)

### Build System

- Migrate to new artifactory
  ([`65525fb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/65525fb78b31de436927809f633f5527ae1721ee))

### Chores

- Add test for too many batches
  ([`27bd95e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/27bd95e8f616a769a6ca2539d096b31df9ed04e1))

- Add typing
  ([`49b5079`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/49b5079d4e020d1f2ff01c921f512f8c85f36270))

- Add typing to compute
  ([`62dd98b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/62dd98b1b37badf655513474d9ce9a6bef5d8fe3))

- Bump version to 1.3.16
  ([`e7969c2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e7969c24131f79c2029156855745da0b2cceb85b))

- Fix docstring
  ([`3580993`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/35809937619b3514315196bfb436470b8ac27739))

- Fix imports
  ([`4b1bc3f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4b1bc3f7a2b7a43593429ccb975a02d9de4fbcb5))

- Fix isort
  ([`5f3cbe5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f3cbe53d8ab41d0d061de6e693bb4ec03be2a8a))

- Fix symlink for tutorial
  ([`b2439e6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b2439e6312eaa65a37288e7c138b73350434d856))

- Minor mr review fixes
  ([`5cef4a0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5cef4a0f1ec20f22436c0e0c46358410fa3abca1))

- Small mr review fixes
  ([`27b9160`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/27b9160328f376483ff469ceef2142a0957539cb))

### Features

- Add batched hamming weight phasing from echo
  ([`3bce9d6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3bce9d6023a634dfc1abbdff1d9ed26e6c1c501a))

- Add batched hwp tutorial
  ([`04f1705`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/04f1705b6318a58ff93de3d6ebe91ba2f893f3ee))

### Refactoring

- Remove unnecessary files
  ([`82dc19f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/82dc19f8da1efdce66bed5a4a4657b936ccfd0e0))


## v1.3.15 (2025-04-22)

### Bug Fixes

- Fixed adder imports
  ([`98d1719`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/98d17197e893b1bc0d57ea9964392911ca882c56))

- Re-ran hwp notebook
  ([`e7a24eb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e7a24ebbdd09fd285f5446008d4b1bd57c5a8334))

- Update imports in hamming weight notebook
  ([`0166852`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0166852416578cbca0ff2d48ca2e937ddd655cf6))

### Chores

- Bump version to 1.3.14
  ([`b616956`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b6169568d8640c310c9625fbc6462edf42f320ce))

- Easier hamming weight computation
  ([`97f7a7c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/97f7a7c581df00601a7e24e1e354c694b587713c))

- Update lock file to satisfy the poetry gods (but really im a heretic and dont like this)
  ([`140768e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/140768e15d973a3fcdf1503d392b66fadadb20fb))

### Continuous Integration

- Add CODEOWNERS
  ([`0029740`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0029740674a298d2a953665418c8931702dd7423))

- Added deploy to new artefactory
  ([`71a0c3e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/71a0c3e2434cf57ab4f743e1984e95704a329217))

- Fix CODEOWNERS
  ([`f6d5cac`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f6d5cac155f07c563f38ec8ad6610917610db11d))

- Update include project reference to semver tag
  ([`8b880e8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8b880e8e9937ea6a977dac595714a3f591d52999))


## v1.3.14 (2025-04-08)

### Bug Fixes

- Fix bug in dirty qubits handling
  ([`abaf139`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/abaf139129bb7a56e3a6e69c24596cafb7ba1fb4))

- Make automr commit meet conventional std
  ([`a28159d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a28159d4dadaeda3b572eed66c80af53771b82d9))

- Sort imports to fix lint
  ([`dcb5d1f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dcb5d1fdb5f2ca32f7e8b82cc7a669fa491b28db))

- **cicd**: Random_seed for a probabilistic test
  ([`f23ba09`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f23ba09450daed123d94abc4210beb72982cf885))

### Chores

- Lint
  ([`03cd47e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/03cd47e5bd9c1656f1f574822b3a155609e5441c))

### Features

- Minor cost reduction for groups of three HW computation qubrick
  ([`8a98c5b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8a98c5b3e38f4e5cfeb682f2a170d1ed77c315d5))


## v1.3.13 (2025-03-27)

### Bug Fixes

- Amend /ket and output pics in dyson
  ([`cfbe195`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cfbe1952d6e2b11e315b5dac6d788f9cdca39f34))

- Amend empty lines in lcu
  ([`94975d6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/94975d65b3d1a26d92a117e89745aa7da636e7a5))

- Amend link in ampamp
  ([`fa7df3d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fa7df3dbcd787a9db1b3c95d7e0f5e7cae962718))

- Amend link in Data loaders
  ([`a6ef415`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a6ef4151fcf17b4997f29dea20e1207be1c1f84c))

- Amend link in dyson
  ([`d6ac0a7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d6ac0a77fa111aed178ca94400cde76c4755921c))

- Amend links and warnings in ham weight phase
  ([`5480126`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5480126a630b5ad6844db32dadb9a5211469ea94))

- Amend links in low kliu
  ([`4c64184`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4c641849b8fff7ecacca0ca42613045aa01804c8))

- Amend minor things in vector
  ([`4bc5a37`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4bc5a37f8ef31cbc593f75c467e2e9c53e9da12c))

- Amend multiple links
  ([`631348c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/631348c68150c8e2921367a1d40e901ee3d58297))

- Amend reference links
  ([`7175c80`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7175c80d11d1c98e5264d206801bafaa9521a278))

- Amend table in dyson
  ([`eb05d3a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eb05d3a14c928c264db5b8658be39f518cea3943))

- Amend warning in Window
  ([`e1e270b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e1e270ba39747f4a88b26e048a7d8f13869b1b50))

- Circular import
  ([`1426603`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/142660326405f6db6ba5d28e1cf76b7eaaac6619))

- Convert \ket in Compression Gadget
  ([`61a8e5f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/61a8e5fa7a4cb92acaef698ee3106082787e4e77))

- Convert \ket notation in Antisym
  ([`11816d0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/11816d0332d05e54e31b458676d4a8435b4fa3ef))

- Don't assign unused variable
  ([`c4f2027`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c4f2027bdd1d1c66b454ecc6f8dcf986a8622cde))

- Example
  ([`2f551ed`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2f551ed85747770fffc21623a19bf232751ac3f8))

- Fix minor things in vector arithmetic
  ([`3b5d800`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3b5d80034995e9ee3170f8ac6bf07d5e7064a6c6))

- Fix qubits alloc in vector arithmetic
  ([`1ccee18`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1ccee18fcb3e514a4ab882461492196cf874e2b4))

- Minor updates to fix warnings and delete blanks in tuts
  ([`ecd2b3b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ecd2b3b3523bfe1c16e0099571d7ef7045c7258f))

- Move build_qubricks_zoo back to utils
  ([`f61977c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f61977c4c839d15347b6389e0be30d9c6bf4b32e))

- Qubricks zoo builder, mkdocs.yml and README
  ([`941cbac`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/941cbace085bf420043f7b139bdcdbb667d59686))

- Remove deprecated WB names
  ([`0ac4e23`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0ac4e23c46ec886ff08a314a72bbaed60d9a396e))

- Remove empty cells in pauli sum
  ([`2c748f5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2c748f58f746ac4144f8443008bf6c14d1cbc865))

- Remove empty lines in multi usp
  ([`156997f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/156997f9c313cd993e4d8c81df8967aa7317b2aa))

- Revert accidental merge
  ([`e8f3fbc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e8f3fbcc52ee5dda79d5f860da0ca1c394a8caf3))

- Update how vectors of qubits are used
  ([`bd9c48b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bd9c48b5aee11343db4a8ab821266ec195ff0cfa))

- Update old architecture paths
  ([`660e4e2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/660e4e2c84e233a3c711e400f3212fdb9b609159))

- Updated paths for migrated repos
  ([`b8c2c2b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b8c2c2b71c0a257b1cf25e6b9b5e836204411f58))

- Use makefile in mkdocs cicd
  ([`f0dea82`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f0dea82fc4f6350f22e4f08d4ffaad7e2013d0cd))

- **test**: Add import to alert user when test fails are not actual fails, per #301
  ([`bf8ce62`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bf8ce6271c922c4a4143a080e2736e25fee4f143))

### Build System

- Added isort as linting dependency and pre-commit hook
  ([`abb59e8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/abb59e8e39629ca845b9ece752ba013f812d99ae))

- Fix python dependency range
  ([`f09d916`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f09d916d0914c3a0a20e1026a62717f04d8450e3))

- Update poetry.lock
  ([`03c6606`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/03c66068f468cc38def3d49f0f125a7952fadc08))

- Updated lint tool from flake8 to ruff
  ([`1522802`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/15228024023cbd8a01d2821235142c06663f4791))

- Updated poetry.lock
  ([`bcc3dc6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bcc3dc6680e27a47a2921e0a1239e96004398614))

- Updated poetry.lock
  ([`655131d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/655131dd796048177401341abd8bbf963f7d0149))

- Updated pre-commit config
  ([`a5645a3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a5645a37d92b367522af9b50a82db72e9a73a6f8))

- Updated python support range to match common spec
  ([`7b20f5e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7b20f5e1ece3181dd6381ab527817ccd3232b6b2))

### Chores

- Add blue and red boxes to multiplexor png
  ([`d17626e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d17626edd9261b07ab3d5ad73c36da615c405189))

- Add copyright
  ([`d857255`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d8572559ae23a2765861134dfe6c14a7c2629fad))

- Add debug line for this branch
  ([`d5f915b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d5f915b2c57c2f21ba908735098f568002f06017))

- Add debug prefix in cicd
  ([`305045a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/305045a332f8d9c0335b1f3eaae35c1d747ec9f5))

- Add dyson and symlink checker/creator
  ([`6e82a7e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6e82a7eaf8051b11c2c4a013aaa26a2d663a0882))

- Add flag to test pipeline
  ([`3b37ca1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/3b37ca1df2a26c1c55177686eca594118d759739))

- Add minor fixes
  ([`72af010`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/72af010d9fd45ab610b7912aafc4e8b087337d9b))

- Add minor fixes to rotations
  ([`be11da3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/be11da327f06df23c20320d976cc955fab393993))

- Add negative angles to test
  ([`329af53`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/329af53377d2bcbb2f7d511b02d0aa5660ef7ac6))

- Add qubricks.md to .gitignore
  ([`0724cbb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0724cbbe08915fd5495bf2bd7fdf1cbd0c3ab669))

- Add the new antisymmetrization ipynb
  ([`770b1d7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/770b1d738eb84e9e3f4a1529061fb7e6628d0b47))

- Add various fixes and tests
  ([`40badcf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/40badcfdea3a807f36fce2f2ca6e864a6d70ede3))

- Audit public API
  ([`722aa04`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/722aa04a623cb88cfcd2b842b993afdb3831f782))

- Bump wb version
  ([`329052c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/329052ccb67c69f7efafd38951106fb2b189c1f0))

- Change jupyter kernel
  ([`98211a5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/98211a58377e2f17331f5121240a4df829e92a85))

- Delete empty cells in bitonic sort
  ([`9bc2b33`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9bc2b332a561831b022ba087b7b2f254fc8624b0))

- Fix amplitude amplification utils doc
  ([`fb8f657`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fb8f657b234b05c55b1604a8ea7aba0ba795a61d))

- Fix arxiv links
  ([`5a67858`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5a678587161c7c416303e050e76d12e043b3b0f0))

- Fix arxiv style links
  ([`baf370b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/baf370bc15ac2e279d2dd0f1d09662b1d4108e26))

- Fix clean arg
  ([`0bb63dc`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0bb63dc4b2029ae086e5a2d66947fee0bf4c760f))

- Fix copyrights
  ([`ae118c3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ae118c34e79aaf6186c0f8f4db3c6a7a39a9ee22))

- Fix deprecate
  ([`1b5d6de`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1b5d6defbf584814203b3a6bb762e82e2072a695))

- Fix deprecate python block
  ([`c4528be`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c4528bed38bd6767179d788d94374e4719fd520b))

- Fix deprecation warnings
  ([`e40b33f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e40b33f286a53de62c262cd33d6314518ce3ce66))

- Fix deprecation warnings
  ([`ad9bac0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ad9bac06728fb2cbb891895dd544fd9fb46c3255))

- Fix deprecation warnings
  ([`afb5085`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/afb5085951b455095dbedf8d654f5b600b824464))

- Fix docstring
  ([`cd37f82`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cd37f82a81145f8f761bea7f60a4480c96d04298))

- Fix documentation rendering
  ([`678b7f9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/678b7f9c51ccda0231d41cfcaa85411ba002e774))

- Fix flake8
  ([`dee2c43`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dee2c43660156f041148ddcd33e516025b1624a8))

- Fix flake8
  ([`896ccab`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/896ccab181a7bdc520221bb4d74557cdee94e4de))

- Fix func sphinx links
  ([`643131c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/643131c4c1a37f5274d42773054285fcc210253d))

- Fix gitlab cicd
  ([`f7e0c5e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f7e0c5e030fe0c07af2240c3ae7fdf18ca8dc537))

- Fix imports
  ([`091ad77`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/091ad777b59a58c3bffce29934e124abda24944c))

- Fix imports
  ([`93defdd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/93defddd4e5a907cdaa17cebafdde8924026ea76))

- Fix links in ipynb files
  ([`95d469a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/95d469a1b9107166f3c26381f61a951215c07b81))

- Fix lint errors
  ([`daa4af0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/daa4af06ec5f2c3ab09d19f1704c2466b4166393))

- Fix lint errors
  ([`7593e04`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7593e045396508c02c642072f6501ad2e1694626))

- Fix lint errors
  ([`31fb480`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/31fb480a345576ee32074640a47b04514f2bee15))

- Fix linter
  ([`4fd30be`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4fd30be26aa9ea095c4fda3846d2fb572769719e))

- Fix linter and a few other things
  ([`ba16a16`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ba16a16fdf715d77839b22794f0f2fccfc814d4a))

- Fix linter errors
  ([`40cf566`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/40cf56624f4c59c704871a4296afed8293ed6ec1))

- Fix linter errors in trotter utils
  ([`5103282`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/51032822738c94d9ec70216649e9413f706f7900))

- Fix linting
  ([`e96dc2a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e96dc2ad0403256b36d5a9f2b5f1852baab60f29))

- Fix linting
  ([`8c4f9d0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8c4f9d01b293396c5f46bd867307a914ea32d339))

- Fix linting
  ([`5c2e405`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c2e4051118b150eacd15f16944e3bef91410564))

- Fix linting errors
  ([`b0ba85c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b0ba85cd9b047c15e3e08ba135eb3a957f647175))

- Fix math
  ([`6acb433`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6acb433950080a378661b44dd4a50c937930241b))

- Fix missing qbk.
  ([`07e2125`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/07e2125d689186e418f67de3bcfd4c5336e1d9c6))

- Fix more arxiv links
  ([`c3936f0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c3936f0f4c688e22857786cae2deb76e706fa1e9))

- Fix more links and fix run_notebooks
  ([`9b68158`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9b681586cf5f98cef06fe15f2fee66efe223f16b))

- Fix more linter errors
  ([`39def4a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/39def4a6b03bec6776ae5bd65420c4c5e314a6af))

- Fix more linter issues
  ([`107128f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/107128f4b114850ce79d0ebb012717f0d58d18d9))

- Fix qbk.qbk
  ([`b6bd0c3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b6bd0c3ef53d341d3881030b906517c13b0d155f))

- Fix small issues in two notebooks
  ([`cf249d6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/cf249d617cb8230770834fa669b17f14716e0628))

- Fix some math
  ([`acd5e06`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/acd5e06fcd9318be1a4b2751b9fc09ae0024acac))

- Fix utils docstrings
  ([`c2422eb`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2422eb8743f5f5dc4e7ad8202444694d2dbd1d9))

- Get rid of comment lines
  ([`447d545`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/447d54535502689e44dbb577b2808fc908a2c85a))

- Get rid of overwrite_reg everywhere
  ([`1d675ce`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1d675ce632905863798e1ef37afd8fed15097dc2))

- Isort set_version
  ([`0c032ca`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0c032ca1eec40c6c752eb2e072249609d325b392))

- Isort set_version.py
  ([`573019a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/573019a61979ba0ed8758b391b8e848737749ce4))

- Lint
  ([`e54e651`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e54e6519785d90ea43bb83aef97bafd0900da89b))

- Lint qubricks zoo
  ([`c24224e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c24224e9a28ed3574ed2061bbc152150626c4b01))

- Minor fixes
  ([`a2d6927`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a2d6927c209c5d73dce711c43177b13d4b3472df))

- Minor fixes
  ([`5f2ed04`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f2ed04ad3f8fd4cc64b7bfb80b97b56979aa037))

- Minor fixes
  ([`1cee37c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1cee37ccd3a6ecef342262daf3c9fda7bc6bd0e6))

- Minor fixes
  ([`d390787`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d390787e948d52df7f0a77e1a8557dc3b6ea93ce))

- Remove debug line
  ([`aca724d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aca724d317e77f2fdefd557e4882820c5f3ae548))

- Remove debug lines
  ([`2a96274`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2a9627461a463f42e832b5142908775340d72dfc))

- Remove gitlab rendering comment
  ([`6300020`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/63000208dfc911d449c81e57bd08c31397376a6f))

- Remove link from vector arith
  ([`db3ea19`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/db3ea19960db27f16bf5264ec4194f391c562ee8))

- Remove phase grad as arg
  ([`45a2c16`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/45a2c1629509223c6eecc50897add474f4b7f25d))

- Remove small redundancies
  ([`9215b20`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9215b2053fb32382962dce42a6a450666de0f34b))

- Remove unused import
  ([`c2d0d07`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c2d0d07ee5d337811b22a1075217e7d6050d88c2))

- Revert gitignore
  ([`7febdf3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7febdf37e81c0dfcedefd62820c301e5c46c48d9))

- Run isort on init
  ([`eba9e0c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/eba9e0c9d62908c4ec367f76e7f6d4a75551d105))

- Run linter
  ([`463cc68`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/463cc6888c20153280468d38a0490e7c19adec81))

- Update bartiq version
  ([`53977b9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/53977b948aace406f31bfba466191b14064ffe57))

- Update control structure
  ([`80ea966`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/80ea966ba64494fddd886e0e50be8b0344ea1980))

- Update dependencies
  ([`8e01424`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8e014249d7996617b106d96c0db9dacb2c628b88))

- Update example notebook to render nicely
  ([`2711a0c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2711a0cb7118ae41322db0c84aa7d88c9c07e58a))

- Update lockfile
  ([`5c75095`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5c7509511b65f9ceea0ae14700371d78447dcd44))

- Update math in notebook to get more of it rendering correctly on gitlab
  ([`5e2fa47`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5e2fa478b0dbb8788d32a4b91bfa16a5166d2509))

- Update vector arithmetic number of qubits
  ([`7319001`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7319001a19ddd37df5ad1681cda5c0cf9667be91))

- Use qbk.
  ([`f875c4b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f875c4b457d04483e54fb6ecec4318d4c2725239))

### Code Style

- Apply @sgreenaway 's suggestions
  ([`85daf54`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/85daf54f66e09964b1c25bebfe06f367c0aaf4be))

- Apply @ssim 's suggestions
  ([`9a03df8`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9a03df850da524d1138b1134fc3e2a0007528f9d))

- Apply @ssim 's suggestions
  ([`4daac6f`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/4daac6f0258fd51c701e8222f5e56409d072cc2b))

- Fix style issues
  ([`e3cb638`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e3cb638f5a4e0c70857f446f0d3f615a9b08adc5))

- Isort
  ([`fe743b6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fe743b6ebf30f0d46708d6157e0246b6d62240a7))

- Lint
  ([`68f5a50`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/68f5a50fd00e95a612c45aabd1a5666c1838245e))

- Lint .gitignore
  ([`0142f45`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0142f45fc15e99eea5d95f993628278434430ac3))

- Linted .gitlab-ci.yml
  ([`97242c3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/97242c3dc998b008e141f583074d1ecb9b909afa))

- Ruff format
  ([`aa17531`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/aa1753162327ea659be39ec81a27449c6a16131e))

### Continuous Integration

- Added commitlint and pre-commit config for conventional commits
  ([`19a2b7a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/19a2b7a4598118a3c70711dda2dcf15599aa72ca))

- Added slack notification on failed scheduled pipelines
  ([`ee970b2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ee970b2f49a4198708f3a0430ab0235d17f877ab))

- Adopt common CI configs
  ([`01bf777`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/01bf7773957d6df2fbab7021d69eecc482a1d9d0))

- Change order of stages to put lint before install
  ([`438c686`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/438c6861cee8b98920c05052294bc472fca56697))

- Fix coverage regex
  ([`e6ac4c5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e6ac4c5d2db800a13980252038b7b94526832252))

- Remove unneeded ls calls
  ([`23ef063`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/23ef063be2b63109121869e759b033fe6a7fbeea))

- Updated CI test matrices to include 3.13
  ([`276b2a1`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/276b2a149fd1a20e6957bbfaf07775a2f510ea37))

- **downstream**: Fix URL in tag-based trigger for QRE-CV
  ([`fbd9799`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fbd979917a4901a6b5981ba82e49cb71925d7b1c))

### Documentation

- Add most of the missing docstrings
  ([`49dc159`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/49dc1594ebca40ff0a2254f14969e3732b97baca))

- Add release section to README
  ([`7b7b0d7`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/7b7b0d73e27361ae88fa1d40406dc275479030c4))

- BitonicSort with VectorRegister
  ([`581c724`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/581c7241b69cc72a8b49df6501e9098ca461eb55))

- Fix bad pages URL
  ([`549f9a6`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/549f9a6194531748f8364d77e6368ef714b8f125))

- Fixed a link
  ([`6d1c403`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/6d1c403f117deb050438b3f83a4f997ec0f1aff3))

- Format bitonic docs
  ([`5132e82`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5132e82787b8ec508edd793d555df93935e3f884))

- Renamed examples to tutorials
  ([`9796277`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/97962772db29acd15013399e3ad6b3a18449d7eb))

- Restructured docs and updated some pages incl. notebooks
  ([`fbdf251`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fbdf2511fa2cb1d0c97416b8579d97f562b2bca7))

- Updated CR headers
  ([`e59db0e`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e59db0e097752b66465edf8d2d6cfb265e6153e3))

- Updated for tone
  ([`ce854e5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ce854e57d4acee28ae1cd7086df48a5acbca199c))

- Updated links in a notebook
  ([`5f72e34`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/5f72e34a385dd3c8c3680243b99116f510ab4be2))

- Updated poetry lock
  ([`8ad29d5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8ad29d5fd3d785985fc5c5db6f55df8a7921c1ff))

- Updated symlinks
  ([`a9e91a2`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a9e91a214b5c65cc603035926b93c7e0d5f48fae))

- **readme**: Added conv commit section to readme
  ([`2a43cfd`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2a43cfdd5ffa61ac32c6c9856a98999f2687399e))

- **readme**: Added Developer Guide section
  ([`41348cf`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/41348cff39a9652d3a5596afd8db4176366ae8a0))

- **readme**: Fixed bad URL
  ([`07fef89`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/07fef89b54ae520c5d2c30b5d3532e7b5d5a0297))

### Features

- (lint) COmpression gadget
  ([`1afc81d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/1afc81d0f57fafa3d7a35b4d9a565980537d97c5))

- (lint) Compression gadget
  ([`803eae9`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/803eae9a5774bb974025ebbad57be3edb507549e))

- (lint) COmpression gadget
  ([`2ca4b21`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2ca4b21fda37ad8f8e70ab778f3c2dad4fb0be2c))

- (lint) Compression gadget
  ([`e8d6c6a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/e8d6c6ac28658c613596ba280fb8403ed4d921e3))

- Add auto-MR versioning
  ([`2015e00`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/2015e0031b2f05fe6491d2ab0cc2d646de15a3ce))

- Add dataclasses for rotation qubricks
  ([`16fe25a`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/16fe25aa9b4118734454910e51c40f6564991a15))

- Add public API for qubricks Zoo
  ([`9feecfa`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9feecfa6be26995f9dfaa051d7c7c552db892963))

- Add search to offline mkdocs thru offline plugin
  ([`fb738db`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/fb738db41b34239b6ecea15bc25ff126ed138668))

- Add unary qrom
  ([`9ea7bd3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/9ea7bd3c34bf871b1ffe153de048ab22584ef5ef))

- Compression Gadget
  ([`d6070da`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/d6070da3633fde77b7b5b0e7833d3cc3364ea4b3))

- Compression gadget
  ([`c9a129d`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/c9a129d6c214ce015cdf4439fde30ff6ff4158ed))

- Compression Gadget
  ([`af1d143`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/af1d1437e192d742171f94a8b6bf841c82729f45))

- Compression gadget
  ([`0c11de3`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/0c11de3ff5903ef6a52e70d4ae38f7691fea83cf))

- Compression Gadget
  ([`bf9e344`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/bf9e3448e3f75fb319daed0c363e6e089d6b51ba))

- Compression gadget for powers
  ([`ed98114`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/ed981144bca488e7fd4f2e41b01dc315e952e0bd))

- Compression gadget for powers
  ([`abccd9b`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/abccd9bf50e39dabe6a26d34bf4a604caf45a0f7))

- Compression gadget multiply list
  ([`b9d5155`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b9d515588c09cb71cb0d3a1c329385d28d26c2f2))

- Compression gadget multiply list
  ([`64b3508`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/64b35088ff66229d5c45af00dfc0574761da64e3))

- Rename ArbitraryStatePrep -> GroverRudolphStatePrep
  ([`a23ea40`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a23ea401be014af02c068be4c7201d541795b3da))

- Tidy up interfaces and remove dependency on QPU ops
  ([`889a8d5`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/889a8d5a6eb818ceb5175ffdec88299cc7eea8dc))

- Typo fix
  ([`b26f210`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b26f210a1dca474df15bd1c8dc00b871e9d28a61))

- Update mkdocs.yml to properly display notebook
  ([`a8c344c`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/a8c344c49ebd237b8b708f8c2623d731f86dbe75))

- Update QROM tutorial to also analyze QREs
  ([`8acd346`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/8acd346752d9cc11acccf7e01715a6746f48c836))

- Update readme to include public/private API guideline
  ([`3959156`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/39591564e6b847b4088452a8c3f7319f62e9eba9))

- Updated antisymmetrizer to use vectorregisters
  ([`7411440`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/74114404372e619310baaca6e7ad2430e8adb85d))

- **muxes**: Added MUX qubricks from project scylla repository
  ([`f052d56`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/f052d565c29f2b2913161bf972c79dd42ab89330))

### Refactoring

- Minor update to reduce deprecation warnings
  ([`b398dd0`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/b398dd04d71715a800f5be09372db549d560e595))

- Remove usage of get_num_qubits
  ([`dea0fed`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/dea0fed4b2393d9c043bb7f3951b35f9cf6b70ac))

### Testing

- Add tests from scylla
  ([`44dbb42`](https://gitlab.psiquantum.com/applications/core/workbench_algorithms/-/commit/44dbb429cc1da2d58ba5cde7ca2ec3902093b9aa))


## v1.0.1 (2023-07-11)


## v0.1.1 (2023-02-22)

- Initial Release
