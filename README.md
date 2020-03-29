# CDDLC
Controller-Drone Data Link Communication

Due to number of requests we are publishing list of currently supported tactical CDDLC statuses. 


| Status | Description |
| --- | --- |
| created | flight has been sent and is registered in the system |
| inQueue | flight is awaiting ATC decision |
| accepted | ATC accepted flight data |
| acceptedAck | pilot confirms ATC accept |
| seen | FIS confirmed flight registration |
| atcModified | ATC modified data |
| atcModifiedAck | pilot confirms ATC modifications |
| rejected | ATC rejects flight |
| rejectedAck | pilot confirms ATC rejection |
| cancelled | pilot ends flight  |
| lostControl | pilot reports lost control |
| landNow | ATC orders to land |
| landingAck | pilot confirms landNow order |

List of statuses and naming convention is subject to change.

© [Droneradar](https://droneradar.eu/) 2015-2020
