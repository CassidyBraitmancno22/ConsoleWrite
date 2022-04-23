# ConsoleWrite
ret = WinActivate ("Untitled - Notepad") ConsoleWrite($ret &amp; "/" &amp; @error &amp; "/" &amp; @extended &amp; @CRLF) $ret = Send ("1 1") ConsoleWrite($ret &amp; "/" &amp; @error &amp; "/" &amp; @extended &amp; @CRLF)
