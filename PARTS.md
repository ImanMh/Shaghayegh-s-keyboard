# Parts & Footprint Reference

## Push Button
- **Type:** SMD micro tactile switch, ~3x2mm body
- **KiCad Footprint:** `Button_Switch_SMD:SW_SPST_B3U-1000P`

## USB-to-TTL Adapter
- **Part:** EGBO FT232RL Type-C Mini FTDI USB 3.3V/5V to TTL Serial Adapter
- **Use:** UART debug output from STM32H523 (TX/RX)
- **Note:** Set to 3.3V mode before connecting

## Display Connector
- **Designator:** J1
- **KiCad Footprint:** `Connector_JST:JST_XH_B4B-XH-AM_1x04_P2.50mm_Vertical`
- **Nets:** VCC, GND, SCL, SDA

## MCU
- **Part:** STM32H523CCTx
- **KiCad Footprint:** `Package_QFP:LQFP-48_7x7mm_P0.5mm`

## Encoder Sub-MCU
- **Part:** ATtiny804-SS
- **KiCad Footprint:** `Package_SO:SOIC-14_3.9x8.7mm_P1.27mm`
- **I2C Bus:** I2C_SDA / I2C_SCL (separate from display bus)

## Rotary Encoders
- **KiCad Footprint:** `Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm`

## Programming Pads (ATtiny804)
- **Recommended Footprint:** `TestPoint:TestPoint_Pad_D1.5mm` (one per pin, for pogo pin access)
