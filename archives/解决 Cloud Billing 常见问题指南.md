# 解决 Cloud Billing 常见问题指南

本文档旨在帮助您识别和解决在使用 **Cloud Billing** 时可能遇到的常见问题，并提供详细的解决方案。

如果您使用的是 **Google Workspace**，请参考 [排查 Google Workspace 结算问题](https://support.google.com/a/topic/2413217?hl=zh-cn)。

## 获取 Cloud Billing 支持

**Google Cloud** 为所有客户提供了免费的 **Cloud Billing** 支持服务。如需联系支持代表以解答结算相关问题，请访问 [Cloud Billing 支持团队](https://cloud.google.com/billing/docs/support?hl=zh-cn) 页面获取联系方式。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## 了解扣费原因

以下是一些关于 **Cloud Billing** 扣费的常见问题。

### 按月多次扣费

对于使用自动付款结算周期的账号，如果未付余款超出最低限额，系统会在当天扣费。此外，下个月的第一天也会扣除当月产生的额外费用。

例如，假设最低限额为 500 欧元，当费用达到 500 欧元时，系统会自动扣款。若当月总费用为 1675 欧元，则需分三次支付，每次 500 欧元（3 x 500 = 1500），并在下个月第一天支付剩余的 175 欧元。

[详细了解自动付款和起付金额结算](https://cloud.google.com/billing/docs/how-to/billing-cycle?hl=zh-cn#threshold-billing)。

### 人工付款后扣款

如果您的 **Cloud Billing** 账号设置为自动付款，但在您进行人工付款时，系统可能已经通过自动付款扣款。此外，若账号已到结算周期期末，人工付款后仍会按自动结算周期扣款。

如果扣款总额与人工付款之和大于应付金额，剩余余额将作为贷记项记入您的账号。

## 无法识别的 Google Cloud 或 Google Maps 扣款

如果您收到无法识别的扣款，请根据以下情况采取相应措施。

### 拥有 Cloud Billing 账号

如果与您的 **Cloud Billing** 账号关联的付款方式被收取了无法识别的费用，请联系 [Cloud Billing 支持团队](https://cloud.google.com/support/billing?hl=zh-cn)。

### 没有 Cloud Billing 账号

如果您未拥有 **Google Cloud** 或 **Cloud Billing** 账号，请通过 [未知 Google Cloud 收费咨询](https://support.google.com/cloud/contact/cloud_platform_unknown_charges?hl=zh-cn) 表单提交工单。

### 对扣款提出异议

针对未经授权的扣款提出异议的过程因国家/地区而异。

#### 印度 UPI 用户

1. 取消您的 **UPI** 自动付款授权，避免进一步扣款。
2. 联系银行申请退款。

#### 美国及其他国家/地区

联系银行提出退款申请，银行会将异议通知 **Google**，并进行审核。

## 缺失 Cloud Billing 交易或文档

您可以在 **Google Cloud** 控制台中访问 **Cloud Billing** 文档和交易：

- [查找 Cloud Billing 文档](https://cloud.google.com/billing/docs/how-to/get-invoice?hl=zh-cn)，如账单、对账单和付款收据。
- [查看交易记录](https://cloud.google.com/billing/docs/how-to/view-history?hl=zh-cn)。

**注意**：由于 **Google Cloud** 产品会以不同时间间隔向 **Cloud Billing** 报告使用情况，您可能会在使用服务与查看费用之间看到延迟现象。

## 申请退款

如果您的账号中有未使用的资金，您可以申请退款。但在以下情况下无法退款：

- 结算账号中有使用促销代码余额。
- 账号中有未结余额。

申请退款步骤如下：

1. 登录 **Google Cloud** 控制台的 **付款概览** 页面。
2. 选择要为其申请退款的 **Cloud Billing** 账号。
3. 点击 **申请退款**。
4. 确认退款方式。

## 查看赠金和调整

**Google** 会通过赠金和借记项修改您的账号余额。您可以查看应用于您账号的账单、调整项和通知单。

- [查看账单和通知单](https://cloud.google.com/billing/docs/how-to/get-invoice?hl=zh-cn)。
- [查看赠送金额](https://console.cloud.google.com/billing/credits?hl=zh-cn)。

## 解决自动付款遭拒问题

如果付款遭拒，请按以下步骤解决：

1. 在 **交易** 页面查看遭拒原因。
2. 联系银行或信用卡公司。
3. 重新启用付款方式。
4. 进行人工付款。

## 其他 Cloud Billing 问题

如需进一步支持，请访问 [Cloud Billing 支持团队](https://cloud.google.com/billing/docs/support?hl=zh-cn)。