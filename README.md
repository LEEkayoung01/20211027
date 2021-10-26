# 20211027
11.4. 심사문제

1)
    >>> del x[-5:]
    >>> print(tuple(x))

2)
    >>> a = input()
    >>> b = input()
    >>> a = a[1::2]
    >>> b = b[::2]
    >>> print(a+b)
    
12. 딕셔너리 만들기
    딕셔너리 = {key1: value1, key2: value2}
    
 >>> lux = {'health': 490, 'mana': 334, 'melee': 550, 'armor': 18.72}

12.1.2. 딕셔너리 key의 자료형
    key: 문자열, 정수, 실수, 불 등 자료형 섞어서 사용 가능.
         리스트와 딕셔너리 사용 불가
    value: 모든 자료형 사용 가능
    
12.1.3. 빈 딕셔너리 만들기
    딕셔너리 = {}
    딕셔너리 = dict()
    
12.1.4. dict으로 딕셔너리 만들기
    딕셔너리 = dict(key1=value1, key2=value2)    # key에 "", '' 사용 X. 
                                                # 지정 후 key는 문자열로 바뀜.
                                                
    딕셔너리 = dict(zip([key1, key2, key3], [value1, value2, value3]))    # 리스트들로 딕셔너리 만들기
    
    딕셔너리 = dict([(key1, value1), (key2, value2)])    # 튜플로 딕셔너리 만들기
    딕셔너리 = dict({'key1': value1, 'key2': value2})
    
12.2.1. 딕셔너리의 키에 값 할당하기
    딕셔너리[키] = 값
    
12.2.2. 딕셔너리에 키가 있는지 확인하기
    키 in 딕셔너리
    키 not in 딕셔너리
    
12.2.3. 딕셔너리의 키 개수 구하기
    len(딕셔너리)
    
12.4. 심사문제
    >>> list1 = input().split()
    >>> list2 = map(float,input().split())
    >>> my_dic = dict(zip(list1, list2))
    >>> print(my_dic)
    
    
