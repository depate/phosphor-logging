# Generated file; do not modify.
subdir('Manager')
generated_others += custom_target(
    'xyz/openbmc_project/Logging/Internal/Manager__markdown'.underscorify(),
    input: [ meson.project_source_root() / 'xyz/openbmc_project/Logging/Internal/Manager.interface.yaml',  ],
    output: [ 'Manager.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.project_source_root(),
        'xyz/openbmc_project/Logging/Internal/Manager',
    ],
    build_by_default: true,
)

