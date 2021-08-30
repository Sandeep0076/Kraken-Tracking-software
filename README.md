# Kraken-Tracking-software
KrakenProject

The desktop application (Kraken.me Desktop) is a C# Windows application that tracks user activity data and document content which are later used as the input for the activity
detection and mapping algorithm.
Tracking, storing and sending data to the Kraken.me Server is done in background full automatically, so  no user interaction is needed.

This platform aggregates and stores different sensor data from different sources like mobile devices and the desktop using a simple app that traces the users behavior and collects which resources are accessed by the user. It delivers information like which app is currently running, what user interface objects are clicked and what websites and documents are visited or edited by the user. All collected information is stored and aggregated on a secure server. Based on this platform, we will see how the system is integrated and designed, as well as how good the system performs on real user data.

 If the user starts the application for the first time, the user can register himself using a social network login. The desktop client currently supports Facebook, Twitter and Google+ for authentication. Depending on if the user is unknown, a new user is created. The server then returns a unique user identifier, called Kroken. The Kroken is the framework wide hentication token which represents a single user. Besides the user identification token, a unique device identifier is created for each device, so we can further store which device delivers which data.
Kraken.me Desktop monitor tracks two different kinds of data: (1) it collects information on how users are using their computer. Therefore, it tracks how long and what application the user is using, what user interface controls are clicked and when and what files are accessed or/and edited. This collection of data is called activity data. Secondly, (2) it uses application specific handlers to extract more detailed content from open applications. This could be the content of an email, the start and end date of a calendar entry or the content of a document. This type of data is called content data.
The following list shows the data types for which the user can decide if data should be collected or not:
• Calendar entries
• Tasks
• Keyword extraction
• Full-text
• Geo-location data


