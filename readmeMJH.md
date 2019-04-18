
<code>
sudo apt install libwxgtk3.0-dev

./configure 
</code>
Output from above command
<code>
checking system:
 wx-config found
Warning: --rezflags, along with Mac OS classic resource building is deprecated.  You should remove this from your Makefile and build .app bundles instead.
 ghc found
 ghc-pkg found
ghc-pkg: cannot find package haskell98
 haddock found
./configure: 812: cd: can't cd to /opt/ghc/7.10.3/doc/libraries
 wxWidgets Unicode support found
 install program found

creating configuration files:
 config
 config/config.mk
 config/wxcore.pkg
 config/wx.pkg
 config/wxhaskell-register.bat
 config/wxhaskell-unregister.bat
 config/setcd
 config/macosx-install.info
 config/macosx-postinstall
 config/macosx-app
 config/wxhaskell.spec
 config/prologue.txt
 config/cache.txt

configuration:
 library:     wxhaskell-0.11.1.3  (release 0)
 compiler:    ghc-7.10.3
 wxwidgets:   gtk-3.0.2
 extensions:
   openGL:    no
   mediactrl: no
   contrib:   no
 library dir: /usr/lib

done:
 type 'make' to build wxhaskell.
 type 'make install' to install wxhaskell.
 type 'make help' to receive help on all other make targets
</code>

