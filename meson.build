project('fmt', 'cpp', version : '5.3.0', license: 'BSD', default_options : ['cpp_std=c++14'])

inc = include_directories('include')
lib = library('fmt', ['src/format.cc', 'src/posix.cc'], include_directories : inc)

fmt_dep = declare_dependency(include_directories : inc, link_with : lib)
