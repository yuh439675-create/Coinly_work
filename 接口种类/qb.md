# 接口种类

Coinly提供标准化API，允许企业将我们的钱包无缝集成到他们的应用中，确保流畅的用户体验和高效的运营。通过钱包即服务（WaaS），企业无需构建或维护自己的钱包基础设施即可提供数字钱包服务，从而简化实施流程并降低开发成本。

## 1. 生成地址

<figure><img src="https://2287475285-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FSdMhazXkh30OBfLly0nW%2Fuploads%2F8tOue3AsqxtizGeWCK7B%2Fimage.png?alt=media&#x26;token=3f37353d-1c71-4700-abf2-e65181302c67" alt=""><figcaption></figcaption></figure>

通过API，企业可以生成属于企业主地址的子地址。这些子地址可以分配给用户以接收加密货币支付。Coinly为企业提供“收集”功能，将所有子地址的资产收集到指定钱包地址，方便用户管理和使用。成功收集的资金和矿工费可以在钱包的交易记录中查询。

## 2. 转出（提现或支付 ）

<figure><img src="../images/Snipaste_2025-09-13_17-39-50.png" alt=""><figcaption></figcaption></figure>

企业转账或提现操作必须通过Coinly企业钱包进行。 为确保请求安全，需请求Coinly API服务器的IP地址并将其添加到IP白名单中。Coinly API仅允许白名单中的IP地址访问。

## 3. 支付引擎 （加密支付网关）

<mark style="color:green;">**此API需要申请。如果您有兴趣，请**</mark>[<mark style="color:blue;">**联系我们**</mark>](https://www.Coinly.com/zh/appointment/)<mark style="color:green;">**。**</mark>

* Coinly为企业提供API，帮助企业将加密支付网关集成到其在线商店或实体POS系统中。消费者可以选择加密货币作为支付方式进行结算。
* Coinly将代表商户收款，并在结算时返还给商户。
* Coinly还根据企业需求提供自动货币兑换服务。例如，我们可以将加密货币转换为法币并发放给商户。
* Coinly可以为企业设计支付页面。在收到支付详情后，Coinly将内容转化为可视化页面，可包含企业的徽标，并展示给用户。
* 客户可以选择使用哪种加密货币支付。Coinly将协助计算并直接显示所需金额和转账地址。
* 客户可以复制地址或扫描地址二维码进行支付。

### **使用流程**

1. **支付请求生成**<br>
   消费者创建订单并请求支付。
2. **获取支付详情**<br>
   Coinly接收支付详情，包括支付金额和所需加密货币。
3. **生成子地址**<br>
   Coinly为消费者生成子地址用于支付。
4. **收款**<br>
   Coinly代表商户收款。
5. **结算**<br>
   Coinly进行结算，并将法币或加密货币返还给商户。
