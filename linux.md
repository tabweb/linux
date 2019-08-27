## linux 命令行

| linux 命令行              | 说明                                                        |
| ------------------------- | ----------------------------------------------------------- |
| pwd                       | 查看当前目录名字                                            |
| ls                        | 查看下列目录                                                |
| ls -al                    | 显示当前目录下的所有文件及文件夹包括隐藏的.和..等的详细信息 |
| ls /                      | 查看根目录                                                  |
| sude -s                   | 获取权限                                                    |
| cd xxx                    | 转换目录                                                    |
| cd ..                     | 返回上一级目录                                              |
| cd /                      | 返回根目录                                                  |
| touch xxx                 | 新建文件                                                    |
| mkdir xxx                 | 新建目录名                                                  |
| cp xxx                    | 拷贝文件                                                    |
| rn xxx                    | 删除文件                                                    |
| mv ex3 new1               | 将文件 ex3 改名为 new1                                      |
| mv /usr/men/\* .          | 将目录/usr/men 中的所有文件移到当前目录（用.表示）中        |
| nano xxx                  | 编辑文件                                                    |
| clear / cls               | 清屏                                                        |
| df -h                     | 查看硬盘内存                                                |
| getconf LONG_BIT          | 查看当前 Linux 版本                                         |
| uname -a                  | 查看当前 Linux 信息                                         |
| tar -zxvf filename.tar.gz | 解压 xxx.tar.gz                                             |
| tar -Jxvf filename.tar.xz | 解压 xxx.tar.xz                                             |
| rm -rf \* (rm -rf ./\*)   | 删除文件夹下的所有文件，而不删除文件夹本身                  |
| rm -rf /user/Dfile/httpd  | 将会删除/user/Dfile/httpd 目录以及其下所有文件、文件夹      |
| sudo chmod 777 build           | 赋予 build 文件夹的 xftp (上传下载权限)改成 777             |

## vim

| vim | 说明   |
| --- | ------ |
| :wq | 保存   |
| :q! | 不保存 |
