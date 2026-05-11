## [1.5.0] - 2026-03-27

### Features

- **psiqworkbench**: 4.33.6 → 4.35.2
  - first pass prototype of fallback measurement generators
  - Add new fallback scripts
  - Implement Diagonal Matrix, with test
  - first pass, with test
  - WIP initial functions needed for cudaq filter
  - Add basic support for depth argument in circuit_designer.export
  - Add comments and expand to use different core adders
  - Implement basic circuit_designer.draw function
  - Add path tracking in exporter base
  - Add hash and eq methods to LabelReference
  - Implement somewhat functioning register placement in WB -> CD conversion
  - Implement proper handling of implicitly accessed registers
  - Implement `expanded` flag
  - Sort registers to make output more predictable
  - draft filter
  - Early prototype and speed test iteration
  - Iteration on Construct CUDA testing
  - add native QFT
  - Add mini kernel test, and lots of mess
  - Iteration on the cudaq sim filter
  - Iteration, integration of filter with static kernel sim
  - More iteration and fixes
  - Update from car/les to test #1302
  - Implement parsing of box close and box open events
  - Support special angles < 45 degrees in symbolic rotation catalyst
  - enable AV comparison in assert_resources_equal by default
  - enable AV comparison in assert_resources_equal by default
### Bug Fixes

- **psiqworkbench**: 4.33.6 → 4.35.2
  - fix the == compare to be efficient for all types
  - Remove special cases and fix a test
  - Fixes per MR feedback
  - paramaterize test
  - All MR feedback addressed!
  - MR ideas addressed, first pass
  - Fix per MR feedback
  - Add text per MR feedback
  - Respond to all MR feedback
  - Robustify witness removal pr MR feedback
  - Use correct action when constructing subroutine enter event
  - update logic for subtype specification
  - Make imports from construct_tools optional
  - add tests and a missing compute in qubrick
  - Add missing type-checking import
  - edit docstrings
  - Remove incorrect TYPE_CHECKING import
  - Add type checking import of construct_tools.Circuit
  - Skip alloc_ref and free_ref in register tracking
  - Fix register sorting
  - add test file
  - remove unneeded parents from function
  - improve performance of unitary filter and add catch for slowness
  - just small cleanup
  - iteration on new kernel
  - New kernel logic
  - iterative fixes for ops
  - iterative fixes for ops
  - Test now checks the state vec
  - Small fixes to speed testing
  - Fix per MR feedback
  - Kernel and speed test adjustments
  - Make CUDAQ a soft-import per Make expand default to False
  - trivial change to fix build lint error
  - trivial change to fix CICD lint error
  - fixes based on MR feedback
  - Add >>cudaq-sim-v2>> for testing
  - Comment out second run
  - merge fix for iterative car/les changes to kernel
  - update interoperability code to work with more complicated generic types
  - Remove debugging import
  - update DI logic to handle more complicated interfaces
  - minor fixes in get_dag_from_qpu
  - remove unnecessary option for dags progress bars
  - Fix converting programs releasing rotation catalyst to QREF
  - remove networkx as default dependency
  - address reviewer comments
  - add support for changing unitary dimension between get calls
  - address reviewer comments
  - Remove unused imports
  - Make symbolic catalyst QREs more robust for multiplicities of pi/8
  - cudaq QPU.reset() bug fix
  - update IMSModel docstring
  - remove IP-sensitive QPU Driver model
  - update logic for subtype specification
  - Move qpudriver subpackage out of Workbench
  - Fix WB -> CD export for Qubricks with no inputs
  - Fix WB -> CD export for Qubricks with no inputs
  - update ci to build all images on tag
  - update ci to build all images on tag
  - updated build job to copy instead of move from dist
  - updated build job to copy instead of move from dist
- **workbench-algorithms**: 1.13.0 → 1.13.4
  - fix symbolic uncompute in DataLookupClean
  - release trigger commit
  - release trigger commit
  - fix bug with numpy arrays as inputs to DataLookupClean
  - fix symbolic uncompute in DataLookupClean
  - fix discrepancies for several qubricks
  - fix discrepancies for several qubricks
  - Cheby warning in test
  - Cheby warning in test
### Performance Improvements

- **psiqworkbench**: 4.33.6 → 4.35.2
  - Add in test optimization from #1274 into #1297
  - Added parametrize

### Documentation

- **psiqworkbench**: 4.33.6 → 4.35.2
  - replaced commitlint README section with MR title linting docs
  - Add example notebook with CD conversion
  - Refresh notebook
  - Update WB -> CD notebook to correctly discuss expand kwarg
  - Fix typo in docstring
  - Wrap Qubrick labels in \\text{}
  - Add basic docstrings to QPU ops.
  - Place comment about QPU_op where it should be
  - add 'Basic numeric QREs' tutorial
  - outline CUDA-Q simulator tutorial section
  - fix reaction depth example
  - remove reference to igraph in example
  - add basic numeric QRE how-tos
  - improve API docs for ppm and peek_ppm_probability
  - clean up API docs
  - Update comment
  - add 'Advanced Gates' tutorial and docs map
  - outline CUDA-Q simulator tutorial section
  - add 'Non-standard Gates' tutorial and documentation map
  - add CUDA-Q simulator tutorial section
  - move items from private docs to examples
  - remove info about private docs from configs
  - move items from private docs to examples
  - add instruction about installing graphviz
  - update graphviz instructions
  - add instruction about installing graphviz
  - update Slack webhook variable reference
  - fix release notification channel name
  - Unify internal and external docs builds
  - Unify internal and external docs builds
- **workbench-algorithms**: 1.13.0 → 1.13.4
  - add check for broken external links
  - add CI check for broken external links ()
  - exclude CondCleanBuild from qubricks
  - exclude CondCleanBuild from qubricks.md
  - update Slack webhook variable reference
  - fix release notification channel name
  - remove filterwarnings('ignore') from tutorial notebooks
  - remove filterwarnings('ignore') from tutorial notebooks


## [1.4.1] - 2026-03-17

### Features

### Bug Fixes

## [1.4.0] - 2026-03-06

### Features

- **psiqworkbench**: 4.33.5 → 4.33.6
  - fixed unc bug in edge case for ltc and included this in tests
  - 18s for CC, 8s for Cuccaro
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - integrated the select and old tests passing but seeing weird warning about release of qubits and need to test ctrl case
  - added smarted ctrl incorporation and all test passing for all Selects updating test to call interface.
  - pulling out ancilla assignment from test files and pytest parametrising select instance, fixing typos, removing unnecessary init
  - wrap selects in sorted to allow tests to run in parallel on workers
  - adding explicit uncompute test and bumping WB version
  - warnings bashed
  - pytest warn included
  - updated syntax in two qubricks to use reg.ppr vs. qc.ppr
  - removed unused lines of code
### Bug Fixes

- **psiqworkbench**: 4.33.5 → 4.33.6
  - Test building 6 flavors, both pinned and unpinned
  - Test unpinned default build
  - Try to force no bookworms
  - Again, try to force no bookworm
  - reduce number of unnecessary warnings
  - Signed/unsigned errors and warnings fixed
  - debugging CICD fail
  - Try to install just the compatible wheel and relax when the incompatible ones fail
  - See if we can autodetect the correct one
  - Try to install just what's compatible
  - fix typo per MR feedback
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - Fix a few deprecation warnings
  - fixes for AV in symbolic select
  - fix QREs for controlled selects
  - fix trotterization to use Y weights
  - remove warnings by skipping incompatible pairs of register sizes and basis states
  - remove warnings of duplicate flag arg in compute
  - reducing the size of the system to stay within memory bounds
  - only passing in valid tuples of basis state and size of system
  - changing size of system to stay within memory limits of workers
  - remove warning from block encoding duplicated be_ancillae_reg arg
  - remove test warning by adding pytest-repeat to pyproject
  - test release
### Documentation

- **psiqworkbench**: 4.33.5 → 4.33.6
  - fix issue with broken w3.org links
- **workbench-algorithms**: 1.11.2 → 1.13.0
  - replaced commitlint README section with MR title linting docs
  - updated README.md with release flow and mr-title-linting
  - minor docstring changes
  - replaced commitlint README section with MR title linting docs


## [1.3.0] - 2026-03-02

### Features

- **psiqworkbench**: 4.33.2 → 4.33.5
  - all warnings bashed

### Bug Fixes

- **psiqworkbench**: 4.33.2 → 4.33.5
  - fix cswap handing in UnitaryFilter
  - control only the center CNOT in controlled SWAP
  - check for catalytic T warning checking
  - check for conditional RS warning
  - get rid of DeprecationWarnings
  - remove warnings triggered when expected
  - Remove AWS version file from version update script
  - remove all aws references from build scripts and .gitignore
### Documentation

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
### Performance Improvements

### Documentation

- **workbench-algorithms**: 1.9.3 → 1.9.4
  - removed installation instructs from construct for external users
- **basquiat-adapter**: 0.4.3 → 0.5.0
  - updated readme instructions for poetry v2
  - updated release instructions in README.md
### Other Changes

- **psiqworkbench**: 4.30.5 → 4.30.6
  - fix(get_av_from_op.py); delete redundant tests
  - fixup! fix: add fix for old parameter
  - fixup! test: fix tolerance for av in comparators
  - fixup! fixup! fix: add fix for old parameter
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
- **openfermion**: none → 1.7.1
  - Added new component: openfermion 1.7.1
- **pubchempy**: none → 1.0.5
  - Added new component: pubchempy 1.0.5
