# Binairo

You can find the instructions of the project in the file `binairo.ipynb`.

To submit your solution, please modify the file `binairo.lp` of the directory asp with your encoding.

Every time you push a new commit, your solution will be tested automatically. The timeout per instance is 100 seconds, and the actual command call for the test is:

`python3.8 asp/test.py -e asp/binairo.lp  -i asp/instances -s asp/solutions -opt -t 100 -m 1 --correct`

For help, type `python3.8 asp/test.py --help`.

After the tests are run, you will be able to see the results in the Actions tab:

* Select one of the tests, click in run-autograding-tests and go to the tab "Print output"
