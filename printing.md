## Print class attributes

```py
attrs = vars(class_instance_with_attrs)
print(',\n '.join("%s: %s" % item for item in attrs.items()))
```
