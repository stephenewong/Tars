# tars֧��protobuf service�����ļ�

�����˽⵽tars��ʱ�����Ѿ��в���ҵ�������protobufЭ�飻���Ҫ����Щҵ��Ǩ�Ƶ�tars���㻹��Ҫ�ֶ���proto�ļ������tars�ļ����ǳ��鷳�������׳�����
����tarsʹ��protoc�Ĳ�����ƣ��ṩ�˶�proto�ļ���ֱ��֧�֣��ܹ�����tars rpc��ش��룬ʹ��Ǩ��ƽ��ʡ�ġ�


## ʹ�÷���


### 1. ׼��proto�ļ�
proto�ļ����﷨�ǲ����Ƶģ������ʹ��proto2��proto3��
��ע�⣬һ������**option cc_generic_services=false;**
��Ϊ���ǵ�Ŀ����ǲ�ʹ��protoc���ɵ�pb rpc�ӿڣ�����Ҫ��tars����ӹܣ����ɷ���tars��ܵ�rpc�ӿ�.


### 2. ֱ��ִ��make����
��Ϊ����tars pb�������䣬�Ѿ������ڿ��makefile.tars�ļ��С�
����protocĬ�����ɵ��ļ�������.pb.h��׺,tars���Ҳ��ѭ��������������ɵ��ļ���׺��.tars.h

