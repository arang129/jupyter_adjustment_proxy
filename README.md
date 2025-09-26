# jupyter-adjustment-proxy : 教師與助教調整分數與評語用

jupyter-streamlit-proxy exposes and launches Streamlit via the relative URL
'streamlit', thereby enabling Streamlit-based web applications being launched
on top of an existing Binder infrastructure.  In addition it provides a button
within JupyterLab to launch and access the Streamlit web app via the GUI.

As the entry point for the webapp launch it expects a script at

`pip install git+https://github.com/arang129/jupyter_adjustment_proxy.git`

`pip install --upgrade git+https://github.com/arang129/jupyter_adjustment_proxy.git`

`pip uninstall jupyter_adjustment_proxy`

which has the actual streamlit launch command inside, including the actual
file name of the web application.

A usage example, the Streamlit-based web application GlycoSHIELD, is available at   
https://gitlab.mpcdf.mpg.de/dioscuri-biophysics/glycoshield-md

The package is provided as-is, see 'LICENSE'.

This package was derived from   
https://jupyter-server-proxy.readthedocs.io/en/latest/
