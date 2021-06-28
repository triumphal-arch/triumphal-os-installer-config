project('triumphal-os-installer-config',
          version: '0.1.0',
    meson_version: '>= 0.50.0',
  default_options: [ 'warning_level=2',
                   ],
  license: 'GPL-3.0-or-later',
)

scripts = [
  'scripts/prepare.sh',
  'scripts/install.sh',
  'scripts/configure.sh',
]
icons = [
  'icons/libreoffice-main.png',
]

install_data(scripts, install_dir: '/etc/os-installer/triumphal/')
install_data(scripts, install_dir: '/opt/triumphal/os-installer-config')
install_data('config.yaml', install_dir: '/usr/share/gnome-background-properties/')
