sources = [
  'btDefaultSoftBodySolver.cpp',
  'btSoftBody.cpp',
  'btSoftBodyConcaveCollisionAlgorithm.cpp',
  'btSoftBodyHelpers.cpp',
  'btSoftBodyRigidBodyCollisionConfiguration.cpp',
  'btSoftMultiBodyDynamicsWorld.cpp',
  'btSoftRigidCollisionAlgorithm.cpp',
  'btSoftRigidDynamicsWorld.cpp',
  'btSoftSoftCollisionAlgorithm.cpp',
]

BulletSoftBody = library(
  'BulletSoftBody',
  sources,
  include_directories: include_dirs,
  link_with: [BulletDynamics]
)
