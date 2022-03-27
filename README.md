# portable-executable-2-hex-code
This project will convert portable executable both bin &amp; exe to hex code.

To create an independent HEX code of any Portable Executable you need to follow these steps/

<ol>
  <li>Use Donut.exe "donut.exe -f {YOUR_PAYLOAD}" and you will get payload.bin which is an independent binary.</li>
  <li>Use pe2hex.exe "pe2hex.exe -h {payload.bin}". You will get an independent HEX code in text file.</li>
  </ol>
