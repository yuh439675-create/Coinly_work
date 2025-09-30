# 接口种类

Coinly提供标准化API，允许企业将我们的钱包无缝集成到他们的应用中，确保流畅的用户体验和高效的运营。通过钱包即服务（WaaS），企业无需构建或维护自己的钱包基础设施即可提供数字钱包服务，从而简化实施流程并降低开发成本。

## 1. 生成地址

<figure><img src="https://2287475285-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FSdMhazXkh30OBfLly0nW%2Fuploads%2F8tOue3AsqxtizGeWCK7B%2Fimage.png?alt=media&#x26;token=3f37353d-1c71-4700-abf2-e65181302c67" alt=""><figcaption></figcaption></figure>

通过API，企业可以生成属于企业主地址的子地址。这些子地址可以分配给用户以接收加密货币支付。Coinly为企业提供“收集”功能，将所有子地址的资产收集到指定钱包地址，方便用户管理和使用。成功收集的资金和矿工费可以在钱包的交易记录中查询。

## 2. 转出（提现或支付 ）

<figure><img src="../images/Snipaste_2025-09-13_17-39-50.png" alt=""><figcaption></figcaption></figure>

企业转账或提现操作必须通过Coinly企业钱包进行。 为确保请求安全，需请求Coinly API服务器的IP地址并将其添加到IP白名单中。Coinly API仅允许白名单中的IP地址访问。

