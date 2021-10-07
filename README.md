# A protobuf spec for an Hotrod-like protocol
This is a protobuf specification for a protocol that carries 
the same information of the Infinispan/HotRod protocol.

A parser for any protobuf supported language, can be generated as:

	protoc --java_out=java_out protobuf/hotrod.proto
