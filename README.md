# Landing page database

[![Made with Docker](https://img.shields.io/badge/Made%20with-Docker-0091e2.svg)](https://www.docker.com/)
[![Made with Docker Compose](https://img.shields.io/badge/Made%20with-Docker%20Compose-27343B.svg)](https://docs.docker.com/compose/)

[![MIT Licence](https://img.shields.io/badge/licence-MIT-blue.svg)](https://magno.mit-license.org/)

## TL;DR

```bash
docker-compose pull
docker compose up

# Import dump
docker exec -it <container> bash
psql -h localhost -U strapi -d strapi -W < dump.sql
```

## Contributing

1. Fork it!
2. Create your feature branch
   - `git checkout -b feature/my-new-feature`
3. Commit your changes
   - `git commit -m "feat: add some feature"`
4. Push to the branch
   - `git push origin feature/my-new-feature`
5. Submit a pull request

## Security Vulnerabilities

If you discover a security vulnerability within this project, please send an e-mail to Magno Biét via [magno.biet@gmail.com](mailto:magno.biet@gmail.com). All security vulnerabilities will be promptly addressed.

## License

This package is licensed under the [MIT license](https://magno.mit-license.org/2020). Copyright © Magno Biét
