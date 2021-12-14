# Find Data & Find vedio

制作的原因:
1.看到別人做chrome工具，覺得很有趣，稍為搜尋一下，找到別人做的範例，所以就做做看。
2.有時要找程式的資料，總是要切換不同的網站去找資料，覺得很麻煩。在想說是不是一次輸入關鍵字，就可以直接找最大的幾個網站的資料。第一個功能就是這樣。
3.有時要搜尋教程，在youtube都搜尋不到，所以就將第一個功能，連到幾個大陸比較容易找到程式影片的網站，去做搜尋，方便我找教程。而且找到了就不用再付費去用那些要付費的教程。


## Project First Look
![image](https://drive.google.com/uc?export=view&id=1_CtfGnEOlv-00k-QdLLWYN4CdUw2OqGb)


## Features
| Functions                                                    |
| ------------------------------------------------------------ |
| Generate customized placeholder image                        |
| Search for royalty free image on four popular websites       |
| Generate URL reports with all available size of the image    |

## Installation
The following instructions will get you a copy of the project and all the setting needed to run it on your chrome.


### Prerequisites

- [Google Chrome](https://www.google.com/chrome/)

### Clone

Clone this repository to your local machine

```
$ git clone https://github.com/smallpaes/find-placeholder-image.git
```

### Setup

1. Open the Extension Management page in Chrome

```
chrome://extensions
```

2. Enable Developer Mode & Click on **LOAD UNPACKED**

```
Select the extension directory: find-placeholder-image
```

 ![image](https://drive.google.com/uc?export=view&id=1peOwDvpeI94OF11P2fK9EPOtXyQb3S0Y)

3. Find the Extension Box for successful installation

![image](https://drive.google.com/uc?export=view&id=1lQP83ILin-mz9qAqwWgXpomIrpyg0HlI)

## How To Use
### Generate customized placeholder image
1. Click on extension icon.
2. In **Generate Placeholder Image** section, input your need of your placeholder image.
3. Click on **Generate** button.
4. Click on **OPEN** button to open the image in a new tab / **COPY** button to copy the URL.


![Screen Shot of placeholder image generator in GIF](gif/placeholderIma.gif)


### Search for royalty free image 
1. Click on extension icon.
2. In **Search Royalty Free Image** section, input keyword to search.
3. Click on **Pixabay** / **Pexels** / **stackoverflow** / **juejin** to show search results on their website.
4. Click on **Search All** button to directly show search results of all four websites.


![Screen Shot of free image searcher in GIF](gif/freeImage.gif)


### Generate Image URL reports
1. Search any royalty free image.
2. Visit the image you'd like to access.
3. Right Click on the **image** to open the right-click menu.
4. Choose **ShowImageURL** to generate an URL report.
5. Click on **Search All** button to directly show search results of all four websites.
6. Choose the size you prefer and click on the URL to copy the link.


![Screen Shot of URL report in GIF](gif/URLReport.gif)

## Authors
[Mike Huang](https://github.com/smallpaes)
