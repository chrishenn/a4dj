# Native Instruments Audio 4 DJ Driver

Native Instruments Audio 4 DJ Driver (minimal installer package)

The Native Instruments website serves a malformed header, breaking automatic installation. So I'll host it here until
they fix their infra

- https://www.native-instruments.com/en/company/legal-information/
- https://www.native-instruments.com/en/support/downloads/drivers-other-files/
- https://www.native-instruments.com/fileadmin/drivers/audio_4_dj/Audio_4_DJ_310_PC.zip

---

## dev

The github release step fails under nektos/act because 'gh' is not included in the 'medium' image.
As ever, nektos/act is just a nightmare to use - surely better than gha itself, though that castle is already built upon
a quagmirious swamp.

```bash
# have to manually set the artifact path or it fails. Why?!
act --artifact-server-path /tmp/artifacts
```
