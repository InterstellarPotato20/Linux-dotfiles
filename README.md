# Linux-dotfiles
Dotfiles modified for personal use. To be saved in ~/.config. Currently includes files for Openbox WM and tint2 panel.

## Edits in rc.xml for keybindings
W-s = fsearch    <keybind key="">
      <action name="Execute">
        <command>fsearch</command>
      </action>
    </keybind>    <keybind key="W-l">
      <action name="Execute">
        <command>openbox --exit</command>
      </action>
    </keybind>
    <keybind key="W-x">
      <action name="Execute">
        <command>xfce4-appfinder</command>
      </action>
    </keybind>
    <keybind key="W-e">
      <action name="Execute">
        <command>nemo</command>
      </action>
    </keybind>
    <keybind key="W-t">
      <action name="Execute">
        <command>xfce4-terminal</command>
      </action>
    </keybind>
    <keybind key="W-q">
      <action name="Execute">
        <command>firefox</command>
      </action>
    </keybind>
    <keybind key="W-c">
      <action name="Execute">
        <command>mousepad</command>
      </action>
    </keybind>
    <keybind key="W-f">
      <action name="ToggleMaximize"/>
    </keybind>
