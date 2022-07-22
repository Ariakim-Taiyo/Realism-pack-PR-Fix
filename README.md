# Realism-pack
This is a bookmarklet addon. A tutorial on how to install and run bookmarklets is on my YouTube (channel name is NVB9 2).</br>
**Note:** please wait until GeoFS has fully loaded before clicking on the bookmarklet. If it is clicked before GeoFS is fully loaded, it will not work since it contains a 'ui.notification', and if 'ui' is not defined (which it isn't until GeoFS loads fully), the addon will break.

This combines several addons that enhance the realism of GeoFS. In this one bookmarklet is contained:

- AP++
- You black out when you pull more than 9 Gs
- If you strike the rotor blades of a helicopter on the ground, it crashes
- A bug fix for the F-14 and XB-70
- F-14 swing wing physics
- Lift-based wingflex for most CC airliners
- Falcon 9 control fix
- A massive realism fix for the HAL Tejas
- Automatic control presets (better yaw control on ground, coordinated flight in air) (toggleable)
- Mach buffet (only works with manual weather on, somewhat superfluous since AP++ contains forced Mach tuck. I'll be working on that.)
- Turbofan engines now take longer to spool up to full power between 10% and 70% RPM
- Lag reduction
- Other minor improvements

There is also a bookmarklet version of FMC available seperately.

There are a few things that have been removed, they will be added back when I can get them to work. You may also notice incomplete stuff in the code; that's going to be finished at some point as well.

If anti-aliasing is off, the flight recorder cache is cleared every 100 milliseconds, making the flight recorder unusable. To re-enable the flight recorder, turn on anti-aliasing. (I haven't confirmed that this works lol)

Make sure you use the latest version of this; I update this addon rather frequently.

Also, the autopilot portion of AP++ is sorta bugged with GeoFS 3.0, you kinda have to fiddle with it and it doesn't work all the time.
