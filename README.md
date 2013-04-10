# ZmqWebBridge

This project is forked from https://github.com/hhuuggoo/ZmqWebBridge

## Changes

- Authentication made optional in Socket.connect and Context.connect
- zmq.PUSH, zmq.PULL and zmq.PUB added
- added multi part message support for PUB, SUB, PUSH and PULL:
	- send functions expect array (for single part message, array with one element)
	- onMessage function provide array with received message parts