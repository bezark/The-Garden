---
publish: true
tags: ref/pcom
---

- You can either use the 3.3V pin to supply power to the board, or use the Vin pin.
- By using the VIN pin to power goes through a (step down) voltage regulator, that provides a nice stable 3.3V to the board. The regulator in the Nano 33 IoT is the MPM3610, which requires an input voltage of at least 4 - 4.5 Volt. Which is more that a LiPo or LiFePo single cell can supply. You could use a multi-cell battery pack. Or a USB power bank. So this solutions is not really ideal.
- The other option was to connect the battery directly to the 3.3V pin. The voltage of a LiFePo however changes as it is being discharged. The voltage is around 3.65V when full, and 2.5-2.75V when "empty". The 3.2V rating is called the nominal voltage (kind of an average voltage). So it's a bit too high when full, and too low when empty. The voltage also isn't regulated, so it can fluctuate a bit, based on the amount of current that's being used.
- The maximum voltage for the SAMD21 on this Nano is 3.63V. Maximum voltage for the gyro (LSM6DS3) is 3.6V. The absolute maximum voltage for the radio (NINA-W10) is 3.6V.
- So a full LiFePo is slightly too high for the Nano. Though I think you should be fine. But don't try this with a regular LiPo of Lion battery (4.2V when full).
