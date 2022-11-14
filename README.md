AIMM 5G system simulator

Purpose
-------

The AIMM simulator emulates a cellular radio system roughly following 5G concepts and channel models.   The intention is to have an easy-to-use and fast system written in pure Python with minimal dependencies. It is especially designed to be suitable for interfacing to AI engines such as ``tensorflow`` or ``pytorch``, and it is not a principal aim for it to be extremely accurate at the level of the radio channel.  The simulator was developed for the AIMM project (<https://aimm.celticnext.eu>).

Software prerequisites
----------------------

1. Python 3.8 or higher <http://python.org>.
2. NumPy <https://numpy.org/>. This normally comes with python distributions.
3. Simpy <https://pypi.org/project/simpy/>.   This will need to be installed, e.g. with ``pip install simpy``.
4. If real-time plotting is needed, matplotlib <https://matplotlib.org>.

Installation
------------

Downloading the wheel (typically ``dist/aimm_simulator-2.0.0-py3-none-any.whl``) and running ``pip install <wheel>`` should be all that is needed.

After the install, test it with ``python3 examples/basic_test.py``.

See the full html documentation for further details.