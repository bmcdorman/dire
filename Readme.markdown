How to Use
==========

Send a JSON string of the following form over stdin:

`{"a": {"lat": startLat, "lng": startLng}, "b": {"lat": endLat, "lng": endLng}}`

To begin the route, close stdin by ending the stream programmatically or typing `<Enter> <Ctrl-D>` on the terminal.
  
Error Conditions
================

If there is no route available, the process will exit with code `1`.