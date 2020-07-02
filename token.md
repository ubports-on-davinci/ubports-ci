## How to use self generated token

### Generate new token 
Generate at https://github.com/settings/tokens and mark the value, we need use it later.
We need repo,write:packages,read:packages,workflow permissions.

### Create project secret
Go to **Settings**-**secrets**, click **New secret**, input your secret name, eg. `MySecret`. 

### Replace workflows token
Replace `MyUbtSecret` in [.github/workflows/build.yml](.github/workflows/build.yml) to your secret name `MySecret`. 

