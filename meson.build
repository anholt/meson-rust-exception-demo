
project(
  'rusttest',
  ['c'],
  version : '1.0',
  license : 'MIT',
  meson_version : '>= 0.52',
  default_options : ['buildtype=debugoptimized', 'b_ndebug=if-release', 'c_std=c99', 'cpp_std=c++14']
)

add_languages('rust')
executable('hw', 'hw.rs')
