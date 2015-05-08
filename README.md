# Magento
Magento minor fix, or hacks.

#For Multi site or Multi store
## app/code/local/Mage/Payment/Model/Observer.php
When create Invoice from backend, Bank Transfer Payment Instruction overwritten by default website's. so fixit.

This code use always Orderd website's Bank Transfer Payment Instruction.
