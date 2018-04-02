### lsd
`lsd` will enable your `ls` to become colorful.

Follow the `command` below to make it happen.

```
git clone https://github.com/k-five/cecho.git
cd cecho
make build
make test
make clean
echo 'cecho random *' > lsd
sudo chmod 777 lsd
sudo cp cecho /bin/
sudo cp lsd /bin/
```
Now you can use `lsd`

### screenshot:  
![lsd_screenshot](https://github.com/arjun-gautam/lsd/blob/master/lsd.png)
