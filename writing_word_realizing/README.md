###�˹��������������ķ������

1�������MNIST��д���ּ���ʶ����ɺ��ֵĲ�ͬ����ķ���ʶ��

2�����ֵ�����ʶ���������л�ȡ

3��ÿ��������Ի�ȡ114���֣��������������еıʻ������б仯

4��ʹ�þ�������磬�Ժ���ͼƬ���л�����������ȡ

5����ǩ������MNIST��д���ּ��Ĵ���Ϊ��ͬ����������ƣ����壬���壬�ȡ�������
 
6�����ѵ������ʶ��
-------------------------------------------------------------------------------------
���л������ã�
GPU TITAN xp��python 2.1.15(anaconda)��keras-gpu=2.2.4, tensorflow-gpu=1.8.0
����������...

�����ǲ���ѵ�����������⣺
ttf_sets:
DENG.TTF
FZSTK.TTF
FZYTK.TTF
MSYH.TTC
MSYHBD.TTC
MSYHL.TTC
SIMLI.TTF
SIMYOU.TTF
STHUPO.TTF
STSONG.TTF

�����Ǳ���Ŀ�����ṹͼ��
writing_word_realizing:
  |
  |--datasets/
  |  |--testlabels/
  |  |  |--testlabels.txt
  |  |--testsets/
  |  |  |--001
  |  |  |  |--000.jpg
  |  |  |  |--001.jpg
  |  |  |  |--xxx.jpg
  |  |  |--002
  |  |  |  |--000.jpg
  |  |  |  |--001.jpg
  |  |  |  |--xxx.jpg
  |  |  |--...
  |  |--trainlabels/
  |  |  |--trainlabels.txt
  |  |--trainsets/
  |     |--001
  |     |  |--000.jpg
  |     |  |--001.jpg
  |     |  |--xxx.jpg
  |     |--002
  |     |  |--000.jpg
  |     |  |--001.jpg
  |     |  |--xxx.jpg
  |     |--...
  |--traind_model/
  |  |--model.h5
  |--ttf_sets/
  |  |--xxx.ttf/TTF
  |  |--xxx.ttc/TTC
  |--demo.py
  |--mnist.py
  |--README.md
  |--reshape_img.py
  |--str2img.py

Ԥ����
���ݼ����ɣ�
  ����תͼƬ��
  python str2img.py 
  ͼƬ��С�趨��28*28����
  python reshape_img.py
  
���У�
python demo.py

���ԣ�
 ������������