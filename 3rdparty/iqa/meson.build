iqa = library('iqa',
              files(
                'source/convolve.c',
                'source/decimate.c',
                'source/math_utils.c',
                'source/ms_ssim.c',
                'source/mse.c',
                'source/psnr.c',
              ),
              include_directories: 'include'
             )

iqa_dep = declare_dependency(
  link_with: iqa,
  include_directories: 'include'
)
