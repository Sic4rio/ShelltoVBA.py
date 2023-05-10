# ShelltoVBA.py
shellcode to VBA using python 
__description__ = 'Tool to create a VBA script containing shellcode to execute'
__author__ = 'Didier Stevens'
__version__ = '0.5'
__date__ = '2016/11/16'

"""

Source code put in public domain by Didier Stevens, no Copyright
https://DidierStevens.com
Use at your own risk

History:
  2008/11/22: V0.1 forked from file2vbscript
  2010/02/13: V0.2 added base64 option
  2012/12/19: Fixed BASE64 line length to 80 in stead of 81
  2013/04/24: V0.3 added x64 option; thanks to dominic@sensepost.com
  2013/04/26: Added base64 encoding for x64
  2015/09/18: V0.4 added option --nocreatethread and --writememory
  2015/11/29: refactoring, added option --start
  2016/11/16: V0.5 added option -S

Todo:
"""
