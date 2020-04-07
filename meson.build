project('fmt', 'cpp', version : '6.2.0', license: 'BSD', default_options : ['cpp_std=c++14'])

inc = include_directories('include')
lib = library('fmt', ['src/format.cc', 'src/os.cc'], include_directories : inc)

fmt_dep = declare_dependency(include_directories : inc, link_with : lib)
