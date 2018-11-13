prebuilt_cxx_library(
  name = 'type-traits', 
  header_only = True, 
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
