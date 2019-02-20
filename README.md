1. 设置环境变量
    ```
    FLASK_APP=main.py
    ```
2. 安装依赖
    ```
    pip install -r requirement.txt
    ```
3. 生成数据表
    ```
    # 创建migrate repository
    flask db init
    # 生成migration
    flask db migrate
    # 应用migration
    flask db upgrade
    ```
4. 运行系统
    ```
    flask run
    ```
