# RSG2_Plugin_DisplayGallery
Displays a gallery in an article.

This plugin will replace {rsg2_display: template, GID} or {rsg2_display: template, GID, parameter=value, parameter=value, ...} in an article with the corresponding RSGallery2 gallery using the template specified, with as many parameters as you specify.
  Template: The name of the template you want to use (required; in a default installation 'semantic' will work).
  GID:  Backend > Components > RSGallery2 > Galleries: use the number from the ID column (required)
  Parameter: (optional, for advanced use only) you can add any configuration parameter, e.g. displaySearch=0, display_thumbs_maxPerPage=4, display_thumbs_colsPerPage=2. A list of parameters is available when debug is turned on in the RSGallery2 Configuration, then a button 'Config - View' shows up in the Control Panel which will give you a list of parameters and their current setting. 
Note: These are not the slideshow parameters! When the given template does not exist, or the given gallery does not exist or is unpublished, the plugin will show nothing unless the option Debug is turned on.  

Examples: 
  {rsg2_display: semantic, 10} 
  {rsg2_display: slideshow_parth, 6} 
  {rsg2_display: semantic, 10,displaySearch=0,display_thumbs_maxPerPage=4,display_thumbs_colsPerPage=2}

Please do not forget to enable the Plugin in the Plugin Manager!
