import sys
env = Environment()
env["SRC"] = Dir("#godot-nir-static").abspath
sys.pycache_prefix = Dir("#build/__pycache__").abspath
Export('env')
SConscript('godot-nir-static/SConstruct', variant_dir='build')
