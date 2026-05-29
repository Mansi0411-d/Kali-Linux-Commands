
# Symbolic (constant letters: r, w, x)
chmod u+r file.txt      # Add read for user
chmod g-w file.txt      # Remove write for group
chmod o+x script.sh     # Add execute for others
chmod u+x,g+r file.sh   # Multiple changes at once
# Numeric (variable values: r=4, w=2, x=1
chmod 644 file.txt      # rw- for user, r-- for group/others
chmod 600 secret.txt    # rw- for user only
chmod 755 script.sh     # rwx for user, r-x for group/others
chmod 777 test.sh       # rwx for everyone (not secure!)
