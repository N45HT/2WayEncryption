# 2WayEncryption
Build your own 2-way encryption using PHP

This will make a single letter into 512 random strings 16 length
Example:
```
"A" => [
      "\\AvSb/86q?P1Lm7;",
      "7n[i5W|CxW3]gA6^",
      "2b:s4B|GsX4!zM3:",
      "dP6>bE2+5JkuG/|9",
      "5AcbD\\\\6!WsZs+55",
      "6TeoQ~-8+PvYq_42",
    ...
]
```

### Usage
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
