# Step 1

## Acceptance criteria
OK 	You have a GitHub repo with everything needed to build the Docker image.
OK 	You can do a demo, where you build the image, run a container and access content from a browser.
	You have used a nice looking web template, different from the one shown in the webcast.
OK 	You are able to explain what you do in the Dockerfile.
OK 	You are able to show where the apache config files are located (in a running container).
	You have documented your configuration in your report.
	
	
## Docker configuration documentation
`FROM php:7.2-apache
COPY src/ /var/www/html/`
Retrieve an apache php7.2 official image and copy everything from src/ in the apache's web folder.