pkgdatadir = join_paths(get_option('prefix'), get_option('datadir'), meson.project_name())
utilsdir = join_paths(pkgdatadir, 'vanilla_first_setup/utils')

sources = [
  '__init__.py',
  'run_async.py',
  'processor.py',
  'recipe.py',
  'builder.py',
  'parser.py',
  'network.py',
]

install_data(sources, install_dir: utilsdir)
