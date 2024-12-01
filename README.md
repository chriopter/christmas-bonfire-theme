# Christmas Bonfire Theme 🎄  
**A festive Home Assistant theme for the holiday season.**  

![Preview](https://raw.githubusercontent.com/chriopter/christmas-bonfire-theme/main/images/Example%20Picture.png)  

## 🎁 Features
- Christmas Color palette that looks ugly
- Backgrounbd image

---

## 📦 Installation

### 1. Requirements
1. From HACS thomasloven/lovelace-card-mod
2. From HACS PiotrMachowski/lovelace-html-card

### 2. Install via HACS  
1. Add Repo to HACS
2. Install

### 3. Background Image
1. Place picture from Repo or of your choice in .www/backgrounds/christmas_bonfire_theme.jpg
2. Upload a Video of a Bonfire if you wish and add this HTML Card to your Dashboard
```
type: custom:html-card
grid_options:
  columns: 32
content: |
  <video style="width: 100%; height: auto;" autoplay loop muted playsinline>
    <source src="http://homeassistant.home.lan:8123/local/backgrounds/bonfire.mp4" type="video/mp4">
  </video>
```

---

## 🎅 Support

If you enjoy this theme and want to support development, consider leaving a ⭐ on the repository! Feel free to open an issue

---

## Image Credits

The image used in this repository is provided by [Unsplash](https://unsplash.com). The original photo, titled "Sortierter Weihnachtsschmuck," is by [Unsplash](https://unsplash.com/de/fotos/sortierter-weihnachtsschmuck-7VOyZ0-iO0o).

The image is licensed under the [Unsplash License](https://unsplash.com/license), which allows free use, including for commercial purposes, without requiring attribution. However, credit to the photographer is appreciated.
