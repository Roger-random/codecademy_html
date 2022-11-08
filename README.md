# Codecademy HTML (& friends) Off-Platform Project Exercises
This repository hosts my exercises projects assigned by Codecademy courses
in HTML & related (CSS, JavaScript, etc) technologies. The results are
hosted via GitHub Pages so I could view results from any web capable device
by visiting https://roger-random.github.io/codecademy_html/

## Local Hosting
Since I don't want to push to GitHub Pages and wait to see every change I
make, this repository also includes a
[Docker Compose](https://docs.docker.com/compose/)
file which will launch a
[nginx](https://hub.docker.com/_/nginx) container to act as local web server.
Using nginx (even its stripped-down stable-alpine version) is sheer overkill
for the task but I wanted practice working with it. The first attempt was to
[disable caching](https://docs.nginx.com/nginx/admin-guide/content-cache/content-caching/#limiting-or-disabling-caching)
because I'll be updating my HTML/CSS a lot and I don't want anything cached.

To use this local server:
1. Change to this repository's directory
2. Run `docker compose up`
3. Open browser to `http://localhost:18080`

(Port number 18080 can be changed in `docker-compose.yml`)

## Licensing
I do not know Codecademy's licensing policy on this material. While I'm happy
to release my own work under the permissive MIT license in other repositories,
this repository has a lot of Codecademy content. Yes, they tell students like
me to do these exercises off Codecademy's own platform, but that's not the
same as freely releasing material. I don't think I can say "MIT License" on
this specific repository.
