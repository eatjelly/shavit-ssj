# shavit-ssj
rework of Nairdas ssj plugin that is a rework alkatraz' ssj plugin

changelog
- moved calculations out of OnPlayerRunCmd to OnPlayerRunCmdPost in order to support my auto strafer
- (for dev) there is still info grabbed from runcmd that is important, it is just updated later. also Hook Player_Jump runs after runcmd but before runcmdpost, so I had to move the printouts to runcmdpost
- early version of gain colors added, will make cvar later i guess or selectable
- fixed time option, fixed height option, fixed jumps problem
