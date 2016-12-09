I have the Windows [Fixlet Debugger][1] working on OS X bundled into a .app using [WineBottler][2].

# TODO: replace link:
**Download here:**  NeedNewLink/FixletDebugger_9.2.0.363_OSX_WINE_BETA.zip

**Note:** This will be running under the WINE context, which thinks it is Windows XP. This will not work with OS X only relevance, and it may not work with all Windows based relevance either. I have not tested this enough to know what works and what doesn't, but I still think this could be useful.
  

----------


You can recreate what I did by downloading [WineBottler][3] and use the following settings:

![](https://jgstew.github.io/images/Winebottler_FixletDebugger_9.2.png)
# TODO: Add alt text, caption

----------
  
This may be an option for many Windows Only utilities on OS X. The Session Relevance Tester comes to mind.
  
### References:

- https://github.com/activescott/lessmsi/issues/3
- https://mike.kronenberg.org/winebottler-1-5-30-now-with-codesigning-support/
- https://www.ibm.com/developerworks/community/wikis/home?lang=en#!/wiki/Tivoli+Endpoint+Manager/page/Fixlet+Debugger+(QnA)+Tool
- https://forum.bigfix.com/t/fixletdebugger-on-osx-using-winebottler/12778


  [1]: http://support.bigfix.com/bes/install/utilities/9.2/
  [2]: http://winebottler.kronenberg.org/
  [3]: http://winebottler.kronenberg.org/combo/builds/WineBottlerCombo_1.6.1.dmg
  
