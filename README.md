**1. Clone wallet sources**

```
git clone https://github.com/rdp-studio/rdpcoinwallet.git
```

**3. Set symbolic link to coin sources at the same level as `src`. For example:**

Create a git submodule:

```
git submodule add https://github.com/rdp-studio/rdpcoin.git cryptonote
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
