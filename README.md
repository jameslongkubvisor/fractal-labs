# fractal-labs
Django Application to handle multipart upload of large files to amazon S3

# Requirements
```
docker
docker-compose
AWS Account 
S3 Bucket 
```
# Specification
This application uploads large files to s3. 

# Object
Serve Django Application on the local machine

- docker-compose exec web python manage.py createsuperuser
- docker-compose exec web python manage.py startapp ...

## Notes

- 

## Commands

### Development

- `docker-compose up -d --build`
- `docker-compose down`
- `docker-compose down -v`
- `docker-compose logs -f`
- `docker-compose exec web python manage.py createsuperuser`
