# Command	                            Purpose
ssh-keygen -t ed25519	                SSH key generate
ls -la ~/.ssh	                        SSH directory check
cat ~/.ssh/id_ed25519.pub	            Public key display
ssh username@SERVER_IP	                Remote server connect
ssh-copy-id username@SERVER_IP	        Public key copy
scp file.txt username@SERVER_IP:~/     	File transfer
ssh -v username@SERVER_IP	            SSH troubleshooting

