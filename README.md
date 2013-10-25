# CQErl

*Native Erlang CQL driver*

We needed a good erlang driver to talk CQL3 with a cassandra deployment. [One][1] only talks Thrift, 
and [the other][2] talks a dated CQL over Thrift, and has been stalled for 2 years, so we built one.
It talks modern CQL3 over the [native binary protocol (v2)][3], can be used raw, or with managed connection pools, using [pooler][4].

*It currently is a work in progress though. Stay tuned*

[1]: https://github.com/lpgauth/cassanderl
[2]: https://github.com/ostinelli/erlcassa
[3]: https://git-wip-us.apache.org/repos/asf?p=cassandra.git;a=blob_plain;f=doc/native_protocol_v2.spec;hb=eb96db6c19515e6d1215230f29d25b46fcd005ef
[4]: https://github.com/seth/pooler