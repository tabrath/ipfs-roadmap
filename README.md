
# [Multiformats](https://github.com/multiformats)

## [Multiformats.Codec](https://github.com/multiformats/cs-multicodec)
> .NET Standard 1.6
* Implementation: Complete with support for Json, CBOR and ProtoBuf.
* Stability: Not heavily tested besides unit tests.
* Todo: Dependencies for CBOR are not .NET Standard compliant yet, so those are pulled in as submodules and consumed by source (included in our library) - this needs to change when the vendor releases a new version we can use through NuGet. Documentation.

## [Multiformats.Stream](https://github.com/multiformats/cs-multistream)
> .NET Framework 4.6
* Implementation: Basic, ported from Go.
* Stability: Broken
* Todo: Tests rely on Sockets to make a stream pipe that breaks on Travis CI, and probably is not the best way. Asynchronous handshaking is also not stable. Need to be .NET Standard compliant. Documentation.

## [Multiformats.Hash](https://github.com/multiformats/cs-multihash)
> .NET Standard 1.6
* Implementation: Complete, supports all algorithm in the spec.
* Stability: Not heavily tested besides unit tests and sharness tests that the Go implementation also passes.
* Todo: Keep up with the spec as it evolves. Documentation.

## [Multiformats.Base](https://github.com/multiformats/cs-multibase)
> .NET Standard 1.6
* Implementation: Complete, supports all codecs in the spec.
* Stability: Not heavily tested besides unit tests and some benchmarks.
* Todo: Documentation.

## [Multiformats.Address](https://github.com/multiformats/cs-multiaddress)
> .NET Standard 1.6
* Implementation: Almost complete, supports almost all protocols in the spec.
* Stability: Not heavily tested besides unit tests.
* Todo: Add support for missing protocols. Documentation.


# [LibP2P](https://github.com/libp2p)

## [LibP2P.Crypto](https://github.com/libp2p/cs-libp2p-crypto)
> .NET Standard 1.6
* Implementation: Complete, supports RSA and Ed25519.
* Stability: Not heavily tested besides unit tests, broken on Linux/OSX due to dependency problems (libsodium native).
* Todo: Update dependecy when it's working properly. Documentation.

## [LibP2P.Peer](https://github.com/libp2p/cs-libp2p-peer)
> .NET Standard 1.6
* Implementation: Complete.
* Stability: Not heavily tested besides unit tests.
* Todo: Documentation.

## [LibP2P.Protocol](https://github.com/libp2p/cs-libp2p-protocol)
> .NET Standard 1.6
* Implementation: Complete.
* Stability: Not heavily tested besides unit tests.
* Todo: Documentation.

## [LibP2P.Record](https://github.com/libp2p/cs-libp2p-record)
> .NET Standard 1.6
* Implementation: Complete.
* Stability: Not heavily tested besides unit tests.
* Todo: Documentation.

## [LibP2P.Utilities](https://github.com/libp2p/cs-libp2p-utils)
> .NET Standard 1.6
* Implementation: Complete.
* Stability: Not heavily tested besides unit tests.
* Todo:

## [LibP2P.IO](https://github.com/libp2p/cs-libp2p-io)
> .NET Standard 1.6
* Implementation: Complete.
* Stability: Not heavily tested.
* Todo: Right now it's only a bunch of interfaces to keep the port from Go to C# as equal as possible. We have to drop this and do the .NET-way of handling streams/io. The package may be useful in some other way.

## [LibP2P.KBucket](https://github.com/tabrath/cs-libp2p-kbucket)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested at all besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Peer.Store](https://github.com/tabrath/cs-libp2p-peerstore)
> .NET Standard 1.6
* Implementation: Just ported.
* Stability: Not tested at all besides unit tests.
* Todo: Some async trouble, unit tests fail at it, haven't dived into it yet. Documentation. Move to libp2p org when done.

## [LibP2P.Host](https://github.com/tabrath/cs-libp2p-host)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Routing](https://github.com/tabrath/cs-libp2p-routing)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Transport.Tcp](https://github.com/tabrath/cs-libp2p-transport-tcp)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Abstractions.Connection](https://github.com/tabrath/cs-interface-connection)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Abstractions.Transport](https://github.com/tabrath/cs-libp2p-transport)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## [LibP2P.Net](https://github.com/tabrath/cs-libp2p-net)
> .NET Framework 4.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to libp2p org when done.

## Todo
* Swarm, circuit, muxing, dht, secio


# [IPLD](https://github.com/ipld)

## [IPLD.ContentIdentifier](https://github.com/tabrath/cs-cid)
> .NET Standard 1.6
* Implementation: Just ported.
* Stability: Not tested besides unit tests.
* Todo: Convert to .NET Standard. Documentation. Testing. Move to ipld org when done.

## Todo
* Pretty much everything
