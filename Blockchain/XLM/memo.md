
# Stellar Lumens (XLM)

<aside> 💡 Cheatsheet of XLM for web3 developers.

</aside>

# 요약

1.  리플 v2
2.  protobuf같은 프로토콜인 xdr을 사용하는 특이사항이 있음
3.  트랜잭션 전파시에 가스 부족하면 타임아웃 남
4.  트랜잭션 전파시에 mempool 없어서 재시도 하기 귀찮음
5.  SDK 통해서 txHash 편하게 계산할 수 있기 때문에 찾아보면 좋음
6.  주소 로컬에서 만든다고 네트웍에서 조회 안됨. 한번은 tx 생성을 통해서 노출해줘야함