Extract = {getR29.cs, getToken.cs, getR29prevmonth.cs}
Transform = {chargebreakdowncleaning.py, chargebreakdowncleaningtwo.py, findsame_cb.py}
Load = {sqlconnect.py}

Execute Transform and Load = {run_CBcleaningpipeline.bat}
Execute Extract, then Transform and Load = {run_CBfullpipeline.bat, run_CBprevmonth.bat}
