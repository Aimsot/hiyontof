# �Ђ��Ƃӂ��ǂ�ȕ��ɓ����Ă���̂�

�Ђ��Ƃӂ��ǂ�ȕ��ɓ����Ă���̂����ȒP�ɐ������Ă��܂��B

## .js �t�@�C���̈ꗗ�Ɖ��

�Ђ��Ƃӂɂ� JavaScript �t�@�C�����傫�������ĎO��ގg���Ă��܂��B

- ``main/js/src/`` �ȉ��ɔz�u���ꂽ�A�v���P�[�V�����̂��߂ɏ����ꂽ JavaScript �t�@�C��
- �ݒ�t�@�C�� ``main/hiyontof.conf.js``
- ``main/js/lib/`` �ȉ��ɔz�u���ꂽ�A�v���P�[�V���������p���Ă��郉�C�u����

�����ł̓A�v���P�[�V�����̂��߂ɏ����ꂽ JavaScript �t�@�C���� ``hiyontof.conf.js`` �ɂ��Đ������܂��B

### hiyokoUtilV1.js

 ���[�e�B���e�B�t�@�C���ł��B
�ŐV�� JavaScript �ł͂��ǂ����������\�ł���A�s�K�v�ȏꍇ������܂����A
�ꕔ�̃u���E�U�ւ̑Ή��ⓖ�����������̎��̔F���s���Ȃǂɂ���Ďg���Ă�����̂�����܂��B

### tofClient.js

�ǂǂ�ƂӂɃA�N�Z�X���邽�߂̃t�@�C���ł��B
���̃t�@�C���ɏ�����Ă���N���X�Ɗ֐��������Ăǂǂ�Ƃӂ̏����擾������A�ǂǂ�Ƃӂɏ��𑗂����肵�Ă��܂��B

### tofServerList.js

���O�C�����ɕ\�������T�[�o�ꗗ���������߂̃t�@�C���ł��B
�ݒ�t�@�C���ŗp�ӂ��ꂽ�T�[�o�y�сA���[�U���e�X���͂����T�[�o���Ǘ����܂��B
���[�U����x���͂��A���p�����ǂǂ�ƂӃT�[�o�̓u���E�U�̃��[�J���X�g���[�W�Ɋi�[����A
����ȍ~�̃A�N�Z�X�ł͈ꗗ�ɕ\�������悤�ɂȂ�܂��B

### tofInit.js

�A�v���P�[�V�����̃G���g���[�|�C���g�ƂȂ�t�@�C���ł��B
�K�v�ȏ�񂪂��ׂē��͂���Ă��邩���m�F���A
���͂���Ă���� tofApp.js �̓��e�����s�A
���͂���Ă��Ȃ���΃��[�U�ɓ��͂𑣂���ʂ�\�����܂��B

### tofApp.js

�ǂǂ�Ƃӂ𗘗p���邽�߂̊e�N���X���N�����邽�߂̃t�@�C���ł��B��������e�@�\���Ăяo����܂��B
tofClient.js �����ǂǂ�Ƃӂ̊e�����փA�N�Z�X���邽�߂̃N���X���e�@�\�ɑ}�����Ă��܂��B

### tofChat.js

�ǂǂ�Ƃӂ̃`���b�g�ɃA�N�Z�X���邽�߂̃t�@�C���ł��B
�ȉ��ɕ�����Ă��܂��B

- com.hiyoko.tofclient.Chat: tofChat �Ɋ܂܂��N���X�S�̂��Ǘ�����N���X�ł�
  - com.hiyoko.tofclient.Chat.Display: �ǂǂ�Ƃӂ̃��O��\�����邽�߂̃N���X�ł�
  - com.hiyoko.tofclient.Chat.Status: �ǂǂ�ƂӂƂ̒ʐM�󋵂�\�����邽�߂̃N���X�ł�
  - com.hiyoko.tofclient.Chat.InputArea: ���M����`���b�g���b�Z�[�W���󂯕t���邽�߂̃N���X�ł�
    - com.hiyoko.tofclient.Chat.InputArea.Input: �W���I�ȃ`���b�g���b�Z�[�W�𑗂邽�߂̃N���X�ł�
    - com.hiyoko.tofclient.Chat.InputArea.Parette: �ߋ��̓��͗����𗘗p���ă`���b�g���b�Z�[�W�𑗂邽�߂̃N���X�ł�
  - com.hiyoko.tofclient.Chat.SubMenu: ��ʍ���ɕ\�������T�u���j���[�������N���X�ł�

�����Ƃ��āA InputArea �ȉ��̃N���X�� SubMenu ����C�x���g���󂯎��A
Chat ������ɉ������������s���A�Ƃ���������s���܂��B

### tofMap.js

�ǂǂ�Ƃӂ� Map �������N���X�ł��B
jquery.pep.js ���g���A�R�}�̈ړ����T�|�[�g���Ă��܂��B

�w�ǂ̎d���� com.hiyoko.tofclient.Map.MapWriter ���s���Ă��܂��B

�L�����N�^�[�𓮂����ƃL�����N�^�[����ړ��C�x���g��������A
com.hiyoko.tofclient.Map ��������L���b�`���Ăǂǂ�Ƃӂɔ��f����A�Ƃ������@�ŃR�}�̔z�u�������Ă��܂��B


### tofTable.js

�ǂǂ�Ƃӂ̃C�j�V�A�e�B�u�\�������N���X�ł��B
���\�̎Q�Ƃ݂̂Ȃ炸�A�X�V���ł���悤�ɂȂ��Ă��܂��B

�܂��A�L�����N�^�[�̒ǉ��������ōs���Ă��܂��B

### tofMemo.js

���L�����̕\���ƍX�V���s�����߂̃N���X�ł��B
�e�������C�x���g�𔭂��A com.hiyoko.tofclient.Memo ���ǂǂ�Ƃӂւ̔ɉh���s���Ă��܂��B

## �ݒ�t�@�C��

��q�̒ʂ�A ``main/hiyontof.conf.js`` ���ݒ�t�@�C���ł��B
���ݑ��݂���ݒ荀�ڂ͈ȉ��̂��̂ł��B

### com.hiyoko.tofclient.ServerList.SERVER_LIST

�Ђ��Ƃӂ��J�����Ƃ��A���R�����h�����ǂǂ�ƂӃT�[�o�̈ꗗ�ł��B
URL �� KEY �Ƃ��A�T�[�o���� VALUE �Ƃ��� json �̌`���ɂȂ��Ă��܂��B

�����ɂ悭�g����T�[�o��o�^���Ă����΁A���͂̎�Ԃ��Ȃ��y�ɂȂ邩������܂���B

### com.hiyoko.tofclient.ServerList.RESTRICTION

``com.hiyoko.tofclient.ServerList.SERVER_LIST`` �ɓo�^����Ă���T�[�o�ȊO�ւ�
�A�N�Z�X��F�߂邩�F�߂Ȃ�����ݒ肵�܂��B
``false`` �ł���΁A�o�^����Ă���T�[�o�ȊO�ɂ��A�N�Z�X�ł���悤�ɂȂ�܂��B
``true`` �ɂ��Ă����΁A�o�^����Ă���T�[�o�ȊO�ɂ̓A�N�Z�X�ł��Ȃ��Ȃ�܂��B

���I�p�̂Ђ��ƂӂƂ��Đݒu�������̂ł���΁A ``true`` �ɂ������
``com.hiyoko.tofclient.ServerList.SERVER_LIST`` �Ɏ��I������o�^���Ă����΂悢�ł��傤�B

## �Ђ��Ƃӂ� URL

�Ђ��Ƃӂ� URL �� Query �����𗘗p���ă��[�U�̓��͂����ݒ荀�ڂ�ǂݎ���Ă��܂��B

�t�Ɍ����΁A�������ݒ肳�ꂽ URL �����L����΁A���l�ɂЂ��Ƃӂ𑦍��Ɏg�킹�邱�Ƃ��\�ł��B

�ݒ荀�ڂ����m�F���Ă����܂��傤�B

### url (�K�{)

�ǂǂ�Ƃӂ� URL �ł��B�Ⴆ�� ``https://www.taruki.com/DodontoF_srv1/DodontoF.swf`` �ł��B
������x���͂ɑ΂��ď_��ɑΉ��ł���悤�ɂ��Ă͂��܂����A���E������̂� ``DodontoF.swf`` �ŏI�����̂𗘗p���邱�Ƃ������߂��܂��B

### room (�K�{)

�ǂǂ�Ƃӂ̕����ԍ��ł��B

### pass

�ǂǂ�Ƃӂ̕����ɓ��邽�߂̃p�X���[�h�ł��B

### reload

�`���b�g�y�уC�j�V�A�e�B�u�\�̍X�V�p�x���~���b�ŋL�q���܂��B
10,000 (=10�b) �ȏ�łȂ���Ζ����ƂȂ�܂��B

### time

�^�C���X�^���v���`���b�g�ɕ\�����邩�ۂ���ݒ肵�܂��B

## ���̑��̎g����

### �ǂǂ�Ƃӂ��w�肵�ē�����ʂ�\��

�Ђ��Ƃӂ� URL �� ``room`` ���w�肹���A ``url`` �������w�肵�ĂЂ��ƂӂɃA�N�Z�X�����ꍇ�A
�ŏ�����ǂǂ�Ƃӂ� URL ���Ɏw�肵�� URL ���L�q���ꂽ��ԂłЂ��Ƃӂ̓�����ʂ��\������܂��B

�Ⴆ�΁A�Ђ��Ƃӂ̐ݒu�A�h���X��   
``http://shunshun94.web.fc2.com/tofChatProto.html`` �ł����   
``http://shunshun94.web.fc2.com/tofChatProto.html?url=https://www.taruki.com/DodontoF_srv1/DodontoF.swf`` �փ��[�U��U�����Ă݂Ă��������B

���I�p�Ƃ��ă��[�U�Ɏg�킹�������ɂ͕֗��ł��B

### ���w�\�ȏꍇ

���w�\�ȕ����ɓ�������ꍇ�A
�p�X���[�h���v������Ă����Ƃ��Ă��Ђ��Ƃӂœ����ł��܂��B

���̏ꍇ�A�ꌩ�A�C�ӂ̃`���b�g�^�u�Ŕ������\�Ɍ����܂����A
���ۂɂ͌��w�^�u�ɂ��������ł��Ȃ��悤�ɂȂ��Ă��܂��B

���̂�����̋@�\�͋ߓ����ɏC�����A�킩��₷�����邱�Ƃ��l���Ă��܂��B

### �ނ���͂Ђ��Ƃӂł͖���

�ǂǂ�ƂӃT�[�o��1�Ƃ��Ēm���Ă��� [�ǂǂ�Ƃӂނ���](https://ddntf.museru.com/) �ł����A
�Ђ��Ƃӂł̓A�N�Z�X�ł��܂���B

�Ђ��Ƃӂ͂ǂǂ�Ƃӂ����@�\��1�ł��� WEBIF �𗘗p���č���Ă��܂��B
�������A�ǂǂ�Ƃӂނ���� WEBIF ���g���Ȃ��悤�ɐݒ肳��Ă��邽�߂ł��B

�܂��A���ɂ� WEBIF ���g���Ȃ��ǂǂ�Ƃӂ�����΁A���̂ǂǂ�Ƃӂɂ��Ђ��Ƃӂł͐ڑ����ł��܂���B

