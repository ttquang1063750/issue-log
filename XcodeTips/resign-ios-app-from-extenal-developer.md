If I have old [ipa] file and I can not install on your devices.  How can I install this file on my device ?\

Step by step : 
	- Download iResign.app
	- Create file Info.plist has these <key : value> : 
		+ [application-identifier] : [your identifier]
		+ [get-task-allow] : [false]
		+ [keychain-access-group] : [array]
			* [item1] : [your identifier]
	- Download [Ad hoc] mobile provision file.
	- Open iResign.app and fill information in it.
		+ Fill path of old [ipa] file.
		+ Fill path of mobile provision file.
		+ Fill path of [Info.plist] file.
		+ Fill application\'92s new bundle id (depend on your identifier).\
		+ Choose approximate apple account.
		+ Choose [Change Id] option.
		+ Press [ReSign!] button
	- Use [your-app-name + resigned] ipa file to install on the device.


Reference : 
http://dev.mlsdigital.net/posts/how-to-resign-an-ios-app-from-external-developers/