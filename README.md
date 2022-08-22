Few days back, we implemented a simple blockchain on my youtube channel.

But blockchains aren't in silos, they need consensus mechanisms for adding new blocks.

I've added a proof of work example in my github, this one is a proof of stake example.

For proof of stake, you need to give different amount of tokens to different peers.

This means, you will create multiple peers by -

1. Starting the server for the blockchain by `go run main.go`
2. Opening multiple terminal instances and typing `nc localhost 9000`
3. Each of these terminals will be a new peer and you can see the proof of stake happening in action in the terminal
4. There will be one clear winner and the hash of that peer will be mentioned in the terminal