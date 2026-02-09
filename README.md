# Cyber Security 

## Owner
- Student ID:  6702041511055
- Name:  Rungnapha Aiamchukun
- Email: s6702041511055@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running services
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

## Running services
### Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```