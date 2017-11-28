# Thingy52-Bluetooth-from-web

# Bluetooth BLE connection form the web
Connecting to the [Thingy 52 IoT Sensor Kit](https://www.nordicsemi.com/eng/Products/Nordic-Thingy-52) with Bluetooth BLE from a Chrome browser.
![Thingy 52][https://github.com/findorf/Thingy52-Bluetooth-from-web/raw/master/thingy-52-IoT-Sensor-kit.jpg]

Blog post found at [blog.vertica.dk](https://blog.vertica.dk/2017/11/28/connecting-to-a-bluetooth-device-from-the-web/) 

In the Thingy 52 manual, the most important part is [this page](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/firmware_architecture.html)

1. Simplest is the [button-demo](./button-demo) that only reads the state of the button when user presses it.
2. Writing to the LED with the [led-demo](./led-demo) is only sligthly more complex.
3. Full demo of the Weather Station service with the [temperature-demo](./temperature-demo)
