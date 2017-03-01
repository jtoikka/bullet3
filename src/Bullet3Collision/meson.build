sources = [
  'BroadPhaseCollision/b3DynamicBvh.cpp',
  'BroadPhaseCollision/b3DynamicBvhBroadphase.cpp',
  'BroadPhaseCollision/b3OverlappingPairCache.cpp',
  'NarrowPhaseCollision/b3ConvexUtility.cpp',
  'NarrowPhaseCollision/b3CpuNarrowPhase.cpp'
]

Bullet3Collision = library(
  'Bullet3Collision',
  sources,
  include_directories: include_dirs,
  link_with: [Bullet3Common, Bullet3Geometry],
  cpp_args: '-O3'
)
