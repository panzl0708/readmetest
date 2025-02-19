# RL-Lite3

[English](./README.md)

## ���
A Learning-based locomotion controller for quadruped robots. It includes all components needed for training and hardware deployment on DeepRobotics Lite3.
## ����ܹ�
���ֿ��ɰ�������Ŀ¼��
- rsl_rl: һ����װ��ǿ��ѧϰ�����İ�
- legged_gym: gym-style environments of quadruped robots.


## ׼������ 
1.  ��Ubuntuϵͳ�д���һ��python��3.6/3.7/3.8������ʹ��3.8����

2.  ��װCUDA�����PyTorch��
```
# pytorch
pip3 install torch==1.10.0+cu113 torchvision==0.11.1+cu113 torchaudio==0.10.0+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html
```

3.  �ӹٷ���վ����[Isaac Gym](https://developer.nvidia.com/isaac-gym)���汾 >= preview 3���������������Ŀ�ĸ�Ŀ¼�С�

4. ʹ��`pip`��װpython�����
```
pip3 install transformations matplotlib gym tensorboard numpy=1.23.5
```

5. ͨ�� pip ��װ *legged_gym* �� *rsl_rl*
```
cd legged_gym
pip install -e .

cd rsl_rl
pip install -e .
```

# ʹ�÷���

### �ڷ��滷����ѵ������
```
cd ${PROJECT_DIR}
python3 legged_gym/legged_gym/scripts/train.py --rl_device cuda:0 --sim_device cuda:0 --headless
```

### �ڷ��滷�������п�����
```
cd ${PROJECT_DIR}
python3 legged_gym/legged_gym/scripts/play.py --rl_device cuda:0 --sim_device cuda:0 --load_run ${model_dir} --checkpoint ${model_name}
```
������ļ�����Ƿ���NVDIA GPU�����򣬽������ű��еĵ��� `cuda:0` �滻Ϊ `cpu`��
ͨ�� `--load_run` �� `--checkpoint`  ָ������ģ�͵�·����

### ����ʵ���������п�����

�������ļ����Ƶ���Ŀ[rl_deploy](https://github.com/DeepRoboticsLab/Lite3_rl_deploy.git)��,Ȼ������������ʵ����������ǿ��ѧϰ������

## �ο�����
- [legged_gym](https://github.com/leggedrobotics/legged_gym.git)
- [rsl_rl](https://github.com/leggedrobotics/rsl_rl)
- [quadruped-robot](https://gitee.com/HUAWEI-ASCEND/quadruped-robot.git)


[��ϵ����](https://www.deeprobotics.cn/robot/index/company.html#maps)

