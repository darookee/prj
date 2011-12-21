prj
===

I have a special development layout in tmux (big top pane, two smaller bottom panes) and wanted to automate the directory changing and starting of vim (press C-D, enter project name and get the dev-pane-layout with the right directories set) but find was unreliable so I started learning python and built this (possible very bad implemented) script

Usage
===

    ./prj add --scan

Scans ~/Dev/ for projects, can be used for recursive scanning

    ./prj list

List all projects

    ./prj info <projectname>

Shows the path of the project
