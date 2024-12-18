系统环境
python=3.6以上
torch = 1.8以上
1.需要安装winpcap或者npcap,有安装文件
2.需要到系统设置中，设置环境变量HF_HOME 为datasets默认的cache目录
3.原始的数据下载地址https://www.unb.ca/cic/datasets/vpn.html
然后运行preprocessing.py,具体的路径可以在代码里指定，会生成.parquet文件，里面包含了label和feature，这些生成文件会保存在processed_data下，然后手动选择哪些文件train或者test，分别拷贝到processed_train_data和processed_test_data文件夹中
4.python train_cnn.py运行，HF_HOME下.cache\huggingface\datasets目录里面是运行缓存数据
5.parquet文件格式介绍https://zhuanlan.zhihu.com/p/538163356