# usbGPIOBuDDy

A lightweight USB-controlled GPIO toolkit for testing, debugging and automation.

*Control GPIO over USB as simply as possible.*


## Philosophy

usbGPIOBuDDy is designed to provide the simplest possible way to control GPIO over USB.

- No drivers.
- No complex protocols.
- No vendor lock-in.

Just plug it in and send human-readable commands.


## Features

- USB CDC (Virtual COM Port)
- Human-readable command protocol
- Fire-and-forget operation
- Zero Impact on Target Device (ZIOTD)
- Platform independent
- Extensible command set


## Examples

#### Syntax Examples

```
GPIO_02 ON
```
```
GPIO_02 OFF
```
```
GPIO_02 TOGGLE
```
```
GPIO_02 PULSE 500
```
```
GPIO_02 PWM 50
```
```
GPIO_02 SERVO 90
```


#### Console Command Example ( Mac-Terminal )

```
echo GPIO_02 PULSE 500 > /dev/cu.usbmodem147201
```


#### Console Command Example ( Windows cmd )

```
echo GPIO_01 PULSE 500 > COM1
```


## Project Status

🚧 Early development
