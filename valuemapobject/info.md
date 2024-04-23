# Value Map Object
The Value Map object is a simple hashtable object for Clickteam Fusion 2.5. It can store String and Number data and can be accessed with integer values. (fixed values in this context, but they can be any integer) The object also has a **buffer** which acts like a way to store temporary variables instead of creating a separate Active to store said data or adding unnecessary data slots to your Fusion objects.

**Compatability**<br>
This object is compatible with Windows and Android platforms.
<br>

## Actions
* **Set Current Object**<br>
Sets the current key to the integer provided. This can be any integer; it is not limited to a fixed value.

* **Current**<br>
Set a String or Number value in the current object. If it does not exist, it will be created.

* **With Fixed Value**<br>
Set a String or Number value in the object with the matching provided fixed value. If it does not exist, it will be created.

* **Buffer**<br>
Set a String or Number value in the buffer. If it does not exist, it will be created.

* **Loop through object with loop name**<br>
Loop through each value in the object with the matching provided fixed value.

* **Erase object**<br>
Erases all object data for the object with the matching provided fixed value.

## Conditions
* **Does Value exist in object with fixed value?**<br>
Returns true if the value name provided exists in the object with the matching provided fixed value.

* **Does Value exist in the buffer?**<br>
Returns true if the value provided exists in the buffer.

* **On Value Loop**<br>
Loops on object with the matching provided fixed value's data.

## Expressions
* **Current Object**<br>
Get a Number or String value from the current object.

* **With Fixed Value**<br>
Get a Number or String value from an object with the matching provided fixed value.

* **Buffer**<br>
Get a Number or String value from the buffer.

* **Loops**<br>
Get the Number or String value at the current loop index.
* If the current value at the loop index is a String and you ask for a float, it will return -1. If it is a float and you ask for a String, it will return "".

* **Get fixed value of current object**<br>
Returns the current object's fixed value.
