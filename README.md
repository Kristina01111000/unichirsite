# unichirsite
update to site



- needs an appointment booker
- updated pictures
- contact us page needs to be fixed
- probably using astra theme




old stuff:
  - check out univ. chir. site to see if the theme is fixed
  - use ftp to see if disabling plugins, theme fixes the issue
  - looks like the theme is the issue, not the plugins, switch to 2022 theme
  - changed names of widget and plugin folders in theme, was able to gt into wordpress backend
  - he wants a copy of the site made before changing things
  - deleted 2011 theme from file manager, so that works
  - made a copy of the site in the folder, can't put new plugins in, so i can't do it that way
  - manually changing name of theme makes a fatal error which puts a white screen on the page
  - copy of one warning message "Warning: Declaration of TFuse_Walker_Category_Checklist::start_lvl(&$output, $depth, $args) should be compatible with Walker::start_lvl(&$output, $depth = 0, $args = Array) in /home/customer/www/syracusenaturalhealing.com/public_html/wp-content/themes/medica-parent/theme_config/widgets/TFuse_Widget_Selected_Categories.php on line 6"
  - changing name of widget folder in parent theme removes the top lines of site error message
  - can't change any pages, the error message pops up when i try to edit the page
  - renaming the weird folder above the themes folder doesn't do anything
  - right now the site looks ok except for the appointments page
  - switched to 2019 model of site
  - will try to downgrade to a previous version of wp -> didn't work, still a fatal error
  - neither parent or child theme are working, both put a few error messages on the screen and don't show anything else
  - put one of the wordpress automatic themes up for the site
