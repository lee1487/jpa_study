# jpa_study
```
2022/6/22 복습 
  - jpa 사용시 Entity를 직접 response로 return하면 많은 에러가 발생하기 때문에 dto로 변환해서 리턴해야 한다. 
  - 이 때 페이징을 적용하기 위해서는 fetch조인 최적화를 사용할 때 toMany 관계가 lazyloading될 경우는 항상 생각해서 구현 해 주어야 한다. 
    자세한 내용은 pdf 참조
```
