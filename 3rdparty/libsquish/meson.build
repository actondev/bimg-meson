libsquish = library('libsquish',
                    files(
                      'alpha.cpp',
                      'clusterfit.cpp',
                      'colourblock.cpp',
                      'colourfit.cpp',
                      'colourset.cpp',
                      'maths.cpp',
                      'rangefit.cpp',
                      'singlecolourfit.cpp',
                      'squish.cpp',
                    ),
                    include_directories: '.'
                   )
libsquish_dep = declare_dependency(
  link_with: libsquish,
  include_directories: '.'
)
