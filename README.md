In order for the following to work, you are required to set an environment variable
`DIGITALOCEAN_API_TOKEN`

I recommend setting this in your .bashrc or .zshrc file.

# Build
```
packer build -machine-readable swarm.json | tee swarm.log
```
