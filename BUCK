include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'mathfu',
  header_only = True,
  header_namespace = 'mathfu',
  exported_headers = subdir_glob([
    ('include/mathfu', '**/*.h'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
