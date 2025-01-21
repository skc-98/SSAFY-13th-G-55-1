# 광주 13기 스터디 레포지토리입니다!

## 레포 규칙
- **root/문제출처-문제번호** (ex) **백준-1000**) 디렉토리 안에 코드를 넣습니다.
- 코드 이름은** 이름.확장자**로 해주시면 됩니다.  (ex) 홍도완.rs)

## 문제 추가 예시
- 상단의 문제디렉토리를 만들고, 그 안에 problum.md 와 예제의input.txt를 첨부한다.
- ex) inoutput.txt
```text
# 예제1
5 2

# 결과
2

# 예제2
6 2

#결과
8
  
```
- 추가적으로 hint<n>.txt를 만들어, 문제풀이가 어려운 학우를 위해서 길잡이를 해줄 수 있습니다.
- ex) hint1.txt
```text
  백트레킹으로는 시간초과가 나므로 다른 전략을 생각해 보시면 좋습니다.
```


## 코드 작성 규칙
- 가장 상단에 문제해결 전략 아이디어를 서술합니다.
- ex)
```js
  /// 아이디어
  // hello world를 출력하면 된다.
  ... 코드
  
```
- 입출력의 방식에 대해선 굳이 서술하지 않는다.
- 입력이 많은 경우, 어떤 라인에서 어떤 입력을 받는 구간인지 명시한다.
- 전략의 핵심부분에 이 코드가 아이디어의 어떤 역할을 하는지 서술한다.
- ex)
```python
dfs(n, cnt){
  // 종료처리
  if n == N:
    // 최댓값을 정답에 저장함
    ans = Math.max(cnt, ans)
    return

  // 동작 처리
  ... 코드
}
  
```

_..수정 예정_
