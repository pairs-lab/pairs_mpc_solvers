# pairs_mpc_solvers

PAIRS MPC solver libraries (CVXGEN) for controllers/trackers.

The package, include path (`pairs_mpc_solvers/`), CMake targets
(`PairsMpcSolvers_MpcTrackerSolver` / `PairsMpcSolvers_MpcControllerSolver`), and
the C++ namespace (`pairs_mpc_solvers::`) are all PAIRS-branded. The solvers are
built from source here and linked by `pairs_uav_controllers` /
`pairs_uav_trackers` via the package targets.