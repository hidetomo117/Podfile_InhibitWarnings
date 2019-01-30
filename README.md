# Podfile_InhibitWarnings

<全部を非表示>

target 'YourProject' do

    inhibit_all_warnings!

<個別に非表示>

pod 'Alamofire', '~> 4.7', :inhibit_warnings => true
pod 'SVProgressHUD', :inhibit_warnings => true
