# ASUC Elections Tabulator v4.0
By: Yun Park and Alton Zheng-Xie (2014)

This is a GUI application used by the ASUC of UC Berkeley to tabulate votes.

For questions or concerns, please email altonzheng@berkeley.edu or yunpark93@gmail.com.

# To Build:
Prerequisites:

* wxPython
* Python 2.6 or 2.7

Running the app is easy:

`
python ElectionApp.py
`

# How to Use
1.	Load ballots in proper json format (use election_parser_json if needed)
2.	Load candidates in proper json format
3.	Choose speed / position (to tally)
4. 	Click redistribute to run one step of current race OR click complete to complete the current race

Note:
Sample data is provided from the 2014 ASUC Elections in the input_data folder.
