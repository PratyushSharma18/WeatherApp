# WeatherApp
# It is an Android Kotlin-based realtime data access application that shows explicit weather data of your current location and also gives the weather information of any searched location worldwide. It shows atmospheric pressure, territory location, weather conditions, visibility distance, sunset and sunrise time, relative humidity, precipitation in different units, dew point, wind speed, and directions.
- android:imeOptions can set the text/id of the button displayed near the space key to some pre-defined values (E.g. actionGo set the key label to Go and the id to 2)

- Separate packages(Activities, Models and Utilities)
- Models package contain data classes that being generated from JSON data fetched from current weather data API. 

- Retrofit

- Usage of DataBinding Library (The Data Binding Library is a support library that allows you to bind UI components in your layouts to data sources in your app using a declarative format rather than programmatically).


- Usages of Input method framework (IMF) architecture:

-> The input method manager as expressed by this class is the central point of the system that manages interaction between all other parts. It is expressed as the client-side API here which exists in each application context and communicates with a global system service that manages the interaction across all processes.

-> An input method (IME) implements a particular interaction model allowing the user to generate text. The system binds to the current input method that is in use, causing it to be created and run, and tells it when to hide and show its UI. Only one IME is running at a time.

-> Multiple client applications arbitrate with the input method manager for input focus and control over the state of the IME. Only one such client is ever active (working with the IME) at a time.

- Usages Of ApiUtilitiesObjectClass

- ACCESS_COARSE_LOCATION gives you last-known location whereas ACCESS_FINE_LOCATION It gives you live/ real-time location.

- GPS_PROVIDER or NETWORK_PROVIDER access by enabling through location manager.

- @RequiresApi - Denotes that the annotated element should only be called on the given API level or higher. 
