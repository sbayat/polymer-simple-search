### Status

### General Info `<simple-search>`

`<simple-search>` shows an search on your page and a push notification on your device.

To use, insert `<simple-search>` in the body:

    <body>
      <simple-search></simple-search>

Example:

To show the message instantly.
```
    <body>
      <simple-search autoshow message="Hello">
      </simple-search>
``` 


Example:

To enable push notifications per device.

```
    <body>
      <simple-search notify-device message="Hello">
      </simple-search>
``` 


### Documentation Page

https://github.com/sbayat/polymer-simple-search/components/simple-search/

### Demo Page

https://github.com/sbayat/polymer-simple-search/components/simple-search/demo/

### Styling
The following custom properties and mixins are available for styling:
Custom property | Description | Default

----------------------------|--------------------------------------------|----------

`--dark-primary-color` | The background-color of the message | `#303F9F`

`--text-primary-color` | The text color of the message       | `#ffffff`

### Fonts
The following variable is applied for the font of the element
`--paper-font-common-base`