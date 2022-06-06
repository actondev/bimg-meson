project('bimg', 'cpp')

bx_proj = subproject('bx')
bx_dep = bx_proj.get_variable('bx_dep')

subdir('3rdparty')

bimg = library('bimg',
               files(
                 'src/image.cpp',
                 'src/image_cubemap_filter.cpp',
                 'src/image_decode.cpp',
                 'src/image_encode.cpp',
                 'src/image_gnf.cpp',
               ),
               dependencies: [
                 bx_dep,
                 astc_dep,
                 astc_codec_dep,
                 adtaa3_dep,
                 etc1_dep,
                 etc2_dep,
                 iqa_dep,
                 libsquish_dep,
                 lodepng_dep,
                 nvtt_dep,
                 pvrtc_dep,
                 tinyexr_dep
               ],
               include_directories: [
                 'include',
                 '3rdparty'
                 ]
              )
bimg_dep = declare_dependency(
  link_with: bimg,
  include_directories: 'include'
)
