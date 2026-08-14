# gg_statistics_ex
통계 기본 실습

# 단축키

text 셀 -> code 셀 : [esc -> y]
code -> text 셀 : [esc -> m]
실행 : ctrl + enter
실행 + 다음셀로 커서 이동 : shift + enter
셀 삭제 : esc -> dd
되돌리기 : z
현재 셀의 위쪽에 셀 추가 : [esc -> a]
현재 셀의 아래쪽에 셀 추가 : [esc -> b]

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
