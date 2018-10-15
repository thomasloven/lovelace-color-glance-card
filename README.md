# DEPRECATED

As of vesion 0.80, this is a built-in feature of home-assistant

See: [Glance card documentation](https://www.home-assistant.io/lovelace/glance/#theming)

No support will be given for this card.

---

# color-glance-card

A glance card with colored background

![color-glance-card](https://user-images.githubusercontent.com/1299821/44581913-e5181700-a79f-11e8-963c-38ed303d3dc2.jpg)

```yaml
  - type: custom:color-glance-card
    entities:
    - light.my_lamp
    - light.another_lamp
    - sensor.time
```

The color is the primary color of your theme. Everything else works the same as the built-in glance card.

