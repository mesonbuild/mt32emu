configure_file(input : mt32emu_config_h_in,
               output : 'config.h',
               configuration : conf_data)

foreach file_name, src_file : mt32emu_header_map
  configure_file(input : src_file, output : file_name, copy : true)
endforeach

subdir('c_interface')
