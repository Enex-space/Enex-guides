# ↔ Fee principals

With each transaction, including custom tokens, users need to pay the transaction fee. When sending $ENQ, the user pays 0.1 $ENQ fee to the Enecuum network. When sending custom tokens, the user pays the fee to the token creator. The fee amount is set by that token creator. With each custom token transaction, the token creator pays 0.1 $ENQ fee to the Enecuum network.

The token creator also chooses the fee type. The fee can be either fixed or percentage. The fixed fee stays the same for any transaction. The percentage fee depends on the transaction amount. If the percentage fee is selected, the creator can also choose the minimum fee. Then, the user will pay the minimum fee if the transaction percent fee is too low.

{% hint style="info" %}
**Here's an example of how it works:**

* Carol creates her custom token $CRL. She sets her transaction fee type to fixed. She also sets the fee amount to 1 $CRL. Carol pays the fee in $ENQ to the Enecuum Genesis address for the token creation.
* Alice sends 10 $CRL to Bob. She pays 1 $CRL fee to Carol. Bob receives 10 $CRL.
* Carol pays 0.1 $ENQ fee to the Enecuum Genesis address for the transaction that Alice sent.
{% endhint %}

![fee structure ](<../../.gitbook/assets/Group 1 (1).jpg>)

**Usefull limks:**

{% embed url="https://guides.enecuum.com/enq/token-issue.html#fee-principles" %}

{% embed url="https://pulse.enecuum.com/#!/tokens" %}
