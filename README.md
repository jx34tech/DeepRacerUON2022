# DeepRacerUON2022
Repo for code for running DeepRacer for 2022 at UON

## Purpose of this repo
This repo is a modification of existing code by PhoenixDai's Deepracer, a repo that allows you to train and run ML models (specifically DeepRacer Models) locally with a graphics card, instead of using AWS, as this can become costly for learners and beginners to Machine Learning

## Where this code is from
This repo uses a lot of code from https://github.com/PhoenixDai/deepracer-windows but with many modifications to bring it into current specifications and standards, some instructions have also since changed, since the guide was created

## Things that are working:
- Instructions for downloading and starting Minio
- Instructions for downloading, installing, and starting redis using docker
- Instructions for installing and using Coach on Windows
- Some of the instructions for starting the trainer

## Things that are broken and need fixing:
- Training Worker for Robomaker
- Probably many other things

## Note about Git LFS
This repo makes use of Git LFS (Large File System), this is due to it's complete nature, as in, you should be able to download this repo, and run it with the configuration instructions and everything should be self-contained to the repo folder

## Contribution
If you have any fixes that you can see for the code base, please feel free to fork and submit a PR
