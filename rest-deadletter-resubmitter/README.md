rest-deadletter-resubmitter
===========================

An example of combining Camel's Restlets with the `pollEnrich` Content Enricher EIP to move messages between queues. This would, for example, provide a simple REST endpoint to resubmit a message from a dead letter queue back to an inbound queue to re-attempt processing.
