# CR - BASH
**Current version: 0.0.1**

---

<!-- TOC -->
* [CR - BASH](#cr---bash)
  * [INSTALLATION](#installation)
  * [USAGE](#usage)
<!-- TOC -->

---

## INSTALLATION

* ```bash
  sudo mkdir -p /usr/local/lib/term-boost \
  && if [ -d "/usr/local/lib/term-boost/cr-bash/.git" ]; then sudo git -C /usr/local/lib/term-boost/cr-bash pull; else sudo git clone https://github.com/term-boost/cr-bash.git /usr/local/lib/term-boost/cr-bash; fi \
  && (cd /usr/local/lib/term-boost/cr-bash && sudo ./install)
  ```

---

## USAGE
**examples**

```bash
# Create a new script in sub-path
cr-bash scripts/custom/example/my-script

# Show help
cr-bash -h
cr-bash --help

# Show version
cr-bash -v
cr-bash --version
```

---
