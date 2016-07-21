source 'https://github.com/CocoaPods/Specs.git'

project 'AeroGearOAuth2.xcodeproj'
platform :ios, '8.0'
use_frameworks!

target 'AeroGearOAuth2' do
  pod 'AeroGearHttp', git: 'https://github.com/410Labs/aerogear-ios-http.git'

  target 'AeroGearOAuth2Tests' do
      inherit! :search_paths

      pod 'OHHTTPStubs', '5.1.0'
      pod 'OHHTTPStubs/Swift', '5.1.0'
  end
end
