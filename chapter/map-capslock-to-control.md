## ӳ���д��������CapsLock�������Ƽ���Ctrl��

��д���������ڼ����������õ��İ�����������Ҫ�ȿ��Ƽ��������װ�����
��Ϊ��λ�����ַ��ڼ���ʱ��[��ʼ��](https://raw.githubusercontent.com/mhinz/vim-galore/master/contents/images/content-homerow.png)��
������úܶ����Ļ���ӳ���д��������CapsLock�������Ƽ���Ctrl��������Ч����
[�ظ�ʹ���˺�](https://de.wikipedia.org/wiki/Repetitive-Strain-Injury-Syndrom) (ps:Ϊʲô�� jk ӳ��Ϊ esc�������� jj���ظ����ͬһ����������ָ�˺��ܴ�)��

������ʾ������ϰ������趨������벻�����ˡ�

**OSX**:

`System Preferences -> Keyboard -> Keyboard Tab -> Modifier Keys`. ���
"CapsLock" Ϊ "Control"��

**Linux**:

Ϊ��ʹ������Ч��������¼��з��� `~/.xmodmap` �ļ�:

    remove Lock = Caps_Lock
    keysym Caps_Lock = Control_L
    add Control = Control_L

����������ʹ֮��Ч<br> `$ xmodmap ~/.xmodmap`��

���������[caps2esc](https://github.com/oblitum/caps2esc) ����
[xcape](https://github.com/alols/xcape)��

**Windows**:

��ο� [superuser.com: ��Windows8.1ӳ���д�����������Ƽ�](http://superuser.com/questions/764782/map-caps-lock-to-control-in-windows-8-1)��
