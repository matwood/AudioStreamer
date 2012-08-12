# AudioStreamer

The excellent audio streaming class from Matt Gallagher.

## Additions On This Fork

- Made the class ARC aware.  It should now work in both ARC and non-ARC environments.
- Added the ability for the streaming class to use OAuth tokens for authentication to protected streams.  The class does NOT manage the OAuth token and leaves it up to the client.
