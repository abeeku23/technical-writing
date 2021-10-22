 
### Cloud Extract
Build ELT pipelines from cloud applications to your data warehouse. All the Cloud Extract sources support sending data only to one data warehouse destination. If you wish to send data to multiple warehouses, you can configure multiple Cloud Extract sources with the same settings and connect them to each data warehouse. Many sources to one warehouse destination

### Connections
RudderStack lets you set up connections between your preferred event data sources and destinations. With this feature, you can build efficient data pipelines across your entire customer data stack. This is a one-on-one directional flow between a source and destination
### Destinations
A destination is a tool or application where you want to send the data via RudderStack. These include the following:
- Data warehouses
- Analytics platforms
- CRMs
- Marketing platforms, etc

### Directory
This option lists all the available sources and destinations supported by RudderStack which you can use to set up your data pipelines

### Event Streams
RudderStack's Event Streams allow you to collect your event data from all of your sites and applications and route it to a wide array of customer tools and data warehouses via RudderStack. One source to multiple destinations
 
### RudderStack Cloud
This is a premium service that allows for the use of the following Sources actions:
- Cloud Extract
- Warehouse Actions

### Sources
Sources are the tools or platforms from which you can send event data to RudderStack. These events can then be routed (with or without transformation) into your data warehouse or third-party destinations for analytics and other activation use-cases. A source also refers to a platform or an application (web, mobile, server-side, or a third-party cloud app) from which RudderStack tracks and collects your event data. Popular sources include:
- JavaScript
- Python
- AuthO
- PHP
- PostHog, etc


### Syncs
This syncs updates in the sources or destination of a pipeline

### Teammates
RudderStack's Teammates feature enables you to add and manage other users in your current RudderStack workspace. It facilitates easier collaboration between you and other team members of your organization in using RudderStack effectively.

### Token
This is needed to consume all the public RudderStack APIs which are associated with your account.

### Transformations
‘Transformations’ is one of RudderStack's key features. It gives you the ability to code custom JavaScript functions to implement specific use-cases on your event data, like:
- Filtering/sampling events.
- Enriching events by implementing static logic or leveraging an external API.
- Cleaning/aggregating data.
- Data masking or removing sensitive PII information in the events to ensure data privacy.
- Implementing external actions on the events using an API. 

Transformations can be used across your Event Stream, Warehouse Actions, and Cloud Extract pipelines. With this option, you can write your own JavaScript functions to transform your events in a destination-specific format. You can also create your own libraries - a RudderStack feature that allows you to reuse the code written for a transformation in other transformations.

### Warehouse Actions
With RudderStack Warehouse Actions, you can leverage the already processed customer data residing in your data warehouse and route this enriched information to your desired destinations. With this feature, you can configure your data warehouse as a source on the RudderStack dashboard, select the right data and then sync this data to all the supported destinations. You can connect only one destination to a Warehouse Actions source. Also, note that this destination should not be connected to any other source (including Event Stream sources.) If you want to send data from a warehouse source to multiple destinations, we recommend creating multiple copies of the source with the same settings and connecting them with each of the destinations. You cannot connect a Warehouse Actions source to a warehouse destination in RudderStack.

