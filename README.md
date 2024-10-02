## Hacky Home assistant support for Xiaomi vacuum STYJ02YM

![icon](https://github.com/user-attachments/assets/4ad960a3-ad78-4b40-8886-5c6e122fc87c)

_Original code by [@nqkdev](https://github.com/nqkdev/home-assistant-vacuum-styj02ym) and [@KrzysztofHajdamowicz](https://github.com/KrzysztofHajdamowicz/home-assistant-vacuum-styj02ym) then I forked it and added HACS support, unique_id and fixed some deprevation notices._  
_Next steps will be to add config flow for the integration and get STYJ02YM working in Home Assistant for as long as I can._

### This is for STYJ02YM (apparently EU version) with 3.5.3_0017 firmware

#### Install

- Install it with HACS by adding (https://github.com/DominikWrobel/home-assistant-vacuum-styj02ym) as a custom repository
- Add the configuration to configuration.yaml, example:

#### Usage

Add to `configuration.yaml`:

```yaml
vacuum:
  - platform: miio2
    host: 192.168.68.105
    token: !secret vacuum
    name: Mi hihi
```

# Support

If you like my work you can support me via:

<figure class="wp-block-image size-large"><a href="https://www.buymeacoffee.com/dominikjwrc"><img src="https://homeassistantwithoutaplan.files.wordpress.com/2023/07/coffe-3.png?w=182" alt="" class="wp-image-64"/></a></figure>
