### v0.4.0
- added ability to persist history either to filesystem or to google drive
- added option to disable internal timer
- various fixes on internal timer average calculation
- now also Energy uses the global internal timer
- added initialTime and getter, for external management of characteristics 11A (last opening/activation on Door/Motion)

### v0.3.8
- improve protocol to ensure prompt download of data even if Eve is missing a single entry (before this commit, two new entries were necessary for Eve to start downloading)

### v0.3.7
- fix to allow showing last activation in Door and Motion

### v0.3.6
- added compatibility with platfoms

### v0.3.5
- added internal global timer

### v0.3.4
- added Door, Motion, Room and Thermo support

### v0.3.3
- cleanup

### v0.3.2
- first NPM release

### v0.3.1
- first fully working version

### v0.3.0
- update readme, fix package.json
- added transmission of several entries per query

### v0.2
- added support for memory rolling

### v0.1
- initial commit (only Energy and Weather)
