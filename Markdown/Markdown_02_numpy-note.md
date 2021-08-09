# Numpy

## 1. ndarray (Numpy Dimensional Array)

### import

* import numpy as np로 불러오기

  ```python
  import numpy as np
  ```

  

### Array 생성

* .dtype으로 array 전체의 데이터 타입을 반환하고 shape(차원 구성)을 반환

```python
test_array = np.array([1,4,5,8],float)
print(test_array)
type(test_array[3])
print(test_array.dtype)
print(test_array.shape)
```



* numpy는 np.array 함수를 활용하여 배열을 생성 -> ndarray
* numpy는 하나의 데이터 타입만 배열에 넣을 수 있음
* List와 가장 큰 차이점, Dynamic typing(예, [1, 2, "5", 4.2]) not supported
* C의 Array를 사용하여 배열을 생성함



## 2. Array shape

#### Vector (1차원)

```python
test_array = np.array([1, 4, 5, 8], float)
```

* shape은 (4, ) : 1차원에 4개의 element가 있는 벡터

  

#### Matrix (2차원)

```python
matrix = [[1,2,5,8],[2,3,4,9],[4,5,6,7]]
np.array(matrix, int).shape
```

* shape은 (3, 4) : 행이 3개, 열이 4개인 매트릭스



#### tensor (3차원)

```python
tensor = [[[1,2,5,8], [2,3,4,9], [4,5,6,7]],[[1,2,5,8], [2,3,4,9], [4,5,6,7]],[[1,2,5,8], [2,3,4,9], [4,5,6,7]],[[1,2,5,8], [2,3,4,9], [4,5,6,7]]]
np.array(tensor, int ).shape
```

* shape 은 (4, 3, 4) : 평면이 4 개 , 행이 3 개 , 열이 4 개인 텐서

