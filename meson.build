project('bbexample', 'cpp',
        version : '0.0.1')

# Include Directories

incdir = include_directories(
  'inc'
)

srcfiles = files(
  'bbfunction1.cpp',
  'bbfunction2.cpp',
  'bbfunction3.cpp',
  'bbfunction4.cpp',
  'bbfunction5.cpp',
  'bbfunction6.cpp',
  'bbfunction7.cpp',
  'bbfunction8.cpp',
  'bbfunction9.cpp',
  'bbfunction10.cpp',
)

# 副程式庫
bblib = static_library(
    'bblib',
    srcfiles,
    include_directories : incdir,)

executable(
  'bbexample2',
  'bbexample.cpp',
  include_directories : incdir,
  link_with: bblib,
)
