# Pop-Corn-Talk

![popcorntalk-image](https://github.com/pop-corn-talk/pop-corn-talk/assets/155416976/57bf3205-848a-40ab-bb1a-af3c1f357575)



## 배포 주소


> **프론트 서버** : <br> http://52.79.44.5:3000 <br>
> **백엔드 서버** : <br> http://pct-alb-1518631164.ap-northeast-2.elb.amazonaws.com <br>



## 👩‍💻 팀원

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/wooseok50"><img src="https://avatars.githubusercontent.com/u/155416976?v=4" width="100px;" alt=""/><br /><sub><b> 팀장 : 조우석 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/Onenyeong"><img src="https://avatars.githubusercontent.com/u/48433827?v=4" width="100px;" alt=""/><br /><sub><b> 부팀장 : 장원녕 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/dosalpark"><img src="https://avatars.githubusercontent.com/u/108345184?v=4" width="100px;" alt=""/><br /><sub><b> 팀원 : 박승현 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/parkjungsub"><img src="https://avatars.githubusercontent.com/u/154612223?v=4" width="100px;" alt=""/><br /><sub><b> 팀원 : 박정섭 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/harrisbang2"><img src="https://avatars.githubusercontent.com/u/84154173?v=4" width="100px;" alt=""/><br /><sub><b> 팀원 : 방세훈 </b></sub></a><br /></td>
    </tr>
  </tbody>
</table>


---
## 프로젝트 소개

<aside>
💡 🎬🍿 **POP CORN TALK** 🍿🎬

🌟 **영화를 사랑하는 모든 이에게!** **영화 리뷰 SNS를 소개합니다!** 🌟

🎥 우리 플랫폼에서 영화 애호가들로 구성된 활발한 커뮤니티에 참여하여 리뷰를 공유하고, 숨겨진 보석을 발견하는 **POP CORN TALK** 서비스에서 참여하세요!

**🔎 영화 선택에 고민이라면?**

당신의 시간과 돈을 아낄 수 있는 영화 리뷰가 여기 있습니다! 영화에 대한 솔직한 리뷰를 서로 이야기하며 당신이 원하는 영화를 선택하는 데 도움을 드립니다.

**📝 당신도 리뷰어가 되어보세요!**

영화에 대한 여러분의 의견을 공유하고 다른 팬들과 소통해보세요. 우리의 커뮤니티에서 영화에 대한 대화에 참여하고 새로운 친구들을 만나보세요.

🌟 **서비스 이용 방법**

- 좋아하는 영화에 대한 리뷰 게시판 게시 📝
- 다른 사용자의 리뷰 게시판에 댓글 달기 💬
- 적립한 포인트로 **POP CORN TALK**에서 제공하는 쿠폰(영화티켓, 팝콘교환권)을 교환

💰 **포인트 적립 방법**

- 가장 댓글이 많이 달린 리뷰 게시판을 선정하여 포인트 지급 💰
- 게시글을 작성하면 포인트 지급 💰
- 커뮤니티 이벤트 및 챌린지에 참여하기 🏆
- 회원가입 리워드 💰

🌟 영화를 사랑하는 분들과 함께 참여하여 영화에 대한 열정을 공유하세요! 

</aside>

#Pop-Corn-Talk #CinemaCommunity #EarnRewards #MovieMagic #SNS

---
## Stacks 

### Backend

- Java  17
- SpringBoot  3.2.4
- MySQL  8.0
- Redis 7.1.0
- SSE
- Log4j2

### Infra

- Docker
- Github Actions
- AWS
    - EC2
    - ECS (Fargate)
    - ECR
    - FARGATE
    - Lambda (EventBridge)
    - RDS(Aurora MySQL)
    - Elasticache
    - S3

### FrontEnd

- React


---
### 실행환경
```
org.springframework.boot' version '3.2.4
JDK 17
```

---
## 아키텍쳐
![스크린샷 2024-04-25 165738](https://github.com/pop-corn-talk/pop-corn-talk/assets/155416976/459b45b4-a325-4e00-be4d-87af7ba46b48)



---
## API 명세서
[https://teamsparta.notion.site/17b7d0c1b7be44a2bf0141b6109ed30d?v=74bc6889cd284f53b7224afaa274f123](https://teamsparta.notion.site/17b7d0c1b7be44a2bf0141b6109ed30d?v=74bc6889cd284f53b7224afaa274f123)


---
## ERD
![erd2](https://github.com/pop-corn-talk/pop-corn-talk/assets/155416976/cf03588e-b481-4eb8-b89b-ea3434bbd5a1)



---
## 주요 기능 

### 🍿 SNS 소통 
- 영화에 대한 리뷰, 이미지, 게시글을 작성하여  커뮤니티에 참여할 수 있습니다.
- 본인의 게시글에 댓글이 작성될 경우 실시간으로 알림을 받아볼 수 있습니다.

### 🍿 포인트 적립
- 회원가입 시 포인트 적립 리워드
- 영화 리뷰 게시글 작성 시 포인트 적립
- 전월 가장 인기 있는 게시글의 리뷰어 3명에게 적립 리워드

### 🍿 영화 할인권 구매
- 적립한 포인트를 사용하여 영화 할인권을 구매할 수 있습니다.
- 구매하신 상품은 구매 버튼 클릭과 동시에 실시간으로 전달 받을 수 있습니다.


# 🛠성능 개선

### 구매 요청에 대한 데이터베이스 부하 최적화

- 재고 관리를 위한 Redis 적용
    - 인메모리 데이터 구조 저장소인 Redis를 활용하여 제품 수량을 관리
    - 구매 요청이 있을 때마다 데이터베이스를 즉시 업데이트하지 않고, Redis에서 상품 재고를 관리하여 상품의 수량 감소
    - Redis의 제품 수량이 0에 도달하여 제품이 품절되었음을 나타내는 경우에만 데이터베이스에 쓰는 메커니즘 구현
    
    상품을 DB에 등록하는 과정에서 **hashOperations.put**() 메서드로 redis의 해시 맵에 데이터 추가
    
    ```java
    @Override
    @Transactional
    public void createProduct(ProductCreateRequestDto productCreateRequestDto,
        Long userId) {
        userService.validateAdminUser(userId);
        Product product = Product.createOf(productCreateRequestDto);
        Product saveProduct = productRepository.save(product);
    
        hashOperations.put(HASH_KEY, String.valueOf(saveProduct.getId()),
            String.valueOf(saveProduct.getAmount()));
    }
    ```
    ![Untitled](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/b3e7db20-c97a-4965-8e98-b8f81968f3ce)

    
    
    redis에 상품 id 와 상품 수량을 등록
    
    구매 요청이 들어오면 아래 메서드가 수행되어, redis의 상품 수량 차감
    
    이후 redis의 상품 수량이 0이 되면 데이터를 삭제하고, 연동된 DB의 상품 수량을 초기화 후 판매완료 상태로 업데이트
    
    ```java
    // 상품 수량 차감 메서드
    private void deductProductAmount(Product product) {
    
      if (!hashOperations.hasKey(HASH_KEY, String.valueOf(product.getId()))) {
          throw new IllegalArgumentException("재고가 소진되었습니다.");
      }
    
      long incrementCount = hashOperations.increment(HASH_KEY,
          String.valueOf(product.getId()), -1);
    
      if (incrementCount == 0) {
          hashOperations.delete(HASH_KEY, String.valueOf(product.getId()));
          product.updateAmount(0);
          product.softDelete();
      }
    }
    ```
    
    Redis에서 상품 재고를 관리하기 때문에 기존 데이터베이스 보다 처리 속도가 빠르고, 데이터베이스 쓰기를 연기함으로써 데이터베이스 트랜잭션 수를 최소화하여 데이터베이스 서버의 부담 완화
    

### 인덱싱

- 검색기능 중 비중이 높은 게시물 이름으로 조회 할 때의 속도개선 필요성

       **→ 인덱스를 이용한 쿼리 최적화**

- [Test]
    - **[테스트 조건]**
        - **100명의 사용자가 1초에 10번 접속**
        - **게시물 100,000 개 등록**

        ![Untitled (1)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/37cb3dfa-5acc-4e0b-bdc2-c0ace54a6c20)
        ![Untitled (2)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/ee6700e0-d0c7-4d6d-8f45-b017ca2d85ad)
        ![Untitled (3)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/d2a95fa9-26bf-4b42-92b9-79fa88b45acb)
      
        - 적용 전 -> Post_createdAt 적용 후 :  33.2/s => 259.1/s   **7.8 배 TPS 향상**

### 캐싱

- 필수적으로 수행되거나, 이용자의 접근이 많아서 DB에 잦은 조회가 발생

       **→ Redis Cache 적용**

- [Test]
    - **[테스트 조건]**
    - **100명의 사용자가 1초에 10번 접속하는 상황**
      ![Untitled (4)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/67459aea-3e07-4f8d-9ed1-83f80654780c)
      ![Untitled (5)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/65895e1c-270a-41d4-8822-5b4875f96548)


    - **DB에 조회 쿼리 최초 1회 발생,**  **DB 부하↓**
    - **캐시에 등록되기 때문에 TPS는 큰 의미 X**
    
    **그라파나 적용으로 System Cpu 사용량 측정**

    ![Untitled (6)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/a6977cd2-371c-49c1-a99e-3cbb78ae4173)

    
    - 적용 전: System CPU 사용량 0.291
    - 적용 후: System CPU 사용량 0.236
    
          → **19.1%** 의 리소스 절약
    

### DB replication

- 웹사이트의 읽기와 쓰기 비중은 읽기 비중이 높음

      ****따라서 복잡한 로직이 다수 수행될 경우 뒤의 읽기, 쓰기 작업의 처리속도 지연 발생 ****

      **→ DB Replication 적용**

- [Test]
    
    **[테스트 조건]**
    
    - 100명의 사용자가 1초에 10번 접속하는 상황
    - Get요청은 100,000건의 데이터 중 10개의 특정한 데이터를 조회
    
      ![Untitled (7)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/3279180b-1ab4-473b-9ace-76aa1a7f01ab)
      ![Untitled (8)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/46c83aed-b143-4782-b215-ee56fa0c1b80)

  
    - 읽기 :  21.8/s => 29.7/s   **36.2% TPS 향상**
    - 쓰기 :  23.0/s => 28.6/s   **24.3% TPS 향상**(post, post2의 평균값으로 계산)
    - 합계 :  63.7/s => 83.3/s   **30.7% TPS 향상**

# 🛠 트러블슈팅

### 스케쥴링

- [문제 상황 & 원인]
    - 특정 조건에 의해 자동으로 포인트를 지급하는 메서드 수행과정
    - @Scheduler 통해 구현한 메서드로 단일 서버 환경에서 정상 동작
    - 하지만 배포 후 멀티 서버 환경에서는 해당 메소드가 서버의 수 만큼 동작하여 리소스 낭비 + 포인트 추가 지급 문제 발생
- [해결 과정]
    - 하나의 서버에서 만 실행되어야 하기에 Spring batch, AWS Lambda를 이용하여 지정된 시간에 스케쥴링을 실행할 수 있다고 판단
    - Spring batch는 스케쥴링 기능은 있지만 대용량 데이터 자동화 처리에서 사용하기 위해 나왔으며, 별도의 서버를 설치 및 구성해야 한다는 점에서 AWS에서 제공하는 서버리스 서비스인 Lambda와 EventBridge를 이용하여 스케쥴링을 구현
        ![Untitled (9)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/db75c910-e0c0-4e84-bbd0-8237adae72f6)
        ![Untitled (10)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/fae04004-82b9-46ae-a90e-188af1579c5f)
    - Lambda에 실행 할 Http 메소드를 기재하고 원하는 시간에 EventBridge에서 이벤트를 발생시켜서 Lambda가 실행되도록 설정

### 동시성 제어

- [문제 상황 1]
    - 상품을 교환하는 로직에서 구매 수량보다 상품의 수량이 적게 차감되는 동시성 문제 발생
    
    [원인]
    
    - 별도의 락이 설정되어 있지 않아서 다수의 이용자가 상품을 구매 할 때 동시에 구매하게 되서 수량이 정상적으로 차감되지 않는 문제
    
    [해결 과정]
    
    - 싱글쓰레드로 동작하는 Redis의 특성을 이용, hashTable을 통한 상품재고 관리 및 동시성 제어
      ![Untitled (11)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/1cfe5d31-8228-4c6c-a30b-f3ec302cf65e)
      ![Untitled (12)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/081b0872-827f-4246-849b-5c310d99de4b)
      
- [문제 상황 2]
    - 관리자가 상품의 정보를 수정 및 삭제 하는 과정에서 유저의 상품 구매 요청이 성공하는 상황 발생
    
    [해결 과정] 
    
    - Redis의 Redisson 라이브러리를 사용하여 pub/sub 방식의 분산락 구현
    
    ```java
    // DistributedLockAop.java
    @Aspect
    @Component
    @Slf4j(topic = "DistributedLock 설정")
    @AllArgsConstructor
    public class DistributedLockAop {
    
        private final RedissonClient redissonClient;
        private final AopForTransaction aopForTransaction;
    
        @Around("@annotation(com.popcorntalk.global.annotation.DistributedLock)")
        public Object lock(ProceedingJoinPoint joinPoint) throws Throwable {
            MethodSignature signature = (MethodSignature) joinPoint.getSignature();
            Method method = signature.getMethod();
            DistributedLock distributedLock = method.getAnnotation(DistributedLock.class);
    
            String baseKey = distributedLock.lockName();
            String dynamicKey = generateDynamicKey(signature.getParameterNames(), joinPoint.getArgs(),
                distributedLock.identifier());
            String key = baseKey + " : " + dynamicKey;
            RLock lock = redissonClient.getFairLock(key);
    
            log.info("{} - 락 획득 시도", key);
            try {
                boolean lockAcquired = lock.tryLock(distributedLock.waitTime(),
                    distributedLock.leaseTime(), distributedLock.timeUnit());
                if (!lockAcquired) {
                    log.info("{} - 락 획득 실패", key);
                    throw new IllegalArgumentException(key + " - RLock 획득 실패");
                }
    
                log.info("{} - 락 획득 성공", key);
                return aopForTransaction.proceed(joinPoint);
            } finally {
                try {
                    if (lock.isHeldByCurrentThread()) {
                        lock.unlock();
                    }
                    log.info("{} - 락 반납", key);
                } catch (IllegalMonitorStateException e) {
                    log.info(e + baseKey + dynamicKey);
                }
            }
        }
    
    ```
    
    - 상품의 수정, 삭제 , 구매 중 다른 유저가 상품에 접근 할 수 없도록 상품의 ID로 분산락 적용
    - 설정 중 코드의 중복이 발생하여서 커스텀 어노테이션 생성하여 코드의 중복 최소화
    
    ```java
    	// ExchangeServiceImpl.java, 상품 구매 로직 메서드
    	@Override
      @DistributedLock(lockName = "product", identifier = "productId", waitTime = 60, leaseTime = 4)
      public void createExchange(Long userId, Long productId) {
    
          Product product = productService.getProduct(productId);
    
          pointService.checkUserPoint(userId, product.getPrice());
    
          productAmount(product);
    
          pointService.deductPointForPurchase(userId, product.getPrice());
    
          Exchange exchange = Exchange.createOf(userId, product.getId(), product.getVoucherImage());
          exchangeRepository.save(exchange);
    
          notificationService.notifyPurchase(userId, ADMIN_EMAIL, product.getVoucherImage());
      }
    ```
    

### Jwt Refresh  토큰 재발급 보안 문제.

- [문제 상황]
    - 토큰을 조작 해서 새로운 토큰을 발급 받을 수 있는 문제
    - 만료된 이전 Access Token을 통해서 토큰을 재발급 받을 수 있음
- [원인]
    - 토큰을 재발급 할 때 유저 가 동일 한지만 검증 함
- [해결 방법]
    - refresh 토큰이 저장되어 있는 cache 에 가장 최근에 발급한 Access 토큰을 포함 시켜서 새로운 토큰 발급 요청 시 로그인 할 때 전달한 Access 토큰 까지 검증
    
    ![Untitled (13)](https://github.com/Onenyeong/pop-corn-talks/assets/108345184/4aefc09c-c86f-417b-a5ca-9e1b2efb7270)


### RedisConfig의 복수의 CacheManager 문제

- [문제 상황]
    - 프로젝트를 실행중 아래의 Exception 발생
    
    ```java
    No CacheResolver specified, and no unique bean of type CacheManager found. 
    Mark one as primary or declare a specific CacheManager to use. excetion
    ```
    
- [원인]
    
    설정이 다른 서비스를 위해 RedisConfig에 추가로 CacheManager를 생성
    다수의 CacheManager가 프로젝트 실행시에 올라와서 발생한 문제
    
    ```java
    // CacheAspectSupport.class
    @Override
    public void afterSingletonsInstantiated() {
    	if (getCacheResolver() == null) {
    		// Lazily initialize cache resolver via default cache manager
    		Assert.state(this.beanFactory != null, "CacheResolver or BeanFactory must be set on cache aspect");
    		try {
    			setCacheManager(this.beanFactory.getBean(CacheManager.class));
    		}
    		catch (NoUniqueBeanDefinitionException ex) {
    			throw new IllegalStateException("No CacheResolver specified, and no unique bean of type " +
    					"CacheManager found. Mark one as primary or declare a specific CacheManager to use.", ex);
    		}
    		catch (NoSuchBeanDefinitionException ex) {
    			throw new IllegalStateException("No CacheResolver specified, and no bean of type CacheManager found. " +
    					"Register a CacheManager bean or remove the @EnableCaching annotation from your configuration.", ex);
    		}
    	}
    	this.initialized = true;
    	}
    ```
    
- [해결 과정]
    - CacheManager중 하나를 Primary로 등록해주어야 하며 하나의 CacheManager에 @Primary 어노테이션 붙혀서 기본 CacheManager 값을 지정하여  조치 완료
    
    ```jsx
     		@Bean(name = "cacheManager")
        @Primary
        public CacheManager cacheManager() {
            RedisCacheManager.RedisCacheManagerBuilder builder =
                RedisCacheManager.RedisCacheManagerBuilder.fromConnectionFactory(
                    redisConnectionFactory());
    
            RedisCacheConfiguration configuration = RedisCacheConfiguration.defaultCacheConfig()
                .serializeValuesWith(
                    RedisSerializationContext.SerializationPair.fromSerializer(
                        new GenericJackson2JsonRedisSerializer())) // Value Serializer 변경
                .disableCachingNullValues()
                .entryTtl(Duration.ofMinutes(10L));
    
            builder.cacheDefaults(configuration);
    
            return builder.build();
        }
    ```
