#Issue :
[This certificate has been an invalid issuer] in [Keychain Access] application

#How to fix : 
	- Open [Keychain Access] application.
	- On menu bar, choose [View] --> [Show Expired Certificates]
	- On [login] keychains, delete expired certificates.
	- On [System] keychains, delete expired version of the [Apple Worldwide Developer Relations Certificate Authority Intermediate]      certificate (expired on February 2016)
	- Download the new certificate from : [Download](https://developer.apple.com/certificationauthority/AppleWWDRCA.cer)
	- Double click on this certificate to install it.

#Reference : 
[Tham khao](https://forums.developer.apple.com/thread/37208)
