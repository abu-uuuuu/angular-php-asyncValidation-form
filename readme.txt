���������� �� ���������

1. �������� � ���������� ����� leko-registration-form.7z:

��������� ����������:

db - ��
leko-registration-form - ��������� ������� (frontend � backend - � ���������� rest-api)
�� - ���� ����������

2. �������� �� �� ������� leko.sql 

3. �������� ������������ leko � ������� leko
(��� ������� ��������� ���������� � �� � ����� config.php)

4. �������� ����������� ����. ������ ������ �� httpd-vhosts.conf

<VirtualHost *:80\>
    DocumentRoot "D:\www\vhosts\leko-registration-form"
    ServerName leko-registration-form
</VirtualHost\>

�������� ��� ����� �������� � ��� ������������ �����.

5. ������ ���� ��������� apache ������ rewrite_module

LoadModule rewrite_module modules/mod_rewrite.so

6. � php.ini ��������� ����������: pdo
extension=php_pdo_mysql.dll


http://leko-registration-form/