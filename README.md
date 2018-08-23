## CRDT

### 배경
- Eventual Consicstency
	
	node 간 데이터 충돌 발생 가능 (데이터 불일치)
	
	read 연산의 값이 다를 수 있음
	
	특정 정책을 사용해 충돌 해결 가능 (데이터 일치)

- Strong Consicstency

	모든 노드들이 update 되기 전까지 클라이언트의 요청이 lock

- Strong Eventual Consistency

	특정 데이터 유형에만 유효 (commutative and associative)
	
	각 연산이 독립적으로 시행되므로 충돌 없이 노드 동기화


### 정의
###
