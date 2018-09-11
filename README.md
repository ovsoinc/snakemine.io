# [snakemine.io](https://snakemine.io)

## Requirements

* Node (tested on v10+)
* NPM
* Redis
* Nginx (production only)

```
git clone https://github.com/ovsoinc/snake.git
```

```
cd snake
```

```
npm install
```

```
nano .env
```

	COINHIVE_SITE_KEY=xxx
	COINHIVE_PRIVATE_KEY=xxx
	SERVER_PORT=3055
	BLOCK_HASHES=250

```
node server
```
