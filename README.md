# English
# GOremote (work in process)
A wireless ESP32 Car/Boat(RC) controller with a Odroid GO as an remote control 

This is an ESP32 project, to control a RC Car or Boat (or whatever you want) with a ESP32 (plus a TB6612FNG Motor Shild) and a Odroid GO as a remote control. The connection work over WIFI.

# iOS and Android App
Insted of the Odroid GO you can use a mobile App
Android: https://play.google.com/store/apps/details?id=com.lacour.vincent.wificaresp8266
iOS: https://github.com/lacour-vincent/wifi-car-esp8266
Usefull hint when you compile the iOS app:
  1. install https://cocoapods.org/
  2. git clone https://github.com/lacour-vincent/wifi-car-esp8266.git
  3. cd wifi-car-esp8266/ios
  4. pod install
  5. open xcode and open another project and select : wifi-car-esp8266/ios/wificaresp8266.xcworkspace
  6. You can look here for more information how to sideload Apps for iOS:
     https://beebom.com/how-to-sideload-apps-iphone-ios-10-without-jailbreak/

Sourcecode: https://github.com/lacour-vincent/wifi-car-esp8266

# Deutsch
# GOremote (Arbeit noch nicht abgeschlossen)
Dies ist ein Projekt, um fernsteuerbare RC Autos, Boote oder andere Fahrzeuge kostengünstig und einfach fernsteuerbar zu machen. Hauptbestandteil ist ein ESP32 mit einer TB6612FNG Motorplatine. An die Motorplatine lassen sich bis zu zwei Gleichstrommotoren anschließen. Als Fernsteuerung dient ein Odroid GO, der besser bekannt ist als GameBoy Emulator, allerdings auch ein ESP32 im inneren besitzt. Über das Steuerkreuz lässt sich so das Fahrzeug bedienen. Die Kommunikation findet über WLan statt. Ein Reichweiteten Test steht noch aus.

# iOS und Android App
Wer kein Odroid GO besitzt (ca. 40€) kann auch eine einfache App verwenden.
App für Android: https://play.google.com/store/apps/details?id=com.lacour.vincent.wificaresp8266
App für iOS: https://github.com/lacour-vincent/wifi-car-esp8266
Vor dem compilieren der iOS App müss folgendes installiert worden sein:
  1. install https://cocoapods.org/
  2. cd wifi-car-esp8266/ios
  4. pod install
  5. open xcode and open another project and select : wifi-car-esp8266/ios/wificaresp8266.xcworkspace
  6. Hier gibt es mehr Informationen zum sideloaden von iOS Apps:
     https://beebom.com/how-to-sideload-apps-iphone-ios-10-without-jailbreak/

Quellcode: https://github.com/lacour-vincent/wifi-car-esp8266
