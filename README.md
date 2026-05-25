# water
10000 bottles of water on the wall<br/>
10000 bottles of water<br/>
take one down, pass it around<br/>
9999 bottles of water on the wall...<br/>

## usage
You can specify how many bottles of water there are on the wall by using an integer greater than 0 as an argument.<br/>
**eg**:
```
./water 100     # for 100 bottles of water on the wall (default value)
./water 10000   # as ParrotX2 once said, "No, it's Thursday bro"
```
> *"rekrap, kenadian, derapchu... anybody out there? gosh I feel so bad for jumper bruh"*

You can also specify what is inside each bottle with the `-b` flag.<br/>
Usage: `./water {bottles} -b {contents}` or `./water -b {contents} {bottles}`

**eg**:
```
./water 100 -b "beer"
./water -b "mangojuice" 10000
```
<br/>

---
### **Note**
Because of the way this script is designed, you cannot put any spaces in the contents of the bottles, even if you escape the spaces or put it in quotes.<br/>
Some examples of this would be:
```
./water 100 -b "mango juice"   # won't work
./water 100 -b mango\ juice    # also won't work
```
