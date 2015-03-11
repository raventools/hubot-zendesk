# hubot-zendesk

Queries Zendesk for information about support tickets

See [`src/zendesk.coffee`](src/zendesk.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-zendesk --save`

Add **hubot-zendesk** to your `package.json` file:

```javascript
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-zendesk": "*"
}
```

Then add **hubot-zendesk** to your `external-scripts.json`:

```json
["hubot-zendesk"]
```

# Configuration:
```   HUBOT_ZENDESK_USER
   HUBOT_ZENDESK_PASSWORD
   HUBOT_ZENDESK_SUBDOMAIN
```
# Commands:
```   hubot (all) tickets - returns the total count of all unsolved tickets. The 'all' keyword is optional.
   hubot new tickets - returns the count of all new (unassigned) tickets
   hubot open tickets - returns the count of all open tickets
   hubot escalated tickets - returns a count of tickets with escalated tag that are open or pending
   hubot pending tickets - returns a count of tickets that are pending
   hubot list (all) tickets - returns a list of all unsolved tickets. The 'all' keyword is optional.
   hubot list new tickets - returns a list of all new tickets
   hubot list open tickets - returns a list of all open tickets
   hubot list pending tickets - returns a list of pending tickets
   hubot list escalated tickets - returns a list of escalated tickets
   hubot ticket <ID> - returns information about the specified ticket
```
