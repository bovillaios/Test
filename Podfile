# Uncomment the next line to define a global platform for your project

platform :ios, '11.0'

use_frameworks!

def shared_pods
pod "Alamofire", "~> 4.8"
pod "AlamofireObjectMapper", "~> 5.2"
pod "AXPhotoViewer", "~> 1.6"
pod 'BarcodeScanner'
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
shared_pods
end
