# Item 21. 인터페이스는 구현하는 쪽을 생각해 설계하라

### Java에서는 

본문에서는 생각할 수 있는 모든 상황에서 불변식을 해치지 않는 인터페이스의 디폴트 메서드를 작성하기 어렵고 때문에 디폴트 메서드로 인해 기존 클라이언트를 망가뜨릴 수 있기 때문에 꼭 필요한 경우가 아니면 인터페이스를 구현하는 쪽으로 생각해 설계하라고 권고하고 있습니다. 