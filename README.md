# How this parser work
This repository is a parser file for converting raw syslog events of Wallix PAM system to CEF(Common Event Format) format.
First you must send from Wallix PAM all events as syslog to a syslog server (linux OS) and store received syslog events to a file. Then install the ArcSight Smart Connector Flex File type and browse that syslog stored file. After that, use the wallixpam.sdkrfilereader.properties file in the <SmartConnector_Path>/current/user/agent/flexagent. Then change some values in  agent.properties content like sdkfilereader to sdkrfilereader and then start the connector.
Enjoy It!
