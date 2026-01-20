# base44453
Detecting High Gas Usage With No State Change
if receipt.status == 1 and receipt.gasUsed > 400_000 and tx["value"] == 0:
    print("Expensive no-op call")
