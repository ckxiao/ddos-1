WinPcap4.10 bate���ֶ���װ����

          www.chinahacker.net



1����װ��Ҫ�õ������ļ���Packet.dll��WanPacket.dll��wpcap.dll��pthreadVC.dll,npf.sys��
2�����ļ�Packet.dll��WanPacket.dll��wpcap.dll,pthreadVC.dll���Ƶ�system32�У���npf.sys���Ƶ�system32\drivers�У�
3����npf��װΪ������������ʹ��sc.exe�İ�װ������
     sc create npf binpath= system32\drivers\npf.sys type= kernel start= demand
   ��Ҳ����ʹ���������ߣ�
4��ж�ط�������ֹͣ����npf��sc stop npf��,��ɾ��������sc delete npf��,���ɾ�������ᵽ��5���ļ���
5��ע�⣺�÷���ֻ��WinPcap3.1���ļ������˲��ԣ������汾���Լ�����(���²���4.0.2)��
         �����ǵ�ʹ�ø÷��������˲��е��κη������Ρ�



ps:��Ŀ¼�е�setup.batΪ��װ�ű�;del.batΪ����װ�ű�
    