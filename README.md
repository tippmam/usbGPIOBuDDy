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


## Example

#### Syntax Example
```
GPIO_01 PULSE 500
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
