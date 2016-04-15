# Multi-Language configurations for pmt.mcpe.me

## English
We hope that you can help translating pmt.mcpe.me into your locale for us.

We use gettext function to make pmt.mcpe.me to multi-language supported. '.po' file is used for translating, '.mo' file is for our system to read the translations. In the **_Translation templates** folder, there is a file which the filename extension is '.pot'. That is a language template for you to translate the language inside.

## How to translate
We don't totally request you to summit a translation to us, but we hope you can help us if you have the ability.

You can use **[Poedit](https://poedit.net/)** to help you to translate the '.po' file. The '.mo' file will be auto-generated when you save the '.po' file.

If you're using Linux OS, 
you can use 'msgfmt' command to convert '.po' into '.mo' or merge it to the old version of the translation. Here is the usage:
* Convert: 'msgfmt -o Filename.mo Filename.po'
* Merge: 'msgmerge -o (FilenameAfterMerge).po (OldFile).po (NewFile).po'

### Attention! You also need to create a folder named 'LC_MESSAGES' in the language folder.


## �c�餤��
�ڭ��H���w��z�� pmt.mcpe.me �^�m½Ķ�I

�ڭ̬O�ĥ� gettext �ӻs�@�h��y���A`.po` �ɬ�½Ķ�ΡA`.mo` �ɬ��t��Ū���ΡA�b **_Translation templates** ��Ƨ��������ɦW�� `.pot` �����A���O�y���ҪO�A�i�Q�� `.pot` �ɳЫطs�y���C

### �p��sĶ
�ڭ̤��n�D�z�@�w�n�sĶ½Ķ�ɡA���Ʊ�z��sĶ���A����C

½Ķ `.po` ���ɥi�H�Q�� **[Poedit](https://poedit.net/)** �o�ӳn��i��½Ķ�A�s�ɫ�|�۰ʽsĶ�� `.mo` ���C

Linux �@�~�t���٥i�H��׺ݱN `.po` ���sĶ�� `.mo` ���ΦX���¦���½Ķ�A�Ϊk�p�U�G
* �sĶ�G `msgfmt -o ���W��.mo ���W��.po`
* �X��½Ķ�G `msgmerge -o �X�֧��n�s���ɦW.po �n��s�ɦX�֪�.po �s���ɮ�.po`

### �Ъ`�N�A�b�y�t��Ƨ����٭n�Ы� `LC_MESSAGES` ��Ƨ��C