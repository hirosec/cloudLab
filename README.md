## cloudLab
<pre><code>
Credits: [HiroSec] https://github.com/hirosec

> Last Edited: 2025/07/14
</code></pre>



## AWS calculator
```
+-----------+---+------+---------+--------+                       
|Type       |CPU|RAM   |Hourly   |Monthly |         
+-----------+---+------+---------+--------+
|t3a.nano   | 2 |  0.5 | $0.0047 |   3.43 |
|t3a.micro  | 2 |  1.0 | $0.0094 |   6.86 | 
|t3a.small  | 2 |  2.0 | $0.0188 |  13.72 | 
|t3a.medium | 2 |  4.0 | $0.0376 |  27.45 | 
|t3a.large  | 2 |  8.0 | $0.0752 |  54.90 |
|t3a.xlarge | 4 | 16.0 | $0.1504 | 109.79 |
+-----------+---+------+---------+--------+
```

## Update
<pre><code>
#-------------------------------------------------------------------------------
# Default Package Update
#------------------------------------------------------------------------------- 
apt update -y -q && apt upgrade -y -q 
</code></pre>

<pre><code>
#-------------------------------------------------------------------------------
# Custom Package Installation [AWS-CLI v2]
#-------------------------------------------------------------------------------
# Package Install AWS-CLI v2 Tools (from Kali Linux Official Repository)
apt install -y -q awscli

aws --version


# Configuration AWS-CLI tools

</code></pre>


<pre><code>
#-------------------------------------------------------------------------------
# Custom Package Installation [Terraform]
#-------------------------------------------------------------------------------
apt install -y -q terraform

apt show terraform

terraform --version  
</code></pre>
## License

MIT

