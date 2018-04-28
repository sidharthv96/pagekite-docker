# PageKite with Captainduckduck
## Remote server setup
1. Install captainduckduck using the steps mentioned [here](https://github.com/githubsaturn/captainduckduck/wiki/Getting-Started)
2. Create new app with name `dyn`
3. Enable port mapping and give both values as `8091`
4. Save the configuration

### Deploying the application to CDD

1. Clone this repo
2. Edit the host name after `dyn.` in `kite.config` file to suit your host name.
3. Also edit the secret to any value you would like.
4. `git commit -m "Updates"`
5. `captainduckduck deploy`

## Running the pagekite clients 

1. Clone this repo
2. Edit the hostname and secret in pagekite.rc file to suit your settings.
3. `cp pagekite.rc ~/.pagekite.rc`
4. `python pagekite.py --clean --optfile=$HOME/.pagekite.rc`

