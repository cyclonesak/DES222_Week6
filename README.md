# DES222 Task 2 Process Journal
***
### The following is the initial pitch presented in the Week 6 Pitch Padlet:
<img width="785" height="1270" alt="image" src="https://github.com/user-attachments/assets/a7fa6e04-d15f-4f73-9f0a-997abbae0f6c" />
## Digital Kaleidoscope
My thought is to create some digital art. I could host a webpage on a raspberry pi that shows a kaleidoscope type live image that evolves in response to inputs from a few sensors 

- ambient light (colour palate - low light dark pastels -> bright light sharply contrasting colours), 

- ambient sound (jitter or flashes - darker/slower for low volume / long duration -> bright flashes and static for louder noises) and, 

- movement (moving lines or shapes that change direction as movements are detected in front of a sensor (may need more than 1 sensor...)). 

As the inputs change, the kaleidoscope art displayed on the page changes ...

To demonstrate the result, I could set up the raspberry pi as a WIFI access point that allow devices to connect and set the page as the default ... a future state would be to host this on the web some place ...

I already have a Raspberry Pi

BH1750 or VEML7700 (ambient light, I2C interface) = <$10

HC-SR501 or SENO0171 PIR motion sensor = <$10

KY-037 or LM358 + ADC board like MCP3008= < $10

and I already have a breadboard and wires, etc

Software would be Python -> Flask + p5.js?

and config OS WIFI for a captive portal

** Might be (IS) a bit too much work for me to take on solo ...

May reduce to just 2 sensors ...

Basic input-response mapping for light level controls color palette and sound level triggers flashes. Keep the visual algorithm straightforward, e.g., radial symmetrical shapes with color and brightness mapped to sensor data...

Or share the load ...
