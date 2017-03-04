![Pushsafer](https://www.pushsafer.com/de/assets/logos/logo.png)
# ispyconnect-pushsafer
##How to send push-notifications out of iSpy with Pushsafer.com
Open source camera security software. iSpy provides security, surveillance, motion detection, online access and remote control.

[Pushsafer.com](https://www.pushsafer.com) make it easy and safe to send &amp; receive push-notifications to your
- Android devices
- iOS devices (iPhone, iPad, iPod Touch, Watch)
- Windows 10 Phone & Desktop
- Browser (Chrome & Firefox)

## Usage
1. Open Video or Audio settings for the desired camera ![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-1.jpg)
2. Open Tab Alerts
3. select the desired alert mode
4. Add a new Alert Action = Call URL
5. enter the Pushsafer API URL with parameters you need ![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-2.jpg)
6. you can use the Link/URL generator in your dashboard
7. choose parameters you want and click on Create Link
8. Copy the generated URL in iSpy
9. iSpy provide 3 variables to merge {ID}, {NAME}, {MSG}
10. these vars you can use in the pushsafer parameter title or message

## Do not use any of these iSpy variables in a pushsafer parameter m=message alone, because when a var has a empty string and a message m transfered empty to pushsafer, the push-notification can not send out

## Example URLs

	https://www.pushsafer.com/api?k=XXXXXXXXXXXXXXXXXXXX&d=418&i=82&s=25&v=3&t=iSpy%20Alert&m=Movement%20detected%20in%20living%20room
  
	https://www.pushsafer.com/api?k=XXXXXXXXXXXXXXXXXXXX&d=418&i=82&s=25&v=3&t=iSpy%20Alert&m=Movement%20detected%20in%20living%20room%0A{ID}%3A%20{NAME}
  
## Screenshots of iSpy Push-Notifications

Client App

Screenshot Client App

![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-3.jpg)

Screenshot iOS > iPhone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-4.jpg)

Screenshot Android

![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-6.jpg)

Screenshot Windows 10 Phone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-5.jpg)

Screenshot Windows 10 Desktop

![Pushsafer](https://www.pushsafer.com/de/assets/examples/iSpy_push-notification-7.jpg)
