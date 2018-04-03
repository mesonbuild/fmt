project('fmt', 'cpp', version : '4.1.0', license: 'BSD', default_options : ['cpp_std=c++14'])

inc = include_directories('.')
lib = library('fmt', ['fmt/format.cc', 'fmt/ostream.cc', 'fmt/printf.cc'])

fmt_dep = declare_dependency(include_directories : inc, link_with : lib)
