# Uncomment the next line to define a global platform for your project
 platform :ios, '17.0'

target 'kxtorrent' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for kxtorrent
  pod 'SVProgressHUD'
  pod 'CocoaAsyncSocket'
  pod 'CocoaLumberjack'
end

target 'kxtorrentTests' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for kxtorrentTests

end

target 'SwarmLoader' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwarmLoader
  pod 'SVProgressHUD'
  pod 'CocoaAsyncSocket'
  pod 'CocoaLumberjack'
end

target 'SwarmLoaderTests' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwarmLoaderTests

end



post_install do |installer|
    installer.generated_projects.each do |project|
        project.targets.each do |target|
            target.build_configurations.each do |config|
                config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '17.0'
            end
        end
    end
end
