scala_library(
  fatal_warnings=True,
  sources=rglobs('*.scala'),
  dependencies=[
    '3rdparty/jvm/com/github/ben-manes/caffeine',
    'util/util-core/src/main/scala:scala',
  ],
  provides=scala_artifact(org='com.twitter',
                          name='util-cache',
                          repo = artifactory,),
  exports=[
    'util/util-core/src/main/scala:scala',
  ]

)
