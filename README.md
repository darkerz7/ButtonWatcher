## Button Watcher
### Buttons Watcher with Bans and Menus. Watching func_button, momentary_rot_button, func_rot_button. Reacts: Use and Damage
Cvar | Parameter | Description
--- | --- | ---
`sm_buttons_view` | <0/1> | Enable/Disable Global the display Buttons
`sm_buttons_timer` | <0.0/10.0> | Timer before showing the pressed button again

Admin Command | Description
--- | ---
`sm_bban <target> [<time in minutes>]` | Buttons Ban on time. (-1 temporarily, 0 permanently, 1-... - ban on time)
`sm_unbban <target>` | Buttons UnBan
`sm_bbanlist` | Currently BBanned Statistic

Client Command | Description
--- | ---
`sm_bstatus` | Show status client's Buttons Ban
`sm_buttons` | Enable/Disable showing the client the button clicks
