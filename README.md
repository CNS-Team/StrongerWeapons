# StrongerWeapons
TShock plugin--StrongerWeapons

# Commands
sw or 'ǿ��'<br>
normal player's permission:StrongerWeapons.use<br>
administrator's permission:StrongerWeapons.admin<br>
You'll get detatied commands list and useages by execute command:'/sw'<br>
# Skill principle explaination
"Skill book" is a special type of items,which can be any existed item whose prefix is '254'
# About learning skills
If you want to learn a skill,you must have matched "skill book" in your inventory,
and your weapon level must higher than the learning level limit of the "skill book".<br>
Each "skill book" can be used only once,and you're allowed to learn different kinds of skills.<br>
Also , you can forget a skill,and the "skill book" will be returned to you inventory.<br>
For administrators,you can set multiple skills for one weapon.<br>
## About passive skills
### About learned multiple skills for one weapon
The effect of mp and hp restore will be stacked and additionally,cooling time will be sumed up. <br>

3.1.2.���ڱ������ܵĴ���<br>
ÿ��ʹ������ʱ����������ʱ�����ᴥ���������ܣ��еĻ�Ѫ�������֣�����ȴʱ��δ���򲻻ᴥ��<br>
3.1.2.1.���ڵ�Ѫ����ʱ�ı�������<br>
��Ѫ��ʱ�ı������ܷ�Ϊ����������<br>
��Ѫ�����ڻ���ڼ����е�Ѫ��ֵʱ�ֳ���Ӧ��������<br>
��Ϊͬ������ѧϰ���ּ���ʱЧ������<br>
4.���ڹ�������<br>
ʹ����Ӧ��һ��������Ʒ�һ������飬��Щ��Ʒ�����ڱ�����<br>
������id���Ǽ��������Ʒid�����Ǽ������������ļ��е�����<br>
�����������ļ����<br>
```
Permission ѧϰȨ�ޣ�""Ϊ����Ȩ��
Name ����������
WeaponID ����id,����д���
NetID ��������Ʒid
Life ��Ѫֵ
Rate ��������Ѫ
��Ѫֵ=Life+Rate x (�������� - 1)
Magic ����ֵ
Delay ��ȴʱ��
Damage ���ӵ��˺�
UseTime ���ٵ�ʱ��
LowLife Ѫ�����ڴ���ֵ�������������ܱ�������
CriticalRate �������ʣ�0-100��������
Critical ������ֵ������ʱ�˺�=ԭ���˺� x Critical��
DodgeRate ���ܸ��ʣ�0-100��������
Level ����ǿ���ȼ����ڵ��ڴ˵ȼ�����ѧϰ����С�ڵ���0��Ϊ�������ƣ�
Drop ���䣬����д���
 BossID ��ɱʱ�и��ʵ����npc id
 Rate ������ʣ�0-100��������
Projectile ��Ļ���ã��������ö����
 Trace �Ƿ����
 ProjID ��Ļid
 Speed ��Ļ�ٶ�
 Damage ��Ļ�˺�
 KnockBack ����
 Delay ��Ļ������ȴʱ��
 Defined �Ƿ������Զ���λ���ٶ�����
 X �����Ϊԭ��x������
 Y �����Ϊԭ��y����
 VX x����ٶ�
 VY y����ٶ�
Coins ����˼������������Ʒ
 netID ��Ʒid
 stack ��Ʒ����
 Perfix ǰ׺�����Բ���
 ```