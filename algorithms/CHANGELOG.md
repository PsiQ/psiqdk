# CHANGELOG

<!-- version list -->

## v1.13.9 (2026-04-27)

### Bug Fixes

- Transient error attempt 3

- Update logic for paulisum weights to get better agreement with numerics

- Update random pauli sum and use symbolic pauli sum in qpe test


## v1.13.8 (2026-04-24)

### Bug Fixes

- **ci**: Mark deployment and key reporting jobs as non-interruptible

- **ci**: Mark deployment and key reporting jobs as non-interruptible

### Continuous Integration

- Allow docs:check-links to fail

- Remove poetry.lock and add to .gitignore

### Documentation

- Add agent guidance

- Add agent guidance

- Replace poetry with uv in AGENTS.md


## v1.13.7 (2026-04-23)

### Bug Fixes

- Compare deprecation deadlines with numeric version tuples

- Compare deprecation deadlines with PEP 440 versions

### Chores

- Fix bug in warning handling

- Remove su2 qubrick and tests

### Code Style

- Fix lint error

### Continuous Integration

- Align notebook stderr warnings with PYTHONWARNINGS filters

- Simplify example warning enforcement to notebooks only

- Treat example warnings as failures

- Treat example warnings as failures

### Documentation

- Add Documentation Map

- Explain the role of 'experimental'

### Refactoring

- Parse dotted versions with a single regex

- Parse leading version segment with int() prefix

- Parse version segments with regex


## v1.13.6 (2026-04-20)

### Bug Fixes

- Resolve "Update AV in tests"

- Use FutureWarning for deprecations

- **test_select_symbolics.py**: Increase the bounds on the av for tests.

### Chores

- Bump ipykernel version

- Bump jupyter version in examples group

- Emit FutureWarning for deprecations

- Migrate WBA to uv

- Migrate WBA to uv

- Remove dependency on ipykernel and contrain scipy during tests for Python 3.13

- Remove direct dependency on ipykernel

- Restrict scipy version to >=1.15.0 for tests group

- Temporarily lower jupyter version to trigger failure

- Update tolerance for qpe qre test

- Update tolerance for qpe qre test

### Continuous Integration

- Fix semantic-release GitLab domain and merge commit parsing

- Fix semantic-release GitLab domain and merge commit parsing

- Increase number of pytest workers to 8

- Increase number of pytest workers to 8

- Streamline uv sync and uv commands

- Streamline uv sync and uv commands

### Documentation

- Update Data Loaders (QROM) tutorial and API docs of mentioned Qubricks

- Update Data Loaders (QROM) tutorial and API docs of mentioned Qubricks

- Update SwapUp + InjectOp tutorial

- Update SwapUp + InjectOp tutorial


## v1.13.5 (2026-04-13)

### Bug Fixes

- Set random seed in qpe qre test for deterministic behavior

### Chores

- Fix regex syntax

- Isort

- Rename google selects

- Switch over selects to new class name

- Update documentation to remove deprecated functions

### Continuous Integration

- Added project-specific webhook for release notification

- Updated dev-ops/common include reference from 0.2.0 to 0.2.1

### Documentation

- Add tutorials to mkdocs nav


## v1.13.4 (2026-03-24)

### Bug Fixes

- Cheby warning in test

### Chores

- Deprecate CODEOWNERS

- Remove source code from API docs

### Code Style

- Fix isort

- Fix style issue

### Continuous Integration

- Deprecate old webhook URL variable

- Fix error in lint job rules

- Remove .gitignore file sorting

- Updated dev-ops/common include reference from 0.1.6 to 0.2.0

### Documentation

- Add check for broken external links

- Exclude CondCleanBuild from qubricks

- Fix release notification channel name

- Remove filterwarnings('ignore') from tutorial notebooks

- Update Slack webhook variable reference

### Testing

- Add discrepancy for AV in QPE

- Minor changes in alias sampling tests

- Test_alias_sampling_symbolics.py

- Update tests for PhaseGradientAdder


## v1.13.3 (2026-03-13)

### Bug Fixes

- Fix discrepancies for several qubricks

### Chores

- Fix known warnings in examples


## v1.13.2 (2026-03-10)

### Bug Fixes

- Fix bug with numpy arrays as inputs to DataLookupClean

### Chores

- Bump WB dependency to 4.33.7

- Update docstring

### Code Style

- Fix isort issue


## v1.13.1 (2026-03-03)

### Bug Fixes

- Release trigger commit

### Chores

- Remove psi-liqtr dependency


## v1.13.0 (2026-02-27)

### Chores

- Remove unneeded commitlint config and pre-commit job

- Remove unneeded commitlint config and pre-commit job

### Continuous Integration

- Bumped dev-ops/common dependency to 0.1.1

- Delete set_version.py and merge main

- Implementing central release jobs

- More fixing of central jobs

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0

### Documentation

- Replaced commitlint README section with MR title linting docs

- Replaced commitlint README section with MR title linting docs

- Updated README.md with release flow and mr-title-linting

### Features

- Removed unused lines of code

- Updated syntax in two qubricks to use reg.ppr vs. qc.ppr


## v1.12.0 (2026-02-26)

### Bug Fixes

- Changing size of system to stay within memory limits of workers

- Fix a few deprecation warnings

- Fix QREs for controlled selects

- Fix trotterization to use Y weights

- Fixes for AV in symbolic select

- Only passing in valid tuples of basis state and size of system

- Reducing the size of the system to stay within memory bounds

- Remove test warning by adding pytest-repeat to pyproject

- Remove warning from block encoding duplicated be_ancillae_reg arg

- Remove warnings by skipping incompatible pairs of register sizes and basis states

- Remove warnings of duplicate flag arg in compute

### Chores

- Change over the angle truncation in LKS to non-deprecated version

- Move psi-liqtr to non-optional dependency

- Sort imports

- **review**: Apply 2 suggestion(s) to 1 file(s)

- **review**: Minor changes

### Code Style

- Fix isort issue

- Fix style issue

- Fixes formatting

### Continuous Integration

- Add duration logging to test jobs

- Pull SMS out as specific codeowner

### Documentation

- Minor docstring changes

### Features

- Pytest warn included

- Warnings bashed

### Testing

- Add cache to worst_case_symbolic_qrom_uncompute_cost

- Fix bound for SelectOneAnc in tests

- Fix failing test

- Fix import sorting

- Fix/ignore few UserWarnings in tests

- Ignore UnstableWarning for Parameter

- Improve performance of symbolic tests

- Refactor tests for symbolic select

- Remove more warnings

- Reorganize how symbolic QREs are cached in QROM tests

- Set seed in test_random_mps_prep


## v1.11.2 (2026-02-09)

### Bug Fixes

- Adding poetry run

### Continuous Integration

- Fix broken docs build in docs jobs


## v1.11.1 (2026-02-09)

### Bug Fixes

- Angle type HWP + PhasingCircuit

- Ctrl rz (WIP)

- Fix AV estimates for TrotterQuery

- Fix estimate for BinaryToUnaryUncomputation

- Reorienting on rotation_encoding

### Chores

- Address a few more deprecation warnings

- Bump version to 1.11.0

- Bump WB version

- Delete unused makefile

- Ensuring test checks for sparse loading

- Removing sorted call as this is fixed in now handled in WB.

- Update interfaces to remove warnings on import

- Update lockfile

- Updated README "master" references to "main"

- **review**: Apply 2 suggestion(s) to 1 file(s)

### Code Style

- Fix lint issues

- Fix typo

- Uniformize angle property and add tests for Units.deg and Units.rad

### Continuous Integration

- Update master reference to main in .gitlab-ci.yml

### Documentation

- Improve docstring

### Features

- Added smarted ctrl incorporation and all test passing for all Selects updating test to call
  interface.

- Adding explicit uncompute test and bumping WB version

- Integrated the select and old tests passing but seeing weird warning about release of qubits and
  need to test ctrl case

- Pulling out ancilla assignment from test files and pytest parametrising select instance, fixing
  typos, removing unnecessary init

- Wrap selects in sorted to allow tests to run in parallel on workers

### Testing

- (WIP) ctrl rz

- (WIP) with @ssim

- Apply reviewers comments

- Ctrl rz (WIP)


## v1.11.0 (2026-01-28)

### Bug Fixes

- Add discrepancy for USP

- Bump version in pyproject.toml so locked version can access debug qpu method

- Fix usp discrepancy description

- Fix USP symbolic tests

- Update alias sampling test to use new debug tool

### Chores

- Address a few deprecation warnings

- Bump version to 1.10.0

- Delete comment with a typo

- Update deprecated imports from psiqworkbench.bit_utils and psiqworkbench.numpy_utils

### Code Style

- Fix isort issue

### Continuous Integration

- Added pytest report generation for latest test jobs

- Make twine considerably and perhaps unbearably but certainly justifiably verbose


## v1.10.0 (2026-01-14)

### Bug Fixes

- Change back to None for HWP qubrick

- Change Qubits | None = None to Qubits | int = 0

- Fix interface registration for phase gradient adder

- Handling of unmerged uncompute

- Just remove the old Givens rotations args

- Now self consistent, issue with fidelity with original qubrick (see FidelityCheck notebook)

- Update alias sampling interface to match protocol

- Update Givens' interfaces to be accurate to implementations

- Working qubrick

- **simplify**: Remove outdated `subroutines/alu.py`, all tests still passing

- **test**: Remove outdated ALU tests

### Chores

- Add naive test to test larger sites for phase qrom merging

- Bump version to 1.9.4

- Clarify notebook with lesley

- Delete example scripts

- Expanded docstring

- First pass on notebook

- Fix comments and delete dead code

- Fix naming convention for u_state

- For lesley

- Isort lint fail

- Notebook clarifications

- One missed isort fix

- Replace deprecated angle truncation function

- Tidy up code

- Update notebook to work with updated code

- Upgrade scipy to a required dependency

- **review**: Apply 3 suggestion(s) to 2 file(s)

### Code Style

- Change variable format to snake case

- Clean up code

- Clearer s_distinguishing_bit function

- Update copyright

- Update copyrights

- Update dataclass name

### Continuous Integration

- Added release stage

- Hard code test worker pool size to 8

- Update number of pytest workers for profiling

- Update number of pytest workers to 4 for profiling

- Updated dev-ops/common include reference from 0.0.8 to 0.0.9

### Documentation

- Added warnings

### Features

- Add clebsch gordan qubrick and test

- Add composite reg for su2 mps

- Add example notebook

- Add test for dagger=True

- Added complex vs real coefficient handling and test file

- Added phase merging, issues with amplitude merging (see notebook)

- Added tidied notebook from sync. added merging functionality from this notebook to qubrick. passes
  initial test.

- Cleaning and responding to review comments

- Responding to review comments

### Refactoring

- Make uncompute of s_distinguishing_bit a function and clarify variable names/docstrings


## v1.9.4 (2025-12-02)

### Bug Fixes

- Update n catalysts

### Build System

- Update WB dependency to v4.30.5

### Chores

- Bump version to 1.9.3

### Continuous Integration

- Allow docs and install jobs to start immediately

### Documentation

- Removed installation instructs from construct for external users


## v1.9.3 (2025-11-19)

### Bug Fixes

- Cond_xor will only actually work if ctrl is first qubit in register, plus reflect handles all
  special cases

- Import

- Number of Ys

### Chores

- Add special angles to test

- Bump version to 1.9.2

### Continuous Integration

- Run examples in serial

### Documentation

- Add _compute to API docs

- Clean up warnings in _compute API docs

- Fix docstrings

- Fix documentation

- Minor cleanup

### Features

- Add feature to __all__

- Bug results from unnecessary assignment of PGA state and an issue with open control and phase fix
  up

- Fix bug with open ctrl

- Removed spurious qubit from RZ Adder

### Refactoring

- Change holevo variance calculation method

- Import order for lint

- Move holevo variance calculations to quantum_phase_estimation_utils

- Reduce rotations in _compute_partial_optimal_state

### Testing

- Add test calculating Holevo variance of QPE


## v1.9.2 (2025-11-06)

### Bug Fixes

- Raise Error type

- Slice PauliSum

- Updated symbolic estimate for phase gradient adder

### Chores

- Bump version to 1.9.1

- Updated docstring with a note

### Features

- Got rid of extra qubit allocation for two adder Givens


## v1.9.1 (2025-11-03)

### Bug Fixes

- Add blackbox costs; need to validate

- Add workaround for failing MPS notebook

- Fix ruff errors

- Lint

- Notebook tests

- Release anc

- **cleanup**: Remove unused qc vars, and radians setting

- **MR**: Fix two MR items

- **PauliMask**: Fix off-by-one error in PauliMask get_pauli() for #371

- **poetry**: Bump WB version and lock

- **reflect**: More reflections added

- **reflect**: The first few reflect fixes for #368

### Chores

- Account for controlled case

- Add other costs

- Add tests for batched HWP

- Address Michal's comments

- Address Will's comments

- Apply to batched HWP

- Bump version to 1.9.0

- Lint

- More comments

- Remove testing notebook

- Rerun notebook

- Ruff

- Use lookup table for C_CCZ

- Write test for other resources

### Continuous Integration

- Run test coverage job in parallel

- Updated dev-ops/common include reference from 0.0.7 to 0.0.8

### Features

- Add zx costs for HWP

### Refactoring

- Replace old filter names with filter presets


## v1.9.0 (2025-10-16)

### Bug Fixes

- Ej's speedup

- Fixed RZAdder case

- Remove process_output

- Update poetry

- Update to work with changes in WB for ast-2308

- **cleanup**: Cleanup per MR

- **lint**: Fix isort error

- **test**: Adjust a test to accept equivalent but non-identical tables

- **wb_version**: Update WB required to 4.30.1

### Chores

- Add docstring to constructor

- Address reviewer comment

- Bump version to 1.8.3

- Isort

- Isort

- Isort

- Linting

- Linting fix

- Update test to have less repetition

### Code Style

- Change _Ul function name for consistency with other funcs

- Linting

- Linting fix

### Continuous Integration

- Parallelise jobs using pytest-xdist

### Features

- Add ctrl to u_l function

- Added symbolic test + equivalence test between phase gradient adder and qc.rz

- Added Toffs to cost dict, updated helper to calculate all resources and return QubrickCosts

- Addressing reviewer comments

- Changed ordering of some lines in a helper method, added a link to a Jira ticket

- Temp fix for RZ and two adder version of Givens

### Performance Improvements

- **alias**: WIP first pass (still needs cleanup)

- **alias_sampling**: Speedup in alias samplinggenerate_alias_table(), and also
  discretized_prob_distribution()

### Refactoring

- Change phase gate to s_inv

- Move hadamard and s gates to _compute_Ul function

- Rename compute_Ul, remove unnecessary line in test, add typing, and check for n_qubit, sign inputs

### Testing

- Add test for ctrl

- Added test for uncompute and real amps case, deleted example script, linting.

- Replace QPU.set_random with explicit state pushes

- Set seed in test with random instances

- Updated set_random_qpu_state to use QPU.random_seed


## v1.8.3 (2025-09-23)

### Bug Fixes

- Adjust protocols and implemented qubricks to match the specified protocls

### Chores

- Bump version to 1.8.2

- Linting fix

### Documentation

- Updated docs sidebar color

- Updated release instructions in README.md


## v1.8.2 (2025-09-15)

### Bug Fixes

- **utils**: Added try clause for scipy import in dyson_utils

### Chores

- Bump version to 1.8.1


## v1.8.1 (2025-09-11)

### Bug Fixes

- Add better instructions when user is missing scipy

- Add docstrings

- Adding more comprehensive test range for d > n

- Address Jess' comments

- Address sms' comments

- Apply 1 suggestion(s) to 1 file(s)

- Change junk version map index to target class name

- Clarify use_ctrl in tests

- Copy amplitudes in data

- Enforcing kwarg usage after wb updates

- Fix set_version to adjust to new pyproject.toml syntax

- Format

- Hard code lambda = 1 for now, need to fix this in the future

- Isort

- Lint

- Make output reg mandatory

- Ran isort on rotations.py file

- Remove release index reg

- Set_version.py sets version in pyproject.toml

- Switch ordering of c-state prep and c-write column

- Typo in example notebook

- Unique positions (sample without replacement)

- Wrap up some output updates

- Write to_arb_state_prep_data

- **qubits**: Fix release of hamming weight phasing qubits per #351

### Build System

- Updated workbench version to latest

### Chores

- Add issue number for amplitudes copying in dataclass

- Add typing

- Added reviewer suggestion

- Address reviewer comments

- AliasSampling Qubrick included back into the StatePreparation protocol

- Apply isort import sorting

- Changed crtl argument default value from None to int=0 for GivensRotation interface.

- Changed crtl argument default value from None to int=0.

- Changed qc gates to qubit gates

- Changed the default ctrl to accept Qubits and int instead of None in compliance with the Qubricks.
  fixed Assymmetrization import issue.

- Changed the default ctrl to accept Qubits and int instead of None in compliance with the Qubricks.
  fixed Assymmetrization import issue.

- Cleaned up LCU interface import and other dependencies.

- Corrected and add CompositeRegister

- Fix lint

- Interface temporarily removed from AliasSampling qubrick to reconcile arguments of
  StatePreparation interface and AliasSampling qubrick.

- Lint

- Minor spelling error in tutorial

- Modified compute to _compute in interface.

- Modified pyproject.toml to use test against workbench MR branch 1868-fix-interface-checking

- Modified pyproject.toml to use test branch

- Remove unused part of tuple

- Removed `None` return type from StatePreparation interface.

- Removed LCU from Interface.

- Removed return type for StatePreparation and AmplitudePreparation protocol interfaces.

- Renamed angles in GivensRotation protocol interface to rot_reg.

- Renamed argument psi to qbits for StatePreparation and AmplitudePreparation.

- Renamed psi argument in ProgrammableRotArray qubrick to qbits.

- Renamed psi to qbits for ArbitraryStatePrep Qubrick.

- Resolved Andrews review comments.

- Returned the naming of the first argument to 'psi' for ProgrammableRotArray. Renamed the 'qbits'
  argument to 'psi'.

- Reverted ArbitraryStatePrep back to the main branch argument implementation.

- Reverted GivensRotation Qubricks to the main implementation

- Reverted GivensRotationTwoAdders qubrick to original main branch implementation

- Reverted StatePreparation protocol back to the main branch argument implementation.

- Separate out mapping

- Simplify sparse state prep

- Sorted imports

- Temporarily removed AliasSampling. Argument different from other qubricks using the same
  interface.

- Updadated argument types for Multiplexor, Permuation and BasisTransform interfaces, and
  BitonicPermutation and PhasingCircuit Qubricks.

- Update the interface and qubrick arguments for Antisymmetrization and Antisymmetrizer
  respectively. Also, updated the spelling for Antisymmetrization in design doc.

- Updated AmplitudePreparation and PhasePreparation interfaces to use the same arguments since they
  are both used by one qubrick (ProgrammableRotArray).

- Updated argument types for Multiplexor protocol interface and BinaryTreeMultiplexor qubrick.

- Updated argument types for OneAncMultiplexor qubrick.

- Updated BinaryToUnaryUncomputation qubrick argurment types.

- Updated ComputeHammingWeightBinaryRecursion qubrick arguments types.

- Updated ComputeHammingWeightGroupOfThrees qubrick arguments types.

- Updated DysonSeriesSelect protocol interface crt argument type and the DysonSeriesSelectUnary and
  DysonSeriesSelectBinary qubrick _compute method arguments.

- Updated HammingWeight interface arguments.

- Updated HammingWeightPhasing qubrick ctrl argument type to default to 0.

- Updated InjectOp qubrick and protocol interface arguments.

- Updated MultiplexedSingleQubitRotationViaQROM qubrick ctrl argument type to default to 0.

- Updated poetry.lock

- Updated StatePreparation protocol interface arguments and return types.

- Updated SwapUp argument types.

- Updated the argument type for FlagCollisionsUnary qubrick and FlagCollisions protocol interface.

- Updated the argument types for Contiguizer qubrick and FlaggedQPEWindowFunction interface
  protocol.

- Updated the argument types for FlagCollisionsBinary qubrick.

- Updated the argument types for MajoranaFermionOperator qubrick and interface protocol.

- Updated the argument types for OrthogonalDotProduct qubrick.

- Updated the argument types for RectWindow, CosineWindow, and WindowStatePrep qubricks and
  QPEWindowFunction interface protocol.

- Updated the argument types for SawtoothMultiplexor qubrick.

- Updated the argument types for SelectOneAnc,, GoogleSelectUnoptimized and GoogleSelectOptimized
  qubricks.

- Updated the argument types for SineWindowPhaseCatalysis, and SelectNaive qubricks and
  FlaggedQPEWindowFunction interface protocol.

- Updated the argument types for TrotterQuery qubrick and Trotterization interface protocol.

- Updated the argument types for VectorAddition qubricks and VectorAdder interface protocol.

- Updated the argument types for ZeroAncMultiplexor qubrick.

- Updated the argument types of PrepareWState protocol and PrepareWState and PrepareWStatePowerTwo
  qubricks

- Updated the arguments for HammigWeight interface and ComputeHammingWeightNaive qubrick to default
  to int=0

- Updated the arguments for HammigWeight interface and ComputeHammingWeightNaive qubrick to default
  to int=0

- Updated the arguments for SwapUp.

- Updated the mux_data argument of RotationViaPhaseGradientAddition to rot_data to be consistent
  with others and the ctrl argument of SuperpositionRotations interface and the Qubrick its
  implements to default to 0.

### Continuous Integration

- Updated dev-ops/common include reference from 0.0.6 to 0.0.7

- Updated examples testing in CI to be compatible with PsiQDK

### Documentation

- Move docs images from lutim.psiquantum.lan to the repo

- Temporarily deprecate broken example notebook

### Features

- Add additional explanation for QROM lambda > 1 problem

- Add example notebook

- Add Jess' state prep, controlled and refactored

- Add sparse state prep with junk

- Added BinaryToUnaryUncomputation to the BinaryToUnaryUncomputation Protocol Interface

- Added BinaryTreeMultiplexor Protocol interface

- Added BitonicPermutation to Permutation Protocol Interface

- Added BitonicSort to the Sort Protocol Interface

- Added ComputeHammingWeightNaive, ComputeHammingWeightGroupofThree, and
  ComputeHammingWeightBinaryRecursion to the HammingWeight Protocol Interface.

- Added ComputeHammingWeightNaive, ComputeHammingWeightGroupofThree,
  ComputeHammingWeightBinaryRecursion

- Added Contiguizer to the EncodingChange Protocol Interface.

- Added CosineWindow to the QPEWindowFunction Protocol Interface

- Added ctrl arg to BRNO

- Added DysonSeriesSelectBinary and DysonSeriesSelectUnary to the DysonSeriesSelect Protocol
  Interface

- Added FlagCollisionsBinary and FlagCollisionsUnary to the FlagCollisions Protocol Interface

- Added GoogleSelectUnoptimized to the Select Protocol Interface. Deleted data types in docstrings.

- Added HammingWeightPhasing and InjectOp to the Protocol Interface.

- Added LCU to the Protocol Interface.

- Added MajoranaFermionOperator to the Protocol Interface.

- Added modified GivensRotationFusedAdder with ctrl to the GivensRotation Protocol Interface

- Added modified GivensRotationTwoAdders with ctrl argument to the GivensRotation Protocol Interface

- Added OneAncMultiplexor to the Multiplexor Protocol Interface. Ran lint formatting using ruff.

- Added OrthogonalDotProduct to the DotProduct Protocol Interface.

- Added PhasingCircuit to the BasisTransform Protocol Interface.

- Added PrepareWState and PrepareWStatePowerTwo to the PrepareWState Protocol Interface.

- Added Protocol to Antisymmetrization

- Added SawtoothMultiplexor to the Multiplexor Protocol Interface.

- Added SelectNaive, SelectOneAnc and GoogleSelectOptimized to the Select Protocol Interface.

- Added SineWindowPhaseCatalysis and RectWindow to the FlaggedQPEWindowFunction Protocol Interface
  and QPEWindowFunction respectively.

- Added SwapUp to the SwapUp Protocol Interface.

- Added TrotterQuery and ZeroAncMultiplexor to the Trotterization and Multiplexor Protocol
  Interfaces respectively.

- Added VectorAddition to the VectorAdder Protocol Interface.

- Added WindowStatePrep to the QPEWindowFunction Protocol Interface.

- Adding example for sparse state prep with junk

- Changed the design doc for MultiplexedRotations and updated the interface implementation

- Second update to docstrings for interfaces in response to lint error.

- Updated docstrings for interfaces in response to lint error.

- Wip tests for sparse state prep


## v1.7.0 (2025-08-12)

### Bug Fixes

- Add tests for experimental symbolic alias sampling

- Add warning and test for 0 bits of precision

- Batched_hemming_weight should allow batches equal to register size.

- Break valid+trim into two functions

- Correct logic flow in alias sampling data handler

- Fixed control structure of ComputeHammingWeightBinaryRecursion

- Qubit_highwater key is not accessible

- Split PrepData into Symbolic and Numeric

- Typing error

- Update docstring

### Chores

- Added unit test checking the number of Toffolis in ComputeHammingWeightGroupOfThrees

- Change .compute() to _computer() in interfaces

- Fix blank space

- Fix isort

- Fix linting

- Fix linting issues

- Improved doc strings, removed unneeded imports, and improved controlled Hamming weight test.

- Merge in main and update pyproject.toml

- Ran isort on hamming_weight.py to fix lint errors

- Remove Q typevar in favor of BaseQubits

- Revert rotations.py file

- Temporary change poetry

- Updating poetry to match needed workbench version

### Continuous Integration

- Only run qdk downstream when pushing to default branch

- Put coverage check in separate job

- Remove needs clauses to avoid early execution of later jobs

### Features

- Add controls for adders

- Get symbolic alias sampling working

- Update to allow for 2 adder Givens

### Testing

- Fixed controlled Hamming weight test. Added control functionality to Hamming weight qubrick.


## v1.6.0 (2025-07-24)

### Bug Fixes

- Add docstrings

- Add init to mps_prep

- Add LKS complex state prep

- Add tests

- Add Trevor's suggestions

- Add Trevor's suggestions #2

- Added a check for unary vs. binary QROM

- Adding Will's suggestions

- Address Will's comments

- Broken tests for 3.11 locked

- Broken tests for 3.11 locked

- Clean modji's notebook

- Fix bug in dagger for BinaryToUnaryUncomputation

- Fix for MR removal of metric and resource estimator

- Fix for MR removal of metric and resource estimator

- Fix for MR removal of metric and resource estimator

- Fix lint

- Fix lint

- Fix lint

- Fix lint errors

- Fix lks qubrick syntax

- Handle lint errors

- Include Trevor's suggestion number 3

- Isort and lint

- Lint

- Lint

- Modji's controlled LKS prep used

- Move MPS prep to experimental

- Poetry update wb

- Re-qubrickify MPS loading

- Remove bug comment in notebook

- Remove unneeded is_complex

- Remove unused imports

- Remove unused phase LKS file

- Removed unused files

- Simplify writing alpha part of circuit

- Update demo

- Updated docstring of a test

- Updated docstrings

- Use experimental state prep for handling complex amps

- Use temp registers and release at the end

- **holder_isometry_synthesis.py**: Add issue number

- **holder_isometry_synthesis.py**: Simplify syntax for MPS loading

### Build System

- Update workbench dependency

### Chores

- Add 1 test, add more docstrings to process_output

- Add MR description template

- Add references and minor syntax update

- Bump version to 1.5.1

- Change jupyter kernel

- Fix isort and docs

- Fix method names

- Got rid of returns in docstring (no longer needed)

- Initial commit

- Isort

- Lint

- Lint

- Minor lint errors

- Rename notebook to be in docs

- Update bartiq dependency in toml file

- Update to non-deprecated function.

### Continuous Integration

- Added downstream trigger job for psi-qdk

- Make downstream:psi_qdk manual for scheduled pipelines

- Remove existing downstream jobs

- Update downstream:psi-qdk rules to run on main and scheduled pipelines

- Updated dev-ops/common include reference from 0.0.5 to 0.0.6

- Updated downstream psi-qdk trigger branch target

### Features

- Add additional content for naive state prep example notebook

- Add dataclass and add controlled tests

- Added dataclass for unitary synthesis, also moved reg args around for unitary synth compute

- BRNO now sets ignore_last_batch on users behalf

- Can turn off custom uncompute inside parent qubrick

- Changed dagger from instantiation to compute

- Demo for latest MPS prep code

- Got rid of overwrite parameter

- Modified muxed rots to allow for batching when used in BRNO

- State prep now takes prep reg, updated tests

- Updated multiplxed rotations notebook to use new BRNO + get rid of deleted attributes

- **test_mps_prep.py**: Added unit test


## v1.5.1 (2025-07-14)

### Bug Fixes

- Add Rz, RzAdder to init

- Changed system size to apply Ham onto in Trotter test, correcting a bug spotted by @jlemieux and
  explained by @sgreenaway

- Cleaned up trotter test with PPRs

- Fix broken links in API reference

- Fix sorting of modules and other linting issues

- Lint everything according to new rules

- Made sure estimate method passes ctrl=ctrl rather than ctrl=0

- Remove extra name in Qubrick instantiation

- Remove tutorial symlinks

- Remove unnecessary noqa tags

- Revert changes to formatting of copyright notice

- Undo changes to the copyright notice

- **cicd**: Bump dev-ops/common version to 0.0.3

### Build System

- Added bartiq extras dependency to psiqworkbench

- Migrated pyproject.toml to poetry v2

- Moved python requirement from tool.poetry.dependencies to requires-python

- Remove explict sympy dependency and fix bad scipy spec

- Update poetry.lock

- Updated poetry.lock

### Chores

- "RotationInterface" -> RotationInterface

- A few improvements

- Add minor fixes

- Add typing

- Bump version to 1.5.0

- Change data to config in name

- Change kernel in notebook

- Delete accidental line

- Enforce rotationprotocol everywhere

- Finalize design

- Fix docstring

- Fix isort

- Fix isort

- Fix lint

- Fix linting

- Fix tests

- Fix typing

- Lint and got rid of unused args

- List -> list

- Make all rot_qbk have same signature

- Minor updates to reduce number of warnings

- More improvements

- More notebook and some minor fixes

- Remove _str_

- Remove knifey filter

- Remove naive

- Remove other mentions of symlinks

- Rename givens loop

- Rename GivensAdderLoop to GivensLoop

- RotationProtocol -> RotationInterface

- Small fixes and more notebook

- Trigger CI again

- Update dependency on bartiq

- Update WB & Bartiq version

### Code Style

- Fix isort

### Continuous Integration

- Add default assignees for version bump MRs

- Added the notify stage

- Deprecate use of old python index server

- Ignore site/

- Pass ref to included dev-ops/common CI script

- Refactored script for more sensible order

- Update dev-ops/common include to pre-release branch

- Updated dev-op/common reference to new 0.0.5 release

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2

- Updated dev-ops/common include reference from 0.0.3 to 0.0.4

### Documentation

- Add batching section to rotation notebook

- Add new givens rotation tutorial

### Features

- Add gates.py submodule

- Add generalized multiplexed rotation

- Add GivensAdderLoop qubrick

- Add GivensTilingScheme

- Changing qc.ppr to system.ppr

- Updated Trotter to use PPRs with a control arg

### Refactoring

- Simplify rotation code structure

- Simplify RotationLoop by removing sequential mode

### Testing

- Add more tests


## v1.5.0 (2025-05-13)

### Bug Fixes

- Add back phase_prep to make the interface+controller happy, still need to figure out how to cut
  this redundancy

- Address linting issues, added missing arguments to docstrings

- Better precision for test with less qubits needed

- Change gray code multiplex name to avoid conflict

- Change grey to gray

- Change inidivual amp comparison to total state l2-norm bound with eps

- Change name for naive and LKS state prep to avoid conflict

- Changes for various comments from Dylan

- Delete MMD files

- Delete unsupported cases to avoid confusion

- Docstring missing

- GidneyAdd object call

- GidneyAdder object name

- Isort errors

- NaiveAdd object call

- Name change, comment fix

- Remove check in .gitlab-ci.yml

- Remove commented out line

- Remove commented-out code

- Revoke import

- RSqrt + GidneySquare object calls

- Several changes from MR comments

- UML_AS

- **cicd**: Remove pytest-rerunfailures dependency

- **cicd**: Remove rerun args

- **poetry**: Un-pin poetry per #327

### Build System

- Add lint rules to pyproject.toml

- Added codeartifact deployment and docs publishing

- Added missing optional dependency on scipy

- Centralizing docs publishing job definitions

- Changed manual optional CI steps to be non-blocking

- Fix python dependency range

- Made docs-build-dev run on every pipeline for testing but without pushing to s3

- Pinning virtualenv in beforescript to v20.30.0

- Refactored definition in docs module

- Trying previous poetrylock

- Updated pyproject toml

### Chores

- Bump version to 1.4.0

- Deleted redundant computation of lenght of list

- Final_version_for_real_this_time (updates to imports in tutorials)

- Got rid of spurious 1e-10 and 1e-15 in tests... overkill and unneccessary

- One (hopefully...) more import fixup

- Update dependencies

- Update imports in some notebooks

- Update wb dep

### Code Style

- Ruff format

### Continuous Integration

- Adopt default python job template

- Install all extras in test jobs

- Updated before_script config for new pypi server

- Updated dev-ops/common dependency to 0.0.1

- Updated poetry dependency to >=2.1

### Documentation

- Add math equation comment for test

- Better reference + additional clarification

- Fix test file summaries

### Features

- [WIP] consolidate tests using the DI framework

- [WIP] refactor state prep qubricks to decouple them

- [WIP] xfail failing QROM tests (TO RESOLVE!)

- Add alias sampling lks interop test

- Add experimental features to the docs

- Add test for uncomputation

- Add tutorial notebook for Qubrick interoperability

- Added LKS state prep changes

- Added test to check we need to pass in the coin toss reg

- Ensure all classes/functions are typed

- Linting/CI fixes

- Minor update to test to remove specific qubrick references

- One more sort

- Re-add complex tests for naive and gray code mux's

- Re-organize files to mimic main repo

- Remove deprecated aliases

- Remove gray code stacked phase gate test

- Remove unneeded "experimental" in test file names

- Revert changes to copyright notices

- Split up tests for easier parsing

- Undo changes to init file

- Undo changes unrelated to the features added

- Undo linting changes in rotations

- Undo linting changes to set_version.py

- Update poetry.lock

- Update pyproject.toml to drop python 3.10 support

- Update qubricks in interoperability notebook

- Update test docstring

- Update tests to check for phase and amplitude correctness separately

- Update tutorial notebooks to new API

- WIP delete some unneeded lines

- WIP get most tests passing

- WIP pinpoint failure of tests

- WIP refactoring of the file structure

- WIP reformat files

- WIP update docstrings for LKS qubricks

### Refactoring

- Change test file structure

- Reorg example notebooks


## v1.4.0 (2025-04-26)

### Build System

- Migrate to new artifactory

### Chores

- Add test for too many batches

- Add typing

- Add typing to compute

- Bump version to 1.3.16

- Fix docstring

- Fix imports

- Fix isort

- Fix symlink for tutorial

- Minor mr review fixes

- Small mr review fixes

### Features

- Add batched hamming weight phasing from echo

- Add batched hwp tutorial

### Refactoring

- Remove unnecessary files


## v1.3.15 (2025-04-22)

### Bug Fixes

- Fixed adder imports

- Re-ran hwp notebook

- Update imports in hamming weight notebook

### Chores

- Bump version to 1.3.14

- Easier hamming weight computation

- Update lock file to satisfy the poetry gods (but really im a heretic and dont like this)

### Continuous Integration

- Add CODEOWNERS

- Added deploy to new artefactory

- Fix CODEOWNERS

- Update include project reference to semver tag


## v1.3.14 (2025-04-08)

### Bug Fixes

- Fix bug in dirty qubits handling

- Make automr commit meet conventional std

- Sort imports to fix lint

- **cicd**: Random_seed for a probabilistic test

### Chores

- Lint

### Features

- Minor cost reduction for groups of three HW computation qubrick


## v1.3.13 (2025-03-27)

### Bug Fixes

- Amend /ket and output pics in dyson

- Amend empty lines in lcu

- Amend link in ampamp

- Amend link in Data loaders

- Amend link in dyson

- Amend links and warnings in ham weight phase

- Amend links in low kliu

- Amend minor things in vector

- Amend multiple links

- Amend reference links

- Amend table in dyson

- Amend warning in Window

- Circular import

- Convert \ket in Compression Gadget

- Convert \ket notation in Antisym

- Don't assign unused variable

- Example

- Fix minor things in vector arithmetic

- Fix qubits alloc in vector arithmetic

- Minor updates to fix warnings and delete blanks in tuts

- Move build_qubricks_zoo back to utils

- Qubricks zoo builder, mkdocs.yml and README

- Remove deprecated WB names

- Remove empty cells in pauli sum

- Remove empty lines in multi usp

- Revert accidental merge

- Update how vectors of qubits are used

- Update old architecture paths

- Updated paths for migrated repos

- Use makefile in mkdocs cicd

- **test**: Add import to alert user when test fails are not actual fails, per #301

### Build System

- Added isort as linting dependency and pre-commit hook

- Fix python dependency range

- Update poetry.lock

- Updated lint tool from flake8 to ruff

- Updated poetry.lock

- Updated poetry.lock

- Updated pre-commit config

- Updated python support range to match common spec

### Chores

- Add blue and red boxes to multiplexor png

- Add copyright

- Add debug line for this branch

- Add debug prefix in cicd

- Add dyson and symlink checker/creator

- Add flag to test pipeline

- Add minor fixes

- Add minor fixes to rotations

- Add negative angles to test

- Add qubricks.md to .gitignore

- Add the new antisymmetrization ipynb

- Add various fixes and tests

- Audit public API

- Bump wb version

- Change jupyter kernel

- Delete empty cells in bitonic sort

- Fix amplitude amplification utils doc

- Fix arxiv links

- Fix arxiv style links

- Fix clean arg

- Fix copyrights

- Fix deprecate

- Fix deprecate python block

- Fix deprecation warnings

- Fix deprecation warnings

- Fix deprecation warnings

- Fix docstring

- Fix documentation rendering

- Fix flake8

- Fix flake8

- Fix func sphinx links

- Fix gitlab cicd

- Fix imports

- Fix imports

- Fix links in ipynb files

- Fix lint errors

- Fix lint errors

- Fix lint errors

- Fix linter

- Fix linter and a few other things

- Fix linter errors

- Fix linter errors in trotter utils

- Fix linting

- Fix linting

- Fix linting

- Fix linting errors

- Fix math

- Fix missing qbk.

- Fix more arxiv links

- Fix more links and fix run_notebooks

- Fix more linter errors

- Fix more linter issues

- Fix qbk.qbk

- Fix small issues in two notebooks

- Fix some math

- Fix utils docstrings

- Get rid of comment lines

- Get rid of overwrite_reg everywhere

- Isort set_version

- Isort set_version.py

- Lint

- Lint qubricks zoo

- Minor fixes

- Minor fixes

- Minor fixes

- Minor fixes

- Remove debug line

- Remove debug lines

- Remove gitlab rendering comment

- Remove link from vector arith

- Remove phase grad as arg

- Remove small redundancies

- Remove unused import

- Revert gitignore

- Run isort on init

- Run linter

- Update bartiq version

- Update control structure

- Update dependencies

- Update example notebook to render nicely

- Update lockfile

- Update math in notebook to get more of it rendering correctly on gitlab

- Update vector arithmetic number of qubits

- Use qbk.

### Code Style

- Apply @sgreenaway 's suggestions

- Apply @ssim 's suggestions

- Apply @ssim 's suggestions

- Fix style issues

- Isort

- Lint

- Lint .gitignore

- Linted .gitlab-ci.yml

- Ruff format

### Continuous Integration

- Added commitlint and pre-commit config for conventional commits

- Added slack notification on failed scheduled pipelines

- Adopt common CI configs

- Change order of stages to put lint before install

- Fix coverage regex

- Remove unneeded ls calls

- Updated CI test matrices to include 3.13

- **downstream**: Fix URL in tag-based trigger for QRE-CV

### Documentation

- Add most of the missing docstrings

- Add release section to README

- BitonicSort with VectorRegister

- Fix bad pages URL

- Fixed a link

- Format bitonic docs

- Renamed examples to tutorials

- Restructured docs and updated some pages incl. notebooks

- Updated CR headers

- Updated for tone

- Updated links in a notebook

- Updated poetry lock

- Updated symlinks

- **readme**: Added conv commit section to readme

- **readme**: Added Developer Guide section

- **readme**: Fixed bad URL

### Features

- (lint) COmpression gadget

- (lint) Compression gadget

- (lint) COmpression gadget

- (lint) Compression gadget

- Add auto-MR versioning

- Add dataclasses for rotation qubricks

- Add public API for qubricks Zoo

- Add search to offline mkdocs thru offline plugin

- Add unary qrom

- Compression Gadget

- Compression gadget

- Compression Gadget

- Compression gadget

- Compression Gadget

- Compression gadget for powers

- Compression gadget for powers

- Compression gadget multiply list

- Compression gadget multiply list

- Rename ArbitraryStatePrep -> GroverRudolphStatePrep

- Tidy up interfaces and remove dependency on QPU ops

- Typo fix

- Update mkdocs.yml to properly display notebook

- Update QROM tutorial to also analyze QREs

- Update readme to include public/private API guideline

- Updated antisymmetrizer to use vectorregisters

- **muxes**: Added MUX qubricks from project scylla repository

### Refactoring

- Minor update to reduce deprecation warnings

- Remove usage of get_num_qubits

### Testing

- Add tests from scylla


## v1.0.1 (2023-07-11)


## v0.1.1 (2023-02-22)

- Initial Release
