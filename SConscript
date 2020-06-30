from building import *

cwd = GetCurrentDir()
path = [cwd+'/inc']
src  = Glob('src/*.c')
 
group = DefineGroup('led', src, depend = ['PKG_USING_LED'], CPPPATH = path)

Return('group')