![error logo not found path: https://github.com/tromoSM/better-jellyfin-ui/blob/main/Assets/fullbannergit.png?raw=true . DEV NOTE DO NOT CHANGE TO RELATIVE.PROJECT MANAGER WILL FAIL](https://github.com/tromoSM/better-jellyfin-ui/blob/main/Assets/fullbannergit.png?raw=true)
===
# Better Jellyfin UI

A modern UI enhancement theme for Jellyfin focused on cleaner layout, smoother animations, and ios like design.

---

## Installation

Go to:

Dashboard → General → Branding → Custom CSS

Paste:

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/theme.css");
```
Click **Save** and refresh the page.

---

# Optional Add-ons

All add-ons require the main theme to be installed first.

You can combine multiple add-ons together.

---

<details>
<summary><strong> Floating Header</strong></summary>

### Description
Makes the top navigation header float with improved spacing and cleaner visual separation.

### Preview
![Floating Header](https://github.com/tromoSM/better-jellyfin-ui/blob/main/options/screenshots/headr.png?raw=true)

### Installation

Add below the main theme import:

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/Floating-header.css");
```

</details>


<details>
<summary><strong> High Contrast Interface</strong></summary>

### Description
Improves readability by increasing contrast across interface elements.

### Preview


https://github.com/user-attachments/assets/bb46422f-92ae-41e6-8535-e02880d1867a


### Installation

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/High-contrast-interface.css");
```

</details>


<details>
<summary><strong> Scale Up Background Animation on Card Hover</strong></summary>

### Description
Adds a subtle scale animation effect to card backgrounds on hover.

### Preview


https://github.com/user-attachments/assets/899687a8-5201-43ab-9ec6-7efa10e8d3a8



### Installation

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/Scale-up-animation-on-hover-card.css");
```

</details>


<details>
<summary><strong> Remove Liquid Glass Borders</strong></summary>

### Description
Removes glass-style border effects for a flatter visual appearance.

### Preview


https://github.com/user-attachments/assets/56181924-8a25-4a21-b272-642b82cead16



### Installation

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/no-liquid-glass-borders.css");
```

</details>


# Example Combined Setup

```css
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/theme.css");
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/Floating-header.css");
@import url("https://cdn.jsdelivr.net/gh/tromoSM/better-jellyfin-ui@main/options/Scale-up-animation-on-hover-card.css");
```

---



# Compatibility

• Designed for Jellyfin Web, desktop and mobile client
• Some animations might not work as expected on desktop(not web) client.
• TV client does not support custom css
• Add-ons can be combined freely  

---

© 2026 - tromoSM. All rights reserved (MIT License)
