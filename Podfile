source 'https://github.com/CocoaPods/Specs'
source 'https://github.com/tuya/TuyaPublicSpecs.git'
source 'https://github.com/tuya/tuya-pod-specs.git'


target 'TuyaAppSDKSample-iOS-Swift' do
  use_modular_headers!

  pod 'SVProgressHUD'
  pod 'SGQRCode', '~> 4.1.0'
  pod "ThingSmartCryption", :path =>'./'
  pod 'ThingSmartHomeKit', '~> 5.1.0'
  pod 'ThingSmartFamilyBizBundle', :source => 'https://github.com/tuya/tuya-pod-specs.git'
  pod 'ThingSmartActivatorBizBundle'
  pod 'ThingSmartDeviceDetailBizBundle'
  pod 'ThingSmartPanelBizBundle'
  pod 'ThingSmartMiniAppBizBundle'
  pod 'ThingSmartBizCore'
  pod "ThingSmartHomeKit"
  pod 'ThingSmartFamilyBizBundle', '~> 5.1.0'
  pod 'ThingSmartBaseKitBizBundle'
  pod 'ThingSmartBizKitBizBundle'
  pod 'ThingSmartDeviceKitBizBundle'
  pod 'ThingSmartShareBizBundle', '~> 5.0.0'
  # 帮助
  pod 'ThingSmartHelpCenterBizBundle', '~> 5.1.0'
  
  # 消息中心
  pod 'ThingSmartMessageBizBundle', '~> 5.1.0'
  pod 'ThingSmartSweeperKit'

end

post_install do |installer|
  `cd TuyaAppSDKSample-iOS-Swift; [[ -f AppKey.swift ]] || cp AppKey.swift.default AppKey.swift;`
end
