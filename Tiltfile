docker_compose('docker-compose.yml')
# https://docs.tilt.dev/custom_build.html
custom_build(
    'backend',
    'pants package src/docker:backend',
    deps=['src/services/backend', 'src/docker/Dockerfile.backend'],
    tag='latest'
)
