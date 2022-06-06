nvtt = library('nvtt',
               files(
                 'bc6h/zoh.cpp',
                 'bc6h/zoh_utils.cpp',
                 'bc6h/zohone.cpp',
                 'bc6h/zohtwo.cpp',

                 'bc7/avpcl.cpp',
                 'bc7/avpcl_mode0.cpp',
                 'bc7/avpcl_mode1.cpp',
                 'bc7/avpcl_mode2.cpp',
                 'bc7/avpcl_mode3.cpp',
                 'bc7/avpcl_mode4.cpp',
                 'bc7/avpcl_mode5.cpp',
                 'bc7/avpcl_mode6.cpp',
                 'bc7/avpcl_mode7.cpp',
                 'bc7/avpcl_utils.cpp',

                 'nvmath/fitting.cpp',

                 'nvtt.cpp',
                 
               ),
               dependencies: [bx_dep],
               include_directories: '.'
              )

nvtt_dep = declare_dependency(
  link_with: nvtt,
  include_directories: '.'
)
