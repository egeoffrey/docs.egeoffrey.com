# Configuration Workflow

As you install eGeoffrey, it has a nice look & feel but tells you nothing about your house yet. eGeoffrey's customization is really simple, leverages a set of pre-built modular components for integrating with your existing devices and follows always a structured workflow.

What you want to get eventually is a visual representation of something but to get there you have a few steps to go through:

1. **[Define what you want to do and install the relevant packages](/configure/packages)**: eGeoffrey is modular and its capabilities are build up in self-contained components. Those are what you see listed in the [Marketplace](https://marketplace.egeoffrey.com/). Define first what you want to do (e.g. get temperature measures from the Internet, trigger a MySensors relay, etc.), find in the Marketplace the package providing this capability (e.g. the module in eGeoffrey's vocabulary) and install it;
1. **[Configure the newly installed module](/configure/modules)**: once the package is installed, the new functionalities will be ready to be leveraged. Most of the modules tough requires some basic configuration to start up (e.g. the API key of the cloud-based weather service, the serial port to connect to, etc.). One special kind of module is called "service", this is the one your sensors can leverage to get data in automatically;
1. **[Add a new sensor and associate it to a service](/configure/sensors)**: register a new sensor, give it a name, tell eGeoffrey which format it has to expect your data in, if it has to apply any automatic aggregation or retention policies, which service it has to be associated with for getting data in or performing actions;
1. **[Once the sensor starts getting data, visualize it](/configure/pages)**: customize the web interface to make your data showing up in the way you like the most. Add new pages and different widgets to e.g. see the latest value of a sensor, control your actuators, etc.
1. **[Set conditions which would make rules triggering notifications](/configure/rules)**: execute specific tasks periodically or when given conditions are met by evaluating your sensors' data and generate notifications;