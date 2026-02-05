![Freya banner](https://raw.githubusercontent.com/Freya-Vivariums/.github/refs/heads/main/brand/Freya_banner.png)

<img src="documentation/Sensor_rendering.png" align="right" width="40%"/>

The sensor is Freya's eyes and ears in the vivarium - the hardware that enables measurement of environmental conditions experienced by the inhabitants of the vivarium.

#### Capabilities:
- Temperature
- Relative air humidity
- Barometric pressure
- Air quality (VOC)
- Ambient light (visible spectrum)
- UVA/UVB/UVC (spectral 220-400nm)

<br clear="right"/>

## Hardware
The Freya Sensor is a curated collection of high-end integrated circuit sensors designed for comprehensive environmental monitoring in demanding conditions, with a standard JST connector for increased repairability and direct compatibility with a wide range of ecosystems.

#### Bosch BME680
**I2C Address:** 0x76 

Integrated environmental sensor combining temperature, humidity, barometric pressure, and VOC gas sensing for air quality monitoring. **[Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme680-ds001.pdf)**

#### Vishay VEML6030
**I2C Address:** 0x10

High-accuracy ambient light sensor with spectral response matching the human eye for precise lux measurement and photoperiod management. **[Datasheet](https://www.vishay.com/docs/84366/veml6030.pdf)**

#### AS7331
**I2C Address:** 0x74 

Three-channel spectral UV sensor with separated UVA, UVB, and UVC detection for UV bulb monitoring and safety verification. **[Datasheet](https://look.ams-osram.com/m/1856fd2c69c35605/original/AS7331-Spectral-UVA-B-C-Sensor.pdf)**

> [!NOTE]  
> The PCB is finished with a coating for resisting the humid conditions.

## Enclosure

## License & Collaboration
**Copyright© 2024 Sanne 'SpuQ' Santens**. This project is released under the [**CERN OHL-W**](LICENSE.txt) license. However, [trademark rules](https://github.com/Freya-Vivariums/.github/blob/main/brand/Freya_Trademark_Rules_and_Guidelines.md) apply to the Freya™ brand.

### Collaboration

If you'd like to contribute to this project, please follow these guidelines:
1. Fork the repository and create your branch from `main`.
2. Make your changes and ensure they adhere to the project's design style and conventions.
3. Test your changes thoroughly.
4. Ensure your commits are descriptive and well-documented.
5. Open a pull request, describing the changes you've made and the problem or feature they address.