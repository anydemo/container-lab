mkdir b0 b1 b2 upper work merged
rm -r b0 b1 b2 upper work merged
mount -t overlay overlay2 -o lowerdir=./b0:./b1:./b2,upperdir=./upper,workdir=./work ./merged
