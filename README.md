# Repo for models and Datasets

## Rules

- Choose a name for the model directory based on the parameters of the net.
- Each commit must contain the number of epochs (other params are well accepted) in the message.


## Installing git lfs 

On Debian:

- Install `git lfs`:
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | bash
apt-get install git-lfs
git lfs install
```

## Download .pth files

- Clone LFS repo :
```bash
git lfs clone https://github.com/git-davi/DeepNnModels.git 
```

- Pull LFS files from repo:
```bash
git lfs pull
```

## Push .pth files

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
