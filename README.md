# Remote Procedure Call
Remote Procedure Call (RPC) is a protocol that one program can use to request a service from a program located in another computer on a network without having to understand the network details.
RPCGEN is a tool that generates C code to implement an RPC protocol.The input to rpcgen is a language similar to C known as rpc language.
The rpcgen compiler debugs the network interface code,thereby allowing programmers to spend their time debugging the main features of their application.
The rpcgen compiler produces a C language output that includes the following:
1.Stub versions of the client and server routines.
2.Server skeleton.
3.External Data Representation(XDR) filter routines for parameters and results.
4.A header file that contains common definitions of constants and macros.
Cleint stubs interface with the rpc library to effectively hide the network from its callers.
Server stubs similarly hide the network from server procedure invoked by remote clients.


To emulate RPC between two systems in our project we send the request from the cleint to server i.e., Finding out the Largest number among two numbers.
The server compares and returns the largest value among two numbers.
