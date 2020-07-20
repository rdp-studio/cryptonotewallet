**1. Clone wallet sources**

```
git clone https://github.com/rdp-studio/rdpcoinwallet.git
```

**3. Create a git submodule to coin sources at the same level as `src`:**

```
git submodule add https://github.com/rdp-studio/rdpcoin.git cryptonote
```

And then...

```
git submodule update
```

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
