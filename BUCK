include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'tinysha1', 
  header_only = True, 
  header_namespace = 'TinySHA1',
  exported_headers = subdir_glob([
    ('', '*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
