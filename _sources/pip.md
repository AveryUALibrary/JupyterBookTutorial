(section-label)=
# PIP Installation

---

If you already have this installed, please head to [Git](git.md)

(section-label)=
## Check for PIP Installation

Before we install **PIP**, let's make sure you don't already have it installed.

1) Open up the command prompt
   1) press the windows ⊞ key 
   2) Type cmd
      1) ```{image} cmdsearch.png
         :alt: search
         :class: bg-primary mb-1
         :width: 500px
         :align: center
         ```
   3) Press Enter
2) Type into the command prompt
   1) 
   ```
   pip help
   ```
3) If it outputs a list of commands, then you already have **PIP** installed

## Installing PIP

1) You are gonna reopen command prompt, as shown above.
2) Type in:

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```
```{image} pipcurl.PNG
:alt: curl of pip
:class: bg-primary mb-1
:width: 500px
:align: center
```
3) To install the **PIP** file, type in:
```
python get-pip.py
```
```{image} pipinstall.PNG
:alt: pip installation
:class: bg-primary mb-1
:width: 500px
:align: center
```

## Verify PIP Install

Type the following into the command prompt:
```commandline
pip help
```
```{image} piphelp.PNG
:alt: pip help output
:class: bg-primary mb-1
:width: 500px
:align: center
```

**Now you are done!!!**




