# polybar-spotify

This polybar module shows details regarding the currently playing song on Spotify. The unique feature of this module is that the text displayed is constantly scrolled to save space on the bar. This is something that is not found in other spotify modules I came across. Also, this module uses [playerctl](https://github.com/altdesktop/playerctl) to do all the work and hence, no >100 line scripts which do all the work themselves. Only one line to fetch the required metadata in the format that you like and another line to scroll the fetched text using [zscroll](https://github.com/noctuid/zscroll).

![](screenshots/demo.gif)

## Dependencies

- [playerctl](https://github.com/altdesktop/playerctl) - To interface with Spotify
- [zscroll](https://github.com/noctuid/zscroll) - To scroll the fetched text