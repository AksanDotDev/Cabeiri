# Cabeiri
A web socket to discord interface for Rube-Goldberg chains.

## Config Arguments
- `-T`
  Used to provide the discord bot token to be used
- `-O`
  Used to provide the user ID of the owner, alternative to using the `|claim` command.
- `-H`
  Used to specify the unqualified host name, defaults to `localhost`. 
- `-P`
  Used to specify the port to operate on, defaults to `6280`.

## Config Commands
- `|claim`
  Used to claim ownership of an unclaimed instance of the bot. 
- `|localize`
  Used to set the channel that the bot answers commands in, can be used in any channel and only by the owner.
- `|ping`
  Used to get a response from the bot to confirm life.
## Basic Commands
- `|register`
  Used to register a new webhook pair, completes in DMs.
- `|status`
  Used to check the details of an existing webhook pair, completes in DMs.
- `|initiate`
  Used to fire the initial outgoing webhook and begin listening on the incoming webhook, mentions the initiator on completion, in channel if localized or DMs otherwise. 

# Competition Premise
  The competition is open to all [HackSocNottingham](https://github.com/HackSocNotts) members and revolves around making the most complicated, convoluted, unreliable and over-engineered methods of plugging one piece of tech into another, beginning and ending with this bot. 
  Prizes are to be awarded for the longest chains, the most protocols used in a chain and the best individual protocol used in a chain and will be awarded after the close of the competition.
  The competition will run from 19:00 28/04/2020 to 19:00 05/05/2020 and entries will be expected to provide evidence of their Rube-Goldberg-Chain whether in the form of source code, that can then be posted after the competition concludes, or appropriate evidence of the more unique stages of the chain. 

# Useful Tools
- [Webhook.site](https://webhook.site/)
  Useful for seeing the output of requests.
- [Postman](https://www.postman.com/)
  Useful for creating and testing requests.
- [Insomnia](https://insomnia.rest/)
  Useful for creating and testing requests.
- [If This Then That](https://ifttt.com/)
  Useful for plugging anything into anything.
