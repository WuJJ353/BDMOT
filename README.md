# BDMOT

This is a multi-object tracking dataset with depth information for basketball sports.

## Data Collection

It contains 40 basketball video clips, collected from campus games and training sessions captured by a stereo camera ZED2i. The video parameters are 1920×1080 at 30fps, with an average of 455 frames per video, and all shooting scenes are indoors.

The entire dataset comprises 18,235 color images and corresponding 18,235 depth images, where the depth images are obtained through disparity calculation, filtering and inpainting, depth normalization, and other steps.

## Data Format

Data in BDMOT is organized in the form of [MOT Challenge 17](https://motchallenge.net/)，only adds a "depth" folder for storing depth images.

Unzip the provided .zip file, you will get

- `dataset`(in MOT challenge format)
  - `train`
    - `VIDEO_NAME1`
      - `gt` 
        <details><summary>details</summary>

        ```text
        1,3,250,578,169,296,1,0,1
        1,4,944,503,145,381,1,0,1
        1,5,1351,479,106,330,1,0,1
        2,0,9,600,177,356,1,0,1
        ``` 
        
        </details>
      - `img1`
        - `0001.png`
        - `0002.png`
      - `depth`
        - `0001.png`
        - `0002.png`
      - `seqinfo.ini`
        <details><summary>details</summary>

        ```text
        [Sequence]
        name=1
        imDir=img1
        frameRate=30
        seqLength=436
        imWidth=1920
        imHeight=1080
        imExt=.png
        ``` 
        
        </details>
  - `val`
    - the same hierarchy as train
  - `test`
    - the same hierarchy as train
   


## Download    
- [QuarkDrive](https://pan.quark.cn/s/92355ce3627b?pwd=ArZM)

## Contact 
This dataset is provided by [Prof. Luo Jiangtao @CQUPT](https://faculty.cqupt.edu.cn/luojt/zh_CN/index/15127/list/index.htm), Chongqing, China.

- [JET LUO](https://jiangtaoluo.github.io/HomePage/)

Valuable issues and chat are welcomed.

## Terms
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />

BDMOT is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

















