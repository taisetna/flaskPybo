#### Could not install packages due to an OSError

```bash
pip3 install package_name --user
```  

#### No moudle named 'pip

```bash
python -m ensurepip
```

### Ignoring invalid distribution -ip

*  ~으로 이루어진 폴더 때문인데 임시폴더를 만들어놨는데 아직 지우지 않았거나 이름이 잘못 배정되어 있는 경우에 저런 폴더가 나타남.
* 해당 경로에 ~로 시작하는 폴더 전부 삭제

### 가상환경 공유

* 

```bash
# 설치 패키지 리스트를 텍스트로 추출
pip freeze > requirements.txt

# 가상환경 진입후 패키지 설치
pip install -r requirements.txt
```