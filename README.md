# YTnidongde
##阴天分支项目，好看的视频API
-使用方法
 ```shell
  pip install YTnidongde
  ```
安装好pip包后可直接使用
##代码示例
```shell
  import search_api.client
  import view_api.client
  ```
我们需要初始化client
```shell
  search_client = search_api.client.SearchClient()
  view_client = view_api.client.ViewClient()
  ```
之后我们可以这样
```shell
result = search_client.search_videos(query: 学生 '''str''',max_pages: 2  '''int''')
result = view_client.get_video_detail("48777"'''str''')
  ```

