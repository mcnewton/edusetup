University of Leicester - Windows setup for eduroam

This installer does the following...


On installation:

Puts a new wireless profile in the Program Files\Eduroam directory.
Removes any wireless profile named 'eduroam' using netsh.
Removes any wireless named 'uol' using netsh.
Installs the new 'eduroam' wireless profile using netsh.

Installs the University of Leicester root certificate in the
computer root certificate store.


On removal:

Removes the University of Leicester root certificate.
Removes the wireless profile named 'eduroam' using netsh.

