junit_tests(
  dependencies=[
    '3rdparty/jvm/com/github/ben-manes/caffeine',
    '3rdparty/jvm/junit',
    '3rdparty/jvm/org/mockito:mockito-all',
    '3rdparty/jvm/org/scalatest',
    'util/util-cache',
    'util/util-core/src/main/scala:scala',
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala')
)

scala_library(
  name='abstract_tests',
  fatal_warnings=True,
  sources=[
    'com/twitter/cache/AbstractFutureCacheTest.scala',
    'com/twitter/cache/AbstractLoadingFutureCacheTest.scala',
  ],
  dependencies=[
    '3rdparty/jvm/junit',
    '3rdparty/jvm/org/mockito:mockito-all',
    '3rdparty/jvm/org/scalatest',
    'util/util-cache',
    'util/util-core/src/main/scala:scala',
  ],
)
