# Repo for models

## Rule

Choose a name for the model directory based on the parameters of the net


## Installing git lfs 

On Debian:

- Install `git lfs`:
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | bash
apt-get install git-lfs
git lfs install
```

## Downloading big files

- Clone LFS repo :
```bash
git lfs clone https://github.com/git-davi/DeepNnModels.git 
```

- Pull LFS files from repo:
```bash
git lfs pull
```

## Push .pth files to GitHub

- Track LFS files:
```bash
git lfs track *.pth
```

- Do a normal push:
```bash
git add *
git commit -m "..."
git push origin master
```
