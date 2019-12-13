# Study Travis



1. create github repository => `study_travis`

2. add `.travis.yaml`

    ```yaml
    language: bash
    script:
    - tests/mytest.sh
    ```

3. dir
    ```
    ├── .travis.yaml
    └── tests
        └── mytest.sh
    ```

4. https://travis-ci.org にログイン

5. sync accountをクリックし，Githubの情報を取得

    ![a](docs/a.png)

6. オンにする

    ![b](docs/b.png)

7.  自動的に，webhookがオンになる

    ![b](docs/b.png)

