ʹ�÷�����äˮӡ
��������������������������������
�ļ���
origin.jpg δ����ˮӡ��ͼƬ
watermark.jpg ˮӡͼƬ������Ҫ���ص���Ϣ������������57117228 ���ӣ�
test.jpg ����ˮӡ������ͼƬ
watermark_result.jpg ��ʹ��decode.py����ȡ����ˮӡ
encode.py ���ش���
decode.py ��ȡ����
��������������������������������
׼����
ʹ��python3����encode.py��decode.py��ͼƬ����һ���ļ����С�
��������������������������������
���裺
��1��hide information:
�����������
python3 encode.py --image origin.jpg --watermark watermark.jpg --result test.jpg
���ɵõ�������Ϣ������ͼƬtest.jpg

��2��extract information:
�����������
python3 decode.py --image test.jpg --orig origin.jpg --result watermark_result.jpg
������ȡ��ˮӡwatermark_result.jpg������Ҫ���ص���Ϣ��
��������������������������������
PS��watermark_result.jpg���Ϸ�����Ϣ��ʶ���е��...���˼���origin.jpg������ˡ�orz