#### Cài đặt Django

- Sử dụng pip để cài đặt Django. Mở cửa sổ cmd, từ cửa sổ cmd gõ lệnh:
```commandline
pip install django
```
**Lưu ý**: Cần cài đặt Python trước, nếu ko có Python sẽ ko cài đặt đc các framework sử dụng python như Django

- Kiểm tra Django đã được cài đặt .Từ cửa sổ cmd, chạy python, sau đó kiểm tra phiên bản Django đã cài đặt với các lệnh:
```commandline
>> import django

>> print(django.get_version())
```

#### Tạo mới project với Django
- Từ cửa sổ cmd, tạo mới project bằng lệnh:
```commandline
django-admin startproject mysite
```

- Project mới sẽ được tạo ra trong thư mục mysite với các file như sau:
```commandline
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```

- Bắt đầu chạy thử server
- Từ cửa sổ cmd, di chuyển vào trong thư mục project (mysite) và khởi động server với lệnh:
```commandline
cd mysite
python manage.py runserver
```
