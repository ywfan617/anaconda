<<<<<<< HEAD
# introduction  

notes of anaconda  

# anacondaѧϰ  

## anaconda��������  

```bash
    conda create [env] python=3 #��������
    # conda create -n learn python=3
    conda env list #�г�����
    activate #activate �ܽ���������anaconda�趨�����⻷����, ��������ʲô������������ô�����anaconda�Դ���base����
    source activate learn #�л�����
    conda env export > environment.yaml #���뵼������
    conda env create -f environment.yaml #����Ҫ���´���һ����ͬ�����⻷��ʱ������
    conda env remove -n env_name #ɾ������
```

```bash
    conda --version #���汾��
    conda upgrade --all #���������
    conda install requests #��װ��������
    conda remove requests #ж�ش�������
    conda list #�鿴��ǰ������Ϣ
    conda info #չʾ��ǰconda��һЩ��Ϣ
    conda search package #��ѯ��
```

## ɾ��anaconda  

```bash
    rm -rf anaconda #�� ~/.bashrc�Ļ������������
```  
