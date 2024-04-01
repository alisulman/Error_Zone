
# Errors

-> The errors we disscuss are:

- Gitbash push error



## GitHub Push Error

![App Screenshot](https://res.cloudinary.com/du9pbx3ro/image/upload/v1711936291/GitHub%20Images/MINGW64__e_Ali_Sulman_VS_Code_Logical_and_Technical_World_projrcts_serious_projects_4_1_2024_6_49_07_AM_zuwyrv.png)


---

Resolve this issue by entered some commands.

```bash
  $ git fetch origin <Your repository branch>:tmp
```

```bash
  $ git rebase tmp
```

Now you can push your code to github    

```bash
  $ git push -u  origin <Your repository branch>
```
---
