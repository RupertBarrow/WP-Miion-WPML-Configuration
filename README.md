# WP Miion WPML Configuration
WPML configuration for the translation of the Wordpress Miion theme

## Why is this even necessary ?
It seems that Wordpress theme providers who use the Elementor page builder (and most certainly others) do not provide all the correct items to make the websites translatable. The extra configuration provided here seems to make things work correctly.

## Disclaimer
This solution was provided to me by the WPML support team.
It is documented here :
https://wpml.org/documentation/support/language-configuration-files/how-to-register-page-builder-widgets-for-translation/

However, there may be a better way of doing this; I am not an expert.

## Environment
- Wordpress 6.1
- WPML 4.5.13
- Miion theme 1.2.3 (last update 16 june 2022) for Elementor : https://themeforest.net/item/miion-multipurpose-wordpress-theme/24578107

## How to use this
- open Wordpress
- go to the WPML > Settings menu, Custom XML Configuration tab
- paste the contents of the wpml-config-custom.xml here; if there is already code there, you will need to merge
