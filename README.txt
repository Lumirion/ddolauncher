 
 ddolauncher.py
 Copyright (C) 2012 by Florian Stinglmayr
 Email: fstinglmayr@gmail.com
 Web: https://github/n0la/ddolauncher
 
 This script runs DDO: Unlimited in a fast and easy way, and supports multi boxing.
 This script requires Python for Windows: http://www.python.org/getit/windows/
 
 Synopsis:
 
  Logging in to MyLogin on Khyber:
  $ python ddolauncher.py -s Khyber MyLogin

  Logging in to MyLogin and MyOtherLogin on Ghallanda, DDO is installed somewhere else:
  $ python ddolauncher.py -s Ghallanda -g d:\games\ddo MyLogin MyOtherLogin
  
 Options:
 
  -g --game-path           Full absolute path to were DDO is. Default:
                           C:\Program Files (x86)\Turbine\DDO Unlimited\
  -h --help                This bugs.
  -o --one-password        All accounts have the same password.
  -l --list-servers        List all servers and exit.
  -p --patch               Runner DDO patcher.
  -s --server              Specify server to login to, default Ghallanda.
  -v --version             Print version and author information. 
  
  License:
  
  This script is released as-is, without warranty under the two clause BSD licence.
  