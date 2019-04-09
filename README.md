# SkiaGL as Default Renderer (Oreo)

This module sets OpenGL (Skia) as the default renderer in Android Oreo (8.x). It does that by adding ```debug.hwui.renderer=skiagl``` to ```build.prop```. So you no longer need to manually choose SkiaGL after every reboot.

It should work on any device running Oreo or higher. Pie and Q already use SkiaGL by default so there's no need to flash this module if your device runs either of those versions.
