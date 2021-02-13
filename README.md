In critical severity defect [Privilege Escalation in Channelmgnt plug-in for Sopel](https://github.com/advisories/GHSA-j257-jfvv-h3x5) the package name `rsopel_plugins.channelmgnt` is displayed.  The affected versions <= 1.0.0 and patched versions = 1.0.3.

A `requirements.txt` with `sopel_plugins.channelmgnt==1.0.0` does not raise a critical error in dependabot.

In the *pypi* project the package name [sopel-plugins.channelmgnt](https://pypi.org/project/sopel-plugins.channelmgnt/) is displayed

May be that the underscore `_` versus dash `-` is the difference and causing dependabot not to report this vulnerability.

As a control, `ansible` which also has a critical vulnerability is in place.

Only the ansible alert may be found at:
https://github.com/gm3dmo/dependabot-python-sopel/security/dependabot
