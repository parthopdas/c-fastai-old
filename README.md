# [fast.ai](http://www.fast.ai/)

## Prep
- Update fastai library: https://github.com/fastai/fastai/tree/master/fastai -> fastai 
- ln -s ~/data ~/c-fastai/data; kaggle download to ~/data/__competetion__
- cd ~/ wget http://files.fast.ai/models/weights.tgz; tar -xvf weights.tgz; ln -s ~/weights ./fastai/weights
- TODO: anaconda environment (refer paperspace doc in azuresetup.md)

## Notes: 
- [Faster experimentation for better learning](http://forums.fast.ai/t/faster-experimentation-for-better-learning/7881)
- Informal chapter notes: e.g. [Chapter 1.1 Notes](http://forums.fast.ai/t/wiki-lesson-1)
- [New data sets](http://wiki.fast.ai/index.php/Image_Datasets)

## Misc tools
- ssh -L 8888:127.0.0.1:8888 partho@52.225.250.170
- [Resuming ssh session](https://askubuntu.com/questions/191573/how-can-i-reconnect-to-a-ssh-session-after-a-broken-pipe)
- Is GPU being used? watch nvidia-smi -q -g 0 -d UTILIZATION -l
- http://wiki.fast.ai/index.php/Kaggle_CLI

## Jupyter shortcuts
- Ctrl + Shift + P: Command palette
- Esc/Enter: Command <-> Edit modes
- A/B: New cell above/below
- M/C: Change to markdown/code
- D + D: Delete current cell
- Shift + Tab: Doc string
- Ctrl + Shift + -: Split current cell into 2 from cursor
- Esc + F: Find & replace in code
- Esc + O: Toggle cell output
- Shift + J/Down/K/Up: Select next cell down/up
- Shift + M: Merge multiple cells

## todo
v dogbreed running on azure
o finish notes for ch 02
x what is missing from the template in dogbreed?
- switch to local box
- smaller data set?
- How to analyze results?
- Another sample with full 
