# gocfg

## go  配置文件读取

    使用方法

    go get -u -v git.dian.so/leto/gocfg

    s := &struct{}
    if err := gocfg.Load(".ini config file path",s); err != nil {
        errHandle(err)
    }