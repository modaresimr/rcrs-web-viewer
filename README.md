# rcrs-web-viewer
RoboCup Rescue Simulator Web Viewer

Thanks to the great work from @amiraslanaslani and arman. 

I have just make it simple to  upload to the cdn server easily and add url parameter.
It is accessible from https://cdn.robocup.org/rsim/public/viewer/

To load another log instead of the test log, you can easily use jlog parameter.
example: [viewer/?jlog=HTTPS://sampleURL](https://cdn.robocup.org/rsim/public/viewer/testlogs/Aura_kobe__1602264875299_viewer_event_log.jlog.zip)

A working example with specifying jlog parameter: [here](https://cdn.robocup.org/rsim/public/viewer/testlogs/Aura_kobe__1602264875299_viewer_event_log.jlog.zip)

It is possible to specify any URL for the jlog but please note that the CORS should be enable for cdn.robocup.org and also the URL has to be secure (use HTTPS).