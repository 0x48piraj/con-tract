# Con-tract


<p align="center">
<img alt="Con-tract" src="https://user-images.githubusercontent.com/5800726/141606560-a6ddb296-840c-4531-8bdc-37121481e784.png"><br>
<b>Hacking the hackers with seemingly vulnerable smart contracts.</b><br>
</p>


Smart contracts that appear to have an obvious flaw in their design, which allows an arbitrary user to drain ether (Ethereum’s cryptocurrency) from the contract, given that the user transfers a priori a certain amount of ether to the contract. However, once the user tries to exploit this _apparent_ vulnerability, a second, yet unknown, trapdoor unfolds which prevents the draining of ether to succeed. The idea is that the attacker (victim) solely focuses on the apparent vulnerability and does not consider the possibility that a second vulnerability might be hidden in the contract. This works because most human beings are often easily manipulated and are not always capable of quantifying risk against their own greed and presumptions. This repository explores extensive research on these so-called _"honeypots"_.