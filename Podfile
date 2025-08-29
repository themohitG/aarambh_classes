platform :ios, '12.0'

use_frameworks!
use_modular_headers!

install! 'cocoapods', :disable_input_output_paths => true

flutter_application_path = '../'
load File.join(flutter_application_path, '.flutter-plugins')

target 'Runner' do
  use_frameworks!
  use_modular_headers!

  flutter_root = File.expand_path('..')
  eval(File.read(File.join(flutter_root, 'Flutter', 'flutter_export_environment.sh')))

  flutter_application_path = File.join(flutter_root, '..')
  load File.join(flutter_application_path, '.flutter-plugins-dependencies')
end
