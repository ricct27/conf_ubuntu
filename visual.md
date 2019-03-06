## Icons
```
https://www.omgubuntu.co.uk/2019/02/4-new-linux-icon-themes
```
## Isolate [Workspaces](https://askubuntu.com/questions/464946/force-alt-tab-to-switch-only-on-current-workspace-in-gnome-shell) 
```shell
sudo apt-get install dconf-editor
dconf-editor
```
Change the value of org/gnome/shell/extensions/dash-to-dock > isolate-workspaces , > multy-monitor
