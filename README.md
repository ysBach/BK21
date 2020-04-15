# BK21
BK21 is... inefficient.

I wish [this short notebook](https://nbviewer.jupyter.org/github/ysBach/BK21/blob/master/BK2020_survey_topublic.ipynb) can help you save your precious time from stupid administrative work.



## Requirements

* tqdm
* astroquery
* pandas

```
$ conda install conda-forge tqdm pandas
```

For astroquery, I recommend developer's bleeding edge version:

```
$ cd <your_github_download_directory>
$ git clone https://github.com/astropy/astroquery.git
$ cd astroquery
$ python setup.py install
```

Alternatively (not recommended), you can do ``conda install -c astropy astroquery``. 



## Note

미래를 너무나 걱정하던 어느 날, 언젠간 제 이름으로 많은 논문이 나오고 정리하기가 귀찮아질 것을 지나치게 일찍부터 걱정한 나머지, ADS에서 개인 이름이 들어간 모든 논문을 찾아서 해당 PDF를 다운로드함으로써 이력서 정리시간을 줄여줄 짤막한 코드를 짠 적이 있습니다. 돌이켜 보니 조금 수정해서 이번 BK조사에 도움이 될 수 있을 것으로 보여 만들어보았습니다. 천문학계는 다행히도 ADS라는 시스템이 있고, astropy-affiliated package인 astroquery에 ADS모듈이 있습니다. 덕분에 이 코드가 돌아갈 수 있었습니다.


학교 자체적으로도 교수 연구실적을 전산화하라고 요청하고 있다는 점을 상기할 필요가 있습니다. 사실 완벽하게 동일한 내용임에도 불편하게 제출 형식만 바꿔가면서 지속적으로 연구진 노동력을 중복사용하게 하는 방식과 지나칠 정도로 비효율적인 조사 체계에 BK측에 강하게 항의한 적이 있습니다. 그 후로 단 한가지 받아들여진 것은 조사를 위한 엑셀 파일이 이번엔 드디어 맥용 엑셀에서 작업이라도 가능한 수준으로 바뀌었다는 점입니다. 그러나 사실상 똑같은 내용을 중복조사하는 과정에서 매번 많은 인력의 소멸을 목도하면서도 고작 이런 발전에 기뻐해야한다는 사실은 연구자를 꿈꾸는 한 사람으로서 비참함마저 느끼게 합니다. 친구가 말하길 남의 돈으로 연구하는 게 어렵지 라고 했는데, 어려운 것이 (귀를 틀어막은 비효율적인 행정체계에 의해 유발되는) 부당한 반복노동이 아니었으면 좋겠습니다.

