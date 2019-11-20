## Green Slate Theme for Home Assistant
Green adaptation of this Home-Assistant theme: https://github.com/seangreen2/slate_theme
---

### Installation

Download the `green_slate.yaml` file from inside the `themes` directory here to your local `themes` directory.

Make sure to add `themes: !include_dir_merge_named themes` under `frontend:` in your `config.yaml` like so:

```
frontend:
  themes: !include_dir_merge_named themes
```
  
Restart Home Assistant and select your theme by clicking on your user's profile circle in the bottom left.

---
