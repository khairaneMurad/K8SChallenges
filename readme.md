# Create a new user with SSL certificate
k config set-credentials martin --client-key=/root/martin.key --client-certificate=/root/martin.crt

# Add a new context for the created User
k config set-context developer --user=martin --cluster=kubernetes
