project('cod', 'c',
        license: 'MIT',
        version: '0.1.0')

subdir('include/cod')

# Networking layer
net_proj = subproject('libnet')
net_dep = net_proj.get_variable('net_dep')

# HTTP API
http_proj = subproject('libhttp')
http_dep = http_proj.get_variable('http_dep')

# Cod stuff
cod_inc = include_directories('include')
cod_src = files('lib/cod.c')

cod_lib = library('cod', cod_src, include_directories: [cod_inc], dependencies: [net_dep, http_dep])
cod_dep = declare_dependency(include_directories: [cod_inc], link_with: [cod_lib])
