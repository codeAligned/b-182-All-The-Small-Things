## PyTricks 

Предыдущая версия Вики -- [здесь](https://github.com/Nejel/coursera-python-specialization-repository/wiki)


with полезен при доступе к чему-либо, что поддерживает протокол управления контекстом. Например open(). В основном это гарантирует то, что любой код очищения или настройки, например, код, закрывающий файлы, спокойно запустится и не вызовет никаких беспокойств. Например, чтобы открыть файл:


```python
#код будет отображаться такъ

with open('/etc/passwd', 'r') as f:
    print f.read()

```