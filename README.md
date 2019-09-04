# Soil Moisture Sensor Calibration

## Introduction 
Create a program that can calibrate the soil moisture sensor. ``||basic: Show||`` the ``||gatorSoil:soil moisture||`` on the micro:bit. Hint: to make the results easier to understand, ``||Math: multiply||`` the value returned by the sensor by 100 to get the percentage soil moisture. You can also ``||Math: round||`` the value to make it easier to read. After you think you've figured it out, ``|Download|`` the code and test it out. 

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showNumber(Math.round(gatorSoil.moisture(AnalogPin.P2, GatorSoilType.Moisture, DigitalPin.P1) * 100))
})
```

```package
gatorSoil=github:sparkfun/pxt-gator-soil
```
