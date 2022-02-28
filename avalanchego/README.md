<div align="center">
  <img src="resources/AvalancheLogoRed.png?raw=true">
</div>

---

## 환경준비 

- [Go](https://golang.org/doc/install) version >= 1.16.8
- [gcc](https://gcc.gnu.org/)
- g++

### Native Install


```sh
git clone https://github.com/ava-labs/avalanchego.git
cd avalanchego
```


#### 아발란체(Avalanche) NOde 실행을 위한 building


```sh
./scripts/build.sh
```

build 디렉토리가 형성되며 avalanchego bibary파일 생성


### Docker Install


```sh
./scripts/build_image.sh
```

### Mainnet에 연결

```sh
./build/avalanchego
```

### Testnet(Fuji)에 연결

```sh
./build/avalanchego --network-id=fuji
```



