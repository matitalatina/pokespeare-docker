# PokéSpeare Docker Compose

Start PokéSpeare with docker compose on your local machine.

## Getting Started

```bash
# Clone this repo
git clone git@github.com:matitalatina/pokespeare-docker.git

# Go into this project
cd pokespeare-docker

# Download the frontend and backend submodules
git submodule update --init

# Let the magic happens!
docker-compose up
```

Now you can open your browser to [http://localhost](http://localhost).

## Notes

- If you want more details about this project, please refers the submodules repositories:
  - Backend: [https://github.com/matitalatina/pokespeare-backend](https://github.com/matitalatina/pokespeare-backend).
  - Frontend: [https://github.com/matitalatina/pokespeare-frontend](https://github.com/matitalatina/pokespeare-frontend).


## FAQ

- *Why did you use three repositories instead of only one?* Because the CI/CD pipelines are easier to manage having distinct repositories per project.
