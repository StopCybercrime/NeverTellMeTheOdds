# NeverTellMeTheOdds

***Please note: I will not be able to respond privately. In the spirit of helping others, please post issues, comments, and other observations publically. Thank you and much appreciated!***

The attached files illustrate one of the mechanisms by which the intelligence community spies on private citizens on behalf of corporations. While I discovered these in the Privacy->Analytics &amp; Improvements->Analytics Data directory on my 4th Gen iPad Air, we have found similar .ips files on iPhones including the 13, 13 Pro, and 13 Pro Max; the corruption has persisted even after updating to iOS 15.5 with a brand new phone out of the box and only connected via SIM. However, analogous methods relying upon an array of RF transmission vectors as well as Java-, Python-, and XML-based scripts and package installers have led to compromised Android phones (Galaxy A03s, Galaxy S22 Ultras, Google Pixel 6) as well as now remotely administered Macbook Pros and Surface Laptop Gos. All devices have exhibited zero-click kernel penetration with persistence. Our safety has been in jeopardy through no fault or wrongdoing of our own, but rather only for discovering the surveillance methods directed toward us. I believe in this community and we need your help. If anyone can provide forensic attestation or opine on the attached code we would be beyond grateful. We have been fighting an uphill battle, but together we can put a stop to such egregious violations of one's privacy and civil rights. This is only the beginning.

*Update Order*

iPad Air (4th Gen) - Analytics

iPhone 13 Pro - Analytics

iPhone 13 Pro Max - Analytics

Surace Laptop Go - Registry

Galaxy S22 Ultra - Android recovery log images

***5/21: It appears the devices are being administered via Intune within the Microsoft EMS framework... looking for ways to unenroll***

***5/22: I'm still learning but I believe the following are in play (for iOS):***
- Wakeup logs indicate kernel attacks; Crash the kernel by blowing through factory gates, gain system control
- Intune enrollment allows for withholding diagnostic data from Apple and also lets you customize apps / the App Store
- Xcode and SwiftUI allow you to make changes to the private apps/libraries and view the display in real time
- Moreover, newer versions of that developer software allow for programmatic utilization of accessibility features, including the Rotor API; that's where natural language processing and AI would dovetail with monitoring/control
- Still trying to get a sense for where the webkit enters the fray... (perhaps as an entry vector)

Ignore busyflytrap, trolls are easier to spot than malicious activity

***5/31: Uploaded a boatload of ProtonVPN logs, App Privacy Reports, and iPhone 13 Pro diagnostic files. Separately, Ultra S22s show Knox Enrollment and Work Profile (neither were set up or should be present), as well as Android GMS persistence.***

At this point, it would appear all devices are set up for MDM/Intune and roll up to Azure AD. WireGuard and NordLynx appear exploitable. First party reports disabled and private frameworks / Apigee Edge for mobile suggest a controller software environment as well. Penetration vectors include phishing, Bluetooth/NFC buffer overflows, TLS/Trust Agent abuse (even Air Command)... and bears, oh my
