# Lake Kilroy Buoy and Water Quality Sensor Project

A multi-semester engineering project (Strnad Project) to design and deploy a floating buoy with water quality sensors on Lake Kilroy, built by Vir Patel and Sam Mathews.

## About

The buoy collects water quality data (pH, dissolved oxygen, electrical conductivity, temperature/RTD) using Atlas Scientific EZO sensor probes, transmitted via a wireless/mesh network (ESP32, MQTT, ThingSpeak) back to a receiver station.

## Repo Structure

Files were reorganized by type from the original folder export — nothing inside any file was changed, only moved.

```
code/               Write-ups and reference docs for the firmware/networking code
                     (BME280, MQTT, ThingSpeak, WiFi/mesh networking, webserver),
                     plus the Ezo_I2c_lib-master.zip sensor library
docs/
  proposals/        Project proposal and application form
  journals/         Engineering journals (full project + first semester)
  partners/         Partner outreach notes, emails, resources
  todo/             Semester plans and task lists
  notes/            Meeting notes, buying lists, misc project notes
  sensor-research/  Sensor/kit comparison research
datasheets/          PDF datasheets for the EZO sensor probes (pH, DO, EC, RTD)
                     and probe hardware references
spreadsheets/        Budgets, receipts, buying lists, MAC address org, data feeds
presentations/       Slide decks, presentation videos, and the water quality
                     user manual
images/              Field/setup photos
```

## Notes

- The `code/` docs are Word write-ups of code (not raw source files) as originally created — GitHub will just render/store them as documents.
- `Ezo_I2c_lib-master.zip` is the Atlas Scientific EZO I2C library used for the sensor probes.
- Several presentation and journal files are large (10–44MB); all are under GitHub's 100MB per-file limit but will make the repo itself fairly heavy (~220MB total).
