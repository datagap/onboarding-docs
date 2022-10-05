# Domain Driven Design

## Introducing Commands, Events, and Messages

**Commands** are imperatives; they are requests for the system to perform a task or action. For example, “book two places for conference
X” or “allocate speaker Y to room Z.” Commands are usually processed
just once, by a single recipient.

**Events** are notifications; they report something that has already happened to other interested
parties. For example, “the customer’s credit card has been billed $200” or “ten seats have been booked
for conference X.” Events can be processed multiple times, by multiple consumers.

Both commands and events are types of message that are used to exchange data between objects.
In DDD terms, these messages represent business behaviors and therefore help the system capture
the business intent behind the message.

