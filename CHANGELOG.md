# Change Log

## [v1.0.3]
* Change _transport_ from _serverSentEvents_ to _webSockets_ for _start_ step
* Implement call to _SignalR_ method _SubscribeToSummaryDeltas_ for tickers subscription (update are not sent automatically anymore by Bittrex)

## [v1.0.2]
* Ensure _disconnected_ and _connected_ events are properly emitted
* New method to retrieve SignalR connectionId
* Changes to logged messages