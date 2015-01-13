# Golang version of punycode

Copy https://code.google.com/p/go/source/browse/?repo=net#hg%2Fidna

##Install

go get github.com/Zverushko/punycode

## Using

import "github.com/Zverushko/punycode"

punycode.ToASCI("ляляля.рф") // xn--k1aaa2fbb.xn--p1ai 

punycode.ToUnicode("xn--k1aaa2fbb.xn--p1ai") // ляляля.рф
