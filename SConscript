
from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c')
path    = [cwd]

group = DefineGroup('bh1750', src, depend = ['PKG_USING_SENSOR_BH1750'], CPPPATH = path)

Return('group')
