Requires:
* python2.6
* virtualenv
* mongodb


Prereq
-----------------------
Activate the virtualenv
<code><pre>$ virtualenv oadev <br>$ source oadev/bin/activate
</pre></code>

Install requirements
<code><pre>(oadev) $ pip install -r requirements.txt
</pre></code>

Starting the Dev Server
--------------------------
Set up the script
<code><pre>(oadev) $ cp runserver.sh.template runserver.sh</pre></code>
Change the details of runserver.sh for your own use. 
(ie, make sure the environment variables point to the right place for you.)

Run the Development Server
<code><pre>(oadev) $ chmod +x runserver.sh <br>(oadev) $ ./runserver.sh</pre></code>
