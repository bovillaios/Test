# Uncomment the next line to define a global platform for your project

platform :ios, '13.0'

use_frameworks!

def shared_pods
pod "Alamofire", "~> 4.8"
pod "AlamofireObjectMapper", "~> 5.2"
pod "AXPhotoViewer", "~> 1.6"
pod 'BarcodeScanner'
pod "GooglePlaces", "~> 3.0.3"
pod "GooglePlacePicker", "~> 3.0.3"
pod "GoogleMaps", "~> 3.0.3"
pod "PINRemoteImage", "~> 3.0.3"
pod 'Localize-Swift', '~> 2.0'
pod "FlagPhoneNumber", '0.7.2'
pod "IQKeyboardManager","~> 6.2.1"
pod 'SwiftGen', '~> 6.0'
pod 'SwiftLint'
pod 'Firebase/Analytics'
pod 'Firebase/Messaging'
end

target 'Test' do
# Comment the next line if you don't want to use dynamic frameworks
# Pods for Test
shared_pods
end

target 'TestTests' do
inherit! :search_paths
# Pods for testing
shared_pods
end

target 'TestUITests' do
# Pods for testing
shared_pods
end

target "A1 Mercado" do
use_frameworks!
shared_pods
end
