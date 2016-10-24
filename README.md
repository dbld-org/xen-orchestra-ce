# xen-orchestra-ce
Docker &amp; docker-compose files to deploy Xen Orchestra Community Edition (ie: from source)

See https://xen-orchestra.com for information on Xen Orchestra

## Running the container

### From docker repo

The most simple way is to use docker-compose. Redis is not in this docker, so we
need to connect XOA-CE to a Redis database, the docker-compose file in the github
repos will take care of this and assure persistance.

```
git clone https://github.com/Ezka77/xen-orchestra-ce.git
docker-compose up
```

Xen Orchestra should be available on: http://localhost:8000

## Versions

Should follow xo-server and xo-web stable version.

## Support

* This Docker project is not supported by Xen-Orchestra or the parent company Vates.
* Xen-Orchestra also provides a fully-supported, turn-key appliance, see: https://xen-orchestra.com/pricing.html
