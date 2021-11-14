# What is Creeds-Streaming?
It's a collection of repositories that I created for my streaming infrastructure.
I had a goal in mind to have a set of collections, models that are easily manageable and interchangeable with easy access to version control.

So what repo contains what? 

installation-configuration: is a collection of configurations, that are instantly deployable with ansible and terraform. That should work with one button press.

nginx-rtmp-with-auth-request-dockerimage: is a docker image that is used as a backbone image for every RTMP server.
streaming-infrastructure-experimental: is such an example that uses the RTMP server and an auth system, that I hacked together for ticket provisioning of live streams. (Provisioning system private, prevent for security leaks)
base-auth: just a template is a nodejs-express server that you have to pass some validation system into. And its acts as a relay to the channel so we can hide the stream key. 

base-rtmp: just RTMP server with a little html page to display.
