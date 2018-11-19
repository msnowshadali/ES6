**Getter** - A getter is a method that gets the value of a specific property

**Setter** - Setter is a method that sets the value of a specific property.

```
Example
 var attendance = {
      _list:[],
      set addName(name){
        this._list.push(name);
      },
      
      get getList(){
        this._list.join(', ');
      }
 }
```
 
 Usage
 attendance.addName = "John";
 console.log(attendance.getList);
