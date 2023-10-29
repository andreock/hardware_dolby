# Moto dolby

Getting Started
---------------
Make sure you are not using any audio effect configuration in your device trees. Also for dolby media codecs to work add this line in your media codecs config (should be in vendor partition) :-

```bash
<Include href="media_codecs_dolby_audio.xml" />
```

To build, inherit the dolby config by adding this in your device's makefile :-

```bash
$(call inherit-product, hardware/dolby/dolby.mk)
```

### Credits

[FlamingoOS-Devices/hardware_dolby](https://github.com/FlamingoOS-Devices/hardware_dolby/tree/A13)

