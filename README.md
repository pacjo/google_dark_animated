# Google Dark Theme

A Home Assistant theme inspired on Google app dark mode.
<br />
<br />

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

### Screenshots

![Google Dark Mode 1](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%201.jpg)<br />
<br />
![Google Dark Mode 2](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%202.jpg)<br />
<br />
![Google Dark Mode 3](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%203.jpg)<br />
<br />

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

```
frontend:
  themes: !include_dir_merge_named themes
```

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### HACS installation
1. Go into the Community Store (HACS)
2. Search for Google Dark Animated
3. Open the theme
4. Press Install
5. (optional) Restart Home Assistant

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new Google Dark Theme

</br>

### Thanks to:
1. [JuanMTech](https://github.com/JuanMTech) for original project
2. [orickcorreia](https://github.com/orickcorreia) for animated icons (from his Caule Themes Pack 1)
