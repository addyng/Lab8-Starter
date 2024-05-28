# Lab8-Starter

Addy Ngo

## How are graceful degradation and service workers related?

Graceful degradation and service workers are related because they both attempt to make the experience of the web-app still have some functionality when not running at full capacity. In the case of graceful degradation, the web-app has full functionality when `JavaScript` can be ran, but will still maintain some functionality when `script` is disabled, such as through the `HTML` and `CSS`. As for service workers, service workers address the issue of not having internet. Network requests require the web-app to be connected to the internet, but service workers offer the ability to still display and get information while offline by intercepting those network requests and storing the data in a cache. The caveat is that the web-app has to be connected to the internet at least once in order for the service workers to store that initial data in cache. So, both graceful degradation and service workers try to prevent the web-app from becoming completely not functional when `script` is disabled and there is no internet connection, respectively.