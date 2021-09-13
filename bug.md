
## urllib.error.ContentTooShortError
<details><summary>代码详情</summary>

```shell
Traceback (most recent call last):
  File "C:\Users\lnd\anaconda3\lib\threading.py", line 932, in _bootstrap_inner
    self.run()
  File "C:\Users\lnd\anaconda3\lib\threading.py", line 870, in run
    self._target(*self._args, **self._kwargs)
  File "bilibili_video_download_v3.py", line 171, in down_video
    urllib.request.urlretrieve(url=i, filename=os.path.join(currentVideoPath, r'{}.flv'.format(title)),
  File "C:\Users\lnd\anaconda3\lib\urllib\request.py", line 286, in urlretrieve
    raise ContentTooShortError(
urllib.error.ContentTooShortError: <urlopen error retrieval incomplete: got only 2097152 out of 35220636 bytes>
```

</details>