
# PC Remote Card

**Sample overview:**

<img src="https://github.com/catgirlkara/pc-card/blob/master/assets/screenshot.png" alt="screenshot" width="300"/>

Add this to your lovelace configuration if your tv is a Samsung Smart TV:

```yaml
type: custom:pc-card
entity: media_player.tv
title: Example 2
power_row:
  - power
channel_row:
  - channel_up
  - info
  - channel_down
apps_row:
  - netflix
  - youtube
  - spotify
volume_row: slider
navigation_row: touchpad
source_row:
  - return
  - home
  - source
media_control_row:
  - rewind
  - play
  - pause
  - fast_forward
```

Look at [README](https://github.com/usernein/tv-card/blob/master/README.md) for more information
