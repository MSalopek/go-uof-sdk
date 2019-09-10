# uof
Betradar unified odds feed Go SDK


### Why

From the Betradar [docs](https://docs.betradar.com/display/BD/UOF+-+SDK): 

SDK benefits over protocol/API
 * The SDK hides the separation between messages and API-lookups. The client system just receives the message objects where all information is prefilled by the SDK caches, and in some cases looked up in the background when the client system requests some more rarely requested information.
 * The SDK takes care of translations transparently. The client system just needs to define what languages it needs.
 * The SDK takes care of dynamic text markets and outright markets automatically, which requires some extra logic and lookups for someone not using the SDK.
 * The SDK handles initial connect and state, as well as recovery in case of a temporary disconnect. This needs to be handled manually by someone not using the SDK.
 * The SDK provides an up to date cache of each sport-events current status that is updated automatically.



### Staging environment weekend downtime

The integration environment is available 24/5, Monday to Friday.  
During the weekend there will be some planned 2 hour disconnections at fixed times:  
Saturday: 14:00 - 16:00 UTC and 20:00 - 22:00 UTC  
Sunday: 00:00 - 02:00 UTC and 13:00 - 15:00 UTC  
