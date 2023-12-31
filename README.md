# delivery_date
This project is a mod on the plugin "Delivery & Pickup Date Time for WooCommerce" to allow setting a delivery date in the past. 
https://br.wordpress.org/plugins/woo-delivery/

I did some digging in the code and modified a couple of files to achieve what I needed. If anyone is interested, the new code can be accessed though the link below:
https://github.com/cloter/delivery_date/blob/main/woo-delivery-19-06-2023.zip

The files that I changed are listed below (all changes have a comment line “NEOORBIT START” and “NEOORBIT END” around the mods).
- class-coderockz-woo-delivery-admin.php
- coderockz-woo-delivery-admin.js
- class-coderockz-woo-delivery-public.php
- coderockz-woo-delivery-public.js
- coderockz-woo-delivery-admin-display.php

Obs.: One interesting complement to this mod is to put a ‘days chooser’ in the settings page (delivery only), to allow the admin to set how far in the past to allow the dates (for the customer and for the admin). In my code the variables ($beginning_date_admin and $beginning_date_public) are hardcoded in the classes:
- Coderockz_Woo_Delivery_Admin
- Coderockz_Woo_Delivery_Public

Update, 06/20/2023: The possibility to adjust the number of days in the past for delivery (per observation above) has been implemented in the settings page of the modified Delivery Date plugin. The plugin zip file has been updated.

I hope it can be useful to other people.
