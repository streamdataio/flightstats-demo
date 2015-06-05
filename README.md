# flightstats-demo
Demo using GoogleMap and flightstats API to display realtime information on airports (departures, arrivals, weather)

Follow these steps to make it work:

1- Create a free FlightStats developer account at https://developer.flightstats.com, then register an app to get your own App ID and App Key.

2- Create a free account on streamdata.io to get your Public and Private Keys at https://portal.streamdata.io/#/register.

3- Edit flightstats-demo.html and replace [YOUR_FLIGHTSTATS_APP_ID], [YOUR_FLIGHTSTATS_APP_TOKEN], [YOUR_STREAMDATA.IO_PUBLIC_KEY] and [YOUR_STREAMDATA.IO_PRIVATE_KEY] with the appropriate keys.

4- Save and launch flightstats-demo.html in your favorite browser (works with Chrome, Firefox and Safari).

Note: If you want to use chrome and launch you must enable "Cross-Origin Ressource Sharing" by installing Allow-Control-Allow-Origin: * Plugin (https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi)

You are done! You will see all airports for the selected country (France as default). When clicking on an aiport you will see
detailed information such as list of flights (departures, arrivals) and weather updated in realtime thanks to streamdata.io.
