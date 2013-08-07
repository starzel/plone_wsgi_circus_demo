This is pretty minimal, it's a bit stupid to not have
zeoclient and zeoserver here, because you can't just
add a worker in circus the way it is running now.

While it works, it is just a proof of concept, and
I only added a Plone site as a test.

To start circus, run

./bin/circusd circus.ini

This keeps circus in the foreground.

You can experiment with circusctl which is similar to
supervisorctl.
Additionally, there is circus-top to experiment with,
and the awesome web interfae that listens on
http://localhost:8080

Have fun
