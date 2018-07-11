
# Playground for mkcert

[mkcert](https://github.com/FiloSottile/mkcert) is a CLI tool that creates locally available TLS certification for tests.

```
$ brew install mkcert
$ mkcert -install

$ (cd certs; mkcert localhost)
$ docker-compose up

# Assuming chrome.
$ open http://localhost:20443
```
