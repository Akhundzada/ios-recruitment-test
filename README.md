# iOS Recruitment Test

The task is to create an app with two screens which can be selected from TabBar. The first screen will show online price quotes taken from the socket.

### Online quotes

Use https://github.com/socketio/socket.io-client-swift library to connect to WebSocket https://q.investaz.az/live

Required:
* Data received from WebSocket must be in a table and updated in real time
* A visual indicator in the UI showing the connection to WebSocket

Optional:
* Cache data that was received from WebSocket (SQL Database must be used)

### Quotes Converter

Second screen will show the currency converter.
It should have an option to select the major currency and input price for that currency.

Secondary currency should be able to be selected from the menu with the main currency being converted to it.

##### Currency list
https://valyuta.com/api/get_currency_list_for_app
DATE = `YYYY-MM-DD`

##### Currency rates
https://valyuta.com/api/get_currency_rate_for_app/{CURRENCY}/{DATE}

Please send the link to repository and wait for the feedback
