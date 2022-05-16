# CalculateBit
#include &lt;CalculateBitEntropy.au3> Local $sPassA = 'Tr0ub4dor&amp;3' ; Passphrase. Local $sPassB = 'correct horse battery staple' MsgBox(0, '_CalculateBitEntropy', $sPassA &amp; ': ' &amp; _CalculateBitEntropy($sPassA) &amp; @CRLF &amp; $sPassB &amp; ': ' &amp; _CalculateBitEntropy($sPassB))
