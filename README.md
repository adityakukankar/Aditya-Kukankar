```epsilon
language EOL;

class SoftwareEngineer {
    var name : String = "Aditya";
    var role : String = "Software Engineer";
    var languageSpoken : Sequence<String> = Sequence{"zh_CN", "en_US"};

    operation sayHi() {
        "Thanks for dropping by, hope you find some of my work interesting.".println();
    }
}

var me : new SoftwareEngineer;
me.sayHi();
```
