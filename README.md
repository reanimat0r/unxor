# unXOR

This tool will search through an XOR-encoded file (binary, text-file, whatever) and use known-plaintext attacks to deduce the original keystream. Works on keys half as long as the known-plaintext, in linear complexity.

The code is pretty straightforward

For more details and a short explanation of the theory behind this, please refer to:

 - My original [blogpost](http://tomchop.me/yo-dawg-i-heard-you-like-xoring/)
 - The insipiring [blogpost from Chris Jordan](http://playingwithothers.com/2012/12/20/decoding-xor-shellcode-without-a-key/)
 

 ## Related Work
 
 unXOR is included in Lenny Zeltser's [REMnux](http://zeltser.com/remnux/), along with other great tools such as
 [XORStrings](http://blog.didierstevens.com/2013/04/15/new-tool-xorstrings/), [ex_pe_xor](http://hooked-on-mnemonics.blogspot.com/2014/04/expexorpy.html), [XORSearch](http://blog.didierstevens.com/programs/xorsearch/), [brutexor/iheartxor](http://hooked-on-mnemonics.blogspot.com/p/iheartxor.html), [xortool](https://github.com/hellman/xortool), [NoMoreXOR](https://github.com/hiddenillusion/NoMoreXOR), [XORBruteForcer](http://eternal-todo.com/category/bruteforce), [Balbuzard](https://bitbucket.org/decalage/balbuzard/wiki/Home)
