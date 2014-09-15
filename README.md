# ZeroMQ

This is a fork of the LibZMQ project, to share it through the biicode plaform, the biicode block is located at: http://www.biicode.com/diego/libzmq.

This is ongoing work, and some improvements have to be made, specifically:
- TweetNaCL is disable by default, as libsodium dependency is not resolved yet. I am working in uploading libsodium to biicode too.
- Works in Mac, Win (VS 2012), and Ubuntu, both included tests as well as being reused from client-server example through the C++ binding. Further testing might be necessary, also checking other compilers as MinGW. One test fails under Win, still investigating reason.
- Automate publish to biicode with travis-ci



## Welcome

The 0MQ lightweight messaging kernel is a library which extends the
standard socket interfaces with features traditionally provided by
specialised messaging middleware products. 0MQ sockets provide an
abstraction of asynchronous message queues, multiple messaging patterns,
message filtering (subscriptions), seamless access to multiple transport
protocols and more.


## Building and installation

See the INSTALL file included with the distribution.

## Resources

Extensive documentation is provided with the distribution. Refer to
doc/zmq.html, or "man zmq" after you have installed 0MQ on your system.

Website: http://www.zeromq.org/

Development mailing list: zeromq-dev@lists.zeromq.org
Announcements mailing list: zeromq-announce@lists.zeromq.org

Git repository: http://github.com/zeromq/libzmq

0MQ developers can also be found on the IRC channel #zeromq, on the
Freenode network (irc.freenode.net).

## Copying

Free use of this software is granted under the terms of the GNU Lesser General
Public License (LGPL). For details see the files `COPYING` and `COPYING.LESSER`
included with the 0MQ distribution.
