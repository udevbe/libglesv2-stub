libglesv2stub = library(
    'libglesv2',
    sources: [ 'stub.c' ],
    version: '2.0',
    install: true,
    include_directories: libglesv2stub_inc,
)

pkg = import('pkgconfig')
pkg.generate(
    libraries: libglesv2stub,
    name: 'GLESv2',
    description: 'OpenGL ES v2 stub library and headers.',
    version: meson.project_version(),
    filebase: 'glesv2'
)
