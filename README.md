# Weather Effect — WordPress Plugin

[![WordPress Plugin Version](https://img.shields.io/wordpress/plugin/v/weather-effect.svg?color=blue)](https://wordpress.org/plugins/weather-effect/)
[![WordPress Compatible Version](https://img.shields.io/wordpress/plugin/tested/weather-effect.svg?color=green)](https://wordpress.org/plugins/weather-effect/)
[![Requires PHP](https://img.shields.io/badge/PHP-%3E%3D%205.6-777bb4.svg)](https://wordpress.org/plugins/weather-effect/)
[![License](https://img.shields.io/badge/License-GPLv2%20or%20later-orange.svg)](http://www.gnu.org/licenses/gpl-2.0.html)

**[Weather Effect](https://wordpress.org/plugins/weather-effect/)** is a lightweight, responsive WordPress plugin that allows you to add animated falling objects to your website. Whether you want to showcase snowfall during winter, falling leaves in autumn, rain drops, or festive decorations for holidays like Christmas, Halloween, and Valentine's Day, this plugin has you covered.

It overlays smooth, cross-device animated elements on your pages to enhance user engagement and create a seasonal atmosphere for your visitors.

---

## 🚀 Live Demo & Links

* 🌐 [Free Version Demo](https://awplife.com/demo/weather-effect-wordpress-plugin/)
* 💎 [Pro Version Demo](https://awplife.com/demo/weather-effect/)
* ⚙️ [Try Admin Demo](https://awplife.com/demo/weather-effect-premium-admin-demo/)
* 📖 [Documentation](https://awplife.com/wordpress-plugins/weather-effect-wordpress-plugin/)
* 🛍️ [Get Pro Version](https://awplife.com/account/signup/weather-effect-premium)
* 📺 [Video Tutorial on YouTube](https://www.youtube.com/watch?v=0ffKTyBsVbw)

---

## ✨ Features & Functionality

### Free Version Features
* **4 Core Themes:** Christmas, Winter, Autumn, and Rainy effects.
* **Falling Animations:** Smooth falling snow, snowflakes, leaves, and rain drops.
* **WordPress Admin Panel:** Dedicated settings panel to manage the active season, toggle effects, and configure standard options.
* **Live Preview:** Instantly test the animations in your admin dashboard before publishing.
* **Mobile Responsive:** Works seamlessly on desktops, tablets, and mobile phones.

---

### Pro Version Features (Premium)
Upgrade to the Premium version for ultimate customization, more seasonal themes, and custom asset support:

* **10 Seasonal Themes & Occasions:**
  * **Christmas:** Balls, Bells, Candy Canes, Gift Boxes, Santa Hats, Ribbons, Santa, Sleighs, Snowmen, Stockings, and Stars.
  * **Winter:** Snowfall, Snowflakes, Ice Cubes.
  * **Autumn:** Beautiful falling maple and golden leaves.
  * **Spring:** Bright green spring leaves.
  * **Summer:** Sun icons, summer drinks.
  * **Rain:** Realistic Rain Drops, Umbrellas, Clouds.
  * **Halloween:** Ghosts, Bats, Moon, Pumpkin lanterns, Spider webs, and Witches.
  * **Thanksgiving:** Turkey graphics.
  * **Valentine's Day:** Roses, Hearts, and Helium Balloons.
  * **New Year:** Colorful Balloons and festive celebration stickers.
* **Advanced Options:**
  * **Randomized Size:** Set minimum and maximum sizes for falling objects.
  * **Speed Control:** Control how fast or slow the objects fall.
  * **Timeout Settings:** Set auto-dismiss timers for the weather effects.
  * **Targeted Pages:** Include or exclude specific pages or posts from showing the effects.
  * **Upload Custom Images:** Upload up to 10 of your own custom falling graphics (PNG, JPEG, GIF supported).

---

## 📊 Free vs Pro Comparison

| Feature | Free Version | Pro Version |
| :--- | :---: | :---: |
| **Themes & Occasions** | 4 (Christmas, Winter, Autumn, Rain) | **10** (All seasons & major holidays) |
| **Mobile Friendly** | Yes | Yes |
| **Live Admin Preview** | Yes | Yes |
| **Custom Size Control** | Limited | **Full (Min/Max Size)** |
| **Adjustable Speed** | Standard | **Custom Speed Slider** |
| **Effect Timeout** | No | **Yes** |
| **Page Exclusion** | No (Shows on all pages) | **Yes (Specific posts/pages/home)** |
| **Custom Graphic Uploads** | No | **Yes (Up to 10 custom PNG/JPG/GIF)** |

---

## 🛠️ Installation & Setup

### Automatic Installation
1. Log in to your WordPress dashboard.
2. Navigate to **Plugins > Add New**.
3. Search for **"AWPLife Weather Effects"**.
4. Click **Install Now**, then click **Activate**.
5. Locate the **Weather Effect** settings menu in your WordPress sidebar.

### Manual Installation
1. Download the plugin zip file from the [WordPress.org Plugin Directory](https://wordpress.org/plugins/weather-effect/).
2. Go to **Plugins > Add New > Upload Plugin** in your dashboard.
3. Upload the downloaded `.zip` file.
4. Click **Install Now** and then click **Activate**.

### Getting Started
1. Navigate to **Weather Effect** in your WordPress sidebar.
2. Select your desired occasion or season under **Select A Weather / Season / Occasion**.
3. Choose the specific falling objects you wish to display.
4. (Optional) Adjust the object speed and size.
5. Click **Preview** to view the effect.
6. Click **Save** to make the effect live on your website.

---

## ❓ Frequently Asked Questions

#### Do I need coding knowledge to use this plugin?
No, the plugin is fully configure-and-save. You can choose objects, seasons, sizes, and speeds using a simple visual setting panel.

#### Does it work with my theme and page builders?
Yes, Weather Effect is fully compatible with standard WordPress themes and major page builders (such as Elementor, Divi, Beaver Builder, Gutenberg, etc.).

#### Will it affect my website load speed?
The animations run via optimized JavaScript (`snowfall.js`). For most websites, it runs smoothly without performance degradation. If you notice high browser rendering load, you can adjust the flake count down in the settings panel.

#### Can I choose which pages display the effects?
In the free version, effects are displayed globally across all pages. To target or exclude specific pages, posts, or the homepage, upgrade to the Pro version.

---

## 📜 Changelog

### 1.6.1
* **Enhancement:** Added dynamic Live Preview auto-update on dashboard settings modification.
* **Enhancement:** Added live background color picker to the Live Preview card header.
* **Enhancement:** Displayed the plugin version dynamically in the dashboard settings header.
* **UI Fix:** Removed button text underlines on all settings buttons.
* **UI Fix:** Enhanced text color contrast on primary button hover/focus/active states.
* **UI Fix:** Removed horizontal scrollbar overflow on "Our Themes" and "Our Plugins" sub-pages.
* **UI Fix:** Removed the cloud icon from the admin settings loading screen.
* **Link Fix:** Updated the "BUY NOW" button to direct to the premium signup page.
* **Clean Up:** Removed the obsolete "Try Pro Version" link.

### 1.6.0
* **Security:** Hardened administrative settings with robust capability checks and nonces.
* **Security:** Implemented output escaping and sanitization across all frontend effects.
* **Standards:** Migrated asset loading to standard WordPress hooks (`wp_enqueue_scripts` and `wp_footer`).
* **Standards:** Prefixed all constants and functions to prevent namespace collisions.
* **Feature:** Added new "Our Themes" and "Our Plugins" submenus to showcase the ecosystem.
* **Optimization:** Cleaned up unused files and optimized database queries.

### 1.5.9
* Tested WordPress 6.8.3 compatibility.

### 1.5.6
* Fixed fatal error on multisite installations.

### 1.5.5
* Fixed footer bottom spacing and scrolling issue.

---

## 🤝 Contribution & Support

* For bugs, feature requests, or queries, please post on the [WordPress.org support forum](https://wordpress.org/support/plugin/weather-effect/).
* Love the plugin? Consider buying the author a coffee at the [PayPal Donation Link](https://paypal.me/awplife).

---
*Developed with ❤️ by [A WP Life](https://awplife.com/)*
