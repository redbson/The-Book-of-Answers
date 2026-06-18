# Changelog

## 0.1

- Initial release.
- Cover / opening-animation / page screens for a "book of answers" oracle.
- Answers seeded from live device state: BLE, SubGHz, and NFC sampling
  (receive only), device RTC/battery telemetry, and the hardware RNG, folded
  into an FNV-1a hash.
- Five answer categories (Forward, Observe, Warning, Explore, Reflection) with
  Normal / Rare / Legendary rarity rolls.
- Each opened page is appended as a JSON record to
  `/ext/apps_data/answer_book/answers.log`.
