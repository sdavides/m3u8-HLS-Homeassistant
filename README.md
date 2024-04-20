# m3u8-HLS-Homeassistant
Goal: Play m3u8 media on HomeAssistant

## Install ##
* Download "m3u8" folder on /config/www/ 
* Edit m3u url inside "test.html"
* Create card webpage on HomeAssistant
     
      type: iframe
      url: /local/m3u8/test.html
      aspect_ratio: 50%'
      
## TIPS ##
* Autoplay:
    * test2.html (autoplay disable)
* Poster player:
    * add poster="/IMAGE.png" on <video> tag

## Test player ##
* Open with browser:
     * http://'homeassistant'/local/m3u8/test.html


 ## Result ##
![immagine](https://github.com/sdavides/m3u8-HLS-Homeassistant/assets/31100253/efd8183d-961e-45bc-abfd-000730ebb154)


## See also ##

[AqaraPOST-Homeassistant](https://github.com/sdavides/AqaraPOST-Homeassistant/)

[EPGItaly-Homeassistant](https://github.com/sdavides/EPGItaly-Homeassistant/)

     

