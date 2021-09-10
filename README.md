# Bookings# Bookings and Reservations

This is the repository for my bookings and reservations project.

- Built in Go version 1.17

Dependencies:

- [chi router](https://github.com/go-chi/chi)
- [alex edwards SCS](https://github.com/alexedwards/scs/v2) session management
- [nosurf](https://github.com/justinas/nosurf)
- [pgx](https://github.com/jackc/pgx/v4)
- [simple mail](https://github.com/xhit/go-simple-mail/v2)
- [Go validator](https://github.com/asaskevich/govalidator)

## Running the Project

```bash
cd src/bookings
docker-compose -f docker-compose.yml up -d --build --remove-orphans
```

Seeing the logs

```bash
docker compose logs -f
```

Stopping the project

```bash
docker compose down
```
