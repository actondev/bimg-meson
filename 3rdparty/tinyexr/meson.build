tinyexr = library('tinyexr',
                  files('deps/miniz/miniz.c'),
                 )

tinyexr_dep = declare_dependency(
  link_with: tinyexr,
  include_directories: ['.', 'deps/miniz']
)
