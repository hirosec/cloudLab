## cloudLab
<pre><code>
Credits: [HiroSec] https://github.com/hirosec

> Last Edited: 2025/07/14
</code></pre>

## Update
#-------------------------------------------------------------------------------
# Default Package Update
#------------------------------------------------------------------------------- 
<pre><code>
 # Default Package Update
apt update -y -q && apt upgrade -y -q 
</code></pre>

#-------------------------------------------------------------------------------
# Custom Package Installation [Ansible]
#-------------------------------------------------------------------------------  
<pre><code>
apt install -y -q ansible

apt show ansible

ansible --version

ansible localhost -m setup  
</code></pre>

## License

MIT

