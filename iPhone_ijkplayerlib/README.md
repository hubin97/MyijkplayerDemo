
//编译时根据需求替换Debug/Release 

合并Debug版本
iPhone_ijkplayerlib MyMac$ lipo -create /Users/Mac/Desktop/iPhone_ijkplayerlib/Debug-iphoneos/IJKMediaFramework.framework/IJKMediaFramework /Users/Mac/Desktop/iPhone_ijkplayerlib/Debug-iphonesimulator/IJKMediaFramework.framework/IJKMediaFramework -output IJKMediaFramework

合并Release版本
iPhone_ijkplayerlib MyMac$ lipo -create /Users/Mac/Desktop/iPhone_ijkplayerlib/Release-iphoneos/IJKMediaFramework.framework/IJKMediaFramework /Users/Mac/Desktop/iPhone_ijkplayerlib/Release-iphonesimulator/IJKMediaFramework.framework/IJKMediaFramework -output IJKMediaFramework