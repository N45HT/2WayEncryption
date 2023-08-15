# 2WayEncryption
Build your own 2-way encryption using PHP

### Example
**command:**

`php 2WayEncryption.php hello`

**output:**

```
encrypted   : 5g@f7D?YgU6!bE7}3UxqO^!4;XjJt^070=}Yni2U3m!x8N\N\DbUg)33g;N9Nz2-[CeRl"05p+H2Yv0{
output file : out.txt
```

The output will automatically be stored in a TXT file

**command:**

`cat out.txt`

**output:**

`5g@f7D?YgU6!bE7}3UxqO^!4;XjJt^070=}Yni2U3m!x8N\N\DbUg)33g;N9Nz2-[CeRl"05p+H2Yv0{`

Now, you can decrypt it by including the output file in the command

**command:**

`cat out.txt`

**output:**

```
input       : 5g@f7D?YgU6!bE7}3UxqO^!4;XjJt^070=}Yni2U3m!x8N\N\DbUg)33g;N9Nz2-[CeRl"05p+H2Yv0{
decrypted   : hello
```
