# Remove files recursively

Just execute 

```
$ find . -type f -name '*.pyc' -delete
```

`find` files in `.` dir, with `-type f` containing `-name '*.pyc'` and just `-delete` them.
