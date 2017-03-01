sources = [
  'b3CpuRigidBodyPipeline.cpp',
  'ConstraintSolver/b3FixedConstraint.cpp',
  'ConstraintSolver/b3Generic6DofConstraint.cpp',
  'ConstraintSolver/b3PgsJacobiSolver.cpp',
  'ConstraintSolver/b3Point2PointConstraint.cpp',
  'ConstraintSolver/b3TypedConstraint.cpp',
]

Bullet3Dynamics = library(
  'Bullet3Dynamics',
  sources,
  include_directories: include_dirs,
  link_with: Bullet3Collision,
  cpp_args: '-O3'
)
