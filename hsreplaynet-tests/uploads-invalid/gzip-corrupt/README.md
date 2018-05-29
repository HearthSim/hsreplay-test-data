This file is an anonymized example of
https://github.com/HearthSim/HSReplay.net/issues/812, in which a gzipped
Power.log payload is uploaded with a plaintext "preamble" of HTTP headers,
making it un-decompressable from the point of view of our log reading toolchain.

