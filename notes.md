# puppyphone

A phone for dogs, by dogs. Because dogs.

General idea:

1. Raspberry Pi Zero
2. Physical keypad
3. Non-touchscreen display
4. Linux (at least at first? idk about long-term.)
5. Custom application software.

## Hardware

Potential GSM modules:

* https://www.adafruit.com/product/1946

| Component  | Price  | Source |
|------------|--------|--------|
| Display    |  $5.74 | [NewEgg](https://www.newegg.com/Product/Product.aspx?Item=9SIAE0E5YM6668) |
| Keypad     |  $7.50 | [Adafruit](https://www.adafruit.com/product/1824) |
| RPi Zero   |  $5.00 | [RaspberryPi.org](https://www.raspberrypi.org/products/raspberry-pi-zero/) |
| Battery    |        | TBD.   |
| GSM module |        | TBD.   |

## Software

1. Alpine Linux.
2. Custom applications.
3. Possibly a custom GUI framework?

### Chat systems

I definitely need Signal, Discord, SMS.
Slack would be nice, but isn't required.
IRC would be nice, and is probably significantly easier than Slack.

| Chat system | Protocol documentation | Library |
|-------------|------------------------|--------|
| Signal      | TODO                   | [libsignal-protocol-c](https://github.com/signalapp/libsignal-protocol-c) |
| Discord     | [API docs](https://discordapp.com/developers/docs/topics/gateway) | TODO |
| Slack       | [API docs](https://api.slack.com/rtm) | TODO |
| IRC         | [modern.ircdocs.horse](http://modern.ircdocs.horse/) | lmao |
| SMS         | TODO | TODO, may need to be at least partially custom? |

