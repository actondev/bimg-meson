pvrtc = library('pvrtc',
                files(
                  'BitScale.cpp',
                  'MortonTable.cpp',
                  'PvrTcDecoder.cpp',
                  'PvrTcEncoder.cpp',
                  'PvrTcPacket.cpp'
                ),
                include_directories: '.'
               )

pvrtc_dep = declare_dependency(
  link_with: pvrtc,
  include_directories: '.'
)
