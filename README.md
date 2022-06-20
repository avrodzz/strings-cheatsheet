# Strings Cheatsheet

<details>
    <summary>
      <span>
        <strong>References</strong>
      </span>
    </summary>
    <ul>

- [Jenny Han's "Strings Cheatsheet" Example](https://jennylihan.notion.site/Strings-Cheatsheet-a9550d6ebd2d40fa909c1faa8cc22b1a)
- [cplusplus](https://cplusplus.com/reference/)
- [Finding a string in a string](https://www.delftstack.com/howto/cpp/how-to-find-substring-in-string-cpp/)

    </ul>
</details>


---
### Declaring a string
```c++
    // C++
    string firstName = "alexis";
    string lastName = "rodriguez";
```
<!-- ```python 
    # Python
    firstName = 'alexis'
    lastName = 'rodriguez'
``` 
```java
    // Java
    String firstName = "alexis";
    String lastName = "rodriguez";
``` -->

---

### Finding the size of a string
```c++
    // C++
    firstName.size() // Returns 6
    lastName.length() // Returns 9
```
<!-- ```python
    # Python
    len(firstName) # Returns 6
    len(lastName) # Returns 9
```
```java
    // Java
    firstName.length() // Returns 6
    lastName.length() // Returns 9
``` -->

---
### Getting a substring (part of a string)
```c++
    // C++
    // Returns "ale" --> starts at index 0, str length 3
    firstName.substr(0,3);

    // Returns "z" --> starts at index 8, str length 1
    lastName.substr(8, 1);
```

---
### Comparing strings
```c++
    // C++
    // Relational operators
    string a = "a";
    string b = "b";
    if(a < b){ // true
        cout << a << " is less than " << b << endl;
    }
    else if(a > b){
        cout << a << " is greater than " << b << endl;
    }
    else{
         cout << a << " and " << b << " are equal" << endl;
    }
    // .compare is also an option
```

---
### Concatenating (joining) two strings
```c++
    // C++
    // Both Return "alexisrodriguez"
    string fullName = firstName.append(lastName); 
    string fullNameToo = firstName + lastName;
```

---
### Looping through a string and accessing one character at a time
```c++
    // C++
    for(int i = 0; i < firstName.length(); i++){
        cout << firstName[i];
    }

    for(int i = 0; i < firstName.length(); i++){
        cout << firstName.at(i);
    }

   for(char c : firstName){
        cout << c;
    }
```

---
### Finding a string in a string
```c++

```






