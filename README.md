This is the same code that I downloaded from subversion on 01/02/2013 using:

# Non-members may check out a read-only working copy anonymously over HTTP.
svn checkout http://zxing.googlecode.com/svn/trunk/ zxing-read-only

except that I added some pdf 417 reader code for the iphone to the ScanTest sample application.

Simply open ScanTest.xcodeproj in XCode and you should be able to build and run the app (I tested with XCode 4.5.)  Caveat that this code addition was ported from some C# code that I found online and I have no idea how well it works.  It seems to work for some PDF 417 codes and works better in landscape orientation for some reason.  If you can figure out why it is not more stable and fix the code, go for it.

Whatever license applies to the zxing codebase applies to this code addition as well.

If you have any questions e-mail me at: adamgf@gmail.com

Also if you are a developer involved in mobile payments check out my Passbook pass creation websites at:

http://www.passsupply.com

and

http://www.passmerchant.com

