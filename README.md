<picture> 
<img src="/assets//images/dev.gif" align="right" width="350" height="255">
</picture>

```js
class Person:
    def __init__(self, name, title, email, country="India"):
        self.name = name
        self.title = title
        self.email = email
        self.country = country

    def introduce(self):
        return f"Hi, my name is {self.name}, I'm a {self.title} from {self.country}."


if __name__ == "__main__":
    me = Person(
        name="Aditya Sebastian",
        title="Backend AI Engineer",
        email="aditya268244@gmail.com"
    )
    print(me.introduce())
```

```cmd
$ python me.py
Hi, my name is Aditya Sebastian, I'm a Backend AI Engineer from India.
```

<div id="user-content-toc">
  <ul align="center">
    <summary><h3 style="display: inline-block">MY STACK </h3></summary>
  </ul>
</div>
<!--icons-->
<p align="center">
<a href="https://skillicons.dev">
<img src="https://skillicons.dev/icons?i=py,mysql,git,sklearn,supabase,docker,postgres,mongodb&perline=6" />
</a>
</p>
