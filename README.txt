ϵͳ����
python=3.6����
torch = 1.8����
1.��Ҫ��װwinpcap����npcap,�а�װ�ļ�
2.��Ҫ��ϵͳ�����У����û�������HF_HOME ΪdatasetsĬ�ϵ�cacheĿ¼
3.ԭʼ���������ص�ַhttps://www.unb.ca/cic/datasets/vpn.html
Ȼ������preprocessing.py,�����·�������ڴ�����ָ����������.parquet�ļ������������label��feature����Щ�����ļ��ᱣ����processed_data�£�Ȼ���ֶ�ѡ����Щ�ļ�train����test���ֱ𿽱���processed_train_data��processed_test_data�ļ�����
4.python train_cnn.py���У�HF_HOME��.cache\huggingface\datasetsĿ¼���������л�������
5.parquet�ļ���ʽ����https://zhuanlan.zhihu.com/p/538163356