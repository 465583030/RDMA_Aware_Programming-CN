RDMA�������û��ֲ�1.4��
======================

###�����
<table>
<tr><th>����</th><th>����</th></tr>
<tr><td>Access Layer</td><td>����ϵͳ�ײ㹹�ܣ�����֧�ַ��ʻ����ļ�Ⱥ(VPI,InfiniBand,Ethernet,FCoE).
����������֧���ϲ�����Э��Ļ�����������м���͹������</td></tr>
<tr><td>AH(Address Handle)</td><td>��UD QP�У���������Զ��·���Ķ���</td></tr>
<tr><td>CA(Channel Adapter)</td><td>һ��InfiniBand��·���ն��豸����ִ�д����Ĺ���</td></tr>
<tr><td>CI(Channel Interface)</td><td>ͨ����������������ع̼����豸��������ϣ����ָ�Verbs
����û���ͨ�Źܵ�</td></tr>
<tr><td>CM(Communication Manager)</td><td>��������ά�֡��ͷ�RC��UC QP�����������ӵ���ϵ;����ID����Э��
ȷ����ʹ��UD������û��ҵ�֧��ָ���豸��QP;ÿ���ն˽ڵ��IB�˿ڶ���һ��CM.</td></tr>
<tr><td>Compare & Swap</td><td>֪ͨԶ��QP��ȡһ��64bit��ֵ�������ֵ���ṩ�ıȽ϶���ֵ���Ƚ�
�������ȣ���ô�ͰѶ�ȡ�����ֵ�滻��QP�ṩ����һ����ֵ��</td></tr>
<tr><td>CQ(Completion Queue)</td><td>һ������CQE�Ķ��У��Ƚ�ѡ����</td></tr>
<tr><td>CQE(Completion Queue Entry)</td><td>CQ�е�һ����¼��������������ɵ�WR����Ϣ
��״̬����С�ȣ�</td></tr>
<tr><td>DMA(Direct Memory Access)</td><td>����Ӳ���ڲ���CPU����������
�����ݿ��ƽ����Ƴ��ڴ�</td></tr>
<tr><td>Fetch & add</td><td>֪ͨԶ��QP��ȡһ��64bit����ֵ�������滻Ϊ����QP�ṩ
�Ĵ������ĺ͡�</td></tr>
<tr><td>GUID(Globally Unique IDentifier)</td><td>��һ�������У�Ψһ��־һ���豸�������
64bit����</td></tr>
<tr><td>GID(Global IDentifier)</td><td>һ��128λ�ı�־��������־�����������ϵ�һ���˿ڣ�
·�����ϻ����鲥���һ���˿�;Ϊ�˸���Ч��Ѱ�ҡ�ͨ�ź�·�ɣ�IBA�ڱ�׼IPV6��ַ�Ļ����϶�����һЩ�����
���Ժ�Լ��������γ���GID��</td></tr>
<tr><td>GRH(Global Routing Header)</td><td>�����������䴫�����ݰ��ʹ����鲥��Ϣ�İ�ͷ��
��ͷ����IPv6Э��</td></tr>
<tr><td>Network Adapter</td><td>���������м����֮�䴫�����ݵ�Ӳ����</td></tr>
<tr><td>Host</td><td>һ̨�����Ų���ϵͳ�����ҿ�����һ������network adapter�ļ������</td></tr>
<tr><td>IB</td><td>InfiniBand</td></tr>
<tr><td> </td><td> </td></tr>
<tr><td>Join operation</td><td>һ��IB�˿�Ҫ��ȷ�ؼ���һ���ಥ�飬������SA��������������
�ಥ���ݰ���</td></tr>
<tr><td>lkey</td><td>��MRע��֮����յ���һ�����֣����ڱ��ر�WR������־�ڴ�ע���
���Ȩ�ޡ�</td></tr>
<tr><td>LID(Local IDentifier)</td><td>
�����������ָ�����ն˽ڵ��һ��16λ��ַ��ÿ��LID�������ڵ���������Ψһ�ġ�</td></tr>
<tr><td>LLE(Low Latency Ethernet)</td><td>
��CEE(Converged Enhanced Ethernet�ۺϼ�ǿ����̫��)����֮�ϵ�RDMA����CEE����IB����̫���ϴ��䡣</td></tr>
<tr><td>NA(Network Adapter)</td><td>
һ���������ӵ��ն��豸����ִ�д���㹦�ܡ�</td></tr>
<tr><td>MGID(Multicast Group ID)</td><td>
MGIDΨһ��־һ��IB�ಥ�飬����SM����SM��ÿ��MGID������һ��MLID�����������е�IB������
���б�̿��ƣ�ȷ������ಥ������ж˿ڶ��ܽ��յ����ݰ���</td></tr>
<tr><td>MR(Memory Region)</td><td>
�ѱ�ע��Ϊ������ʹ�õ������ڴ滺������Ϊ��ʹ�������������������ǣ���Щ��������Ҫ�ȱ�
ע�ᡣ��ע���ڼ䣬һ��L_Key��R_Key��������������������Ӧ��ע�Ỻ������</td></tr>
<tr><td>MTU(Maximum Transfer Unit)</td><td>
�˿��շ����ݰ��������Ч���ص����ݴ�С����������ͷ���޶ȡ�</td></tr>
<tr><td>MW(Memory Window)</td><td>
һ�����������Դ��������ע����ڴ���һ���ض�������󶨺��ܱ�Զ��ֱ��ʹ�á�ÿ��MW����һ��
�����Ĵ��ھ����һЩʹ��Ȩ����Ϣ�͵�ǰ��R_Key</td></tr>
<tr><td>Outstanding Work Request</td><td>
����������û�б���ѯ������ɵ�WR</td></tr>
<tr><td>pkey(Partition key)</td><td>
pkey��־�˶˿������ķ�����pkey�����������̫���е�VLAN ID��pkey����ָ��˿ڵ�
pkey���е�һ�SM(subnet manager)��ÿ���˿����ٹ���һ��pkey</td></tr>
<tr><td>PD(Protection Domain)</td><td>
ֻ���ڲ���Ա���ܽ��н�������AH��QP���н�����MR��WQ���н�����</td></tr>
<tr><td>QP(Queue Pair)</td><td>
Ϊ���������нڵ�֮�䴫�����ݣ���������WQ�����һ���γɵ�һ�����
�����Ͷ��кͽ��ն��У������������͵�QP��UD ���ɿ����ݱ���UC ���ɿ����ӣ�RC 
�ɿ����ӡ�</td></tr>
<tr><td>RC(Reliable Connection)</td><td>
�������������ӵ�QP�������һ��QP����һ��QP�����������֮�����Ϣ�����ǿɿ���
���������������ݵ���ȷ�Ժ�˳���ԣ�</td></tr>
<tr><td>RDMA(Remote Direct Memory Access)</td><td>
�ڲ���Զ�̼����CPU�ĸ�Ԥ�£��������ڴ���в�����</td></tr>
<tr><td>RDMA_CM(Remote Direct Memory Access Communication Manager)</td><td>
���������ɿ������ӺͲ��ɿ������ݱ������API����Ϊ���������ṩ��RDMA����ӿڡ�
��API�����׽��֣�ͬʱ�������ڻ���QP�����壺��Ϣ���ݱ���ͨ��ר�ŵ�RDMA�豸��
�������ݴ����ǻ�����Ϣ���ơ�</td></tr>
<tr><td>Requestor</td><td>
��һ�������У��������ݴ����һ�ˣ�ͨ������һ������</td></tr>
<tr><td>Responder</td><td>
��һ�������У��ظ������߷��͵���������ĵ�һ�ˡ�����������ܰ���
�Իظ����ڴ���ж���д�����󣬺�Ҫ��ظ��߽���һ����Ϣ��</td></tr>
<tr><td>rkey</td><td>
��MRע��֮����յ���һ������,�Ե�����RDMA�������������֤��</td></tr>
<tr><td>RNR(Receiver Not Ready)</td><td>
��һ������RC��QP�У����˵������Ѿ����ڣ�����RRĿǰ���ڽ��նˡ�</td></tr>
<tr><td>RQ(Receive Queue)</td><td>
һ�������洢�û����͵�RR�Ĺ������С�</td></tr>
<tr><td>RR(Receive Request)</td><td>
��һ���ᱻ���͵�RQ�е�WR����������Ӧ�ðѵ�������Ҫд������д�����
��Ҫע����ǣ�һ��RDMAд����������һ��RR��</td></tr>
<tr><td>RTR(Ready To Receive)</td><td>
һ��QP��״̬������ʾĳ��RR���Ա����ͺʹ���</td></tr>
<tr><td>RTS(Ready To Send)</td><td>
һ��QP��״̬������ʾĳ��SR���Ա����ͺʹ���</td></tr>
<tr><td>SA(Subnet Administrator)</td><td>
������ѯ�Ͳ��������������ݵĽӿڡ�</td></tr>
<tr><td>SGE(Scatter/Gather Elements)</td><td>
һ���ṹ��ָ�򱾵���ע������ڴ���һ���ֻ������顣�ṹ�е�Ԫ�ذ���
�ڴ�����ʼ��ַ����С��lkey��������ص�Ȩ����Ϣһ�𣩡�</td></tr>
<tr><td>S/G Array</td><td>
��WR����S/GԪ�ص�Ԫ�顣����ʹ�õĲ���������Խ���ͬ�������������ռ�������
������Щ���ݵ���һ�����������������з��ͣ����߽�һ���������������зֳ���಻ͬ��
��������</td></tr>
<tr><td>SM(Subnet Manager)</td><td>
���ú͹�����������ϵ�����Ĺ��ܰ�������֪�������������˽ṹ������LID��
����·�ɲ��Ժ�����·�ɱ�һ������SM���߻���һ���ӵ�SM��˫���ȱ�ģʽ��,
��ʼ�������н�������·�ɱ�Ӷ��������н�������ͨ·��</td></tr>
<tr><td>SQ(Send Queue)</td><td>
�����洢�û����͵�SR�Ķ��С�</td></tr>
<tr><td>SR(Send Request)</td><td>
��һ���ᱻ���͵�SQ�е�WR����������Ҫ����������ж�����ݵ�Ŀ��λ���Լ�����ķ�ʽ
������Ĳ������ȷ�����䷽ʽ����</td></tr>
<tr><td>SRQ(Share Receive Queue)</td><td>
��һ�������Ž��յ�����Ϣ��WQE���У����յ�����Ϣ�����������κ���ص�RC/UC/UD QP.
���QP����ͬһ��SRQ������</td></tr>
<tr><td>TCA(Target Channel Adapter)</td><td>
һ������Ҫ֧��verb�﷨��ͨ����������ͨ������I/O�豸�С�</td></tr>
<tr><td>UC(Unreliable Connection)</td><td>
�����������ӵ�QP�������һ��QP����һ��QP����ϵ��QP��û��ִ�пɿ�Э�飬���������
��Ϣ���ܶ�ʧ��</td></tr>
<tr><td>UD(Unreliable Connection)</td><td>
һ��QP���������Ϣ���԰�Ϊ��λ��ÿ��UD QP�ܺ�������������UD QP�������ݵĽ��պͷ��͡�
��Ϣ�ڴ��ݵĹ����п��ܻᶪʧ���ҵ���˳����ܻ���ҡ�UD QP��Ψһ֧�ֶಥ��Ϣ��ģʽ��
UD���ݰ��Ĵ�С������MTU</td></tr>
<tr><td>Verbs</td><td>
�����������Ĺ��ܵ�һ�ֳ���������ʹ��Verbs,�κ�Ӧ�ö��ܴ����͹�������RDMA���ݴ����
����</td></tr>
<tr><td>VPI(Virtual Protocol Interface)</td><td>
�����û��ܹ��ı�˿ڵ�2��Э�顣</td></tr>
<tr><td>WQ(Work Queue)</td><td>
SQ��RQ�е�һ�֡�</td></tr>
<tr><td>WQE(Work Queue Element)</td><td>
����Ϊ"wookie"����WQ���������У��е�һ��Ԫ�ء�</td></tr>
<tr><td>WR(Work Request)</td><td>
�û��ύ��WQ���������У���һ������</td></tr>
</table>

###1 RDMA��ϵ�ṹ����
####1.1 InfiniBand
   InfiniBand(IB)��һ�ַ������ʹ洢���Ļ��������������и��١����ӳ١���CPU���ء�
��Ч�ʺͿ���չ�����ԡ�InfiniBand�Ĺؼ�����֮һ������Ȼ��֧��Զ��ֱ���ڴ���ʣ�RDMA��
��InfiniBand�ܹ��÷������ͷ�����֮�䡢�������ʹ洢�豸֮������ݴ��䲻��Ҫ������CPU
�Ĳ��롣InfiniBandʹ��I/Oͨ���������ݴ��䣬ÿ��I/Oͨ���ṩ�����NIC��HCA���塣InfiniBand
�ṩ�˶��ټ���������ÿ���˿ڵ��ٶȴ�10Gb/s(SDR)��56Gb/s(FDR)��ʹ��ͭ����º͹��˽���
���ӡ�InfiniBand�ĸ�Ч�ʺͿ���չ��ʹ���ںܶ������Ϊ��ѵ����ܺ��Լ۱ȵķ���������������
��Щ��������������ܼ��㡢�Ƽ��㡢Web2.0Ӧ�á��洢�����ݿ⡢�����������ĺ�Ӧ�á�InfiniBand
��IBTA��֯������ƶ��ļ�����׼��
