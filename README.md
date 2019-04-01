# Code for the paper 
Code for paper in CVPR2019, 'Multi-source weak supervision for saliency detection'

## Results

   score/datasets  |ECSSD | HKU-IS|PASCALS|SOD    |OMRON|DUTS-test| SED1|SED2|
  ---| ---  | ---   | ---   | ---   | --- | --- | ---|---|
  max$F_\beta$|.878|.856|.790|.799|.718|.767|.902|.849|
  MAE|.096|.084|.134|.167|.114|.096|.081|.097|
  
Download result maps: [OneDrive]()

## Usage
### Test

0. Environment: python2.7, pytorch'0.5.0a0+54db14e'

1. Download models and put in the current folder

<iframe src="https://onedrive.live.com/embed?cid=C655D310650464A5&resid=C655D310650464A5%21932&authkey=AHJJoLa50tTV_fo" width="98" height="120" frameborder="0" scrolling="no"></iframe>

1. Run

```bash
python main.py \
--img_dir 'path/to/images(.jpg)' \
--gt_dir 'path/to/ground-truth(.png)'

```

### Train
coming soon

## Citation
```
@inproceedings{zeng2019multi,
  title={Multi-source weak supervision for saliency detection},
  author={Zeng, Yu and Zhuge, Yunzhi and Lu, Huchuan and Zhang, Lihe and Qian, Mingyang and Yu, Yizhou},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
  year={2019}
}
```




