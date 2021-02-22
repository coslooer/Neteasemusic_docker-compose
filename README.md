# Neteasemusic_docker-compose  
解锁网易云音乐客户端变灰歌曲  
# 默认已经安装docker与docker-compose  
* 运行： docker-compose up  
# 参数配置  
```$ unblockneteasemusic -h  
usage: unblockneteasemusic [-v] [-p port] [-a address] [-u url] [-f host]
                           [-o source [source ...]] [-t token] [-e url] [-s]
                           [-h]  

optional arguments:  
  -v, --version                   output the version number  
  -p port, --port port            specify server port  
  -a address, --address address   specify server host  
  -u url, --proxy-url url         request through upstream proxy  
  -f host, --force-host host      force the netease server ip  
  -o source [source ...], --match-order source [source ...]  
                                  set priority of sources  
  -t token, --token token         set up proxy authentication  
  -e url, --endpoint url          replace virtual endpoint with public host  
  -s, --strict                    enable proxy limitation  
  -h, --help                      output usage information  
  ```
