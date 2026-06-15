# pairs_mpc_solvers

PAIRS MPC solver libraries (CVXGEN) for controllers/trackers.

The package, include path (`pairs_mpc_solvers/`), and CMake targets
(`PairsMpcSolvers_MpcTrackerSolver` / `PairsMpcSolvers_MpcControllerSolver`) are
PAIRS-branded, but the C++ namespace stays **`mrs_mpc_solvers::`** — it is the
ABI of the prebuilt solver blobs shipped by `pairs_uav_controllers` /
`pairs_uav_trackers`, so renaming it would break linking.