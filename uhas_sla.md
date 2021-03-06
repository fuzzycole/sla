

# 运维审计系统等级保护协议（SLA）

UCloud UHAS服务等级协议（以下简称“本协议”）规定了UCloud向客户提供UCloud
UHAS云堡垒机服务的一般性服务等级指标和服务注意事项。本协议是《UCloud用户协议》、《云服务法律声明及隐私条款》的补充。您通过盖章、网络页面点击确认或以其他方式（如点击确认同意《UCloud用户协议》）选择接受本协议，即表示您与本公司已达成协议并同意接受本协议的全部约定内容。如若双方盖章文本与网络页面点击确认或以其他方式选择接受之服务条款文本，存有不一致之处，以双方盖章文本为准。在接受本协议之前，请您仔细阅读本协议的全部内容。您阅读后，如果继续使用UCloud
UHAS服务，即表示您接受本协议并同意受其约束；如果您不同意本协议，您可以选择不使用UCloud UHAS服务。

**1、数据存储的持久性**

  - 1.1 UHAS云堡垒机数据存储的持久性为99.99％。如果服务持久性没有达到承诺，将按照服务赔偿条款进行赔付。
  - 1.2
    数据存储的持久性定义：合同期内数据保持存储状态不丢失的概率。持久性为99.99％意指合同期内用户每月1000000字节的数据，合同期内每月数据不丢失的概率为99.99%，即每月只有100字节的数据丢失的可能性。以自然月为统计周期，不满一个月按一个月计。
  - 1.3 此类数据主要是指云堡垒机存储在数据库中的数据，不包括缓存和临时存储。

**2、数据可销毁性**

2.1 在您要求删除数据或设备在弃置、转售前，UCloud将通过高级清零操作彻底删除用户所有数据且无法复原，并对报废硬盘做消磁处理。

**3、数据私密性**

  - 3.1 UCloud采用了有效的隔离方法，保证同一资源池用户数据互不可见。
  - 3.2
    每个UHAS云堡垒机都是使用独立的MySQL数据库，其他的人员不可访问。同时为更好的确保安全性，UHAS云堡垒机仅能通过内网访问，且网络访问按账户进行隔离。

**4、数据知情权**

  - 4.1 您可在产品控制台看到云堡垒机所在的可用区名称，您可选择您所需要的可用区。北京BGP可用区位于北京市。
  - 4.2 所有数据中心应遵守当地法律和中华人民共和国法律。
  - 4.3
    除政府监管部门监管审计需要或配合安全取证调查外，未经客户同意，不能将用户数据非法提供给任何第三方。为了保障您使用本服务的安全性以及不断改进服务质量的需要，本公司将记录并保存您登录和使用本服务的相关行为日志，不会对外呈现用户个人信息数据。

**5、 业务可审查性**

  - 5.1
    根据国家的法律法规要求，为配合政府监管部门的监管审查，合规或取证调查等，本公司可提供您运行在云服务上业务的相关的信息，如关键组件的运行日志、运维人员的操作记录。

**6、业务功能**

  - 6.1 UCloud
    UHAS提供给用户的服务功能为www.ucloud.cn 网站所展示的云堡垒机服务，完整的功能介绍和操作说明详见产品使用手册和帮助说明。
  - 6.2 UCloud若更换服务的版本或功能会及时通过站内信、短信、邮件或网站等方式通知您，以便您能及时做出相应的调整。

**7、业务可用性**

  - 7.1
    本公司向您承诺UHAS云堡垒机的服务可用性为99.0％。如果服务可用性没有达到承诺，将按照服务赔偿条款进行赔付。预付费方式为计算使用量按月付费。云分发以流量和带宽计费。服务费以订购页面公布的当时有效的计费模式和标准为准。
  - 7.2
    服务可用性定义：合同期内用户每月云服务业务可用时间的概率，即每月实际可用时间／每月（实际可用时间＋不可用时间）。其中不可用时间的定义为从用户无法使用云服务起至云服务恢复正常水平结束，以自然月为统计周期，不满一个月按一个月计，以分钟为单位。

   可用性为99.0％指单个用户每月云服务业务可用时间应至少为30天24小时60分钟99.0% = 42768分钟，即每月最多存在30天24小时60分钟100%-42768=432分钟的不可用时间。云服务业务不可用的统计单元为单台云堡垒机，云服务业务不可用时间达到30分钟以上算作一次不可用，计入不可用时间，不可用时间若低于30分钟则不计入不可用时间。

**8、业务资源调配能力**

  - 8.1
    单台云堡垒机的内存、磁盘可升级扩展，内存单位为MB，范围从4096MB至16384MB，磁盘单位为GB，范围从300GB至1000GB，操作方式请咨询客服

**9、故障恢复能力**

  - 9.1 通过故障监控、快速定位、快速恢复、告知等一系列故障管控体系，保证云服务的故障恢复能力。
  - 9.2 当云堡垒机所在运行环境出现部分故障或资源预警时，应告知用户并及时恢复，避免影响用户正常使用。
  - 9.3 当云堡垒机所在运行环境出现故障，并不会影响被管理云主机的使用，客户可通过直连等其他方式进行访问，避免影响用户正常使用。
  - 9.4
    服务商承诺由于统计或计费逻辑造成云服务不可用时，可临时将统计计费下线，优先保障客户的业务，系统架构设计上可以支持降级，保证业务运行。

**10、UCloud 免责条款**

<span class="underline">因以下原因导致的服务不可用，UCloud不承担任何责任：</span>

  - 10.1 UCloud预先通知客户后进行系统维护所引起的，包括割接、维修、升级和模拟故障演练；
  - 10.2 任何UCloud所属设备以外的网络、设备故障或配置调整引起的；
  - 10.3 客户的应用程序受到黑客攻击而引起的；
  - 10.4 客户维护不当或保密不当致使数据、口令、密码等丢失或泄漏所引起的；
  - 10.5 客户的疏忽或由客户授权的操作所引起的；
  - 10.6 客户未遵循UCloud产品使用文档或使用建议引起的；
  - 10.7 由于客户违反《UCloud用户协议》导致的服务被暂停或终止，包括由于欠费导致云硬盘被暂停服务或被释放等；
  - 10.8 其他不可抗力因素引起的。不可抗力以及意外事件是指由于信息网络正常的设备维护，信息网络连接故障，电脑、通讯或其他系统的故障，电力故障，战争，天灾，政府行为等一切不能预见、不可避免、不能克服的自然、社会现象客观情况。
