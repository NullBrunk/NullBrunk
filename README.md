![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=220&section=header&text=Anas&fontSize=60&animation=fadeIn&fontAlignY=38&desc=Web%20Development%20%2F%20SysAdmin&descAlignY=51&descAlign=62)

```php
class Profile {

    private $info = "Web Developper, SysAdmin";

    private $technos = [
        # Frontend
        "HTML/CSS", "JavaScript", "Bootstrap",

        # Backend
        "Laravel", "Livewire", "PHP", "Python3", "Bash",

        # Database
        "SQL", "Redis"
    ];

    public function __construct($info,  $langs, $techs) {
        $this -> technos = $technos;
        $this -> info = $info;
    }

}
```
