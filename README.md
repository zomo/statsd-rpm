StatsD RPM

Heavily based on Package ioli99sc clone of Etsy statsd as RPM.

Using the rc script and the specfile but based on the upstream etsy stasd repository 


Use build.sh script to create rpm
stasd.spec.in is template for the real specfile.
Do perform a git submodule update before you build.

rpm name will be based on date of build.  (Unless someone tells me about a better way to track versions from github)





