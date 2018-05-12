# Set up

    $ sudo -s
    # dnf install -y tinc git
    # cd /etc
    # rm -rf /etc/tinc
    # git clone https://github.com/goneri/tinc-gone tinc
    # cp <SOMEWHERE>/rsa_key.priv /etc/tinc/gone/rsa_key.priv
    # cp <SOMEWHERE>/tinc.conf /etc/tinc/gone/tinc.conf

# Start up

    # systemct start tinc@gone
    # systemct status tinc@gone

You should have an interface called gone with an IP in the 192.168.135.0/24 subnet.
