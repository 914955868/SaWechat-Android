�����¼�����Build��Windows���ܹ�������EnMicroMsg.db��sqlcipher���Լ����ܸ��ļ��ķ�����

����ʹ��sqlcipher-windows����⣬��ַΪhttps://github.com/CovenantEyes/sqlcipher-windows��Ȼ���������飬�����е��ĸ�Release�汾�У�ֻ��2.0.6���������������������Android�ϵ�΢��ʹ�������Ƶľɰ汾�⵼�µġ�

��https://github.com/CovenantEyes/sqlcipher-windows/archive/v2.0.6.zip��������汾��src������ʹ�õ���VS2010������������þɰ汾��VS����Ҫ������ƽ̨���߼��������⣬���ǻ���Ҫopenssl�Ŀ⡣

����Դӹٷ�������openssl�����б��룬����������http://www.npcglib.org/~stathis/blog/precompiled-openssl/�ҵ��Ѿ�����õİ汾�������������밴��sqlcipher-windows��ҳ�е�˵�����ñ���õ�openssl�⡣Ϊ�������������򵥣�����ֻ����x86�İ汾��

���ˣ��������Ѿ���������sqlcipher�ˡ������Ͷ�Ӧ�汾��libeay32xx.dll����һ��

�����õ���sqlcipher��ȱ��һ��ʵ�õĺ�������sqlcipher_export()������û��ϵ�����ǿ�������һ�ַ���ʵ�ֽ��ܡ�

sqlcipher.exe EnMicroMsg.db
> PRAGMA key='xxxxxxx';
> cipher_use_hmac=off;
> .output a.sql
> .dump
> .quit
sqlcipher.exe MicroMsg.db
> .read a.sql
> .quit

�����Ϳ����ˡ�����������ݿ����Կ���������7��x�������·������㣺

md5(IMEI+uid).substring(0,7)

���ֻ����Ž�������*#06#�����IMEI���ݳƣ���ĳЩ�����ϣ����ܻ�ʹ��IMSI���������֡�

uidΪ΢�ŵ��û���š������ͨ�������Ʒ�ʽɨ��/data/data/com.tencent.mm/MicroMsg/***/�µ��ļ���������һ��֤����ã����ߵ�¼��ҳ��΢�ţ�Ȼ����cookies����wxuidһ�

����ܾ���������Ҫ������ϸ�ڡ�

������ֻ���������ֳɵ�sqlcipher.exe��
