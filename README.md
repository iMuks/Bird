# Bird [![Build Status](https://travis-ci.org/vsouza/Bird.svg)](https://travis-ci.org/vsouza/Bird)

iOS and Android Push Notifications in one lib.

### APNs

[Reference](https://developer.apple.com/library/IOs/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/Chapters/ApplePushService.html)

<p>"Apple Push Notification service (APNs for short) is the centerpiece of the push notifications feature. It is a robust and highly efficient service for propagating information to iOS and OS X devices. Each device establishes an accredited and encrypted IP connection with the service and receives notifications over this persistent connection. If a notification for an application arrives when that application is not running, the device alerts the user that the application has data waiting for it.</p>

<p>Software developers (“providers”) originate the notifications in their server software. The provider connects with APNs through a persistent and secure channel while monitoring incoming data intended for their client applications. When new data for an application arrives, the provider prepares and sends a notification through the channel to APNs, which pushes the notification to the target device."</p>

### GCM

[Reference](https://developer.android.com/google/gcm/index.html)

<p>"Google Cloud Messaging for Android (GCM) is a service that allows you to send data from your server to your users' Android-powered device, and also to receive messages from devices on the same connection. The GCM service handles all aspects of queueing of messages and delivery to the target Android application running on the target device. GCM is completely free no matter how big your messaging needs are, and there are no quotas." </p>

### Status

__in development__

## License

[MIT License](http://vsouza.mit-license.org/) © Vinicius Souza