---
title: "Plantillas"
date: 2021-11-20T13:54:16+01:00
draft: false

---

***
## BOTONES
{{% button href="https://gohugo.io/" icon="fab fa-centos" %}}Get Hugo{{% /button %}}
{{% button href="https://gohugo.io/" icon="fas fa-download" %}}Get Hugo with icon{{% /button %}}
{{% button href="https://gohugo.io/" icon="fas fa-download" icon-position="right" %}}Get Hugo with icon right{{% /button %}}

## DESCARGAR 

{{%attachments title="descargar ficheros" style="grey"/%}}

## EXPANDIR TEXTO

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Scelerisque viverra mauris in aliquam sem fringilla ut morbi. Nunc sed id semper risus in hendrerit. Eu ultrices vitae auctor eu augue ut lectus arcu. Laoreet non curabitur gravida arcu ac. {{% expand "Leer más..." "false" %}}
Enim sit amet venenatis urna cursus eget nunc scelerisque viverra. Scelerisque viverra mauris in aliquam sem fringilla. Felis bibendum ut tristique et egestas quis ipsum suspendisse ultrices. In tellus integer feugiat scelerisque varius morbi enim nunc faucibus. Molestie ac feugiat sed lectus. Amet massa vitae tortor condimentum lacinia quis vel eros. Vel elit scelerisque mauris pellentesque pulvinar pellentesque habitant. Enim tortor at auctor urna nunc id cursus metus aliquam.

Massa tincidunt nunc pulvinar sapien et ligula ullamcorper. Nibh sed pulvinar proin gravida hendrerit lectus. Tempor orci eu lobortis elementum nibh tellus molestie. Mattis aliquam faucibus purus in. Habitant morbi tristique senectus et netus. Aliquet enim tortor at auctor urna nunc id cursus. Bibendum at varius vel pharetra vel turpis nunc eget lorem. Turpis massa sed elementum tempus egestas sed sed. Tempor id eu nisl nunc. Mi in nulla posuere sollicitudin aliquam ultrices sagittis orci. Aliquam eleifend mi in nulla. Consequat semper viverra nam libero justo laoreet sit. Nulla posuere sollicitudin aliquam ultrices. Dolor sed viverra ipsum nunc aliquet bibendum. Lorem sed risus ultricies tristique nulla aliquet enim tortor at. Sed cras ornare arcu dui. Erat velit scelerisque in dictum non. Felis eget nunc lobortis mattis aliquam faucibus purus in.

Venenatis cras sed felis eget velit. Erat velit scelerisque in dictum non consectetur a. Facilisis mauris sit amet massa vitae tortor condimentum lacinia. Pellentesque pulvinar pellentesque habitant morbi. Libero enim sed faucibus turpis in eu mi bibendum neque. Sed turpis tincidunt id aliquet. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque eleifend. In massa tempor nec feugiat nisl pretium fusce id. Enim sed faucibus turpis in eu. Malesuada pellentesque elit eget gravida cum sociis natoque. Etiam erat velit scelerisque in dictum non consectetur a erat. Duis at consectetur lorem donec massa sapien faucibus. Pharetra convallis posuere morbi leo urna. Justo donec enim diam vulputate.

Massa massa ultricies mi quis hendrerit dolor magna eget. Mollis aliquam ut porttitor leo a diam sollicitudin tempor id. Cursus in hac habitasse platea dictumst quisque sagittis purus sit. Lorem sed risus ultricies tristique nulla aliquet enim tortor. Scelerisque varius morbi enim nunc faucibus a pellentesque. Sit amet purus gravida quis blandit turpis cursus.
{{% /expand %}}

## NOTICIA
{{% notice note %}}
A **notice** disclaimer

You can add:

- multiple paragraphs
- bullet point lists
- _emphasized_, **bold** and even ***bold emphasized*** text
- [links](https://example.com)
- other shortcodes besides `notice`
- etc.

```plaintext
...and even source code
```

> the possiblities are endless
{{% /notice %}}


## GRÁFICO MERMAID

{{< mermaid align="left" >}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{<strong>Decision</strong>}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

## TABS ELEMENTOS

{{< tabs >}}
{{% tab name="Tab 1" %}}
```python
print("texto en python")
```
{{% /tab %}}
{{% tab name="Tab 2" %}}
```java
> print("texto en java")
```
{{% /tab %}}
{{% tab name="Tab 3" %}}
```PHP
echo "texto en PHP"
```
{{% /tab %}}
{{< /tabs >}}

