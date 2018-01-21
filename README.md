# cpumon
CPUMon is a Linux Bash Script created to quickly on the fly change the processor speeds of Dual Core CPUs.
It is a self-automated script which means all you have to do is run it as sudo and away you go.

sudo ./cpumon

cpumon runs from the location /var/cpumon
if you dont have the folder cpumon in your var directory
create it using sudo mkdir /var/cpumon
sudo chown it to the local user, i.e. you.
sudo chmod +x both the scripts

included in the files are.

./cpumon

./cpulist

cpumon then sets the max cpu speed based on the avilable speeds.
it also sets them independently for each core, one by one.
as a finisher it will retrieve the lscpu information for the Processor within your system.
its a nifty script that has come in handy to set the speed of my processor as it likes to fluctuate 
between 1Ghz and 1.6Ghz and at those speeds, you really notice the drop....

It is Primarily Designed for the Compaq NX6310 Business Laptop - 
I work mainly on older hardware to keep older hardware running,
So i figure, why let all that processing power go to waste? 

Again. Free and Open Source.
Enjoy.
Master Cassidy.
Droitech Games.
