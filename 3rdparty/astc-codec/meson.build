astc_codec = library('astc-codec',
                         files(
                           'src/decoder/astc_file.cc',
                           'src/decoder/codec.cc',
                           'src/decoder/endpoint_codec.cc',
                           'src/decoder/footprint.cc',
                           'src/decoder/integer_sequence_codec.cc',
                           'src/decoder/intermediate_astc_block.cc',
                           'src/decoder/logical_astc_block.cc',
                           'src/decoder/partition.cc',
                           'src/decoder/physical_astc_block.cc',
                           'src/decoder/quantization.cc',
                           'src/decoder/weight_infill.cc',
                         ),
                         include_directories: 'include'
                        )
astc_codec_dep = declare_dependency(
  link_with: astc_codec,
  include_directories: 'include'
  )
