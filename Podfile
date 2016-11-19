platform :ios, '10.0'
inhibit_all_warnings!
use_frameworks!

target 'RxCameraUI' do
    pod 'RxSwift',    '~> 3.0'
    pod 'RxCocoa',    '~> 3.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    puts "#{target.name}"
  end
end