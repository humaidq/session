# session

Middleware session provides session management for
[Emmanuel](https://github.com/go-emmanuel/emmanuel). It can use many session
providers, including memory, file, Redis, Memcache, PostgreSQL, MySQL,
Couchbase, Ledis and Nodb.

### Installation

The minimum requirement of Go is 1.6 (*1.7 if using Redis, 1.10 if using MySQL*).

	go get github.com/go-emmanuel/session
	
## Credits

This package is a modified version of
[beego/session](https://github.com/astaxie/beego/tree/master/session) and
[go-macaron/session](https://github.com/go-macaron/session).

## License

This project is under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for the full license text.
