# Simple Interest Calculator (Bash Script)

This is a simple **Bash script** to calculate the **Simple Interest** based on the principal amount, annual rate of interest, and time period in years.

⚠ **Note:** This script is for learning and demonstration purposes only. Do not use in production.

---

## 📌 **Author**

* Original Author: **Upkar Lidder (IBM)**
* Additional Authors: **\<your GitHub username>**

---

## 📝 **Description**

The script calculates the **Simple Interest (SI)** using the formula:

$$
\text{Simple Interest} = \frac{P \times T \times R}{100}
$$

Where:

* **P** = Principal amount
* **T** = Time period in years
* **R** = Annual rate of interest (%)

---

## ▶ **How to Run**

1. **Make the script executable**

   ```bash
   chmod +x simple_interest.sh
   ```

2. **Run the script**

   ```bash
   ./simple_interest.sh
   ```

3. **Provide input when prompted**

   ```
   Enter the principal:
   1000
   Enter rate of interest per year:
   5
   Enter time period in years:
   2
   The simple interest is:
   100
   ```

---

## 💻 **Script Code**

```bash
#!/bin/bash
# This script calculates simple interest given principal,
# annual rate of interest and time period in years.
# Do not use this in production. Sample purpose only.
# Author: Upkar Lidder (IBM)
# Additional Authors:
# <your GitHub username>

echo "Enter the principal:"
read p
echo "Enter rate of interest per year:"
read r
echo "Enter time period in years:"
read t

s=`expr $p \* $t \* $r / 100`

echo "The simple interest is:"
echo $s
```

---

## ✅ **Sample Output**

```
Enter the principal:
1500
Enter rate of interest per year:
4
Enter time period in years:
3
The simple interest is:
180
```

---

## 📄 **License**

This project is licensed under the MIT License - feel free to modify and use.
