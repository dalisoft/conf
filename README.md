# conf

configuration files optimized for you

## Used Resources

- <https://github.com/denji/nginx-tuning>
- <https://vitux.com/nginx-performance-tuning>
- <https://sysopstechnix.com/7-tips-for-nginx-performance-tuning>
- <https://www.freecodecamp.org/news/powerful-ways-to-supercharge-your-nginx-server-and-improve-its-performance-a8afdbfde64d>
- <https://risaksson.com/post/9/2022-05-10/HTTP3-with-NGINX>
- <https://github.com/macbre/docker-nginx-http3/blob/master/nginx.conf>

## Usage

### [nginx](https://nginx.org)

Replace `/etc/nginx-http{VER}/nginx.conf` file with this one which in this repo.

You can use [this image](https://github.com/macbre/docker-nginx-http3) for Docker

### [binserve](https://github.com/mufeedvh/binserve)

Use `binserve.json` from this repo

### [postgres](https://postgresql.org)

Use [`postgres.conf` 1core/1GB RAM](./postgres/postgres_1c-1gb.conf), [`postgres.conf` 1core/2GB RAM](./postgres/postgres_1c-2gb.conf) or [`postgres.conf` 2core/4GB RAM](./postgres/postgres_2c-4gb.conf) from this repo

## License

MIT-License
