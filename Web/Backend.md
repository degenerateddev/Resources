# Caching
- Client Side Caching
	- Cache API responses through caching rules
- Server Side Caching
	- Cache using e.g. Redis, Memcached, Varnish
- Cache Hit Ratio
	- Number of cache hits / (Number of cache hits + Number of cache misses) = Cache hit ratio
- Useful details
	- Read intensive endpoints
	- Idempotence
		- Property of an operation that ensures that, if an operation is repeated once or more than once, you get the same result
		- Set cache key of request equal to idempotence key
	- Caching POST/PATCH/PUT/DELETE = Antipattern
	- Store route, parameters, auth headers
# Frameworks & Langs
- Django / FastAPI / Flask
- ExpressJS / ElysiaJS
- GoLang
- Actix / Rocket
- [Serverless](https://www.serverless.com/)
# Authentication
- Token based authentication
	- Stateless Tokens
	- Stateful Tokens
- Session based authentication
- JWT Token authentication

# API
- Fail fast for non-HTTP API connections
# Payment
- [[Gateways]]