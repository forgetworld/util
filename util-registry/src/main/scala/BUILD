scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'util-registry',
    repo = artifactory,
  ),
  dependencies=[
    'util/util-core/src/main/scala',
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala')
)
