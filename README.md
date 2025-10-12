# My-android-journey

just my journy on android

Not a project

DISPLAY

#Display in termux

termux-x11 :0

#Display in proot

export DISPLAY=:0



AUDIO

#Audio in termux

pulseaudio --start --exit-idle-time=-1

#Audio in proot

export PULSE_SERVER=127.0.0.1



Hardware Aceleration

#in Termux

virgl_test_server_android &

#in proot

export GALLIUM_DRIVER=virpipe
export LIBGL_ALWAYS_INDIRECT=1
export MESA_GL_VERSION_OVERRIDE=3.2




