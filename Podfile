# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def shared_pods
  pod "Alamofire", "~> 4.8"
  pod "AlamofireObjectMapper", "~> 5.2"
  pod "GooglePlaces", "~> 3.0.3"
  pod "GooglePlacePicker", "~> 3.0.3"
  pod "GoogleMaps", "~> 3.0.3"
  pod "PINRemoteImage", "~> 3.0.3"
  pod "AXPhotoViewer", "~> 1.6"
  pod 'Localize-Swift', '~> 2.0'
  pod "FlagPhoneNumber", '0.7.2'
  pod "IQKeyboardManager","~> 6.2.1"
  pod 'BarcodeScanner'
  pod 'Firebase/Core'
  pod 'SwiftGen', '~> 6.0'
  pod 'SwiftLint'
  pod 'Firebase/Messaging', '6.34.0'
  pod 'Firebase/Performance'
end

target 'Test' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Test
  shared_pods


  target 'TestTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'TestUITests' do
    # Pods for testing
  end

end

target "A1 Mercado" do
  use_frameworks!
  shared_pods
  firebase_pods
end
