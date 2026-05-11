# CHANGELOG

<!-- version list -->

## v4.38.2 (2026-04-23)

### Bug Fixes

- Bug fix in HermitianWindowFilter

- Fix QFTAdd/QFTSubtract Qubricks for integer rhs

- Fix QFTAdd/QFTSubtract Qubricks for integer rhs

### Chores

- Refresh example and tutorial notebook outputs

- Refresh example and tutorial notebooks (outputs and selective warning silences)

### Continuous Integration

- Treat example notebooks warnings as errors

- Treat example warnings as errors in the examples test suite

- Treat example warnings as errors in the examples test suite

- Updated examples/conftest.py to match latest in WBA

### Documentation

- Clean up API docs of exposed Qubricks

- Make pages missing from nav and incorrect anchors into errors

- Make pages missing from nav and incorrect anchors into errors

### Refactoring

- Refactor qpu methods to act on specific filter types rather than pass down filter chain


## v4.38.1 (2026-04-21)

### Bug Fixes

- >>qasm-export>> handles zero-target gates and ignores nop

- >>qasm-export>> handles zero-target gates and ignores nop


## v4.38.0 (2026-04-20)

### Features

- CUDA-Q: Improvements to peek_read_probability() and measurement


## v4.37.3 (2026-04-17)

### Bug Fixes

- Update format_stream to output runnable code in asm format

- Update format_stream to output runnable code in asm format

### Chores

- Use FutureWarning for deprecations


## v4.37.2 (2026-04-17)

### Bug Fixes

- Migrate from GoogleSelectOptimized to BinaryTreeSelect

- Migrate from GoogleSelectOptimized to BinaryTreeSelect

### Continuous Integration

- Fix broken changelog generation

- Fix broken changelog generation and regenerate


## v4.37.1 (2026-04-16)

### Bug Fixes

- Resolve merge conflict

### Documentation

- Modernize example_rotation_api.ipynb example and mark Rotation Qubrick as experimental

- Modernize example_rotation_api.ipynb example and mark Rotation Qubrick as experimental

### Features

- Resolve "Revert QFT into Hardcode"


## v4.37.0 (2026-04-14)

### Bug Fixes

- Add abstract classes to average qubit estimator

- Categorize composite filter and device filter

- Update IMS model to not be simulation or device for now

### Features

- "ast-2834 Add Filter Base Classes"

- Adding base filters initial implementaiton


## v4.36.2 (2026-04-13)

### Bug Fixes

- Add edge case to avoid swap

- Delete other reference for naive phase gradient

- Delete phase gradient example notebook

- Fix interoperability bug causing warning

- Fix interoperability bug causing warning

- Flip control order, fix swap code

- Remove symbolic test for PGA error reporting, remove catalyst test for QFT

- Revert QFT code, delete phase gradient Qubricks and tests

### Documentation

- Add Units support to docs for reflect theta


## v4.36.1 (2026-04-10)

### Bug Fixes

- Ppr gate bug when called with identities


## v4.36.0 (2026-04-10)

### Bug Fixes

- Fixing linting

- Ppr bug in unitary filter

- Qpu.pps can return probability slightly > 1

- Remove errant change in qpu

- **path**: Minor import path fix

- **timing**: No longer measuring witness

### Chores

- Clean up latest changes

### Documentation

- Document qpu.enable_qubit_allocation_debugging

### Features

- Adding check, analyze and process to basic filter

- Adding clean ladder with new filter

- Adding example filter

- Adding the By Operation Type Filter

- Document qpu.enable_qubit_allocation_debugging and add flushing if this check is enabled
- Prototype for simple filter test

### Performance Improvements

- **cache**: Add op cache for speed

- **filter**: Another filter without cache but with index checking

- **filter**: Speed up filter with index scanning, v1

- **prototype**: Testing filter prototypes

- **scan**: 10% speedup for op scanner


## v4.35.5 (2026-04-08)

### Bug Fixes

- Updated unitary filter to properly handle zero target gates


## v4.35.4 (2026-04-02)

### Bug Fixes

- Round rotation angles in diagrams to 3 decimal places

### Chores

- Add removal version 5.0.0 to deprecation notices

- Make sure .pyi files are included in wheels

### Continuous Integration

- Added project-specific webhook for release notification

- Revert cp to mv for post-build artifacts

- Updated dev-ops/common include reference from 0.2.0 to 0.2.1

### Documentation

- Add IntelliSense/API docs for compute method of qubricks

- Add QubrickCosts to numeric QRE tutorial

- Add static images for circuit designer howto

- Add unpkg.com to IGNORE_DOMAINS

- Fix typos + other changes suggested in review

- Include static svgs in Circuit Drawing howto


## v4.35.3 (2026-03-30)

### Bug Fixes

- Fix small bug with parsing generics for DI container


## v4.35.2 (2026-03-26)

### Bug Fixes

- Updated build job to copy instead of move from dist


## v4.35.1 (2026-03-25)

### Bug Fixes

- Update ci to build all images on tag


## v4.35.0 (2026-03-25)

### Bug Fixes

- Fix WB -> CD export for Qubricks with no inputs

### Chores

- Bump version to 4.34.2

- Remove do_boxes from Qubrick constructor arguments

### Continuous Integration

- Deprecate old webhook URL variable

- Fix broken image matrix on test:macos:extras job

- Fix issues in test:macos:extras job script

- Overwrite rules to test new matrix setup

- Re-enable default rules for test jobs

- Removed commitlint job

- Updated dev-ops/common include reference from 0.1.6 to 0.2.0

### Documentation

- Add instruction about installing graphviz

- Fix release notification channel name

- Move items from private docs to examples

- Remove info about private docs from configs

- Unify internal and external docs builds

- Update graphviz instructions

- Update Slack webhook variable reference


## v4.34.2 (2026-03-19)

### Bug Fixes

- Remove IP-sensitive QPU Driver model

- Remove unneeded parents from function

- Update DI logic to handle more complicated interfaces

- Update IMSModel docstring

- Update interoperability code to work with more complicated generic types

- Update logic for subtype specification

### Chores

- Add tests for the new functionality

- Address reviewer comments

- Bump version to 4.34.1

- Tidy up old code


## v4.34.1 (2026-03-18)

### Chores

- Bump version to 4.34.0


## v4.34.0 (2026-03-18)

### Bug Fixes

- Address reviewer comments

- Fix converting programs releasing rotation catalyst to QREF

- Make symbolic catalyst QREs more robust for multiplicities of pi/8

- Remove debugging import

- Remove networkx as default dependency

- Remove unused imports

- **cuda**: Add >>cudaq-sim-v2>> for testing

- **cuda**: Comment out second run

- **cuda**: Iteration on new kernel

- **cuda**: Iterative fixes for ops

- **cuda**: Iterative fixes for ops

- **cuda**: Just small cleanup

- **cuda**: Merge fix for iterative car/les changes to kernel

- **cuda**: New kernel logic

- **cudaq**: Make CUDAQ a soft-import per **test**: Add test file

- **test**: Test now checks the state vec

- **tests**: Kernel and speed test adjustments

- **tests**: Small fixes to speed testing

### Build System

- Fix networkx dependency

### Chores

- Add specific warning text to ignore

- Add version to deprecation warning

- Address Ian's comments

- Address Michal's comments

- Address Michal's comments

- Address more comments

- Address more comments

- Bump version to 4.33.7

- Improve handling of warnings showcased in tutorials

- Remove a few more warnings

- Remove CODEOWNERS

- Remove global warnings filtering from QPU

- Remove psi-basquiat from dependencies

- Remove unneeded commitlint config and pre-commit job

- Rename condition_mask argument of Qubits methods to cond

### Code Style

- Fix formatting

- Formatting fixed

- Tidy-up imports

### Continuous Integration

- Add deploy stage for docs:deploy jobs from construct/devops

- Add missing version bump config to semantic release

- Add semantic release config, fix version, delete set_version.py

- Bumped dev-ops/common dependency to 0.1.1

- Cleaned up .gitlab-ci.yml for new pipeline config

- Removing skip_on_version_tag and removing construct/devops include

- Switching to centrally defined release jobs

- Updated dev-ops/common include reference from 0.0.9 to 0.1.0

### Documentation

- Add 'Advanced Gates' tutorial and docs map

- Add 'Basic numeric QREs' tutorial

- Add basic docstrings to QPU ops.

- Add basic numeric QRE how-tos

- Improve API docs for ppm and peek_ppm_probability

- Place comment about QPU_op where it should be

- Remove reference to igraph in example

- Replaced commitlint README section with MR title linting docs

- Update comment

- **api**: Clean up API docs

- **wip**: Outline CUDA-Q simulator tutorial section

- **wip**: Outline CUDA-Q simulator tutorial section

### Features

- Draft filter

- Enable AV comparison in assert_resources_equal by default

- Implement parsing of box close and box open events

- Support special angles < 45 degrees in symbolic rotation catalyst

- WIP initial functions needed for cudaq filter

- **cuda**: Add mini kernel test, and lots of mess

- **cuda**: Early prototype and speed test iteration

- **cuda**: Iteration on Construct CUDA testing

- **cuda**: Iteration on the cudaq sim filter

- **cuda**: Iteration, integration of filter with static kernel sim

- **cuda**: More iteration and fixes

- **qft**: Add native QFT

- **test**: Update from car/les to test #1302

### Refactoring

- Add helper functions serving as type guards

- Add type hints and minor style changes

- Get rid of unused if statement

- Remove known_discrepancy marker for RotationCatalystHandler

- Remove unusd check_and_fix_op function

- Rename _has_masks to is_pauli_product

- Rename op_labelid_to_label to op_label_id_to_label

- Simplify expressions for number of pi/8 and 3pi/8 phases gates

- Turn QPU ops into new style NamedTuples

- Use op_label_id_to_label instead of op_labelid_to_label

- Use typeguard helpers

### Testing

- Add tests for converting program with boxes to CD

- Enable AV comparison in symbolic rotation catalyst tests

- Extract logic for constructing 3 symbolic rotation catalyst fetches to a separate function

- Optimize symbolic rotation catalyst test cases

- Rename fixture and clarify why we use 3 fetches

- Skip dag-related tests if networkx not installed


## v4.33.7 (2026-03-05)

### Bug Fixes

- Add missing type-checking import

- Add tests and a missing compute in qubrick

- Add type checking import of construct_tools.Circuit

- Edit docstrings

- Fix register sorting

- Make expand default to False

- Make imports from construct_tools optional

- Minor fixes in get_dag_from_qpu

- Remove incorrect TYPE_CHECKING import

- Remove unnecessary option for dags progress bars

- Skip alloc_ref and free_ref in register tracking

- Use correct action when constructing subroutine enter event

- **cicd**: Trivial change to fix build lint error

- **cicd**: Trivial change to fix CICD lint error

- **compareEQ**: Fix the == compare to be efficient for all types

- **docs**: Add text per MR feedback

- **MR**: All MR feedback addressed!

- **MR**: Fix per MR feedback

- **MR**: Fixes based on MR feedback

- **MR**: Fixes per MR feedback

- **MR**: MR ideas addressed, first pass

- **MR**: Paramaterize test

- **MR**: Respond to all MR feedback

- **MR**: Robustify witness removal pr MR feedback

- **simplify**: Remove special cases and fix a test

- **unitary**: Fix per MR feedback

### Chores

- Add cond_reg api docs (with deprecated note)

- Add construct_tools to examples group

- Add optional dependency on construct_tools

- Bump version to 4.33.6

- Regenerate lock file

- Remove dependency on igraph – stage 1

- Remove igraph codepaths

- Remove temporary files

- Replace use of qpu.metrics with resource_estimator in new_tutorials

- **review**: Apply 4 suggestion(s) to 2 file(s)

### Code Style

- Apply formatting

- Improve formatting

### Documentation

- Add example notebook with CD conversion

- Fix reaction depth example

- Fix typo in docstring

- Refresh notebook

- Update WB -> CD notebook to correctly discuss expand kwarg

- Wrap Qubrick labels in \\text{}

### Features

- Add basic support for depth argument in circuit_designer.export

- Add hash and eq methods to LabelReference

- Add path tracking in exporter base

- Implement `expanded` flag

- Implement basic circuit_designer.draw function

- Implement proper handling of implicitly accessed registers

- Implement somewhat functioning register placement in WB -> CD conversion

- Sort registers to make output more predictable

- **diagonal_matrix**: Implement Diagonal Matrix, with test

- **fallback**: Add new fallback scripts

- **falllback**: First pass prototype of fallback measurement generators

- **modular_add**: Add comments and expand to use different core adders

- **modular_add**: First pass, with test

### Performance Improvements

- **parametrize**: Added parametrize

- **test**: Add in test optimization from #1274 into #1297

### Refactoring

- Add register tracker as an attribute to exporter

### Testing

- Add tests for draw function

- Add tests using rotation catalyst

- Include examples with registers currying in CD integration tests

- Indulge ruff with removal of lambda usage

- Rename test as suggested by reviewers

- Restore test skips

- Reword terminology about implicit registers and currying

- Temporarily disable currying test


## v4.33.6 (2026-03-02)

### Bug Fixes

- Add support for changing unitary dimension between get calls

- Address reviewer comments

- Improve performance of unitary filter and add catch for slowness

- Reduce number of unnecessary warnings

- **cicd**: See if we can autodetect the correct one

- **cicd**: Signed/unsigned errors and warnings fixed

- **cicd**: Try to install just the compatible wheel and relax when the incompatible ones fail

- **cicd**: Try to install just what's compatible

- **MR**: Fix typo per MR feedback

- **test**: Debugging CICD fail

### Chores

- Add missing sams

- Bump version to 4.33.5

- Ignore profiling directory

- Move unitary benchmark to speed tests

- Remove explicit psi-liqtr dependency

- Remove references to internal sources

- Remove references to internal sources

- Remove support for psi-liqtr in rotation synthesis

- Update tutorial notebook and add tests for exceptions/warnings

### Continuous Integration

- Add docs preview job to CI pipeline

- Disable lint:commitlint

- Make per-image wheel passing between jobs more deterministic

- Pull SMS out as specific codeowner

- Update preview job to use docs build artifact instead of docs.psiquantum.lan

### Documentation

- Fix issue with broken w3.org links

### Features

- 18s for CC, 8s for Cuccaro

### Testing

- Remove QPU.draw call in CC test suite


## v4.33.5 (2026-02-17)

### Bug Fixes

- **cicd**: Remove all aws references from build scripts and .gitignore


## v4.33.4 (2026-02-17)

### Bug Fixes

- **cicd**: Remove AWS version file from version update script


## v4.33.3 (2026-02-13)

### Bug Fixes

- Check for catalytic T warning checking

- Check for conditional RS warning

- Control only the center CNOT in controlled SWAP

- Fix cswap handing in UnitaryFilter

- Get rid of DeprecationWarnings

- Remove warnings triggered when expected

- **linux**: Again, try to force no bookworm

- **linux**: Test building 6 flavors, both pinned and unpinned

- **linux**: Test unpinned default build

- **linux**: Try to force no bookworms

### Chores

- Add security policy

- Bump version to 4.33.2

- Deprecate aws code

- Improved warning messages

- Remove a few more deprecation warnings

- Remove newlines from warnings

- Remove outdated comment

- Silence ross-selinger warnings if pygridsynth isn't installed

### Continuous Integration

- Add dependency scanning to GitLab options

- Enable full matrix for build job testing

### Features

- All warnings bashed

- Fixed unc bug in edge case for ltc and included this in tests

### Refactoring

- Remove unnnecessary witness functionalities

### Testing

- Ignore warnings about DAG support in test suite


## v4.33.2 (2026-02-06)

### Bug Fixes

- Fix handling swap in compute_args

- Fix how registers are sifted up

- Fix main call in test

- Fix pyliqtr calc and switch off warnings

- Fix typing errors

- Fix typo making controL_type for phases incorrect

- Implement support for PPMs and PPRs

- Make display label for subroutines correct

- Make registers bubble up when finalizing qubrick conversion

- Remove debug print

- Remove nonexistent import

- Remove nonexistent LabelType from __all__

- Remove unnecessary pass statements

- Remove unused imports

- Remove unused variables

- Removing print statement

- Returning single filter option correctly

- Reuse variable instead of calling get_instructions twice

- Use cnot gate type instead of plain "x"

### Chores

- Add kwargs to dummy qubrick

- Bump version to 4.33.1

- Configure codeowners for integrations submodule

- Fix the rest of the qiskit warnings

- Fix warnings for dag conversion

- Move to new_tutorials

- Remove radians param set from qasm export

- Remove references to deprecated AV counter

- Remove whitespace changes to file

- Skip tests properly for pyliqtr

- Spelling, removing code from headers, improving readability and style matching other docs

- Suggestions added, deleted old tutorial

- Update master -> main in README

- Update pyproject.toml to ignore qiskit deprecation warnings

- **review**: Apply 1 suggestion(s) to 1 file(s)

- **review**: Apply 11 suggestion(s) to 4 file(s)

### Code Style

- Add type hints to some functions in bit_utils

- Apply formatter

- Change cond_mask to cond_xor

- Fix typing in _common.py

- Improve formatting

- Improve typing in events.py

- Improve typing in qpu_ops.py

### Documentation

- Add basic howtos

- Adding correct capitalization

- Fix docstrings still mentioning serializers

- Replace 'how to define routine' example with ReflectAboutMean

- Update example names in RotationEvent

### Features

- Add base class for CD serializer

- Add explicit input registers to routines

- Add s and t to gate mape

- Add stub for circuit designer serializer

- Add support for exporting missing ops

- Add utilities for converting ops to abstract events

- Added Cuccaro and benchmark graphs

- Adding list option to get_filter_by_name

- Fixed bug and added test for >2 ctrl op's.

- Implement forward referencing of labels

- Implement helpers for register-tracking

- Implement missing details of RegisterTracker and MaskBasedTracker

- Implement public interface for Circuit Designer serializer

- Implement serving exported diagrams directly to file

- Improving test and removing dead code

- Thinning code examples and other style changes

- Thinning code examples and other style changes

- Use correct control type with phase operation

- Wrap labels in \text{}

- Wrap returned implementations in sorted to allow pytest parallelisation, update test_tags, and
  separated out adder interop test file

### Refactoring

- Change gate_id to opcode

- Change terminology: serializer -> exporter

- Remove LabelType

- Remove numeric_op_to_event

- Rename release -> dealloc

- Rename serialize -> export

- Simplify getting CD gate type from WB opname

- Simplify logic in _resolve

### Testing

- Add missing tests

- Add tests for exporting qubrikcs

- Add tests for repeating primitive ops of the same type

- Adding missing tests and fixing docs

- Fix PPM and PPR tests

- Fix register tracker tests to match changes in corresponding module

- Update tests


## v4.33.1 (2026-01-30)

### Bug Fixes

- Add missing known_discrepancies for GidneyAdd and RotationCatalystHandler.

- **drawing**: First pass at a fix for #1249

### Chores

- Add free_symbols to old parameters to make exceptions easier to understand

- Address 'condition arg is deprecated' deprecation warning

- Address a few more deprecation warnings

- Bump version to 4.33.0

- Fix deprecation warning Qubits.QFT is being considered for deprecation

- Fix warning for non-svg file extension in qpu_draw

- Remove errant warning missed in previous commit

- Remove unnecessary warning

- Remove warnings when dealing with baseline architecture filter

- Update cond_reg -> cond_zip

- Update to new resource_estimator interface

### Continuous Integration

- Add pytest reporting for extras job

- Added pytest report generation for linux test jobs

### Documentation

- Address Ian's comments

- Fix wording in docstrings

- Improve Qubricks docs based on mentees' feedback

- Updated reg issue in releasing qubits

### Features

- Add discrepancy decorator to comparators

### Testing

- Address warning in qpu ram limit test

- Addressed some easy-to-resolve warnings in our test suite

- Avoid using get_av_from_instructions in test_1113_y_parity_in_av_costs.py

- Remove unnecessary test

- Update tests for GidneyAdders


## v4.33.0 (2026-01-19)

### Bug Fixes

- **MR**: All MR requests met

- **test**: Update an old test to the new behavior

### Chores

- Bump version to 4.32.0

### Documentation

- Update readme

### Features

- Initial commit

- **reset**: Clear ops on reset per #1276

### Testing

- Fix faulty logic for AV in test_black_box_exact_coverage


## v4.32.0 (2026-01-15)

### Bug Fixes

- Add default functions_map

- Change idx mechanism in catalyst to using ARBITRARY_ANGLE

- Condition needs to default to 0 not none for interface tests to pass

- Fix handling of rotation epsilon override for catalyst

- Fix import problems

- Fix issue with av for ppm

- Fix issue with wrong defaults in default_functions_map

- Fix some edge cases for symbolic ops compilation

- Fixed symbolics for rotations certain angles

- Fixes calculation of z_mask with control

- Fixes calculation of z_mask with control

- Fixing me repeatedly mispelling cuccaro

- Improve handling symbolic rotations

- Intermediate stage of fixing AV of PPRs & PPMs

- Intermediate stage of fixing AV of PPRs & PPMs

- Less zealous override for rotation

- Make default value for rotation epsilon 0

- Make interface extraction more robust to parallelization

- Qint range

- Remove additional string append

- Remove incorrect changes to active_volume_lookups

- Remove leftover mentions of rot_bits

- Remove redundant assignment

- Remove some leftover code

- Remove unnecessary "error_param" user parameter

- Remove unnecessary logic

- Remove unnecessary None case

- Remove unused arg to get_gate_cost

- Remove unused default value to compute_active_volume_rotation_ross_selinger

- Repeated test line

- Revert meaningless changes to qpu.py

- **adder**: Sign-extension fix for adders

- **check_zero**: Check that allocations are returned to zero when freed

- **cleanup**: Add switches to different behaviors

- **cleanup**: Remove all 64bit references, add a test and a warning

- **cleanup**: Remove commented-out exception

- **cleanup**: Simplify measured testing

- **cpp**: Fix returning of new array

- **debugging**: Add simple stack debugging

- **debugging**: Fix debugging feature so it works as requested in MR

- **elbows**: Remove elbow measurements, which are hiding errors

- **elbows**: Temporarily always enable debugging

- **get_dag_from_qpu.py**: DAG should now produce the correct graph and run faster.

- **get_dag_from_qpu.py**: Refactored some code at the bottom of get_dag_from_instructions.

- **get_dag_from_qpu.py**: Updated a comment.

- **jumps**: Fix minor op counting error

- **lint**: Fix lint issue

- **MR**: Fixed per MR feedback!

- **namd**: Minor typo fix

- **release-check**: Iteration on #648

- **simplify**: Further simplification

- **simplify**: Reduce the set of changes to get this delivered soon

- **swap**: Fix tracking when we swap measured qubits with non-measured ones

- **test**: New fail case from Mariia to handle

- **tests**: Fix a few test issues

- **typing**: Minor type fix

- **user_error**: Provide a much better user error on non-zero release

- **zero-ckeck**: WIP on the zero-check fix

### Chores

- Add newline to test_1266_qubits_bit_qpu_pull_state.py

- Add override rotation method for epsilon

- Add type hinting

- Adding copyright header

- Adding more docstring

- Adding more type hinting, removing empty lines, moving arg to init

- Adding tests for rotation precision interface

- Adding xfail for zero case to be solved in EJ's revamp of file

- Bump version to 4.31.2

- Catalyst-specific epsilon override

- Copyright dating

- Copyright statement

- Delete benchmark notebook

- Delete unused variable

- Deleting non AddBase versions

- Deleting notebooks, moving refs to gidney arithmetic doc

- Fix comment string and remove elbow option from dirty case

- Fix mod in docs

- Fix my fix

- Fixing broken test and updating rot_bits in active_volume_lookup and gate_costs

- Fixing nonfunctional inconsistency in qubit register names that was copied throughout

- Increasing test register size

- Madd with signed values

- Made rotation precision helpers abstract and added docstrings

- Making changes in base qpu to support echo workflow.

- Making update to qbk_rotation for error param

- Moving rotation_precision content to rotation_utils

- Remove testing code

- Remove unstable warning and patch Ross-Selinger synthesis

- Removing repeated comment from tutorial

- Removing unnecessary string

- Restore branch

- Spelling

- TO RAISE: break case when int=0 for lt, zero qubit register for all.

- Undo test changes

- Updat ctx and cat to better respective naming conventions

- Using bit default, spaces before args, adding tutorial

- **review**: Apply 1 suggestion(s) to 1 file(s)

- **review**: Apply 1 suggestion(s) to 1 file(s)

- **review**: Apply 7 suggestion(s) to 5 file(s)

### Code Style

- Minor fixes

- Update copyrights

### Documentation

- Add missing docstrings

- Change comment about bit-vector simulator

- Explain purpose of Overridable class

- Minor clean up of API docs and tutorials

- Update docstring of ResourceTolerance

### Features

- 100% coverage

- Add overridable objects to QPU

- Add support for error_param for PPRs

- Add support for pull_state_specific to bit-qpu

- Added carry input for subtractor functionality, added tests for QInt, added doc references

- Added edge case

- Adding Cuccaro to quantum arithmetic doc

- Adding hermitian-window-filter to docs and removing ctrl (added to work with WBA which is now its
  own MR)

- Adding option to do controlled qubricks. translated to AddBase but not all inhereted tests passing
  instantly.

- Adding QUFixed, QFixed testing pyres

- Adding select test specifically for sparsity

- Adding sparsity trick for CC and edgecase fix for Cuccaro adder

- Adds payload ancilla when non-Pauli and most tests passing. need to update dirty ancilla version

- All test passing

- Allow computing RS AV when precision is symbolic

- Borrowing naive adder for quantum + classical value for multiply add to work with QInt

- Cleaning test file

- Coverage 92%

- Cuccaro with AddBase passing all tests

- Deleting unused file, EJ fix for bug for deferred result

- Doc fixes, CC ltc edge case caught, made CC tests more efficient, tutorial notebook for benchmarks
  (to be deleted)

- Final optimisations

- Final tests tidyup

- Hybridising Cuccaro and Gidney for lhs > rhs addition.

- Implement Overridable class

- Implement overriding epsilon for SymbolicQPU

- Implement overriding epsilons per Qubrick instance

- Implement overriding symbolic catalyst rotation epsilon

- Include MAdd

- Interface to alter bits of precision for rotation.

- Pragma cases

- Qubricks for cuccaro addition with tests

- Removing partial call and adding swap to self-inverse ops

- Sign extension and carry-in, slight bug left with combination of sign extension and carry-in

- **64bit**: Move 64bit conversion into cpp conversion

- **64bit**: WIP, first pass unhooking the 64bit converter

- **assert**: Iteration on zero-assert in #648

- **bit-check**: Assert if bit-sim error detected

- **classical-tracking**: Track classical values for warnings

- **clear-on-free**: Second pass at auto-clear classical qubits on free

- **events**: Event system first pass

- **events**: First pass of event reporting system

- **get_dag_from_qpu.py**: Added a comment and a fix strat for incorrect dag construction.

- **stack**: Wip-stack-collection

- **wip**: First pass of state vector classical checking

- **zero-check**: Simplification iteration

### Performance Improvements

- **64bit**: Much faster 64bit conversion

- **64bit**: Speed improvement for 64-bit checking

- **witness**: 2x speedup for witness collector

- **witness**: Quick dive into why the witness takes time

### Refactoring

- Change get_effective_rotation_epsilon and its catalyst counterpart to properties

- Change weight to mask in symbolic PPR and PPMs

- Cleaning symbolic code for active volume of PPRs & PPMs

- Extract computing effective error_param into separate method

- Get rid of _get_override_rotation_epsilon

- Get rid of _get_override_rotation_epsilon

- Get rid of get_default_rotation_bits

- Get rid of get_effective_rotation_bits

- Get rid of override_error_param

- Improve interfaces definition

- Move override mechanism to BaseQPU

- Move rotation epsilon configuration from __init__ to QubrickSettings

- Refactor symbolic ops tests

- Remove eror_param from __init__ method of QPU

- Remove old, unused implementation of rotation overrides

- Remove unused imports

- Remove unused imports

- Remove unused rot_bits

- Restore "effective eps" logic in Ross-Selinger filter

- Restore previous import structure

- Tidy up logic for symbolic pprs & ppms

### Testing

- Add test for bitwise_and in parameter

- Add tests for pull_state_specific in bit-qpu

- Adding coverage for qint

- Correct and improve the test cases

- Fix failing tests

- Fix typo (gres -> qres)

- Improve tests

- Mark rotation eps symbolic tests as needing Bartiq

- Minor fixes

- Minor fixes

- Reorganize tests and rotation parametrization

- Update coverage tests to use operator rather than private methods in most cases

- **bit-sim**: Add tests for bit-sim


## v4.31.2 (2025-12-18)

### Bug Fixes

- **cicd**: Remove --skip-existing to try to work around a CICD server issue

- **cicd**: Remove references to core_expiration.cpp from build and distro


## v4.31.1 (2025-12-16)

### Bug Fixes

- Caught bug in calling none ctrl

- Change to list of messages to allow for mutability

- Docs misprint

- Forgot about elbow->x replacements in filter

- Qint range and type hinting

- Running more tests of filter mux issue

- Something is failing with the filter which is only obvious with MUX with grey counting

- Workaround getting new message in qpu debugging when warnings turned off

- **cond_xor**: Fixes for invalid cond_xor constructions

- **MR**: Fixes and cleanup per MR feedback

- **MR**: Fixes per MR feedback

- **poetry**: Poetry lock

- **test_ops.py**: Removed failing test cases from
  test_controlled_phase_special_angles_numeric_theta as they are not valid equivalent comparisons
  when written as controlled operations.

- **tests**: Remove capsys from printing tests

- **tiny**: Very small fixes

### Chores

- Add do_draw to test_arithmetic, delete plotting notebook

- Add type hints, add extra test for filter problem

- Bump version to 4.30.6

- Delete notebook

- Expanding cov

- Fix in notebook and adding helper functions

- Fixing ctrl so that adder interface test passes

- Fixing type hinting, adding seed to tests

- Incrementer was occasionally including one too many ancilla, extending test cov with previous
  adder tests

- Linting

- Linting

- Moving filter and expanding test to all self-inverse ops. making qubrick names more verbose and
  fixing minor ancilla logic bug.

- Removing same functions from example notebook

- Removing unnecessary helper functions and inputs

- Update basquiat-adapter to 0.5.0

- Updating example notebook

### Continuous Integration

- Added release stage

- Manually specify number of runners

- See if 2 workers does better than 8

- Set number of pytest workers to 8

- Test performance with 4 pytest runners

- Updated dev-ops/common include reference from 0.0.8 to 0.0.9

### Documentation

- Adding a few fixes

- Adding batch filter messages, and more drawing

- Adding clarifications to the compilation pipeline outline

- Adding conclusion and edits from mariia

- Adding deepdive feedback

- Adding examples to pipeline deep dive with extra verbosity to be shown during some passes

- Adding explanation of register type printing to testing-debugging notebook

- Adding fixes to docs and examples

- Adding more to outline

- Adding outline of compilation deep dive

- Adding rough draft text for QPU section

- Adding text and examples to the compilation pipeline deep dive

- Edits for clarity, spelling, and grammar

- Filling out links

- More edits

- Remove autoreload, add to mkdocs

- Sneaking in a typo fix

- Updating docs language and tests

- Updating title to match file name

### Features

- Add docs references, add QInt testing fro incrementer, adder. Remove cond input from
  CondCleanBuild.

- Add initial typing to print_state_vector

- Add padding for floating point values

- Add witness_qre-analysis serialization dialect

- AddBase versions tested.

- Adding QUFixed, QFixed tests.

- Adding sorting for typed register values

- Changed filter to work for any self-inverse op. made partial_compute qubrick to avoid reverse
  input and utilise dagger. small chore's from MR feedback.

- Deleting dead code, adding more comments, temporary tutorial notebook

- Fixing argument names

- Toffoli window filter with cond clean MUX

- Transforming adder to AddBase and making ctrl case apparent for incrementer. Notebook with
  possible bug case in AddBase.

- **get_dag_from_qpu.py**: Rename instruction_dag to operation_dag and update related logic for
  clarity

- **get_reaction_limit.py**: Speed up node removal

- **gridsynth**: Add pygridsynth and mpmath as optional dependencies

- **pygridsynth**: Built-in support for pygridsynth

- **synth**: Allow selectable synthesis filters

- **visualization_tools**: Add newlines and progress bars

- **visualization_tools**: Enhance progress iterator with improved ETA calculation

### Testing

- Adding tests for new typing with print state vector

- Adding typing test


## v4.30.6 (2025-12-04)

### Bug Fixes

- Add fix for old parameter

- Adding rel and abs tol to validate to prevent WBA upstream failures.

- Bounds check Nonetype

- Fix av cost for 0-target lelbow

- Fix bit length calculation

- Fix lambdified resources for assert_resources_equal

- Fix test_elbow_av_calculation_from_get_av_from_op_symbolic

- Imports in qubricks.py

- Lint

- Simplify logic for get_gate_cost and fix 0 for s or z angles.

- Symbolic qres for controlled adder (and other qubricks)

- Testing downstream qdk triggers

- Update av costs for symbolic comparators

- Update QFT to give correct AV counts

- **_op.py**: Changed double quote to single quotes due to issues with f string.

- **_op.py**: We now only trigger validation logic for numbers, i.e. symbolics are fine. Also allow
  for target = 0 so other tests pass.

- **build**: Fix setup_legacy.py

- **cleanup**: Migrate namespaces form Tau to PsiQWorkbench

- **cleanup**: Move exception to a warning

- **cleanup**: Remove cpp from docs

- **cleanup**: Remove straggling refe to the old lib

- **cpp**: Cleanup on C++ rework

- **cpp**: Iteration on C++ refactor

- **cpp**: Iteration on C++ rework

- **cpp**: Iteration on pybind11 removal

- **cpp**: More iteration on C++ rework

- **cpp**: WIP for C++ rework

- **cpp**: WIP progress on C++ refactor

- **docs**: Fix warning from mkdocs

- **expiration**: Complete removal of the license and expiration systems

- **get_av_from_op.py**: Accomodate symbolics in lelbow

- **get_av_from_op.py**: Allow for no symbolics

- **get_av_from_op.py**: Get rid of sympy

- **get_av_from_op.py**: Is_symbolic

- **get_av_from_op.py**: Tests pass

- **lock**: Update poetry lock

- **pybind11**: Set up more functions for external calling

- **pybind11**: WIP on C++ overhaul

- **python**: Properly incref None to fix tests

- **test_1128**: Move to tests/qre folder

- **test_994**: Move lelbow tests to test_994

- **test_optimized_multi_target_elbows.py**: Add symbolic tests

- **test_optimized_multi_target_elbows.py**: Rename to exclude number.

- **test_optimized_multi_target_elbows.py**: Specified conditions

### Chores

- Accomodating phases and rotations for gate cost

- Add xfail and relevant comment for failing test for compare_av

- Adding additional angles to test_rx_ry_right_angles_uncontrolled_symbolic.

- Adding compare cost for ref and cost in compare_costs

- Adding tests and removing isclose functionality.

- Altering to a Pydantic dataclass

- Broaden numeric-like handling in _normalize_resource_tolerance

- Bump Bartiq version to 0.16.0

- Bump version to 4.30.5

- Condensing test cases for controlled slices

- Consolidate tests

- Empty commit to trigger GitLab

- Enhance testing for test_ops

- Enhancing test for rtol and tol

- Fix lint warnings

- Make ToleranceSpec not return None but always return ToleranceSpec

- Merge master and minor update

- Merge master and minor update

- Minor cleanup

- Minor tweaks to comments

- One approach to using resource tolerance

- Reduce None for tolerance interface

- Reducing constants for theta angles

- Remove test_special_angles_symbolic_get_gate_cost test

- Removing comment

- Removing unneeded block of code in test.

- Rename expect_op to expected_op

- Rename qa_n qb_n to qbts_a and qbts_b for consistency

- Simplify tests by passing Qubits

- Update codeowner file

- Update to exclude

- Updated _validate_cost_with_tolerance so tolerance defaults directly to an immutable
  ResourceTolerance.

- Updating ToleranceSpec to a frozen dataclass

- Use field validators instead of post_init

- Using conditions for heaviside logic in gate costs

- **review**: Apply 1 suggestion(s) to 1 file(s)

- **review**: Apply 1 suggestion(s) to 1 file(s)

### Code Style

- Remove unused import

### Continuous Integration

- Debugging manual job

- Don't allow failure for docs warnings or broken links

- Updated psi-qdk trigger jobs

### Features

- Add random.seed() in set_param()

- Add support for zero target T, S, t_inv, and s_inv stale count

- Mark RotationCatalystStatePrep as first-pass only routine for Bartiq

- Optimize mutli-target lelbow AV

- **_op.py**: Added code to restructure_op that catches SWAP gates that have invalid arguments.

- **test_1232_swap_gate_target_validation.py**: Added tests for new swap gate validation code.

### Refactoring

- Change is_pauli to is_opcode_pauli

- Get rid of qubrick_handler class

- Remove unnecessary commit

### Testing

- Add tests for repeated nested qubricks with rotation catalyst

- Add xfail to QFT tests

- Fix tolerance for av in comparators

- Minor fixes


## v4.30.5 (2025-11-20)

### Bug Fixes

- All resources except AV working

- AV working, code needs refactor

- Fix issue for handling specific angles for rotation catalyst with symbolic size

- Remove atomic attribute from Parameter

- **active_volume_lookup.py**: Made lookup table entries occupy only one line.

- **active_volume_lookup.py**: Simplified some code as t_cost is the same as reactive_t_cost.

- **coverage**: Coverage and cleanup, removal of unused stuff

- **coverage**: Coverage WIP for #1236

- **coverage**: Increase in coverage per #1236

- **coverage**: More coverage improvements

- **coverage**: More coverage updates

- **cpp**: Minor cleanup

- **cpp**: Start by removing cpp functions we've outgrown...

- **cpp**: WIP first success at c++ rework

- **cpp**: WIP on C++ remap

- **cpp**: WIP removing pybind11

- **expiration**: Push expiration to Dec 2026

- **get_av_from_op.py**: Added 33.75 angle to _get_av_from_qpu_op_ppr_symbolic function.

- **get_av_from_op.py**: Changed divisors to integer divisor for if states in the numeric and
  symbolic get_av_from_qpu_op_ppr function.

- **get_av_from_op.py**: Fixed ppr numeric and symbolic functions for pi/16 and 3pi/16 rotations.

- **get_av_from_op.py**: Removed white space for linting.

- **get_stale_state_count_from_op.py**: Fixed 33.75 and 11.25 identification for the
  _get_stale_state_count_from_qpu_op_ppr function.

- **get_stale_state_count_from_op.py**: Reformatted elif logic.

- **get_stale_state_count_from_op.py**: Reorders thetas to be optimal.

- **MR**: Fixes per MR feedback

- **MR**: Use parameterize, per MR feedback

- **ppm_functions.py**: Updated docs to point to the new note for PPM formula.

- **ppr_functions.py**: Changed import to t_gate_cost rather than the now disused reactive_t_cost.

- **ppr_functions.py**: Fixed typo in docs and improved readability.

- **ppr_functions.py**: Imporved readibility of the _get_3pi_16_ppr_av_cost function formula.

- **ppr_functions.py**: Improve code readability in _get_pi_4_ppr_av_cost function.

- **ppr_functions.py**: Improve doc to provide a link to a note and state how classical interpretion
  must be updated.

- **ppr_functions.py**: Reordered lines the _ppm_injection_cost function.

- **ppr_functions.py**: Updated doc to say corrective measurements rather than reactive.

- **ppr_functions.py**: Updated doc to use or new definition of reactive and conditioned corrective
  measurements.

- **pybind11**: LARGE change: complete removal of pibind11, WIP

- **test_1063_create_get_stale_state_count_from_op_function.py**: Updated
  get_stale_state_count_from_op tests to include new operations.

- **test_1113_y_parity_in_av_cost.py**: Fixed the tests in 1113.

- **test_1113_y_parity_in_av_cost.py**: Updated test for 1113 to use the corrected AV for a single
  qubit Y ppm.

- **test_1209_single_qubit_ppm_av.py**: Updated another deprecated function call.

- **test_1209_single_qubit_ppm_av.py**: Updated from deprecated function call

- **test_native_dialect_numeric.py**: Fixed expected test results to match new AV formulas.

- **test_native_dialect_numeric.py**: Updated hard coded AV in test file such that test passes
  updates to AV costs.

- **tests**: Restore reverse_bitsa and add coverage

### Chores

- Bump version to 4.30.4

- Clean up some pieces of the reworked tests

- Remove Qubrick statefulness

- Removing gate_costs_v2.py

- Update codeowners

- Update codeowners again

### Continuous Integration

- Run examples in serial

### Documentation

- Add 'Built-in Qubricks' tutorial

- Address reviewers' comments

### Features

- **active_volume_lookup.py**: Added references to AV derivation files.

- **ppm_functions.py,ppr_functions.py**: Added doc to link tl formula derivations.

- **test_994_create_get_op_av_function.py**: Add a comment to explain the location of CX and CZ
  gates in the test file.

- **test_994_create_get_op_av_function.py**: Added more tests and fixed test values for new code. CH
  is not a support op also.

### Refactoring

- Minor refactors

- Update code for symbolic AV

### Testing

- Converting to operator norm in one more test

- Use epsilon instead of bits of precision for Ross-Selinger test and update to new operator norm


## v4.30.4 (2025-11-06)

### Bug Fixes

- **reflect**: Handle error_param=None in reflect Qubtick

- **synth**: Fix for not-conditions in rotation synthesis, and re-run notebook

- **USP**: Some fixes for USP, and the characterization notebook, first pass

### Chores

- Bump version to 4.30.3

- Removing unused variable

- Skip tests that require bartiq or sympy

### Documentation

- Add 'Controlled Qubricks' tutorial

- Add allow_multi_qubit_ctrl info

- Remove accidentally added link to QRE reference

### Features

- **notebook**: Characterization notebook, second pass

### Testing

- **synth**: Add a test for the synth fix


## v4.30.3 (2025-11-03)

### Bug Fixes

- Actually use ntz instead of nlz

- Add missing _type_aliases file

- Adding min_val_to_print check for qregs

- Attempt to fix broken test

- Ensure resource estimator is not expanded when constructed with factory function

- Failing test

- Fix some type annotations

- Fixing bug in roll_left and adding verbose check in qubrick

- Fixing tests and updating comments for new code

- Fixing typos, adjusting phrasing, updating warning

- Formatting

- Handle phase fixup correctly

- Make estimators non-expanded by default

- Make tests runnable without Bartiq installed

- Remove tree map example to simplify dependencies

- Remove unreachable code path

- Resolve the bit utils deprecation

- Update usage of children_names

- Updating docstrings, fixing bug where 0 state treated differently

- Using preset instead of filter pipeline

- **archive**: Archive ims_transpilation filter per #1213

- **cleanup**: Remove commented code

- **dagger**: Raise an exception when a daggered compute is used on a qubrick which allocates RAM
  and doesn't release it, per #1211

- **deprecation**: Per MR requirement, re-add potential deprecation warning for Qubits.QFT()

- **flush**: Remove extra pipeline flushes per #1222

- **get_allocs**: Fis get_allocated_qubits per #1224, first pass

- **MR**: Add comments about never_uncompute

- **MR**: Apply feedback per MR

- **MR**: Two small changes per MR feedback

- **pyproject.toml**: Add pylatexenc to qiskit install

- **pyproject.toml**: Remove pylatexenc to qiskit install

- **QFT**: Remove all zero-target phases, unify QFT with Qubits.reflect() and QFT Qubrick

- **qiskit_qpu.py**: Add docstrings for __init__ args

- **qiskit_qpu.py**: Correct device spefication for MPS simulator

- **qubit_interation.py**: Create SwapPushEngine

- **qubit_interation.py**: Don't require matplotlib

- **qubit_interation.py**: Don't require matplotlib again

- **qubit_interation.py**: Get rid of matplotlib objects in function definitions

- **qubit_interation.py**: Remove unneeded import

- **test**: Fix failing test caused by override of >>batch>> filter

- **test**: Fix for test #617, related to changes in #1221

- **test**: Fixes for failing tests in #1224

- **test**: Test for #1211

- **test_1148**: Add copyright

- **witness**: Allow witness to smooth out symmetric Z gates for the AV counter

### Chores

- Add as_basquiat() to docs ref.

- Add needs_sympy where needed for tests that require sympy

- Add tests for multicontrol case

- Adding back in abs func

- Adding docs and updating notebook.

- Adding gidney_lelboew and gidney_relbow costs

- Adding new location for compute_T_rotation_magnitude_approximation_numeric

- Adding sympy back in docs deps

- Adding sympy back in docs deps

- Adding tests and removing unused imports.

- Apply suggestion for gates for states.

- Apply suggestions from MR.

- Attempt docs build fix

- Attempt docs build fix

- Attempt docs build fix

- Attempt docs build fix

- Attempt docs build fix

- Attempt docs build fix

- Bump Bartiq to 0.15.2

- Bump Bartiq version to 0.15.1

- Bump minimum compatible version of Bartiq to 0.15.0

- Bump version to 4.30.2

- Check deprecation shims

- Clarify comment and test.

- Deprecation stubs:

- Deprecation stubs:

- Deprecation stubs:

- Deprecation stubs:

- Don't use bartiq in test.

- Don't use bartiq in test.

- Expected to fail fix av from op stuff

- Ffs

- Ffs

- Fix imports

- Fix KeyError issue

- Fix test and demonstrate lambdify

- Fix test skip

- Fixing typos

- Ignore AI agent files

- Lelbow/relbow fix

- Let's just change one.

- Making things on one line

- Move typing info into args

- Partial eval better example

- Poetry lock

- Reintroduce Bartiq to examples deps group

- Remove future annotations import

- Remove test skip

- Remove unneeded line

- Remove warning

- Remove workaround for ntz as it's no longer required with newer Bartiq

- Removing dead code

- Removing gate_costs_v2

- Removing unused vars/imports and replacing sympy back in optional deps

- Reverting costs for elbows in gate costs

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Trying something silly to see if tests pass

- Undo replacement of lock

- Update descend function

- Update reference doc with better example

- Updating comments

- Using new AV interface

### Code Style

- Fix lint issues

- Improve typing

### Continuous Integration

- Removed unused examples dependencies

- Updated dev-ops/common include reference from 0.0.7 to 0.0.8

### Documentation

- Adding docs changes

- Adding requested language change in Qubricks

- Adding small changes to Testing-Debugging notebook

- Change Return: to Returns:

- Massive docstrings improvements

- More typos

- Remove unneeded docs page

- Rerunning notebook for new outputs

- Update docs

- Update docstring of resources() method

- Update QRE example notebook

- Updating docstrings

- Updating documentation notebooks

- Updating explanation of entangled states in print_state_vectro and print_probabilities

- Updating language based on pair programming

- **dev**: Update developer README

### Features

- Add depth argument to children_names

- Add prototype of high-perf resource evaluator

- Adding verbose option to kwargs for qubrick to use

- Allow passing keywords to sympy.lambdify

- Allow querying children names through children_names property

- Make symbolic estimator expanded by default

- Print state vector for qubits now shows state vectro rather than state vector, also adds
  print_probabilities as an alternative

- Refactor so we do cheap entanglement check first, and make show_entangled the default

- Remove duplicate qbk_control_decomposition file

- **pyproject.toml**: Add pylatexenc as dependency for qiskit

- **qasm3_export.py**: Add cz gates

- **qasm3_export.py**: Add large CCZ gates

- **qasm3_export.py**: Support no target, no control circuits

- **qiskit_qpu.py**: Added comments

- **qiskit_qpu.py**: Added qiskit result object link

- **qiskit_qpu.py**: Allow GPU accelerated MPS

- **qiskit_qpu.py**: Allow GPU accellerated tensor network sims.

- **qubit_errors**: Raise exceptions if Qubrick result qregs are freed before they can be used, per
  #1221

- **qubit_interactions.py**: Add qubit interactions filter

- **test_1190**: Add integration tests for cz gates

- **test_1190**: Add negctrl tests

- **test_1190**: Add tests for cz gates

### Refactoring

- Extract _resources method and improve typing

- Flipping logic in is_symbolic and adding a few more needs_sympy decorators

- Revert as sympy will not be dep.

### Testing

- Add test for obtaining child names of depth > 1

- Adding assertions and checks for warnings

- Adding more coverage, 34 lines left to cover

- Adding tests for print_state_vector on qubits

- Fix tests to use reasonable expression for register sizes

- Initial coverage testing for gidney arithmetic

- Rename variables in conftest to better match their contents


## v4.30.2 (2025-10-22)

### Bug Fixes

- Add http://www.w3.org/2000/svg to ignored urls

- Broken from symbolic comparators

- Broken from symbolic comparators

- Broken from symbolic comparators

- Broken test for comparators

- Lint

- **active_volume_lookup.py**: Accidently left some bridging cost addition in the table, these may
  be added back later.

- **active_volume_lookup.py**: Added optimised cost for Y pi/4 PPR rotations. Also updated table
  cost to use Y state distillation cost instead of hardcoded 3 cost (this was previously missed).

- **active_volume_lookup.py**: Found optimised costs for ctrl Y and sqrt y, also update other
  clifford formulas to use the distillation of Y states explicitly.

- **active_volume_lookup.py**: Update entries in the av look up table to agree with the new
  formaulas.

- **active_volume_lookup.py**: Updated an incorrect comment.

- **active_volume_lookup.py**: Updated reactive T measurement AV formula to be more optimal.

- **cleanup**: Comment removed

- **example_swap_push_filter.ipynb**: Use Qubits()

- **get_av_from_op.py**: Fixed the cost of single qubit y ppms. Now costs 5 av instead of 7.

- **get_av_from_op.py**: Single qubit Y measurement cost 3 not 5 as bell measurements are free.

- **ppm_functions.py**: Fixed the dirty ppm function formulas to include y_parity in the return
  cost.

- **ppm_functions.py,get_av_from_op.py**: Moved new case logic from _get_av_from_qpu_op_ppm in
  get_av_from_op.py to _get_ppm_av in ppm_functions.py, this solves an issue with symbolics and a
  testing issue.

- **ppr_functions.py**: Reverted back to original function for pi/8 rotations as X injection does
  not work for T gates.

- **ppr_functions.py**: Update to _get_pi_4_ppr_av_cost function such that we use a more optimised
  formula.

- **reflect**: Convert all known symmetric Z gates to Qubits.reflect()

- **reflect**: Re-add reflect to decomps

- **swap_push.py**: Added copyright notices

- **swap_push.py**: Flushed swaps corrected

- **swap_push.py**: Formatting and comments

- **swap_push.py**: Write operations support

- **swap_push_filter.py**: Get rid of unneeded checks

- **swap_push_filter_example.ipynb**: Cal -> can

- **symbolics**: Better workaround for symbolics issues

- **symbolics**: Two small symbolics fixes

- **test**: Tiny test fix

- **test_1187**: Delete repeated test

- **tests**: Several test fixes

### Chores

- Bump version to 4.30.1

- Don't define symbolic a twice

### Documentation

- Address reviewers' comments

- Fix docstring for .

- New 'Uncomputation context manager' tutorial

- Ran code cells

- Updated final code example to be self-sufficient

- Updated kernel to not include images

### Features

- Added pi/16 and 3pi/16 PPR rotations as well as some updates to the AV lookup table.

- **active_volume_lookup.py,stale_state_count_lookup.py**: Added optimised ctrl H to av and ssc
  lookup tables.

- **active_volume_lookup.py,stale_state_count_lookup.py**: Added rx, ry, rz support for theta = 90
  as this are just control paulis.

- **get_av_from_op.py**: Updated _get_av_from_qpu_op_ppm such that single qubit x and z ppm have no
  AV.

- **get_stale_state_count_from_op.py,stale_state_count_lookup.py**: Added stale state count formulas
  and logic for 3pi/16 PPR rotations.

- **ppm_functions.py**: Updated dirty ppm functions to now include the block cost of bridge qubits,
  also implemented a small cost optimisation.

- **ppr_functions.py**: Added a comment to mention that ppms outcomes must be interpreted
  differently for y_injections.

- **ppr_functions.py**: Change get_pi_4_ppr_av_cost to calculate both methods of doing the pi/4
  rotation and then return the minimum cost, as this is more robust and has a minimal impact on the
  computation cost.

- **ppr_functions.py**: Update pi/4 rotation function to use one of 2 formulas depending on y
  parity.

- **ppr_functions.py**: Updated pi/8 function to use X or Z for state injection.

- **swap_push.py**: Implement calling filter from string

- **swap_push.py**: Implement swap push filter and tests

- **swap_push.py**: Push to end by default

- **swap_push.py**: Support qpu.write()

- **test_1187**: Add read() test

- **test_1209_single_qubit_ppm_av.py**: Added test for new single qubit and 2 qubit ppm
  optimisations.

### Refactoring

- Comparator calculation refactor


## v4.30.1 (2025-10-16)

### Bug Fixes

- Added needs_sympy in appropriate places

- Fix get_instructions with format="asm-stack" for SymbolicQPU

- Fix outdated import

- Fix test with scipy

- Typos

- **cicd**: Per #1203 make examples optional

- **lock**: Add updated poetry.lock

### Chores

- Bump version to 4.30.0

- Change imports from relative to absolute

- Remove old tutorial symlinks and unneded examples

### Code Style

- Style fixes

### Documentation

- Update docstring for capture_instructions

### Features

- Add negation to Parameter (both new and old)

- Correctly count rotations and other gates when preparing rotation catalyst state

- Support angles >= 360 in symbolic rotation catalyst via padding

### Refactoring

- Move conditions to a separate module

- Remove _expr suffix from condition functions and use them in rotation catalyst state prep

- Simplify class hierarchy for conditions

### Testing

- Add missing test

- **lock**: See what happens if there's no lockfile


## v4.30.0 (2025-10-10)

### Bug Fixes

- Address parallelisation failure

- Address sean's comments

- Answer code review comments

- Eliminate qiskit warning deprecation in test

- Fix lint problems

- Fixed AV calculation for symbolics

- Lint

- Remove warning: UserWarning: Returning QubrickCosts objects from estimate/unestimate methods is
  deprecated...

- Skip test if antlr4 not installed

- Test_811_qasm_export_filter.py qiskit warning

- **detect_entanglement**: Fix for #1178

- **filtername**: Handle failing tests in transition from >>qpu>>, per #1139

- **formatting**: Revert reformatting changes, leaving (I think) the relevant changes intact, with a
  few fixes.

- **minor**: Fix witness setup to include bit-sim

- **MR**: Add a test as requested

- **MR**: Fix per MR feedback

- **MR**: Reworked all tests to keep the changes just as needed and make deprecation easier

- **scatter**: Cleanup for scatter assert

- **scatter**: Restore qubit masks for scatter Qubits, with a fix for numpy int-poisoning

- **test**: Fixed an AV bug so now this test succeeds in failing again.

- **test**: Small adjustment to test 614 for #1139

- **tests**: Revert all tests to main

- **witness**: Fix for witness counter treatment of conditional PPRs per #1155

### Chores

- Add a more general test

- Added >>state-vector-sim>> to speed_tests/small_circuit_speed_test.py

- Added >>state-vector-sim>> to test_205_feedforward.py

- Added >>state-vector-sim>> to test_269_feedforward_demo.py

- Added >>state-vector-sim>> to test_269_feedforward_demo.py

- Added >>state-vector-sim>> to test_767_jump_back_iteration

- Added >>state-vector-sim>> to test_767_jump_back_iteration

- Added >>state-vector-sim>>, >>bit-sim>> and >>clifford>> to test_339_postselect.py

- Added >>state-vector-sim>>, >>bit-sim>> and >>clifford>> to test_339_postselect.py

- Bump version to 4.29.1

- Eliminate deprecation warning for truncate angles test

- Removed return notes

- Universal -> Uniform State Preparation

- **review**: Apply 1 suggestion(s) to 1 file(s)

### Code Style

- Minor changes

### Continuous Integration

- Run tests in parallel

- See if limiting to just one runner fixes CI error

### Documentation

- Add new 'Quantum Arithmetic Data Types' tutorial

- Address reviewer's comments

- Address reviewers' comments

- Clean up Qubricks API docs

- New 'Quantum Arithmetic' tutorial

- Replace old filter names with new ones

- Update the docstring explaining caching strategy

### Features

- Add global phase invariant op norm

- Add tests for globally invariant op norm

- Narrow down numeric types when extracting value from parameter

- Working version of new AV for symbolics

### Performance Improvements

- **witness**: Double speed of witness test case by changing operator overload

### Refactoring

- Remove gate_costs_v3 and update gate_costs_v2 instead

### Testing

- Add AV reference assert to RS QRE trends test

- Add missing tests

- Add test for symbolic ppm

- Added test for slope of Ross-Selinger T-count costs

- Added tests for naughty theta values and fixed bug

- Increase range for RS synth tests

- Loosen RS synth absolute error bound for controlled RS qubrick

- **MR**: Add requested tessting


## v4.29.1 (2025-09-29)

### Bug Fixes

- Avoid registering unbound "idx" parameter when using rotation catalyst with symbolic QPU

- Short term fix for the allocation bug in **rounding**: Fix rounding error in #1188

### Chores

- Bump version to 4.29.0

- Merge master

### Documentation

- Fix docstrings and comments

- Improve register_dummy_parameter docstring

### Features

- Add ignore_dummies argument

- Allow register dummy parameters for symbolic QPU

### Refactoring

- Use Parameter object instead of string in register_dummy_parmmeter

### Testing

- Check that adding dummy param does not prevent compilation

- Improve testing of dummy param registration


## v4.29.0 (2025-09-26)

### Bug Fixes

- Accounting for case where cond_reg_deprecated could be an integer, and checking that first before
  checking it is 0

- Add extra line for rendering docs

- Add tie breaker for equal probability state vectors to select to state vector with more non-zero
  amplitudes

- Added parameterization to tests rather than loops

- Adding error when AsynReadResult used directly as boolean

- Adding fix for printing state vector with bit-qpu when no qubits defined

- Changed from userwarning to deprecationwarning

- Correct docs notebooks

- Correcting notebook to remove excess information

- Ensuring dummy qubrick uses its keywords

- Ensuring kwargs are passed explicitly

- Ensuring tests pass

- Error on pydantic none fields

- Intermediate fix for off-by-two comparators

- Invalid number of reset qubits

- Lint

- Lint

- Lint.

- Missing conditional statement

- Moving normalization logic to python, adding tests for normalization

- Removing another loop from a test

- Removing debugging

- Removing mutable obj fromm default argument

- Removing testing code

- Removing unused kwargs

- Tests.

- Typos, adding option to turn off normalization, adding adjustment to make the first element of the
  state vector positive

- Undoing unintentional change

- Updating and adding tests

- Updating warning message, and checking entanglement with probabilities rather than amplitudes

- **arg**: Remove use_mod arg from integerize_truncated_rot_angle(), as it never changes the output

- **cleanup**: Docs and warnings

- **cleanup**: Remove commented print

- **cleanup**: Simplify scatter to always be a tuple

- **composite**: Fix for failing CompositeReg test also a lint fix :]

- **deprecation**: A suggestion for #1177

- **int**: Fix the case where integer angles are passed

- **lint**: Fix a linting error in the speed test

- **lint**: Minor lint fix

- **modulo**: Minor fix to optimization in #1106

- **test**: Test fix for list/typle checking in #1183

- **use_mod**: Replace legacy code with new code, and ignore use_mod

### Chores

- Add docs page and script for generating.

- Better exception catching for qubrick discovery

- Bump version to 4.28.6

- Cleaning up orphan comments and misc. refactors

- Combining get_known_discrepancies conditions

- Filtering objects for getmembers

- Fix formatting

- Fixing linting errors

- Fixing test name

- More deliberate error raise for walk submodule

- More minor refactors.

- Moved test back into class

- Moving discrep. page to private

- Moving page for better discoverability

- Pulled in master

- Reduce warning with mismatched @implements signature to a deprecation warning to reduce visibility

- Remove callable bucket

- Remove debugging code

- Remove try/except in _iter_module_objects

- Remove unnecessary bound from typevar.

- Removing resets from tests and consolidating tests and using BIT_SIM preset

- Removing stray print debugging

- Respond to diff comments

- Respond to diff comments

- Respond to diff comments

- Responding to diff comments

- Rewriting docstring for qubrick __init__

- Simplify record add.

- Simplify walk submodules

- Undoing formatting changes

- Updating type-hint return for known_discrepancies

### Documentation

- Add 'Auxiliary Qubit Management in Qubricks' tutorial

- Add cross-references between tutorials

- Adding better descriptors for fields in DiscrepancyRecord

- Address reviewers' comments

- Delete user guides

- Minor text edits

- Remove user guides and old tutorials replaced with new ones

- Updated getting started import instructions

- Updated release instructions in README.md

- Updated sidebar nav color

- Updating docstirng for Qubit.pull_state()

- Updating documentation

- Updating documentation and tests

### Features

- (WIP) add more test cases

- (WIP) add test for PPO weights

- (WIP) added tests for rotation angles and checking all single ops in the lookup

- (WIP) remove PPR buckets for clifford/non-clifford buckets

- Add all the missing fields except the ppo average weights and aggregates

- Add in ppo weights

- Add passing tests for av count and bucketting

- Add support for variable length argument lists

- Add support in bit-qpu for print_state_vector

- Address reviewer comments

- Change relative imports to absolute for consistency

- Delete commented-out function names

- Deprecate unused args in metrics

- Discrep. tracking for sqre/nqre mismatch

- Document average PPO function

- Fix incorrect typing

- Made buckets for AV counts

- Make non_strict_av_func private

- More tests, now covering all Dylan's use cases

- Remove reference to checking old values

- Remove single controlled rotation from cliffords

- Remove support for direct AV evaluation of multi-target Toffs

- Remove unnecessary num_targets_check

- Reorder imports to avoid circularity

- Simplify metrics logic

- Symbolic filters further progress

- Update the documentation to make the PPR bucketing clear

- WiP version of symbolic filters with new AV

### Performance Improvements

- Change bitstring to num calculation to python builtin

- Optimizing pull state on a reigster by reimplementing pull state filter on a particular register
  in C++

- Rework print_state_vector when there is only one amplitude to improve performance specifically
  with bit-qpu

- **mask**: Additional speedup for the most common mask() cases for #1183

- **mask**: First-pass speedup for Qubits.mask() per #1183

- **rotations**: First pass of optimization in #1106, with a speed test

- **test**: Activate this optimization carefully

### Refactoring

- Added explicit checks on kwargs

- Cond_reg to cond_zip

- Fix argument order for `ConditionedGateBase` and derived

- Further cleanups

- Further refactor in symbolic filters

- Further refactor in symbolic filters

- Making dataclass frozen in registry.py

- Minor cleanup

- Moved to pydantic dataclass

- Remove redundant import for qubrick discovery.

- Removed relative imports

- Simplify membership check for dataclass obj

- Simplify symbolic compilation

### Testing

- Adding test for the transitional error messages

- Adding tests

- Adding tests for optimized pull state

- Adding tests for QASMExportFilter to fill out coverage

- **ladder**: Add a failing test for #1155

- **old_vs_new**: Comprehensive testing and comparison of the old vs. new methods


## v4.28.6 (2025-09-10)

### Bug Fixes

- Add missing seed

- Add phase gradient via catalyst circuit oracle

- Address bug in QFT using phase gradient qubrick

- Apply Dylan's suggestions

- Catalyst syntax in example nb

- Change adder variable name

- Deg unit import

- Delete unused helper function

- Delete unused import statement

- Reorg phase gradient example notebook

- Reverse QFT class back to the original implementation

- **coverage**: Remove autogenerated QASM3 Parser from coverage

- **docs**: Remove link to deleted Witness Counter Deep Dive tutorial

- **error**: Improved error messages for phase gradient

- **highwater**: Fix for highwater witness bug in #1164, bug introduced in !667

- **lock**: Re-add a line which got merged out

- **phase_grad**: WIP fix for Schwinger part 3 #1158

- **witness**: Fix error in #1164 and ALSO update test #1004 so it fails before the fix

### Chores

- Apply review comment

- Bump version to 4.28.5

- Merge master

### Continuous Integration

- Pin poetry version

### Documentation

- Address reviewers' feedback

- New 'Testing and Debugging' tutorial

### Features

- Add test and example for sequential phase gradient

- Allow QFT fallback, simplify for loop logic

- Include more abstraction for phase gradient via catalyst state

- **locks_and_docs**: Some minor tweaks, and better function call documentation


## v4.28.5 (2025-09-04)

### Bug Fixes

- Add unstable marker to Parameter class

- Catch warnings when using QubrickCosts at module-level

- Improve error message when formatting stream that is None

- **coverage**: Moved old_conversion_code into archives for #1154, adjusted tests, all tests WB
  pass, and WBA QApps still pass unmodified.

- **MR**: Fix for #1147 per MR feedback

- **qubits**: Fixes for qubits release detection, per #1147

- **synth**: Fix for synthesis filter issue in #1142

### Build System

- Added examples dependency group

### Chores

- Adding gate costs back....

- Bump version to 4.28.4

- Moving compute_circuit_volume_arbitrary_unitary to get_av_from_op

- Remove accidentally committed basquiat file

- Remove old av notebooks

- Removing deep dive notebook and gate_costs.py

- Updated bartiq dependency for examples

- Updated poetry.lock

### Continuous Integration

- Add examples test job

- Added graphviz installation to examples job

- Allow most jobs to be interruptible

- Ensure poetry installs right groups in test jobs

### Documentation

- Address reviewers' comments

- Fixes/removed old example notebooks and scripts

- Moved broken examples to examples_on_hold

- New 'Simulating Workbench Programs' tutorial

- Removed unneeded notebooks and script

### Testing

- Remove bare call of shor_sample in test_strdemo

- Removed test_strdemo.py

- **examples**: Added ability to run .py example scripts as tests

- **examples**: Fixed simplest issues in example scripts


## v4.28.4 (2025-08-26)

### Bug Fixes

- Fix handling of zero-target Z and phase gates in >>unitary>> filter

- Reorder imports

- **cicd**: Skip over intermittent crash in rotation synth

- **cicd**: Streamline build more

- **cicd**: Testing CICD synthesis crash

- **testfiles**: Move output files from #1122 to ./output folder per #1135

- **yml**: Restore the yml to the main version

### Chores

- Bump version to 4.28.3

### Documentation

- Address reviewers' comments

- New 'Configuring Program Execution' tutorial

### Features

- Add need_basquiat_adapter helper

- Split Qubrick labels in circuit diagrams into two lines

### Testing

- Use need_basquiat_adapter for tests of symbolic resource estimators


## v4.28.3 (2025-08-23)

### Bug Fixes

- Failing qapps test

- **av_ops**: A few small fixes to the AV witness counter

- **jump**: Fix for jump opcode checking

### Chores

- Add wrapper function for get_av_from_restructured_op

- Alter simple to gate_counting for cost format

- Bump version to 4.28.2

- Do not suppress warning in non-strict case.

- Refactored the optional Basquiat import

- Remove need for cast function for baquiat

- Update decomposition rule

### Continuous Integration

- Fixed macos build issue


## v4.28.2 (2025-08-21)

### Bug Fixes

- Avoid import to pytest in needs_xxx decorator factory

- Do not yield av warnings if no av is requested.

- Previously failing tests.

- Turn off av counting

- Witness counter warnings for toffs

- **cicd**: Add scipy to the CI/CD build for docs

- **docs**: Fix link to getting started

### Chores

- Bump version to 4.28.1

- Merge master

### Continuous Integration

- Add explicit image specification for macos jobs

- Stop calling different python commands

- Updated dev-ops/common include reference from 0.0.6 to 0.0.7

### Documentation

- Address reviewers' comments

- New 'Uncomputation' tutorial


## v4.28.1 (2025-08-20)

### Bug Fixes

- Adapt column counting such that when there are non-consecutive qubits in the operation, it counts
  as a use for drawing purposes

- Add check for whether the space between qubits has been used in a previous operation to determine
  the latest usage

- Adding tracking for more full column, but no direct qubit addressing operations

- Allow multiple phase gradient

- Change start gate to z, reverse bit order

- Changing the padding factor and labels with no operations are removed

- Ensure empty labels at end of circuit are not expanded

- Fix indentation that was excluding some instructions, rework logic such that operations on
  different qubits don't artifically expand the width

- Formatting

- Make sure nops get counted in the operation width

- Minor edits for test file and lint

- Modify naive phase gradient and phase gradient via catalyst state classes

- OP_qc_swap is not being used and yet not having it imported somehow broke the docs. Nothing makes
  sense.

- Remove print statement, fix assumption when getting all_qubit_mask

- Reorganize conrolled naive phase gradient test to include checks on the entire matrix

- **assert**: Per feedback, require assert for overlapping |

- **assert**: Re-add overlap assert, per collaborative feedback

- **cicd**: Add basquiat-adapter to extras to fix test:coverage job

- **cicd**: Add more optional references to basquiat-adapter

- **cicd**: Add pyyaml as a non-optional dependency to fix builds

- **cicd**: Allow mypy lint to fail gracefully

- **cicd**: Attempt to fix poetry issues

- **cicd**: Minor fix for docs build in cicd

- **masks**: Minor fix for mask overlap checking

- **MR**: Tiny fixes per MR feedback

- **operators**: New tests and substantial fixes

- **poetry**: Update poetry lock file

- **test_name**: Rename test to issue number

### Chores

- Add -p no:warnings flag in coverage job

- Adding additional tests for _get_magnitude_approximation_av_from_bits

- Adding get_av_from_op to ims_transpilation.py

- Adding test with wrong extension.

- Bump version to 4.27.1

- Fix lint

- Making get_magnitude_approximation_av_from_bits private

- Moving imports to top of file for test.

- Remove active_volume_lookup_v2 from
  psiqworkbench/resource_estimation/witness_counter/witness_metrics_functions.py

- Remove old count av logic

- Rephrease comment docstring for PPR magnitude function.

- Responding to MR comments.

- Revert function to not break api for magnitude approx.

- Simplifying test and clarifying docstring

- Split magnitude approximation av calculation.

- Update comments

- Update psiqworkbench/compilation/filters/composite_filters/ims_transpilation.py

- Update tests/test_912_debugging_witness.py with updated av logic.

- Updated poetry.lock

### Continuous Integration

- Update docs:deploy:prod dependency

### Documentation

- New 'Qubricks' tutorial

### Features

- Add controlled naive phase gradient unitary equivalence test

- Add helper function to classically compute catalyst state

- Add new names for simulation filters

- Add padding to fit long label names if needed

- Add phase gradient example notebook

- Add test for phase gradient circuits

- Draw format for qpu obj

- Implement phase gradient via catalyst state class

- **operators**: Adjust overloaded QPU operators per Sean suggestions, just to test. All
  back-compatible, all tests passing

### Testing

- Added WBA as explicit test dependency


## v4.27.1 (2025-08-14)

### Bug Fixes

- Fix needs_sympy import

### Chores

- Add generic warnings to check_warnings.py

- Add install lxml to gitlab yml

- Add statistics to mypy report

- Add txt-report to mypy output

- Add || true

- Bump version to 4.27.0

- Fix artifacts section

- Fix pyproject

- Remove &&

- Remove backslashes

- Remove conftest left over after the merge

- Remove level reports and fix rules

- Remove statistics in mypy

- Update Adders to match interface

- Update lock

- Update lock file

### Continuous Integration

- Add mypy to gitlab ci

### Documentation

- Address reviewers' comments

- New 'Controlled Gates' tutorial

- Publish new tutorials and deep dives

### Testing

- Adds needs_sympy and needs_bartiq for simpler test skipping


## v4.27.0 (2025-08-12)

### Bug Fixes

- Restore import of compile_symbolics_costs in test_helpers

- Use "active_volume" key instead of "total_av"

- **ppm_functions.py**: Account for parity in y weight for av

- **ppr_functions.py**: Account for additional Z weight in ppr injection.

- **test_994**: Add y parity to rotation av checks

- **test_native_dialect_numeric**: Update PPR and Rotation AV costs.

### Chores

- Bump version to 4.26.1


## v4.26.1 (2025-08-11)

### Bug Fixes

- Add handling for more arguments in class, but must have defualt. fix adder interfaces to have the
  same name to satisfy the conditions of the interface checker.

- Fixing qubrick injection demos

- Grammar and spelling

### Chores

- Bump version to 4.26.0


## v4.26.0 (2025-08-11)

### Bug Fixes

- Add CompiledRoutine to except block

- Add missing __all__ field to resource_estimation.qre.__init__

- Add missing Any import

- Add phase gradient qubrick to QFT qubrick

- Add resource_estimator to __all__

- Adding lelbow and relbow for av lookup in tests

- Allow docs to build when bartiq is not installed

- Attempt to fix pipeline

- Broaden the class of warnings ignored in tests

- Docs build adding placeholder function

- Fix broken docs build

- Fix lint errors

- Fix message pattern in ignore_unstable_warnings

- Fix module name in rotation_utils deprecation warning

- Fix typo

- Fix typo

- Fix typo in import

- Get_total_costs for witness counter now has desired behavior

- Improve how registers are filtered out in QREF conversion

- Invalid variable name

- Lint

- Lint

- Lint copyright

- Ommit message in ignore_unstable_warnings

- Place import-related try-excepts near top of the file

- Remove duplicated ignore_unstable_symbolic_warnings function

- Remove extra whitespaces

- Remove filtering warnings from gate_costs_v2 module

- Remove trace output.

- Remove unused imports

- Updating non-intuitive behavior in get_total_cost and fixing add bug

### Chores

- Add docstrings to public methods

- Add error_param per rotation

- Add xfails for ppr tests

- Added minus sign cases for PPR tests

- Added test to verify PPR with same angle but negated yields same AV

- Adding all AV tests as described by Dylan

- Adding av tests

- Adding docstrings for Op class.

- Adding test for ppr neg angles.

- Attempt to fix check_project_configs.py

- Attempt to fix check_project_configs.py

- Better exception handling for try/except block in notebook

- Bump bartiq version

- Bump version to 4.25.2

- Clarify arg_sig to argument_signature

- Cleaning up tests in 1042 test file

- Deleting commented decomposed_witness

- Deleting non-functional code.

- Globally disable warnings about unstable symbolics in tests

- How in the hell does changing this break tests in completely unrelated places

- Import * changed to explicit import

- Import Callable in notebook.

- Made op.py to _op.py and moved all to init

- Putting if flag counts back for failure

- Refactor default metrics functions

- Remove comment psiqworkbench.resource_estimation.witness_counter.witness_metrics_functions
  import... from tests

- Remove commented out import.

- Remove commented-out needs-compilation message code

- Remove dangling comment

- Removed imports from test_771_independent_metrics_counter.py

- Removed validate_witness function in favor of witness.validate, added some TODOs to be addressed
  post joint review session with @vrusso, @acaesura, and @ssim

- Removing assert false from is_cost_event

- Removing assert false from is_cost_event

- Removing commented out line from witness and highwater function from EJ note

- Removing commented out resource field

- Removing commented out resource field

- Removing extranous cells from av notebook

- Removing something that is not used

- Ripping out anything with an if_flag in lookup.

- Throwing all into init for witness counter

- Update av tests based on comments

- Updated test 914 to use new AV functions

- Updated tests in 1042

### Code Style

- Tidy-up imports, fix docstrings and add type hints

### Documentation

- Add docs on QRE interface

- Add docstring for resource_estimator function

- Add docstring for SymbolicResourceEstimator

- Correct info about default backend in docstring

- Fix typos in docstring of _SymbolicEstimatorBase

- Improve docstrings and typing

- Improve docstrings in Numeric estimator

- **readme**: Added pip config instructions

### Features

- (WIP) add black box counting to the metrics witness

- (WIP) get QREs working with the witness metrics

- (WIP) making some changes to the underlying framework

- (WIP) most of the tests now working

- (WIP) updates to witness counter and tests

- [WIP] better formatting for metrics witness

- [WIP] trying out a new idea

- Add active volume witness

- Add aggregate method to symbolic estimators

- Add assert_resources_equal function

- Add basic implementation of numeric resource estimator

- Add default metrics functions

- Add demo notebook for AV witness

- Add filename option to some resource estimator methods

- Add phase gradient qubrick

- Add ResourceEstimator protocol

- Add support for multiple metrics (WIP)

- Add test helper for disable unstable API warning for symbolics

- Add unstable feature's name to unstable API warning

- AV black boxes now working properly

- Enable importing resource_estimator from top-level package

- Get all tests working

- Get highwater integrated into the new system

- Implement creating Basquiat graphs from symbolic programs

- Implement ResourceEstimator protocol for symbolic qpus

- Inlclude pprs and ppms in numeric resource_estimator

- Introduce separate protocol for symbolic resource estimators

- Make numeric estimator resource name match the symbolic one

- Minor fixes to the witness counter (WIP)

- Remove ActiveVolumeWitness from __all__

- Support QubrickCosts and symbolic comparisons in assert_resources_equal

- Update native dialect tests

- Use resource_estimator in test helpers

- WIP updates to the general cost witness

- **get_av_from_op.py**: Improve op handling

### Refactoring

- Move AV calculation from sympy backedn to resource estimators

### Testing

- Correctly skip symbolic res. est. tests when Bartiq is unavailable

- Move skip_without_bartiq and bartiq_only to test_helpers

- Replace usage of pytest.skipif with skip_without_bartiq

- Use assert_resources_equal instead of deprecated comparison

- Use Bartiq resource type instead of looping through ADDITIVE_RESOURCES

- Use expanded=True in swap tests


## v4.25.2 (2025-08-06)

### Bug Fixes

- Add missing \\ to awk command

- Add version bump to pyproject.toml in set_version.py

- **catalyst**: Add ability to suppress gate playback during qubrick recompute

### Continuous Integration

- Make coverage job non-blocking for MRs

- Only run qdk downstream when pushing to default branch

### Documentation

- Address reviewers' comments

- Address reviewers' comments

- New "Basic Gates" tutorial

- New "Measurements" tutorial


## v4.25.0 (2025-07-31)

### Bug Fixes

- Adding Qubrick inheritance to the test classes

- **color**: Gray change per MR

- **get_dag_from_qpu.py,test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**:
  Renamed qubits_engaged to active_qubits and qubits_removed to inactive_qubits.

- **ppr-color**: Fix for PPR colors per #1114

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Removed comment out code,
  updated doc strings, updated attribute names.

- **version**: Manually fix pyproject.toml version.

### Chores

- Bump version to 4.24.0

- Change USP to universal state preparation

- Cicd permission issue

- Fix griffe error

- Fix griffe issues

- Fix review comment

- Fix review comment

- Review comment fix

- Update merge request description template

- Updated MR template based on review feedback

### Code Style

- Typos

### Continuous Integration

- Added coverage reporting to test jobs

- Make downstream:psi_qdk manual for scheduled pipelines

- Updated dev-ops/common include reference from 0.0.5 to 0.0.6

### Documentation

- Add development workflow to README

- Add private members to qubricks and show source to all

- Add specific qubricks to python api

- Address review comments

- Address reviewers' comments

- Make private members show in python api

- New "Execution Model" deep dive

- New "Qubits Data Type" tutorial

- Only show _compute out of private qubrick members

### Features

- Add error when class does not match its specified interface

- Refactored code in get_dag_from_qpu.py and avg_qubit_estimator.py into a function in utils called
  get_active_and_inactive_qubits_for_op.

- Removed count_1_bits function and replaced with python function .bit_count().

- **get_dag_from_qpu.py**: Adds activated_qubits and removed_qubits as attributes to vertices in the
  DAG.

- **get_dag_from_qpu.py**: Improve code quality and updated attribute name for qubits_activated to
  qubits_engaged.

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Added tests for the
  assignment of the new activated and removed qubits attributes.

- **test_1093-add-acted-on-qubits-to-dag-representation-of-circuits.py**: Made try optional based on
  igraph import.

### Testing

- Adding initial suite of tests for interface checking

- Adding test to handle multiple paramters and multiple interface with different methods

- Fixing how tests are structure to pass CI


## v4.24.0 (2025-07-21)

### Bug Fixes

- Add copyright header

- Better error message when missing filters required for drawing

- Broken test

- Modernize matching in check-warnings script

- Reduce warning count for negative value

- Remove get_trace

- Remove rs-synth-filter from witness counter

- TestQbk warning trigger

- Typo in pyproject.toml

- Use built in typing

- Using QUInt over QInt for optimized multiply in test

- Using QUInt over QInt for optimized multiply in test

- Using QUInt over QInt for optimized multiply in test

- **allocation**: Fix for TLB reallocation bug caused when alloc and free are not in the same
  instruction set

- **build**: Fix legacy runtime dependencies

- **cicd**: Cleanup loose testing structures

- **cicd**: Fix error in psi-liqtr import, and also try adding wba

- **cicd**: Fix punctuation error

- **CICD**: Minor tweaks to finish off #1098

- **cicd**: Remove check for WBA install success

- **cicd**: Testing override of env vars

- **cicd**: Testing Shelob's new pip.config file

- **CICD**: Trivial blank line added to try to bump the CICD system

- **cicd**: Try overriding PIP_CONFIG

- **cleanup**: Remove debugging tags

- **cleanup**: Remove unnecessary diffs

- **lock**: Poetry lock

- **macos**: Try generating the missing file

- **pip**: More debugging prints

- **pull**: Fix for #1088

- **stale_state_count_lookup.py**: Fixed sqrt T stale state count.

- **test**: Cleanup the the old test_hydrogen()

- **test**: Cleanup, remove unused imports

- **tests**: Add WBA and QApps tests to extras

- **trivial**: @sam Added a space because commit-lint forced the tests not to run, and I can't run
  them manually.

- **trivial**: Add a blank line to force the pipeline to build

### Build System

- Add psi-liqtr to setup_legacy

### Chores

- Accidentally removed metrics_stack.

- Add additional op name checks for test_catalyst

- Add additional op name checks for test_catalyst

- Add check on instructions op stream

- Add copyright header

- Add debug line

- Add dependencies in ci

- Add deprecation warning for QPU.set_zero

- Add print instructions to Qubrick notebook

- Add requests library

- Adding test 760 back

- Address bitwise not for Python 3.16+

- Bump version to 4.23.0

- Change psi_pyliqtr to psi_liqtr

- Changing name for Parameter for sympy register size from N to reg_size

- Fix gitlab ci

- Fix macos reset fail

- Fix mkdocs.yml

- Fix pipeline failure

- Fix pyproject.toml versions

- Fix radix round warning

- Fix warnings for alloc_result

- Fix witness stack warning

- Fix witness stack warning

- Fix witness stack warning

- Fix wrong name

- Putting unused ops_asm2 var back in test.

- Qreq compare warning

- Release ancillae deprec addres.

- Remove allow of negative for unsigned input for Madd

- Remove cross-validation scripts

- Remove other unneeded functions

- Remove other unneeded functions

- Remove other unneeded functions

- Remove other unneeded functions

- Remove other unneeded functions

- Remove other unneeded functions

- Remove profile_mode from eccshors test

- Remove remnants of get_trace

- Remove remnants of get_trace

- Remove remnants of get_trace

- Remove ResourceEstimator class

- Remove speedscope and export trace functions

- Removing notebooks for tracer

- Responding to diff comments.

- Update psi-liqtr dependency

- Update rot count check for test in res_est_tweaks and cleanup.

- Use print instructions for test 423

- Use qc.metrics() for print in test_440

- Use qc.metrics() for print in test_440

### Continuous Integration

- Add check warnings to gitlab ci

- Add image link check

- Add script to check for broken links

- Added downstream test for integration test repo

- Make check_links new stage that allows failure

- Make warnings check allow failure

- Move docs-warnings to docs stage

- Remove old downstream trigger jobs

- Update downstream:psi-qdk rules to run on main and scheduled pipelines

- Updated downstream psi-qdk trigger branch target

- Updated psi-qdk downstream job for new project location

### Documentation

- Add new page to the navigation under Private

- Add note about num_qubits being upper bound, not exact

- Address Ian's comments

- Apply 1 suggestion(s) to 1 file(s)

- Clean up unused images

- Fix broken filter pipeline links

- Fix deprecation warning

- Fix SMS's comments

- Fix syntax warning

- Fix typos

- Get rid of cpp warnings

- Get rid of unnecessary outputs in notebook

- Move check_links to scripts folder and add max_retries

- New "QPU Object" tutorial

- New "Write your first Workbench program" tutorial

- Quantum engine -> quantum processing unit

- Remove duplicates in stream_ops

- Remove explicit reset call

- Remove many warnings and move make_symlinks.sh

- Update installation guide

- **heap**: Add docstrs for all heap methods

- **readme**: Update release doc section

### Features

- Add script to detect warnings in mkdocs

### Refactoring

- Changed pyliqtr dependency to psi_pyliqtr

### Testing

- Add failing test

- Fixed test broken by new error thrown

- Have fun debugging this one guys

- Remove use of sympy.sympify

- **CICD**: See if the psi-liqtr. This is only a test.

- **MR**: Add requested test which fails without #1088 fix

- **poison**: Add a failure to show that WBA is being tested

- **Schwinger**: This code catches the double-free bug BUT ALSO passes our entire testsuite


## v4.23.0 (2025-07-01)

### Bug Fixes

- Added a link to a note that explains stale states.

- Change instances of .cnot to .x

- Cherry-pick qft_increment deprecation fix.

- Minor typos fixed in notebook

- Refactored stale state counting code into a seperate folder. Also make all stale state count
  import values set in 'stale_state_count_lookup.py', and added
  '_get_multi_target_stale_state_count' to the init file in stale_state_functions.

- Test in 319 qft compute

- Test in 319 qft compute

- Typos

- Update check_zero_fields to have a parameter called property_name, and update tests and code to
  supply this parameter.

- Updated name of _unsupported function to _unsupported_op.

- **__init__.py**: Added default_ross_selinger_av to init file.

- **av_functions/__init__.py**: Updated _unsupported_av to _unsupported.

- **avg_qubit_estimator.py**: Add copyright

- **avg_qubit_estimator.py**: Add formula to docstring

- **avg_qubit_estimator.py**: Add qubits.release thread to docstring

- **avg_qubit_estimator.py**: Delete unneeded functions

- **avg_qubit_estimator.py**: Format with ruff

- **back-compat**: Fix for backward compatibility

- **catalyst**: Fix for cases where catalyst qubits have been released

- **catalyst**: Simplify catalyst release-check

- **docs**: Remove :math:text$ tags

- **draw**: Remove stray dots from targetless ops

- **example_avg_qubit_estimator.ipynb**: Allocate -> activate

- **example_avg_qubit_estimator.ipynb**: Define \bar{w}

- **get_dag_from_qpu.py**: Change strict = False to True for get_dag_from_instructions function.

- **get_dag_from_qpu.py**: Fixed import issue for get_av_from_op.

- **get_dag_from_qpu.py**: Remove igraph typing

- **get_dag_from_qpu.py**: Removed debug print statements.

- **get_stale_state_count_from_op.py**: Now import NON_CONTROL_FLOW_UNPHYSICAL_OPCODES and
  QPU_OP_OPCODES from get_av_from_ops

- **get_stale_state_count_from_op.py**: Remove uneeded comments in
  get_stale_state_count_from_restructured_op function.

- **get_stale_state_count_from_op.py**: Remove unused import.

- **mask**: Mask fixes wip with mariia

- **merge**: Fix merge for #1004 and !668

- **MR**: Fixes per MR feedback

- **MR**: Forbid qubits types for x_mask and z_mask, per MR feedback

- **MR**: Minor MR changes

- **MR**: More changes from MR feedback

- **MR**: Tiny MR comment

- **MR**: Undo MR change to fix lint

- **qpu_op_functions.py,utils.py,get_av_from_op.py**: Change name of _unsupported_av to
  _unsupported, as this is this function is used in get_stale_states_from_op and so should have a
  generalised name.

- **qpu_op_functions.py,utils.py,get_av_from_op.py**: Refactored _unsupported and check_zero_fields
  into the utils file under resource_estimation, also added a parameter to _unsupported to indicate
  which operator property is not supported.

- **reaction_limit_estimator/visualization_tools.py**: Added check for optional matplotlib install,
  we through and error if a users tries ot use draw_dag without having all necessary libraries.

- **resource_estimation/utils.py,test_1063_create_get_stale_state_count_from_op_function.py**:
  Reduced repeated code in unsupported_op function and added tests for it.

- **resource_estimation/utils.py,test_994_create_get_op_av_function.py**: Fixed _unsupported
  function call in check_zero_fields, we now have a property name for failing the zero fields check.

- **stale_state_counting/__init__.py**: Added an init file for stale state counting.

- **stale_state_function**: Added an init file

- **test**: Fix failing test #844

- **test**: Fix for test after reflect change in #1048

- **test_1063_create_get_stale_state_count_from_op_function.py**: Removed ross-selinger tests,
  remove 16.5 degree rotations from common ops test, added pi/16 rotations to to tests.

- **test_929**: More tests

- **tests/test_994_create_get_op_av_function.py**: Restored test994.

-
  **utils.py,test_1063_create_get_stale_state_count_from_op_function.py,test_994_create_get_op_av_function.py**:
  Improved robustness of _unsupported_op function and updates its tests.

- **visualization_tools.py**: Removed unneeded comments.

- **witness**: Revert witness metrics change for this MR

### Build System

- Fixed validation issues in pyproject.toml

- Move extras dependency specifiers to project.optional-dependencies

- Update poetry.lock

- Updated build specification for poetry v2

### Chores

- Change double to single quotes

- Cherry-pick test changes from test_319_python_draw_svg from SMS.

- Cherry-pick test changes from test_347_print_qubits_state_vector from SMS.

- Cherry-pick test changes from test_408_xv_api from SMS.

- Cherry-pick test changes from test_catalyst from SMS.

- Cherry-pick test changes from test_composite_filters from SMS.

- Cherry-pick test_519_builtin_add_and_qft from SMS.

- Cherry-pick test_847_skeleton_window_filter from SMS.

- Cherry-pick test_cross_ops from SMS.

- Cherry-pick test_cuquantum_export from SMS.

- Cherry-pick test_hydrogen from SMS.

- Cherry-pick test_qint from SMS.

- Cherry-pick test_shor_compile from SMS.

- Fix gitlab yml

- Fixing downstream variable handling for doc building

- Remove test_helpers deprec warning.

- Test_qft changes for most tests

- Update import for numpy utils

### Continuous Integration

- Make error message more clear

- Pass reference as input to included dev-ops/common script

- Update GitLab CI to fail on markdown_exec warnings

- Updated dev-op/common reference to new release

- Updated dev-ops/common include reference from 0.0.3 to 0.0.4

- Use pre-release dev-ops/common branch

### Documentation

- Add markdown-exec

- Updated README for poetry v2 usage

- **qpu**: Add Returns to print_state_vector and detect_entanglement docstrings

### Features

- Change the DI controller and selectors to pydantic classes

- Removed support for arbitrary angle synethsis but added support for pi/16 rotations, also merged
  in updates from main.

- Support reset in OpenQASM

- Update check for generic class to work on python 3.12

- Update pyproject.toml to add pydantic dependency

- **__init__.py,get_stale_state_count_from_op.py,stale_state_count_lookup.py**: Added comment to
  header which explains stale states.

- **avg_qubit_estimator.py**: Added average qubit estimator

- **cz-cphase**: Implement Qubits.cz() and qubits.cphase() with tests

-
  **get_dag_from_qpu.py,visualization_tools.py,resource_estimation/utils.py,get_stale_state_count_from_op.py,stale_state_count_lookup.pymqpu_op_functions.py**:
  Added code to get the number of stale states produced by an operation, we also now attach and
  display this stale state count on DAG graphs.

- **h**: Add h() as alias to had()

- **h**: Add h() as alias to had()

- **MR**: Reflect implemented per MR feedback

- **qpu_op_functions.py**: Added a note for a future update to the code.

- **reflect**: Add Qubits.reflect per feedback

- **reset**: Implement automatic qc.reset()

- **stale_state_functions/ppr_functions.py**: Added functions that return the stale state count for
  the ross_selinger implementation of a arbitrary angle ppr.

- **test_1063_create_get_stale_state_count_from_op_function.py): added test file for
  get_stale_state_count_from_op. fix(utils.py): added missing line to raise and error for
  'stale-state-count' case. fix(stale_state_functions/ppr_functions.py**: Removed op parameter from
  various functions are it is not needed.

- **visualization_tools.py**: Added a colour bar to the DAG graph.

- **visualization_tools.py**: Added colouring to nodes based on relative AV cost.

### Refactoring

- Suppress Expected Warnings in Overflow Tests

### Testing

- **cz**: Adding tests for the new API


## v4.22.2 (2025-06-20)

### Bug Fixes

- Add back removed truncate_angles function


## v4.22.1 (2025-06-19)

### Bug Fixes

- Add fixes for proper rounding

- Add numpy cover to lower_bit_index func

- Broken macos tests

- Fix failing docs

- Fix how the requirements are constructed in setup_legacy.py

- Integerize_truncated_rot_angle around 360

- Remove `ig.graph` from typing as it was causing failures.

- **cicd**: Bump dev-ops/common version to 0.0.3

- **debug**: Fix leak-detection printed message

- **docs**: Add missing tutorials to mkdocs.yml

- **draw**: Auto-expand for partial circuit drawing

- **heap**: Fix a heap allocation integer error

- **indent**: Fix two indent errors

- **lint**: Fix lint error

- **MR**: First round of MR fixes

- **MR**: Fixes per MR, with test adjustments

- **MR**: Handle rotation catalyst in #1041

- **MR**: Remove unneeded test

- **MR**: Tiny MR feedback item fixed

- **names**: Print angle units sensibly

- **poetry-lock**: Recompile with reaction-limit extra

- **ppr/ppm**: Fix for bit mask values in PPR and PPM

- **rotation**: Fix case where rotation catalyst qubits are deallocated but not registered as
  deallocated

- **serialize**: Fix tree-crawling issue

- **test**: Fix a test where a qubrick op label is zero

- **test**: Fix for valueerror raised #1007

- **test**: Fix test dependencies

- **test**: Moved set_random to after Qubits initialization

- **test**: Remove old test

- **test**: Remove old, unnecessary, nonfunctional test

- **tests**: Allow comparison with 0 in #1041

- **trivial**: Better test name printing

- **workaround**: Disable AV for this test

### Chores

- Add accidentally deleted function

- Adding ntz to special functions

- Backward compat for num_leading_zeros func

- Bump version to 4.22.0

- Changes to reduce number of warnings while running tests

- Deprecate theta_bin

- Deprecate theta_bin in tests

- Fix tests

- Json file ignore in tests directory.

- Json file ignore in tests directory.

- Nlz to ntz

- Remove deprecated function from test

- Remove extra test

- Remove old functions in favor of hardcoded values

- Remove truncate_angles

- Revert test_qbk_rotation changes

- Rework implementations into older functions

- Rewrite inefficient code

- Update to non-deprecated function.

### Features

- Added another test for QFT

- **nqre**: Nerge stacks in witness counter for #1004

- **push_state**: Finish per MR feedback, remove the old implementation (moved to the test file),
  provide docs and exceptions

- **pyproject.toml**: Add reaction-limit install

- **WIP**: Adding stacks to the witness counter, added a serialization comparison test

- **wip**: Stacks for witness counter WIP

- **WIP**: Witness counter stacks for #1004

- **WIP**: Witness to Basquiat WIP

- **witness-stack**: Success! Saving Basquiat files instantly

- **witness_export**: Integration of witness-to-basquiat and serialization

### Performance Improvements

- **filter**: Massive performance fix, avoid duplicating QPUHeap when it's not needed

- **push_state**: Complete optimized implementation of push_state for #1007

- **push_state**: More setup for optimized push_state() per #1007

- **push_state**: Setup for C++ implementation of Qubits.push_state() per #1007

- **push_state**: Switch over to the optimized one for #1007

### Testing

- Add new tests for 1018

- Correct eps in rot_qbk test suite

- **cleanup**: Add easy switch for existing serialize

- **push**: Add a test for push speed

- **speed**: Speed up test

- **validate**: Validate tests against normal witness for #1004

- **witness**: Test witness counter export to basquiat per #1004

- **witness-basq**: Adjustments to the test file


## v4.22.0 (2025-05-30)

### Bug Fixes

- Add missing rotation catalyst events

- Catch qubit numeric names before qasm export

- Convert used_symbols from set to list to allow for JSON serialization

- Correctly handle input arguments to uncomputes

- Correctly handle symbolic PPMs and PPRs

- Fix Bartiq compilation flags for numeric QPUs

- Fix circular imports

- Fix minor issues with new bartiq version

- Fix storing of input_qregs_ids when some regs are lists

- Fixes in serialization

- Further fixes in serialization

- Make name of repeated ops wrapper match the old implementation of symbolic serialization

- Minor fixes from code review

- Propagate qc.used_symbols to serialized output

- Remove an invalid test case

- Remove debug if statement

- Revert unneeded changes

- Revert unneeded changes

- Standardize how masks are stored (namely: as ints, not registers)

- Swap in QFT and _get_symbolic_costs_from_gates

- Update .gitlab-ci.yml

- WiP work on unifying serialization

- **active_volume_lookup.py**: Disambiguate property 2

- **active_volume_lookup.py**: Fix comment

- **active_volume_lookup.py**: Point to av_counting folder in warning

- **active_volume_lookup.py**: Remove bare z gate

- **active_volume_lookup.py**: Remove cx

- **active_volume_lookup.py**: Remove phaseless phase gate

- **active_volume_lookup_v5.py**: V5 -> v2

- **arithmetic**: More tests and fixes for #1041

- **av_counting**: Import sorting

- **av_counting**: Update comments

- **check_ops.py**: Improved documentation for is_physical_op

- **get_av_from_op.py**: Support more types of cz gates

- **lint**: Fix minor lint issues

- **mkdocs**: Fix broken link to tutorials/QPU-Standard-Setups.ipynb

- **output**: Restore outupt files

- **qpu_op_functions.py**: CX->CZ in multitarget CZ comment

- **qpu_ops.py**: Attribute of QPU_op_write restored

- **qpu_ops.py**: Get rid of extra space

- **qpu_ops.py**: Get rid of extra space

- **qpu_ops.py**: Undo formatting changes

- **simple_av_counter.py**: Added deprication warning

- **test**: A fix for the testing code in #1041

- **test**: Minor fix to a test in #1041

- **test/output/out**: Unneeded test files

- **Witness_counter_deep_dive.ipynb**: Back to new metrics functions

- **Witness_counter_deep_dive.ipynb**: Back to old metrics functions

- **witness_counter_deep_dive.ipynb**: V5 -> v2

### Build System

- Added deployment to codeartifact task to ci

- Added docs publishing

- Added docs publishing

- Adding yq for docs build

- Centralizing docs publishing job definitions

- Changing image for deploy job

- Corrected ci task rules

- Enabled overwrite in codeartifact

- Fix gitlab doc publishing job

- Job logic adjustment

- Made optional publishing steps non-blocking

- New flag req in yq

- One final test with actual docs publishing

- Reducing merge to only deploy packages

- Renamed job to clarify what it is

- Speeding up docs build

- Trying twine skip existing

- Typo in product name fixed

- Update python range in pyproject.toml

- Updated logic for construct docs publishing to only run on master commit

### Chores

- $$$ -> $$

- Bump version to 4.21.3

- Fix poetry install

- Fix qasm2 test

- Fix tests and add special case for ctrl

- Rename test file

- Tidy up imports

- Update bartiq version

### Code Style

- Blackified native.py

- Mark children key in native format as NotRequired

### Continuous Integration

- Changing image to python 3.11

- Deprecate wheel upload to old pypi index

- Minor fixes to deploy_external job

- Refactored gitlab-ci config

- Remove aarch and DARPA builds

- Update dev-ops/common dependency to 0.0.2

- Updated dev-ops/common include reference from 0.0.1 to 0.0.2

### Documentation

- Add print_state_vector docstring and fix detect_entang.

- Moving c++ api docs to top level and filtering for external build

- Privatize C++ API

- Remove :meth

- Replace :math with mkdocs math strings

- Update docs on symbolics

- Update sqre docs

- Update sqre docs

- Updated docs build job to support both internal and external deployment

- Updated logic and naming as for wba

### Features

- Add checks for more special chars in qasm export

- Add support for qc.read in new symbolic serialization

- Automatically register parameteters associated with new SymbolicQubits allocation

- Implement new algorithm for infering symbolic input/output registers

- Implement symbolic version of _infer_registers

- **active_volume_lookup.py**: Re-add CX as it is a special case

- **arithmeic**: First implementation of arithmetic for rotation units per #1041

- **get_av_from_op.py**: Update old comment

- **ppm_functions**: Disambiguate _get_pure_ppm_av description

- **qpu_op_functions.py**: Add optimized multitarget cz gates

### Refactoring

- Clean up serialization code

- Get rid of some commented out code

- Simplify how input qregs ids are extracted from target_mask and condition_mask

- Simplify how registers are normalized

- Unify symbolic and numeric registers

### Testing

- **arithmetic**: Simplify tests for #1041


## v4.21.3 (2025-05-08)

### Bug Fixes

- **active_volume_lookup.py**: Add v5 version

- **active_volume_lookup.py**: Improve comments

- **av_counting**: Ruff format

- **poetry**: Un-pin poetry per #1022

- **setup.py**: Passes ruff checks

- **simple_av_counter.py**: Circular import

- **simple_av_counter.py**: Match witness av counter

- **symbolic**: Flip the symbolic workaround in #998

- **symbolics**: Revert prior change, keeping the symbolics workaround in place

- **symbolics**: Workaround for symbolics issue in #998

### Build System

- Added "all" extra dependency for installing all extras

- Fixed missing extras in setup_legacy.py

### Chores

- Add doxygen inst. to readme

- Bump version to 4.21.2

### Continuous Integration

- Add doxygen install to page runners

- Adopt default settings for python jobs

- Fixed remaining bugs in macos jobs

- Refactored .gitlab-ci.yml to reduce duplication and remove uneeded commands

- Updated poetry.lock

- Use poetry>=2.1.0

### Documentation

- Add doxygen comments and api overview sections

### Features

- Add comparison of two numpy mats

- Add doxygen support to mkdocs

### Performance Improvements

- **ram**: Massive memory usage improvement for #998

### Testing

- **cicd**: Restore TEST_ON_LATEST_DEPENDENCIES to false (it seemed to have no effect)

- **cicd**: Switch to test-latest

- **MR**: Test added per MR feedback

- **ram**: Add first RAM tests

- **symbolics**: Testing a fix for symbolics in #998


## v4.21.2 (2025-05-02)

### Bug Fixes

- Fix import

- **warnings**: Fix all compile warnings per #1003

### Chores

- Bump version to 4.21.1

### Documentation

- Update Witness Counter deep dive notebook


## v4.21.1 (2025-05-01)

### Bug Fixes

- Remove explicit pytest dependency

### Chores

- Bump version to 4.21.0

### Continuous Integration

- **codeowners**: Removed C++ sections

### Features

- Delete unused warning filter

- Remove pytest entirely


## v4.21.0 (2025-04-30)

### Bug Fixes

- Allow conversion of nested sliced registers to QREF

- Fix how the input and output registers are calculated

- Fix problems with serializing nested access to rotation catalyst in uncomputes

- Fixes issue where pprs and ppms are not counted correctly

- Melt registers before stripping children

- Start re-adding rotations

- Update how AV for arbitrary unitaries is calculated

- **active_volume_lookup.py**: Allow universal import

- **active_volume_lookup.py**: Depricate old version

- **av_counting**: Formatting and sorting by opcode

- **av_counting**: Privatize

- **clifford**: Fix for the case where z() has no target and 2 conditions, per #1010

- **deprecation**: Warning and test, but warning doesn't work

- **docs**: Add Setups doc to Tutorials

- **docs**: Docs tweak for #816

- **get_av_from_op.py**: Fortify multitarget CX

- **get_av_from_op.py**: Improved reactive gate handling

- **get_av_from_op.py**: Passes wills common ops circuit test

- **lint**: Fix one lint error

- **macOS**: Attempted fix for MacOS builds

- **macOS**: Modified fix for MacOS builds per #990

- **macOS**: Remove extra version check

- **macOS**: Revert macOS install lines

- **macOS**: Some prints to debug versions

- **MR**: Changes per MR feedback

- **MR**: Fix MR feedback items

- **MR/back-compat**: Fixes for backward-compatibility and MR feedback

- **setup.py**: Deleted old version

- **test_994**: Add Op_qc_phase test

- **test_994**: Added tests for rotation synthesis methods

- **test_994**: Re-add accidentally delete test case

- **test_994**: Ruff checks pass

- **tiny**: Fixed a variable name in a notebook for #983

- **warning**: Fix deprecation warning #816

- **witness_counter.py**: Fix reverting back to normal Op

- **witness_counter.py**: Revert some formatting changes

### Chores

- Bump version to 4.20.5

- Fix CI settings

- Replace QPU.cnot calls with QPU.x

- Replace QPU.cz calls with QPU.z

### Continuous Integration

- Add WB crew members as default reviewers for bumpversion MR

- Stop pages and wheel deployment running if previous stage fails

### Features

- Add data type to circuit labels for qubit allocation

- **filter-sets**: Adjustments per design doc feedback for #983

- **radians**: Specify rotations as radians or fractions of pi, per #816

- **rz**: Testing new variants of rz()

- **test_994**: Add test for multitarget cases

- **test_994**: Added 337.5 ppm test

- **units**: Add rotation unit tweaks for #816

### Testing

- Add bartiq skip for pprs test

- Add test verifying serialization of alloc/dealloc pair

- Update test for pprs

- Update test_916_numeric_black_box_qubricks

- **cz**: Add more test cases per MR feedback

- **macOS**: Switch to clang++ to see if it matters

- **macOS**: Testing MacOS update probes

- **macOS**: Try separating -arch from arm64 etc

- **MR**: Add test per MR feedback


## v4.20.5 (2025-04-24)

### Bug Fixes

- **cleanup**: Remove extra assert

- **matrix**: Fix a very terrible bug in the matrix code which caused const_gates_2x2 to be
  modified, per #1000

- **ppr**: Fixes to PPR matrix and draw code, per #1000

- **random**: Random seed for #1000

### Build System

- Increased floor for pyliqtr dependency

### Chores

- Bump version to 4.20.3

- Bump version to 4.20.4

### Documentation

- Made all edits suggested by Sean Greenaway and SMS

- Removed vector-register from CompositeRegisters-and-VectorRegisters.ipynb

- Update How-auto-uncomputation-works.ipynb

- Updated tone and made changes based on QA feedback


## v4.20.4 (2025-04-23)

### Chores

- Sync ci with master

### Continuous Integration

- Updated CODEOWNERS for version bumping updates


## v4.20.3 (2025-04-23)

### Chores

- Bump version to 4.20.2

### Continuous Integration

- Add wheel upload to new artifactory


## v4.20.2 (2025-04-21)

### Bug Fixes

- Docstrings + added option to choose b/w decomps and am testing both now

- **capture**: Fix for capture buffer overflow in #997

- **test_991_qasm2_string.py**: Add qiskit install check.

- **test_991_qasm2_string.py**: Added copyright header to test file.

### Chores

- Changed tabs to spaces indentation in PPR test file

### Continuous Integration

- Update include project ref to 0.0.0 tag

- Updated CODEOWNERS

### Features

- **qasm3_export.py): added get_qasm2_string function to QasmExportFilter class.
  feat(test_991_qasm2_string.py**: Added tests for get_qasm2_string.

### Performance Improvements

- **2x2**: Speed up 2x2 matrix ops with not-conditions

- **cz**: Speedup not-conditions for CZ gates

- **hadamard**: Speedup for had() with not-conditions

- **ppr**: Optimize not-conditions for PPRs

- **sim**: Massive speedup for cphase when not-conditions are used

- **sim**: Massive speedup for not-conditions on X and Elbow gates

### Testing

- **rename**: Rename test script

- **speed**: Add test for not-cond speed


## v4.20.1 (2025-04-16)

### Chores

- Bump version to 4.20.0

### Continuous Integration

- Refactored .gitlab-ci.yml to remove duplication

- Remove test template extends from mac osx extras job

- Run default job rules on tags


## v4.20.0 (2025-04-15)

### Bug Fixes

- Add copyright

- Add site to gitignore

- Circuit label for write uses data type

- Clarify restructure op is for av

- Delete dag stuff

- Fix for another failure mode with AV of read

- Get rid of av specificity with restructure op.

- Makes costs in QubricCosts to be None by default

- Update av calculation logic for symbolics

- Update old parameter class to handle None values

- Use the value that's actually written

- **active_volume_lookup.py**: Get rid of unused compute_av_multitarget_cx

- **av_counting**: Account for CZ gates in targetless op

- **av_counting**: Add copyright tag

- **av_counting**: Add typing

- **av_counting**: Clarify ppr costing function names

- **av_counting**: Delete duplicate get_ppm_av function

- **av_counting**: Get rid of get_av_from_witness dict

- **av_counting**: Get rid of serialization

- **av_counting**: More Selinger spellinger

- **av_counting**: Pass ppr av counting method explicitly

- **av_counting/utils.py**: Improved documentation of strict option

- **av_counting/utils.py**: Update typing

- **cicd**: Revert #970 per #992

- **create_simple_av_lookup_table.py**: Delete dead code

- **create_simple_av_lookup_table.py**: Delete improvement comment

- **get_av_from_op.py**: Delete double import of restructure_op_for_av

- **op_av_function_tests**: Ensure all adder operations are supported

- **output**: Delete unneeded json files

- **output**: Delete unneeded txt files

- **ppm_functions.py**: Get rid of type annotations in comments.

- **ppm_functions.py**: Specify meaning of pure weight

- **ppr_functions.py**: Add comment clarifying half Y state costs.

- **ppr_functions.py**: Add default case to RS

- **ppr_functions.py**: Improve function description for arbitrary angle PPR

- **ppr_functions.py**: Make default rotation synthesis case more explicit.

- **ppr_functions.py**: Selinger spellinger.

- **qpu_op_functions.py**: Delete unused import

- **qubit-mask**: Fix for #996 mask error

- **serializtion/native.py**: Revert imports to master

- **simple_av_counter.py**: Add copyright notice

- **test_994**: Add ppr tests

- **test_994**: Adder verification tests

- **test_994**: New default RS imports

- **witness**: Finished include y weight

- **witness_counter.py**: Faster hashing

- **witness_counter.py**: Simpler hashing

- **witness_counter.py**: Y_weight excluded from x_weight

### Chores

- Accounted for factor 1/2 in PPR angle convention

- Bump version to 4.19.0

- Bump version to 4.19.1

- Bump version to 4.19.1

- Fix test

- Remove references to >>knifey>> filter

### Features

- Add set_random() to Qubits

- Added dag

- Added PPR into PPM + anc decomp as well

- Added tests for RS synth for PPRs

- Adding some code to convert from PPRs to RZs

- Av lookup table

- First version of PPRs with RS synth working after pairing with @ssim

- Paired with @acaesura, made some updates

- Simplified decompose_op, now calls ross selinger qbk

- Small fixes, looks like PPR examples are working

- Updated test to use new qbits.set_random method

- **av_counting**: Add safe av counter

- **setups**: Filter setups for WB users per #983

- **simple_av_counter.py**: Create simple AV counter

### Refactoring

- Apply 3 suggestion(s) to 2 file(s)

### Testing

- Add missing "requires bartiq" decorator


## v4.19.1 (2025-04-10)

### Bug Fixes

- **cicd**: Revert #970 per #992

### Chores

- Bump version to 4.19.0


## v4.19.0 (2025-04-10)

### Bug Fixes

- Add types to resource map in native.py

- Allow for setting the QPU RAM limit via environment variable

- Correctly handle integer sizes when constructing remainder ports

- Fix split-merge pair cancellation

- Fix tracking unique names in native serialization

- Fix typo (again)

- Further improve performance of split-merge cancellation

- Handling measurements and elbows in numeric serialization

- Import BaseQPU for typing purposes instead of QPU

- Improve performance of split-merge cancellation

- Make tracking unique names more performant in numerical serialization

- Remove left-over breakpoint

- Remove no longer needed is_based_on method

- Remove redundant call to qc.to_serializable

- Remove unnecessary case in _numeric_precursors + add docstrings

- Remove zero inputs in qubricks as well

- Restore resources to repetition wrapper

- Skip zero masks from all outputs

### Chores

- Add CR notices

- Add note to docstring and more tests

- Add typing_extensions module to dependencies

- Bump required Bartiq version to 0.12.0

- Bump version to 4.18.1

- Fix failing tests

- Fix random seed and use fidelity

- Fix weird corner case output

- Redo with faster method

- Remove comment in docstring

- Remove references to >>knifey>> filter

### Code Style

- Improve type hints and formatting

- Remove extra spaces

- Typing and style fixes

- Typing improvements

### Continuous Integration

- Always run extras test job

- Downgrade extras test to 3.10

- Move sast to own stage

- Only automatically run non-3.10 jobs on master

- Remove lint:ruff job needs

- Run sast ASAP

- Turn off manual pipelines and ensure everything run on master

- Use poetry to invoke ruff

### Documentation

- Add docstring for _symbolic_precursors

- Add docstrings to register getters

- Document the algorithm for inferring input/output registers

- Fix docstring saying that Wb -> QREF works only for numerics

- Fix missing docstring

- Make qubits pull_state doc raw string

### Features

- Add extra step constructing splits and merges for output ports

- Add information about QPU type to QPUDict

- Add pull_state() and entangled() to Qubits class

- Catch malformed env vars and add tests

- Implement initial version of numeric WB -> QREF conversion

- Implement new algorithm for infering inputs and outputs

- Remove reference to env var in (user-facing) C++ error message

- Update exception class in test, fix exception hierarchy

### Refactoring

- Introduce common base class for numeric and symbolic reg dataclasses

- Make WB register interface more flexible

- Move functionality from source_registers to _precursors

### Testing

- Refactor tests for symbolics and testing utils


## v4.18.1 (2025-04-03)

### Bug Fixes

- Add check for same qubits in target and condition

- Add runtime error

- Add test cases per reviewer comments

- Add test for cond_reg per reviewer comment

- Add warning for the case with duplicate args in compute.

- Change to qubits and add error

- Decouple native serialization code from symbolics module

- Fix bugs in witness and vector tests

- Fix construction of random test cases in test_rotation_utils

- Fix copyright notice

- Fix issue in how compute_args are being calculated

- Fix native serialization plugin path in setup_legacy.py

- Fix numeric serialization for deallocated qubits and default args for compute_args

- Fix numeric serialization test cases once again

- Linting

- Make witness counter (and metrics) work for an empty QPU

- Remove old names

- Rename MatrixV2 to Matrix and delete MatrixV1

- Rename square_engine_v2 to square_engine and del v1

- Split pages into test and publish

- Treat x_mask and z_mask of ppr as masks in witness counter

- Typo in quint docs

- Update WitnessCounter demo notebook to match updates signature of metrics()

- **cicd**: Step around failing qiskit CICD tests

- **deprecate**: Deprecate Grover per #575

- **MR**: Changes per MR feedback

- **MR**: Changes per MR feedback

- **MR**: Fix examples link per MR feedback

- **MR**: Fixes for MR feedback

- **MR**: Rename notebook per MR feedback

- **op_filter_clifford_qpu.h): Corrected copywrite info text at the top of the file.
  fix(test_958_add_clifford_qpu_gates.py**: Removed logic that triggers the entire python test suite
  and tidied up test code.

### Build System

- Bound pyliqtr python dependency range and update poetry.lock

- Replace wildcard dependencies with specific bounds

### Chores

- Add dependencies

- Add more qubits to test

- Add skip to pytest

- Add small fixes to make work

- Add some improvements and more tests

- Add tests

- Add uncompute

- Bump version to 4.18.0

- Clean up not used stuff

- Fix stage

- Fix tests and add detect entanglement

- Move import

- Recheck composite tutorial

- Remove dependencies

- Remove dependencies

- Remove entanglement and rename MatrixV2 to Matrix

- Remove import

- Remove period

- Removed old cruft files

- Rename qubricks in tests

### Code Style

- Simplify imports and improve typing

- Tidy up imports in native.py

### Continuous Integration

- Add CODEOWNERS

- Added directory-specific controls for cpp and cuda

### Documentation

- **compilation**: Add compilation filter notebook.

### Features

- (WIP) add unstable API

- [WIP] Add option to turn off warnings

- [WIP] integrate DI framework with existing tag/interface framework

- Add arithmetic QRE notebook

- Add back used QPU aliases

- Add Cassandra's demo directly

- Add DI framework notebook

- Add initial implementation of serializing resources for numerical QPUs

- Add numeric primer tutorial

- Add push_state method to Qubits class

- Add rudimentary save/load functionality

- Add support for Qubrick specification via dicts

- Add symlinks

- Add utility functions for use with numeric serialization

- Address reviewer comments

- Address reviewer comments and lint

- Address reviewer comments, update symlinks

- Change private QPU methods to use underscores

- Defined api for qubits and qubrick, removed old unused functionality in qubrick

- Expand DI tests

- Expand test coverage

- Fix one missed API

- Fix singledispatch typing

- Fix the linting

- Fix type check to get tests passing

- Fix warnings filter test

- Flag symbolic, baseline arch and counters as unstable

- Implement native numeric serialization for PPMs and PPRs

- Lint fixes

- Remove dead code, add functools wraps

- Remove standard gate counter and AV counter

- Remove unused aliases and deprecate cnot/cz for now

- Remove unused symbolic cost helpers function

- Rename numeric QRE notebook

- Revert fail tests on warn

- Update DI controller to support non-optional arguments

- Update DI demo notebook

- Update documentation

- Update framework to accept lists for registration

- Update mkdocs.yml

- Update qiskit and qasm tests to not use old API

- Update sym link to docs for tutorial

- Update test to remove check for failure on warn

- Update tests to not use old API

- Update tutorial to not use old API

- Update unstable decorator to handle classes properly

- Update warning message and add docstring

- Update witness demo notebooks to no longer use standard AV counter

- WIP add arithmetic tutorial notebook

- Workaround for python 3.10 typing

- **op_filter_clifford_qpu.h, test_958_add_clifford_qpu_gates.py**: Added control handling for Z
  gates in CliffordQPU. Also added a test to check it works.

- **tutorial**: Add simulation notebook per #964

### Refactoring

- Get rid of invert in QFT

- Make some functions in witness_counter public

- Minor logic simplification

- Simplify how the cost format is determined

### Testing

- Add (currently failing) test cases for witness counter PPR problem

- Add test case for serializing PPRs and PPMs

- Add test for serialization of program with deallocation

- Fix some numeric serialization test cases


## v4.18.0 (2025-03-25)

### Bug Fixes

- Update av calculation for symbolics

- **merge**: Adapt optimization to new witness counter

- **merge**: Another fix to the very complicated merge

- **merge**: Minor fixes and cleanups

- **merge**: More merge fixes for #767

- **merge**: Working on merge for #767

- **MR**: Changes per MR feedback

### Build System

- Fix python dependency range

- Updated poetry.lock

- Updated pyproject.toml to adhere to linting requirements

### Chores

- Bump version to 4.17.0

- Update bartiq version

### Continuous Integration

- Adopt common ci jobs

- Refactored linting jobs

- Require lint:ruff to pass

### Documentation

- Fix CR headers

### Features

- **loops**: Add repeats to witness counter for #767

- **repeat**: First pass of #767 using jumps for qubrick repetition

### Performance Improvements

- **loops**: First pass at the real optimization for #767

- **ops**: Optimize conversion of oy ops to cpp, per #959


## v4.17.0 (2025-03-25)

### Bug Fixes

- Add fixes to ensure backward compatibility

- Add friendliness features to box and filters

- Add logic disallowing release of vector register slices

- Bump copyright hook version.

- Convert assert statement into proper exception raising

- Correctly account for the case where bit_size is a sequence

- Correctly set name of sliced vector register

- Enable concatenation of symbolic qubits with vector registers

- Fix >>unitary>> filter and update tests

- Fix melting of composite registers (and corresponding test cases)

- Fix naming of vector register-related classes

- Fix notebook

- Fix return type in VectorRegister.__getitem__

- Fix slicing of SymbolicVectorRegister

- Fix test for vector register

- Fix typing related to QPUType

- Fix typo and reword error message in SymbolicVectorRegister initializer

- Fixes for vector registers

- Improve handling of slice assignment

- Make _list_to_mask compatible with VectorRegister

- Make `mask` method of vector register conform to BaseQubits.mask interface

- Make inplace addition and subtraction work for iterables of ints

- Make Qubits.__or__ work with VectorRegister

- Make single dispatch methods in VectorRegister compatible with Python 3.10

- Make VectorRegister.is_allocated work reliably

- Make VectorRegister.swap work with vector registers as targets

- Missing import

- Remove pytest as dependency

- Track allocation ownership when constructing SymbolicVectorRegister from bitsizes

- Track atomic parameters used for constructing SymbolicVectorRegister

- Update composite register after __setitem__ call

- Updated old .lan URLs for new repo path

- **cicd**: Disable WBA to see what else fails

- **cicd**: Fix antlr4 import check

- **cicd**: Fix capitalization of pyLIQTR

- **cicd**: Fixes to import checks for #954

- **cicd**: Remove internal extras, leave externals

- **cicd**: Remove unused darpa target, install extras

- **cicd**: Test extras on latest

- **cicd**: Verify that extras are installed, per #954

- **CR**: Fixed missed .cpp, .h, and .sh copyright headers

- **MR**: Comment added per MR

- **MR**: Fix per MR feedback

- **qubitmask**: Fix for an issue in #945 where numpy contaminates `int` variables into `np.int64`

- **security**: Medium security items per #709

- **security**: Remediate some vulnerabilities per #709

- **test**: Fix test #771 by removing rs-synth

- **witness**: Witness counter isn't working with RS synthesis yet, so remove the rs-synth filter

### Build System

- Added pre-commit config for CR notice linting

### Chores

- Bump version to 4.16.1

- Fix kernel

- Fix kernel

- Fix kernel

- Fix toc in multiple ipynb

- Remove Notebook prefix from notebooks

- Remove pytest

- Style and minor typo fixes

- Update bartiq version

- Update dependency on bartiq

### Code Style

- Adressed @sgreenaway's comments

- Make method names more readable

- Minor formatting and style fixes

- Minor refactor of vector registers

- Remove unnecessary backticks

- Sorted .gitignore

### Documentation

- Add missing operations

- Added CR notices

- Removed ruff format section of README

- Update CR headers to conform to standard

- Update docs of VectorRegisterSymbolic

- Update vector register example notebook

- **readme**: Added section on conv commits

- **readme**: Linted

- **readme**: Update developer guide

### Features

- (WIP) VectorRegisterSymbolic

- (WIP) VectorRegisterSymbolic tests

- Add allocation ownership tracking to SymbolicVectorRegister

- Add index property to SymbolicVectorRegister

- Add index property to VectorRegister

- Add missing methods from BaseQubits interface to SymbolicVectorRegister

- Add search bar to offline docs

- Cache composite_reg in VectorRegister

- Fix test for VectorRegisterSymbolic

- VectorRegisterSymbolic

- VectorRegisterSymbolic (address @sgreenaway's comments)

- **py3.13**: Add py 3.13 to CICD per #809

### Refactoring

- Add qubits_type to VectorRegister

- Move some attributes of vector register to properties

- Refactor VectorRegister and its symbolic counterpart

- Use single vector register type instead of separate classes for numerics and symbolics

- Use singledispatchmethod for different cases in BaseVectorRegister.__setitem__

### Testing

- Add tests for manually constructed VectorRegister

- Add VectorRegister tests

- Clean up masks used in vector register tests

- Consolidate tests for all flavors of vector registers

- Move test utilities to test_helpers module

- Remove obsolete test

- Remove unnecesary 64 bit filter

- Rename numeric_qpu helper function to bit_qpu

- Skip some vector register tests if Bartiq is not installed

- **change**: Added a test for #945

- **extras**: Check to see if extra libs ever get used

- **extras**: Remove test for extra installs, as it's not part of this change


## v4.16.1 (2025-03-12)

### Bug Fixes

- Ammend bumpversion cicd commit message

- **witness_metrics_functions.py**: Mult by num repetitions for AV

### Chores

- Attempt to fix yaml complaint

- Attempt to fix yaml round 2


## v4.16.0 (2025-03-11)

### Bug Fixes

- Corrected bad pages URL in xv_utils.py

- Fix == for Parameter

- Fixed symbolic log function

- Modified log function to use custom log2 and log10 functions for those bases.

- Old arch URL

- Reinstantiated _condition_deprecation_warning

- Updated references for new repo paths

- **docs**: Fix documentation link after repo migration #937

### Chores

- Linting

- Remove commented code

### Continuous Integration

- Avoid annoying emojis in slack notifications

- Remove pauli docs deployment jobs

### Features

- Add adder typing

- Add demo notebook for tags and Qubrick registration

- Add tagging and qubrick registration functionality

- Add test for generic adders

- Added blackbox AV test

- Expand tagging functionality

- Expand testing

- Fix for Generics interface in python 3.10

- Fix measurement bug causing WBA tests to fail

- Fix test and linting

- Fix tutorials, lint and fix PPO issue

- Improve performance by using defaultdict instead of dict

- Linting and moving tutorial to docs tutorials

- Made changes to metrics functions

- More tests, update demo notebook

- Re-add buffer to notebook

- Re-organize cost functions, allow custom cost functions to be passed

- Remove symbolic_metrics=True kwargs from metrics calls

- Respond to reviewer comments

- Restructure tags and add unit tests

- Speed up runtime by deferring witness build until qc.metrics is called

- Support more robust aliasing for rotation args in metrics functions

- Update demo notebook

- Update generic adder qubrick tests

- Update interface for metrics calls

- Update metrics to point to new witness counter

- Update PPR calculation

### Refactoring

- Decouple symbolic and numeric code in qubricks

- Minor changes


## v4.15.0 (2025-02-25)

### Bug Fixes

- Fix creation of multiple issue labels

### Chores

- Add private notebooks

- Bump version to 4.14.0

- Fix AV calculation for symbolic Qubricks

- Fix deprecated link/statement

- Fix index and getting_started md

- Fix index.md

- Fix symbolic links

- Fix wording in index.md

- Move AV calculation to Bartiq post-processing

- Reword older statement

- Small fixes for mkdocs

- Various small fixes

### Code Style

- Linted .gitlab-ci.yml

- Update imports

### Continuous Integration

- Added slackbot notification for failures on scheduled pipelines

- Added variable for testing latest

- Updated gitlab-ci.yml

### Documentation

- Rearrange mkdocs structure


## v4.14.0 (2025-02-21)

### Bug Fixes

- (WIP) ctrl logic SymbolicQPU

- Add estimate variable

- Add estimate variable

- Add failing test

- Add issue number to pytest skip

- Address reviewer comment for clean ladder qbk

- Avoid circular import

- Ctrl logic for SymbolicQPU

- Fix assertion to reflect change in register size

- Fix deprecation warning in qpu classes

- Fix PPR lookup and demo notebook

- Fix symbolic av calculation

- Fix test

- Fixed circular import

- Misc errors

- Not sure why I need to commit?

- Properly connect children with through ports in repetition wrapper

- Removing some files to make MR smaller and moved to a different MR

- Removing some files to make MR smaller and moved to a different MR

- Simplify logic

- Update imports in the other CC example notebook

- Various changes related to symbolic filters refactor

- **active_volume_lookup.py**: Error in T count

- **active_volume_lookup.py**: Fix docs for PPR AV function

- **costs**: Costs events fix for #916

- **lint**: All ruff issues fixed

- **MR**: Fixes per MR feedback

- **poetry.lock**: Revert to master version

- **poetry.lock**: Revert to master version again

- **qasm3_export.py**: Unique qubit allocations

- **qiskit_qpu.py**: Don't declare helper functions when qiskit isn't imported

- **qiskit_qpu.py**: Move import to top and docstring improvements

- **ruff**: Semicolons and == None

- **test**: Fixed a test which was using 3.5 GB of RAM by mistake

- **test**: Fixes to the custom uncompute test for #916

- **test_861**: Assert allclose instead of 1 for fidelity

- **witness_metrics_functions.py**: Missing 1q clifford AV bucket counts

### Build System

- Added linting groups to pyproject.toml

- Removed unneeded semantic-versioning poetry group

- Updated poetry.lock

- Updated poetry.lock

### Chores

- Add debugging print option to witness

- Removed spurious jupyter notebook

- Restoring do_warning in convert_value_to_type

- Reverted elbow cancellation filter files to current state on master (with updated CR notices)

- Update docstring

### Code Style

- Update imports

### Continuous Integration

- Added commit linting job

- Added commitlint config

### Documentation

- Add more docstrings in the AV lookup

- Added readme section for contributing, including pre-commit hooks install

- **licenses**: Updated all license headers

- **pre-commit**: Updated CR notice

- **readme**: Updated conv commit example

- **readme**: Updated instructions for pre-commit hooks

### Features

- Add numeric black box functionality for Qubricks (witness almost working)

- Add support for composite registers with optional parameters

- Added test file for conditionally clean arithmetic, added docstrings

- Fix bug with decomposing gates with black box qubricks

- Get old metrics functions working

- Implement native serialization for numeric QPUs

- Moved cuccaro adder tests to separate file... seems to not work...

- Re-wrote example notebook demonstrating conditionally clean decompositions

- Removing various files, addressing reviewer comments

- Restore active volume calculation for symbolics

- Unravel composite registers for purpose of serialization

- Update cost events to use start/end

- Update tests, add av functionality, add demo notebook

- **qiskit_qpu.py**: Create clear error messages for when qpu is not provided.

- **qiskit_qpu.py**: Speed up MPS simulator and add debugging features

- **test_861**: Use existing fideltiy function rather than custom

- **witness_metrics_functions.py**: Add PPR/PPM AV counts

### Refactoring

- Minor cleanups

- Minor fixes

- Remove highwater calculations for symbolics and rely on bartiq

- **examples**: Moved experiment notebooks to /examples

### Testing

- Add 2q cliff tests for av

- Add test for counting PPRs with same weights, diff angles

- Address @sgreenaway's comments

- Address @sgreenaway's comments

- Cleaned up pytest config

- Remove set_repetition_env where unnecessary

- **test_771_independent_metrics_counter.py**: Add test for no PPO circuit


## v4.13.1 (2025-02-11)

### Bug Fixes

- Fix logic in equal_compare_engine_symbolic

### Chores

- Add missing import

- Add set_version for .whl files in gitlab yml

- Extract pyproject.toml version in setup_legacy

- Get version without toml

- Only check for v on release tag cicd runs

- Remove unnecessary poetry install

- Remove update_versions() function

### Refactoring

- Remove qc from decompose_op

- Update logic in equal_compare_engine_symbolic


## v4.13.0 (2025-02-06)

### Bug Fixes

- (WIP) Symbolic estimate method gidney adder

- Add test from issue 718

- Remove unused mathjax.js file

- Symbolic cost Gidney adder

### Chores

- Adding pip install whl back

- Adding pybind11 manually

- Adding the test for linux aarch

- Fix macos test jobs

- Fix qiskit

- Fix the parallel job for macos

- Fix the test job for macos

- Instantiate the virtualenv

- Made the qiskit macos job even more dynamic

- Pages need dependencies

- Remove resource_groups

- Reverting the macos

- Simplify .gitlab-ci.yml

- Simplify .gitlab-ci.yml

- Specifying the python version explicitely

- Testing the new scheme

- Trying to tie the test whl to built whl

### Continuous Integration

- Clean up .gitlab-ci.yml

### Documentation

- Add info about emitted event to fetch_rotation_catalyst

- Add links to notebooks on the symbolic qre page

- Improve docstrings for event_start and event_end

### Features

- Emit events when accessing rotation catalyst state

### Refactoring

- Further extraction of methods from BaseQPU

- Make num_qubits property in QPU

- Move logic associated with threads from BaseQPU to SymbolicQPU

- Move QPU_cpp and associated methods out of BaseQPU

- Remove unnecessary imports and count_1_bits method from BaseQPU and QPU

- Remove unnecessary methods from QPU

- Update examples/fh_benchmark.py

### Testing

- Add parametrization


## v4.12.3 (2025-01-28)

### Bug Fixes

- Add default cond value for ppr in SymbolicQubits

- Minor fixes

- **cicd**: Lock file and cicd instructions

- **lint**: Fix actual ruff errors (undefined variables)

### Chores

- Add missing attributes to QubrickComputeState docs

- Fix debug comments

- Fix docstring

- Fix uncomputation filter docs

- Remove emit_op from qubits

### Documentation

- Add initial MkDocs docstrings to qubrick.py

- Add rendering fixes and move around some files

### Refactoring

- Add BaseQPU class

- Remove unnecessary functionalities from SymbolicQPU


## v4.12.2 (2025-01-24)


## v4.12.1 (2025-01-23)

### Bug Fixes

- Remove metrics method from rsqrt qubrick

- Remove stray parentheses causing test fail

- Revert back to correct build version

- Sync version with master

- Update how we resolve whether an object is a Qubrick in QubitLogic

- Update logic to fix circular import problems

- **.gitlab-ci.yml**: Get rid of qiskit-aer install in macos test

- **.gitlab-ci.yml**: Revert back to original ci

- **.gitlab-ci.yml**: Test qiskit interoperability in CICD

- **dagger**: Fix for dagger ops in #870

- **links**: Updated documentation notebook links

- **poetry.lock**: Add install extras

- **poetry.lock**: Regenerate with new extras

- **psiqworkbench/__init__.py**: Unsort imports

- **qiskit_qpu.py**: Add legalese

- **qiskit_qpu.py**: Apply isort and black

- **qiskit_qpu.py**: Ooutput -> output in comments

- **qiskit_qpu.py**: Require qiskit install for qiskit qpu usage

- **qiskit_qpu.py**: StreamBitQPU -> QiskitQPU in comments

- **setup_legacy.py**: Undo version update and isort

- **test_861**: More descriptive import failure message

- **test_symbolic_qint.py**: Don't require sympy install for test_composite_register_symbolic

- **test_symbolic_qint.py**: Require bartiq install to run bartiq tests

### Chores

- Redo imports after fixing some circular imports

- Remove _copy_internals method

- Remove unnecessary fields

### Features

- **lint**: Add flake8 files for #875

- **lint**: First pass at ignore items

- **qiskit_qpu.py**: Add in Statevector, MPS, and Stabilizer Qiskit simulators

### Testing

- Add test for #870


## v4.12.0 (2025-01-15)


## v4.11.1 (2025-01-13)

### Bug Fixes

- Add explicit exception for symbolics in QFTIncrement

- Add index to SymbolicQubits again

- Added QasmExportFilter to built in filters

- Minor fixes in usage of qubits classes

- **qasm3_export.py**: Add support for elbow operations

- **qpu_ops.py**: Re-align inputs to ops decalaration

- **test_811**: Refer to filter by name

### Chores

- Add BaseQubits class and refactor Qubits and SymbolicQubits

- Refactoring parts of SymbolicQubits

- WiP refactoring of SymbolicQubits class

### Code Style

- Fix style issues

- Fix style issues

- Fix typing


## v4.11.0 (2025-01-10)


## v4.10.1 (2024-12-12)

### Bug Fixes

- Fix compatibility with old Parameter class

- Update highwater calculation to use Parameter class


## v4.10.0 (2024-12-06)

### Bug Fixes

- Fix in serialization

### Chores

- Make docs dependency optional

- Rename parameter_new to parameter

- Update poetry.lock

- Update poetry.lock

### Code Style

- Run black and isort on symbolics


## v4.9.2 (2024-12-04)


## v4.9.1 (2024-12-03)

### Bug Fixes

- Fix numerical issues in compare_symbolic_total_cost_with_numeric.

- Fix usage of Parameter class when sympy is not installed

- Get rid of circuit_volume mentions

### Chores

- Add sympy to docs dependencies

- Fix CI settings

- Minor refactors

- Multiple refactors

- Update example notebooks

- Update Parameter class


## v4.9.0 (2024-11-26)

### Bug Fixes

- Fixes bug in Old parameter

- Fixes in parameter handling in symbolics

### Chores

- Make _get_serializable_qubits_representation not mutating

- Move Min/Max from classical_stubs to Parameter


## v4.8.11 (2024-11-25)

### Bug Fixes

- Add support for repeated structures when exporting to qref

- Fix logic for handling slices in SymbolicQubits

- Update logic for bit_count in new Parameter class

- Update symbolic slice handling

### Chores

- Further refactor in Parameter class

- Minor refactor in QubrickCosts class

### Code Style

- Fix typing in symbolic_compilation_filters

### Documentation

- **filters**: Removed reference to workbench web

- **index**: Simplify installation instructions

- **index**: Updated docs landing page

- **readme**: Fix underscore error in package name

- **README**: Updated installation instructions

### Testing

- Improve usage of sorted in qref serialization tests


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


## v4.7.3 (2024-08-22)

### Bug Fixes

- Add __init__.py to placate CICD

- More inits

- **psiqworkbench**: Fix and clean imports

- **psiqworkbench**: Tests pass

- **qpu.py**: Export_to_json

- **test_qasm**: Run tests instead of skipping

- **working_with_qubtis.rst**: Fix placement of QPU in docs test

### Features

- Move necessary files


## v4.4.5 (2024-08-19)


## v4.4.4 (2024-08-16)


## v4.4.3 (2024-08-16)


## v4.4.2 (2024-08-16)


## v4.4.1 (2024-08-16)

### Bug Fixes

- **reaction_limit_estimator**: Improve comments

- **reaction_limit_estimator**: Sacrifice perfect DAG for speed.


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

- **get_dag_from_qpu**: Don't require igraph


## v4.2.8 (2024-06-27)

### Bug Fixes

- Allow python 3.8

- Clean up imports

- Double time for left elbows

- Ignore I in ross-sellenger

- Images inside image folder

- Improve typing in operations

- Indent in ross-sellenger default

- Instruction filter -> instruction selector

- Is_quantum_operation -> is_physical_operation

- Issues with merge

- Make all_op_types decalaration more compact

- Missing merge conflicts

- Missing merge conflicts again

- Rearrange imports to after copyright

- Remove testing output

- Require python>=3.8

- Respond to PR comments

- Target and condition in example

- Tell users when to install igraph

- Typo

- Typo in reaction instructions explanation

- Unify qubit mask getters

- Update comments to latest version

- **example_reaction_depth**: Add QFT example

- **example_reaction_depth**: Will's corrections

- **get_dag_from_qpu**: Improve comments on inst argument

- **get_dag_from_qpu**: Simplify elbow check

- **get_dag_from_qpu**: Use num_qubits for reset

- **ordered_qpu_ops**: Self.hash -> self._hash

- **ross_sellenger_synthesis**: Bug from I no longer defined

- **ross_sellenger_synthesis**: Bug from I no longer defined

- **test_531**: Test adder for more qubits

### Features

- Add default to error to ross-sellenger - 1

- Add default to error to ross-sellenger - 2

- Add default to error to ross-sellenger - 3

- Catch warnings and explicitly manage queue

- Changes before cleanup

- Examples for reaction depth calculation

- Expose number of circuit layers in reaction limit

- Express circuits as DAGs

- Fast reaction time calculation

- Jess's idea

- Jess's idea in igraph

- Minimal graph

- Minimal graph numba

- Organized DAG creation functions

- Stuff before cleanup

- **get_dag_from_qpu**: Specify get_qubits_used_mask for dag creation

- **test_531**: Test adders with shared register can be parallelized

- **test_531**: Test doubling the sequence doubles layers

- **test_531**: Test parallel adders don't add layers


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
