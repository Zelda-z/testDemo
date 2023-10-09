# Uncomment the next line to define a global platform for your project
# platform :ios, '10.0'

target 'testDemo' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  pod 'Tweaks'
  pod 'AFNetworking', '~> 4.0.1'
  pod 'MJExtension', '~> 3.4.1'
#  pod 'BlocksKit', '~> 102.2.18'
  pod 'BlocksKit'
  
  # Pods for testDemo

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '11.0'
    end
  end
end
