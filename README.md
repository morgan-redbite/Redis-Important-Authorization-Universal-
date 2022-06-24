# Redis_Quicknote
Redis Quicknote

To secure redis:
redis-cli CONFIG SET requirepass [your-pass]

To Authenticate Secured Redis
redis-cli AUTH [your-pass]

To get redis default/preset config value
redis-cli CONFIG GET [redis config name]

e.g: redis-cli CONFIG GET maxmemory
