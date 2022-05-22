[Technologies](#Technologies) | [Installation](#installation-guide) | [Usage](#usage) | [Screenshots](#screenshots) | [Contributors](#contributors) | [License](#license)

# pychain
This is a blockchain-based leger system, using Streamlit for a user-friendly web interface. The leger allows the users to record financial transactions between sender and receiver on the blockchain ledger and can verify the integrity of the data using a Block inspector. We use Python libraries/modules along with Streamlit for achieving results shown below. 

## Technologies

This project leverages python 3.7 with the following packages / IDEs:

* [python] (https://wiki.python.org/moin/FrontPage) - is an object-oriented, interpreted, and interactive programming language.

* [streamlit] (https://streamlit.io/) - Streamlit is an open-source app framework for Machine Learning and Data Science teams.

* [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/#) - Is a browser-based interface to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

* [Visual Studio Code](https://code.visualstudio.com/?wt.mc_id=DX_841432) -Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. 

---

## Installation Guide

You will need Python version 3.7 or above and gitbash/terminal on your computer, along with other supporting packages as mentioned below. 

Please follow instructions from the below link to install python 3.7 or above on your computer

[To install Python, follow instructions from this link](https://www.python.org/downloads/)

[To install Git Bash, follow instructions from this link](https://github.com/git-guides/install-git)

[To install Anaconda, follow instructions from this link ](https://docs.anaconda.com/anaconda/install/)

[To install Streamlit, follow instructions from this link ](https://docs.streamlit.io/library/get-started/installation)

[To install Visual Studio Code, follow instructions from this link ](https://code.visualstudio.com/docs/setup/setup-overview)

```python
# install conda dev environment and activate it
    conda update conda
    conda create -n dev python=3.7 anaconda
    conda activate dev

Optional:
# install Jupyter Lab
    pip install jupyterlab

# To verify if you have scikit-learn and hvplot already installed
    conda list scikit-learn
    conda list hvplot
  
# Install Streamlit 
    conda activate dev
    pip install streamlit 
    
 
```

---


## Usage

To use the PyChain App, clone the repository and run the above commands in gitbash as applicable,

```git
git clone https://github.com/sidbetatester/pychain.git
cd pychain
streamlit run pychain.py
```
Note: to close Streamlit from gitbash, click ctrl + 'c'

## Screenshots

![pychain app with transactions recorded on the Blockchain ledger](Images/image1.png)
![pychain app - transactions validation with Block Inspector](Images/image2.png)
![pychain app - transactions validation with Block Inspector](Images/image3.png)
![pychain app w- Winning Hash and Blockchain Validation Output](Images/image4.png)


## Contributors

Siddharth Venkumahanti
[linkedin](https://www.linkedin.com/in/siddharthvenkumahanti/)


---


## License

### MIT License

Copyright (c) [2022] [Siddharth Venkumahanti]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

![MIT License](Images/MIT_License.png)
