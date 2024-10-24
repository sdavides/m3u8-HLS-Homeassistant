# M3uPlayer addon HomeAssistant

  M3uPlayer Homeassistant.

  *Player m3u8 list or single video*

## Installation

Add custom component remote repository:
"https://github.com/sdavides/m3u8-HLS-Homeassistant"


![immagine](https://github.com/user-attachments/assets/1f100850-d7db-40ca-a036-97254154b408)


## Configuration

  * Playlist or Video (url type)
  
    * enable=playlist
      
     * disable=video

  * http URL m3u

  * Enable/Disable fields

  or create playlist "file.m3u" on "/addon_configs/537fde62_m3u_player/"

## Update/Apply new config

  * Delete "file.m3u"
    
    * ( usually into "/addon_configs/537fde62_m3u_player/" from SAMBA )

  * Update config

  * Restart addon


## Example card:

           type: iframe
           url: ../537fde62_m3u_player
           aspect_ratio: 100%

     
## Result

![immagine](https://github.com/user-attachments/assets/4d431123-cc07-4aec-bd4a-88bc0c2f7635)

![immagine](https://github.com/user-attachments/assets/b8aa32d7-1de8-4705-ae04-94cfbf6e83af)

