<?xml version="1.0" encoding="UTF-8"?>

-<simulator-profile>


-<general>


-<rates>


-<item>

<name>⭐cis-_-⭐</name>

<rate>16456556:33265506</rate>

</item>

</rates>

<direction>1</direction>

<rateindex>1</rateindex>

<cardindex>9</cardindex>

</general>


-<latency>

<enabled>true</enabled>

<type>0</type>

<delayfrom>100</delayfrom>

<delayto>0</delayto>

<impact>50</impact>

<correlation>0</correlation>

</latency>


-<loss>

<enabled>true</enabled>

<impact>500</impact>

<type>0</type>

<burstlo>28</burstlo>

<bursthi>28</bursthi>

</loss>


-<duplication>

<enabled>false</enabled>

<impact>500</impact>

<type>0</type>

</duplication>


-<reordering>

<enabled>true</enabled>

<impact>500</impact>

<gap>25</gap>

</reordering>


-<corruption>

<enabled>true</enabled>

<impact>500</impact>

<type>2</type>

<berval>10</berval>

<time>0</time>

</corruption>


-<capture>

<enabled>false</enabled>

<before/>

<after/>

<writemode>0</writemode>

<snaplen>25558</snaplen>

</capture>


-<blocking>

<enabled>true</enabled>

<portlist>U1,1,U1-6672</portlist>

</blocking>

<groups/>


-<filter>

<enabled>1</enabled>

<protocol>2</protocol>

<vlanid>0</vlanid>


-<source>


-<address>

<type>3</type>

<address-1>0.0.0.0</address-1>

<address-2>0.0.0.0</address-2>

<mac>000000000000</mac>

<groupid>-1</groupid>

</address>


-<port>

<type>0</type>

<items/>

</port>

</source>


-<destination>


-<address>

<type>3</type>

<address-1>0.0.0.0</address-1>

<address-2>0.0.0.0</address-2>

<mac>000000000000</mac>

<groupid>-1</groupid>

</address>


-<port>

<type>0</type>

<items/>

</port>

</destination>

</filter>

</simulator-profile>
