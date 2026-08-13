# gg_statistics_ex
통계 기본 실습

명령어

# git 레포지토리 만들기

```
git clone <git url ssh> statistics_ex


```


# 가상환경 구현하기

- 폴더이동
```
cd statistics_ex/
```

- 가상환경만들기

```
uv init --bare
```
- 파이썬 버전 확인

```
uv run python -V
```


# 주피터 노트북 사용환경 구성하기

- ipykernel 설치

```
uv add ipykernel
```

- 가상환경 .venv eda_env 이름으로 등록하기
```
uv run python -m ipykernel install --user --name .venv --display-name "eda_env"
```



# 설치 라이브러리

```
uv add numpy
uv add scipy
uv add pandas
uv add scikit-learn
uv add matplotlib
```

- 라이브러리 설치 후 자동완성이 안보인다면? 재시작 
