// ��ȡ�����û���Ϣ
http://localhost:3000/users

// ��ȡidΪ1��
http://localhost:3000/users/1

// ��ȡ��˾��������Ϣ
http://localhost:3000/companies

// ��ȡ������˾����Ϣ
http://localhost:3000/companies/1

// ��ȡ��˾idΪ3���û�
http://localhost:3000/companies/3/users

// ���ݹ�˾���ֻ�ȡ��Ϣ
http://localhost:3000/companies?name=Microsoft

// ���ݶ�����ֻ�ȡ��Ϣ
http://localhost:3000/companies?name=Microsoft&name=Apple

// ��ҳ ��ȡһҳ��ֻ����������
http://localhost:3000/companies?_page=1&_limit=2

// ��������
http://localhost:3000/companies?_sort=name&_order=asc

// ��ȡ������ڵ���30��
http://localhost:3000/users?age_gte=30

// ��ȡ������30-40֮���
http://localhost:3000/users?age_gte=30&age_lte=40

