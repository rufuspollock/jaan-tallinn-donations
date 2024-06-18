---
resources:
  - name: donations
    path: donations.csv
    schema:
      fields:
        - name: disbursed
          type: date
        - name: via
          type: string
        - name: cur
          type: string
        - name: amount
          type: number
        - name: value
          type: string
        - name: recipient
          type: string
        - name: purpose
          type: string
---

# Jaan Tallinn philanthropic donations

Interesting as a big funder of Effective Altruism and especially AI existential risk.

Wonderfully he makes his giving data directly available in both human readable *and* machine readable form on his site 👏👏

https://jaan.online/philanthropy
https://jaan.online/philanthropy/donations.csv

![image](https://github.com/rufuspollock/jaan-tallin-donations/assets/180658/3c26e189-35cf-4284-a4f1-7a12ebdfe807)
