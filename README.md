# rcrs-web-viewer
RoboCup Rescue Simulator Web Viewer

Thanks to the great work from @amiraslanaslani and arman. 

I have just make it simple to  upload to the cdn server easily and add url parameter.
It is accessible from https://cdn.robocup.org/rsim/public/viewer/
to load another log instead of the test log, you can easily use jlog parameter.
example:
https://cdn.robocup.org/rsim/public/viewer/?jlog=https://cdn.robocup.org/rsim/public/viewer/testlogs/Aura_kobe__1602264875299_viewer_event_log.jlog.zip

You can specify any URL for the jlog but please note that you have to enable CORS for cdn.robocup.org and also the URL has to be secure (use HTTPS).