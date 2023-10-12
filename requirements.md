The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

# Functional Requirements
1. Hardware System MUST mount and enclose the following:
    1. UP Core Single Board Computer (https://up-shop.org/default/up-core-series.html) and UP Core Carrier (https://github.com/UCSD-E4E/rct_up_core_carrier)
    2. NI USRP-B200mini(-i) (https://www.ettus.com/all-products/usrp-b200mini/)
    3. 900 MHz Radio (https://www.sparkfun.com/products/19032)
    4. SanDisk Ultra Fit (https://www.westerndigital.com/products/usb-flash-drives/sandisk-ultra-fit-usb-3-1?sku=SDCZ430-256G-G46)
    5. Associated Power Electronics (5V regulator)
    6. Low Noise Amplifier (https://www.nooelec.com/store/lana.html or similar)
2. Hardware System MUST provide a mounted and weather sealed 50 ohm termination for the antenna feedline (SMA-F).
3. Hardware System MUST provide a way to connect to a battery pack.
4. Hardware System MUST provide a way to swap battery packs without the electronics losing power.
5. Hardware System battery pack MUST allow the electronics to run for at least 48 hours from full charge.
6. Hardware System MUST provide IP54 ingress protection or better.
7. Hardware System MUST be able to be secured to the ground.
8. Main receiving antenna MUST be omnidirectional (no more than 6 dB difference in the horizontal plane at a fixed radius).
9. Main receiving antenna SHOULD be mounted at least 5 m above ground level.
10. Main receiving antenna MUST provide IPx4 ingress protection or better.
11. Main receiving antenna MUST be able to withstand 30 mph winds.
