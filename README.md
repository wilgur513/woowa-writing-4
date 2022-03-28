### 오프라인 같은 온라인
코로나로 인해 온라인으로 우테코 교육을 진행했다. 오프라인으로 모일 수 없어 매우 아쉬웠는데, 대부분의 크루와 코치들도 똑같을 것 같다. 3월 초부터 온라인의 아쉬움을 달래기 위해 게더를 활용하게 됐는데, 너무 너무 너무 만족스러웠다. 게더에서 다른 크루 및 코치들과 만나다보니, 프로그래밍에 대한 서로의 생각을 공유할 수 있었다. 사람들이 모여있는 장소는 대부분 토론의 장이였다. 상속과 조합과 같은 다양한 주제로 끝없는 토론이 펼쳐졌다. 토론에 참석하면 끝없는 정신적 활동으로 인해 힘은 들었지만, 서로의 생각을 공유할 수 있다는 점에서 너무 좋았다. 특히, 나와 다르게 생각하는 사람들을 만날 수 있어 생각의 지평을 넓힐 수 있는 기회가 된 것 같다. 포비의 말로는 레벨 2부터는 최대한 오프라인으로 진행할 예정이라고 했는데 너무 기대된다. 오프라인으로 모여 페어 프로그래밍하고, 의견을 나누고 토론하는 과정이 큰 성장으로 이끌 것 같다. 

### 설계에는 정답이 없다!

우테코에서 한 달 동안 교육을 받으면서 여태까지 겪을 수 없었던 경험을 체험했다. 주변 지인 중에 개발자로 활동하는 사람이 거의 없었기에, 내가 만든 코드
에 대한 리뷰가 이번이 처음이였다. 당연히 "어떤 코드가 현 상황에서 더욱 적절한 코드인가?" 또는 "현 상황의 코드는 어떤 장점과 단점을 가지고 있는가?"에 대한 토론도 이번이 처음이였다. 처음에는 "내가 왜 이런 설계를 선택했는지?"에 대한 답을 찾는 과정이 괴롭고 힘들었다. 누군가 나의 설계에 대해 의문을 제기했을 때, 상대방을 완벽히 납득시키기 위해 완벽한 정답을 찾으려 노력했기 때문에 이러한 괴로움이 발생한 것 같다. 설계에는 정답이 없고, 그 어떤한 풀이도 가능하다. 또, 설계의 과정은 트레이드 오프의 산물이기에 완벽한 정답은 없다는 사실을 한달간의 교육을 통해 깨닫게 됐다.

### 과한 설계

미션을 진행하면서도 오버엔지니어링에 대한 리뷰도 받았다. 미션을 수행하는 데 필요치 않는 추상화와 클래스 추출을 수행했기 때문인데, 이 과정을 수행하게 된 주된 계기는 중복 제거와 단일 책임 원칙이였다. 이러한 과정을 겪은 코드를 본 크루와 리뷰어는 "너무 과한 설계인 것 같다"라고 의견을 제시해줬다. 처음에는 "당연히 중복 제거와 단일 책임 원칙을 준수하기 위해서 수행할 수 있는 과정이 아닌가?"라는 생각을 했지만, `Object Design` 이라는 책을 접하고 생각이 바뀌었다. 아래의 글은 `Object Design`에서 설계에 대한 짤막한 글을 가져왔다.

> **Pursing a Solution**
> How should you choose among acceptable design alternatives? Consider this simple strategy:
> 1. If you don’t have any predefined notions, create a solution that seems to work.
> 2. Explore the limits and strengths of that solution. To hedge your bets, measure at least one alternative against the first solution.
> 3. Favor a solution that contributes to design consistency.
> 4. Don’t overwork a solution.
> 5. Fit your solution into known design patterns.
> 6. Borrow and adapt proven design ideas and archetypes.
> 7. Be willing to revise earlier decisions when this get ugly.
> 8. If you don’t have the time, don’t search for insights. Abstraction or cleverness can’t be forced.

이 글을 접하고 나서, 우테코 미션의 과정을 다시 한번 생각해보게 되었다. 블랙잭 미션에 빗대어 본다면, 1 ~ 4번까지의 과정은 페어와 함께 미션을 수행하면서 초기의 다양한 설계를 시도하고 비교하는 과정이라고 생각된다. 5, 6번과 같이 디자인 패턴을 활용하는 과정은 네오가 블랙잭 피드백 강의에서 보여준 상태 패턴을 적용하는 과정이라고 생각된다. 책에서는 초기 설계에 과한 공을 들이지마라고 얘기하고 있다. 그 이유는 초기에 과한 추상화로 인해 발견할 수 있는 다양한 설계 대안들을 발견하기 어렵게 만들기 때문이라고 말한다.

미션을 수행하면서 설계 원칙을 과하게 준수하려 노력하다보니 과한 추상화가 발생하게 됐고, 이로 인해 초기의 다양한 대안들을 발견하기 어려운 상황이 발생했다. 이 글을 접하고 미션을 수행할 때 너무 과한 추상화를 수행하고 있는 건 아닌지 한번 의심하는 시간을 가졌다. 확실히 이전보다는 과했던 추상화 수준이 많이 낮아진 것을 느꼈지만, 아직 많이 부족한 것 같다. 전체 과정 중 거의 1/5을 진행했는데, 벌써부터 성장함을 느끼고 있다. 아무래도, 책으로만 습득할 수 없는 경험을 우테코를 통해 겪고 있어서 그런 것 같다. 앞으로 남은 과정을 통해 얼마나 더 큰 성장을 겪을 지 기대된다.
