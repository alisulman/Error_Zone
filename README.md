
# Errors

-> The errors we disscuss are:

- Gitbash push error
- Gitbash Cloning error



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

## GitHub CLoning Error

![App Screenshot]([https://github.com/alisulman/Error_Zone/issues/1#issue-2242235981](https://res.cloudinary.com/du9pbx3ro/image/upload/v1713111143/WhatsApp_Image_2024-04-14_at_21.01.22_y4qerh.jpg))

---

Resolve this issue by entered some commands.

```bash
  $ ssh-keygen -t ed25519 -C "your_email@example.com"
```
