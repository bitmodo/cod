project('cod', 'c',
        license: 'MIT',
        version: '0.1.0')

subdir('include/cod')

cod_inc = include_directories('include')
cod_src = files('lib/cod.c')

cod_lib = library('cod', cod_src)
cod_dep = declare_dependency(include_directories: [cod_inc], link_with: [cod_lib], version: meson.project_version())
