---
    title: How to Apply General Ledger Entries [FR]
    description: You apply general ledger entries to justify ledger balances on asset and liability accounts.

    author: SorenGP

    ms.service: dynamics365-business-central
    ms.topic: conceptual
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 06/18/2021
    ms.author: edupont

---
# Apply General Ledger Entries in the French Version
You apply general ledger entries to justify ledger balances on asset and liability accounts. For example, you can apply transactions on the bill of exchange accounts to get a clear picture of which bills make up the balance of the account.  

## To apply general ledger entries  

1.  Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Chart of Accounts**, and then choose the related link.  
2.  On the **Chart of Accounts** page, select the account that you want to apply entries for, and then choose the **Apply Entries** action.  
3.  On the **Apply G/L Entries** page, select the ledger entries that you want to apply.  
4.  Choose the **Set Applies-to ID** action to populate the **Applies-to ID** field with the user ID of the current user.  
5.  Choose the **Post Application** action.  

This effectuates the application by setting the **Letter** and **Letter Date** fields.  

> [!NOTE]  
>  Applied entries can be identified by having the same three-letter combination and the same date.

## See Also  
[Unapply General Ledger Entries](how-to-unapply-general-ledger-entries.md)  
[Apply Vendor Payments Manually](../../payables-how-apply-purchase-transactions-manually.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]