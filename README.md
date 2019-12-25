# iOS-Notes



## What happens if my certificate expires or has been revoked?

### Apple Push Notification Service Certificate

You can no longer send push notifications to your app.

### Pass Type ID Certificate (Passbook)

If your certificate expires, passes that are already installed on users' devices will continue to function normally. However, you will no longer be able to sign new passes or send updates to existing passes. If your certificate has been revoked, your passes will no longer function properly.

### iOS Distribution Certificate (App Store)

If your iOS Developer Program membership is valid, your existing apps on the App Store will not be affected. However, you will no longer be able to submit new apps or updates to the App Store.

### iOS Distribution Certificate (In-house, Internal Use Apps)

Users will no longer be able to run apps that have been signed with this certificate. You must distribute a new version of your app that is signed with a new certificate.

### Mac App Distribution Certificate and Mac Installer Distribution Certificate (Mac App Store)

If your Mac Developer Program membership is valid, your existing apps on the Mac App Store will not be affected. However, you will no longer be able to submit new apps or updates to the Mac App Store.

### Developer ID Application Certificate and Developer ID Installer Certificate (Mac Applications)

If your certificate expires, users can still download, install, and run versions of your Mac applications that were signed with this certificate. However, you will need a new certificate to sign updates and new applications. If your certificate has been revoked, users will no longer be able to install applications that have been signed with this certificate.

Original Source Apple Doc
https://developer.apple.com/support/certificates/
