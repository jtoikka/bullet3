sources = [
  'details/MultiBodyTreeImpl.cpp',
  'details/MultiBodyTreeInitCache.cpp',
  'IDMath.cpp',
  'MultiBodyTree.cpp',
]

BulletInverseDynamics = library(
  'BulletInverseDynamics',
  sources,
  include_directories: include_dirs,
  link_with: [Bullet3Common, LinearMath],
  cpp_args: '-O3'
)
