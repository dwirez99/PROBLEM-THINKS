# PROBLEM-THINKS
this wiil contain my steps to solve the problem

# ntfs3 mounting partition failed
first install ntfs-3g 
<pre>
  sudo pacman -S ntfs-3g
</pre>
install ntfs utils
<pre>
  sudo pacman -S ntfs-utils
</pre>

and then excute this command
/dev/xyz is your partision
<pre>
  sudo ntfsfix -d /dev/xyz
</pre>

after that mount your partition 
mount
<pre>
  sudo mount -t ntfs3 /dev/xyz /locationformount

</pre>
