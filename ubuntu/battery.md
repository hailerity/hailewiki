upower -i /org/freedesktop/UPower/devices/battery_BAT0| grep -E "state|to\ full|percentage"

alias bat='upower -i /org/freedesktop/UPower/devices/battery_BAT0| grep -E "state|to\ full|percentage"'
