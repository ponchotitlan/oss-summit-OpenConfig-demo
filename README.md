# Data Networks Neutrality with OpenConfig 🧙🏼‍♂️⚙️
## Open Source Summit Europe 2024 🐧🇪🇺🇦🇹

<p align="center">
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/made-with-python.svg" /></a>
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/built-with-love.svg" /></a>
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" /></a>
</p>

### Nice to see you! ☕
And **thank you!** for having attended [my session at this year's summit](https://events.linuxfoundation.org/open-source-summit-europe/program/schedule/). I hope that you enjoyed it and found it useful for your day-to-day network management, or even any side project or certification prep.

You can find in this repository the following items:
- Jupyter notebook shown in the session
- PDF with the slides deck

### Using the notebook 📚
To execute the code snippets, you need to first create a virtual environment and install the Python libraries mentioned in the ```requirements.txt``` file.

```
:~$ python -m venv myenv

:~$ myenv\Scripts\activate (Windows)
:~$ source myenv/bin/activate (Linux)

:~$ pip install -r requirements.txt
```

The virtual environment must be selected as the Python kernel for your Jupyter notebook. The steps vary depending on your IDE (if using any). [You can find here the instructions for Visual Studio code.](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)

This notebook makes use of the [always-on Cisco IOSXR device provided by DevNet](https://devnetsandbox.cisco.com/DevNet/catalog/ios-xr-always-on). The credentials hardcoded in this notebook might change, hence it is important to have a look at the sandbox for any possible updates.

### Resources and more 💻
| Resources    |
|----------|
| [OpenConfig public repository](https://github.com/openconfig/public/tree/master/release/models) |
| [OpenConfign schema paths online explorer](https://openconfig.net/projects/models/paths/) |
| [OpenConfig schema documentation - trees and docs](https://openconfig.net/projects/models/schemadocs/) |
| [Cisco YANG Suite](https://developer.cisco.com/yangsuite/) |


---
Done with 🧡  by [Alfonso Sandoval](https://linkedin.com/in/asandovalros)