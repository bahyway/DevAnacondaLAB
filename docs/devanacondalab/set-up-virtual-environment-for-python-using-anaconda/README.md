---
description: Setup Page
---

# Set up virtual environment for Python using Anaconda

{% hint style="success" %}
Use This Link:

[**Set up virtual environment for Python using Anaconda**](https://www.geeksforgeeks.org/set-up-virtual-environment-for-python-using-anaconda/)
{% endhint %}

### **Step 1: Check if conda is installed in your path.**

```bash
conda -V
# Update conda
conda update conda
```

**Step 2: Set up the virtual environment**

*   Type conda search “

    ```python
    ls -ls /usr/bin/python*
    ```

    ” ,or:&#x20;

    ```python
    ls -1 /usr/bin/python* | grep '.*[2-3]\(.[0-9]\+\)\?$'
    ```

&#x20;to see the list of available python versions.

* Now replace the envname with the name you want to give to your virtual environment and replace x.x with the python version you want to use.
