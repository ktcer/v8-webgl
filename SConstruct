Program('gltest',
        [
         'example/gltest.cc',
         'src/canvas.cc',
         'src/console.cc',
         'src/v8_binding.cc',
         'src/v8_webgl.cc',
         'src/webgl_rendering_context.cc',
        ],
        CCFLAGS='-ggdb3',
        LIBS=['v8_g'], LIBPATH='../v8', CPPPATH=['../v8/include', 'src', 'include'])
