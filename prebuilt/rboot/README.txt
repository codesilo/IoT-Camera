�Ȱ�rboot.bin�ŵ����tf����Ŀ¼��������һ��rboot.sh�����'rboot.sh'����rboot�������Զ�ִ�У���������ǣ�

boot http://192.168.10.246:8000/firmware/rtthread.bin

���������PC�ϵ�����webserver���ܹ����ʵ����ӵ�ַ��

Ȼ�������ӵ�uboot�У�����uboot���
setenv bootcmd 'fatload mmc 0 0xA0200000 rboot.bin;go 0xA0200000'
saveenv

������ʱ��rboot����������һ������ʱ����rboot.bin������
wifi cfg your_ssid your_passwd

������rboot������Wi-Fi���硣Ȼ���ٴ�����������ÿ��rboot�����󶼻��Զ�ȥ���PC�����ع̼���������
