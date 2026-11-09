install_subdir('symbolic',
    install_dir: join_paths(get_option('prefix'), get_option('datadir'), 'icons/hicolor/scalable/actions/'),
    strip_directory: true,
    follow_symlinks: false
)

install_data('xsi-adwaita-symbolic.info', install_dir : get_option('datadir') / 'xapp')

configure_file(
  input: 'xsi-replace-adwaita-symbolic.in',
  output: 'xsi-replace-adwaita-symbolic',
  configuration: {
    'XAPP_DATA_DIR': join_paths(get_option('prefix'), get_option('datadir'), 'xapp'),
  },
  install: true,
  install_dir: get_option('bindir'),
  install_mode: 'rwxr-xr-x'
)
