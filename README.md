----
----

#  M3uPlayer-Homeassistant addon #

![images](https://github.com/user-attachments/assets/5a658414-ff3d-4546-a655-fbd2f124e968)


  * [M3uPlayer addon](https://github.com/sdavides/m3u8-HLS-Homeassistant/tree/main/addon-M3uPlayer/README.md)
  
----

----

# m3u8-HLS-Homeassistant
Goal: Play m3u8 media on HomeAssistant

  * Playlist or Video

    *m3u8, mpd, mp4, mov, webm*
    
    *playlist m3u*


## Install ##
* Download folder "m3u8_player" on /config/www/
  
   Edit url src on index.html

   delete: *style="display:none"* for more fields

   or create playlist on "file.m3u"
  
           type: iframe
           url: /local/m3u8_player/index.html
           aspect_ratio: 70%

      
## TIPS ##
* Autoplay:
    * remove autoplay on \<video\> tag
* Poster:
    * add poster="/IMAGE.png" on \<video\> tag

## Test player ##
* Open with browser:
     * http://'homeassistant'/local/m3u8_player/index.html
     * http://'homeassistant'/local/m3u8/index.html


 ## Result ##
![immagine](https://github.com/user-attachments/assets/85d21159-13e2-4f85-8a0d-615381adbd87)




## See also ##

[AqaraPOST-Homeassistant](https://github.com/sdavides/AqaraPOST-Homeassistant/)

[EPGItaly-Homeassistant](https://github.com/sdavides/EPGItaly-Homeassistant/)

     

