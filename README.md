# simple-webapp-color
Simple Web Application developed in Flask with Colorful background

Add the following annotations to the route to get round robin loadbalancing


haproxy.router.openshift.io/disable_cookies: 'true'
</br>
haproxy.router.openshift.io/balance: roundrobin

