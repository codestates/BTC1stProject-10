
### 환경준비
* Go version <= 1.15.5+


### Native Install


```zsh
git clone https://github.com/ava-labs/avash.git
cd $GOPATH/src/github.com/ava-labs/avash
go build
```

### 5개 노드 실행

```zsh
./avash
Config file set: /Users/username/.avash.yaml
Avash successfully configured.
avash> runscript scripts/five_node_staking.lua
RunScript: Running scripts/five_node_staking.lua
RunScript: Successfully ran scripts/five_node_staking.lua
```

### Commands

* `avaxwallet` - 네트워크를 통해 Avalanche Payments와 상호 작용하기 위한 도구
* `exit` - 종료
* `help` - 커맨드에 대한 설명
* `network` - 원격 호스트와 상호 작용하기 위한 도구.
* `procmanager` - avash 클라이언트의 프로세스 관리자에 액세스
* `runscript` - 스크립트 실행


### Funding a Wallet

로컬 네트워크에서 기본 서브넷의 3가지 체인(X-Chain, C-Chain 및 P-Chain)에는 test를 위한 개인 키 'PrivateKey-ewoqjP7PxY4yr3iLTpLisriqt94hdyDFNgchSxGGztUrTXtNN'이 있습니다. 
개인키는 X-Chain에 300m AVAX, C-Chain에 50m AVAX, P-Chain에 30m AVAX(20m는 잠금 해제되어 있고 10m는 잠겨 있고 스테이킹 가능)가 있습니다. 

참조 : [로컬 테스트 네트워크 자금 지원 튜토리얼](https://docs.avax.network/build/tutorials/platform/fund-a-local-test-network)

### Customize configuration
[Avalanche Documentation](https://docs.avax.network/build/tools/avash).
