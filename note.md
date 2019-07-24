## 目录操作
  mkdir
  cp
  mv
  rm
  ls
  pwd
  cd
  find
    这个咋用？
## 文本操作
  过滤
    grep
      对内容进行过滤

      参数 -An(n是行数) -Bn         -Cn
          after        before     count 前后
      grep: warning: recursive search of stdin
        When the -R option is used, MacOS grep requires you to explicitly give it a directory to search; for example, specify . to recursively search the current directory:

        grep -R 'networks' .
    awk
    sed
    diff
      用来比较两个文件的差异
  vim
  查看
    less
      针对大文件
      进入文件
        q退出
    tail 尾巴 后几行
      tail -f (somefile)
      tail -n+行数 (somefile)
    head 头几行
      head -n+行数 (somefile)
    cat
      cat (somefile) 查看文件内容
      输出在控制台
    du -h (somefile) 查看文件大小
  统计
    sort
    uniq

## 压缩
  tar
  bzip2
  zip
  rar

  .tar 使用tar命令压缩或解压
    tar: Error opening archive: Failed to open 'sometest.tar.gz'
  .bz2 使用bzip2命令操作
  .gz 使用gzip命令操作
  .zip 使用unzip命令解压
  .rar 使用unrar命令解压

  常见.tar.gz
    经过tar打包再使用gzip压缩

## 日常运维
  shutdown
  mount
    挂载外接设备
  chmod ！！！
    用来改变文的访问权限
  chown ！！！
    用来改变文件的所属用户和所属组
  文件权限777
  su
    切换用户
    su xjj
    su - xjj
  yum
    centos的包管理工具
  password
  service   systemctl
    centos 管理后台服务
  kill
    kill -9
      只有这个无条件终止进程
    kill -15
    kill -3
  ps 显示瞬间行程（process）的动态
    -A 所有进程
    ps -ef

## 系统状态概览
  ps
    能够查看进程/线程状态
  top
    系统状态
  free
    查看内存
  df
    查看磁盘使用量
  ifconfig
    查看ip
  uname
    输出当前内核信息
    uname -a
  ping
  netstat
    查看网络套接字连接情况
## 工作常用
  crontab
  export
    设定环境变量
    env
      查看当前系统所有的环境变量
  xargs
    读取输入源然后逐行处理？？？
  date
    当前系统时间
  hwclock
  whereis
  scp
    用来进行文件传输，也可以传输目录
    更高级的sftp命令
  ssh
    ssh隧道？？？
  wget
    下载
  mysql
  
[参考资料](https://m.imooc.com/article/289529?from=singlemessage&isappinstalled=0)

## 持续学习中...