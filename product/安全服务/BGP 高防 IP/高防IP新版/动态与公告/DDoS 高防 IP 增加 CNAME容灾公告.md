尊敬的腾讯云用户，您好：
为提升业务稳定性2022年5月12日起高防 IP 实例资源调整为 CNAME 的形式（不涉及三网资源），具体详情如下所示：

- 请用户尽快将访问源的 DNS 解析修改至高防资源 CNAME。该 CNAME 将解析至拥有高防属性的 IP 上，通过清洗中心后并转发回源站。（不影响现存量用户的正常使用）。
- 因 CNAME 可以解析到多个 IP 上，当主 IP 发生故障（不包括攻击导致封堵）时，我们会将 CNAME 解析至备用 IP 保证业务稳定。（高防 IP 地址可能会更换。建议将您的 DNS 解析地址修改至高防资源 CNAME，避免 DNS 解析失败。）
>!
>- 2022年5月12日前所购买高防 IP 实例，该实例下的高防 IP 将作为主 IP 保留，不会更改。为了您的业务具备更优的稳定性，请尽快需修改 DNS 解析目标为高防资源的 CNAME。（不涉及三网资源）
>- 2022年5月12日后所购买高防 IP 产品的用户，请修改 DNS 解析为高防资源 CNAME。（不涉及三网资源）

