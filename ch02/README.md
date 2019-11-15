


```
export FLASK_APP=application.py
flask run

curl http://127.0.0.1:5000/v1/test
curl -LI http://127.0.0.1:5000/v1/test -o /dev/null -w '%{http_code}\n' -s
```




# 参考

https://menta.work/post/detail/3638/7PiI6kAHGQJbQTAbWjlJ
