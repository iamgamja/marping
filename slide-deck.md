---
marp: true
theme: gaia
style: |
  img[alt=M] {
    width: 100%;
  }
  img[alt=N] {
    width: 50%;
    margin: 0 auto;
  }
---

<!-- _class: lead -->

# 가중평균으로 기하 공식 분석하기

20309 김주원

---

## 평균

* 1, 2, 3의 평균?
* 1, 2, 3, 3, 3, 3, 3, 3, 3의 평균?
* 개수가 많을수록 더 큰 영향력을 갖는다
* **가중치** ≔ 각 원소의 영향력
* 각 원소에 가중치를 곱해 표현

---

## 가중평균
$$
\text{평균} = \frac{a_1 + a_2 + \cdots + a_N}{N}
$$

$$
\text{가중평균} = \frac{w_1a_1 + w_2a_2 + \cdots + w_Na_N}{w_1 + w_2 + \cdots + w_N}
$$

* 평균은 모든 가중치가 1인 가중평균
* $w_i$는 자연수가 아니어도 된다!

---

<!-- _class: lead -->

# 기하에 적용하기

---

## 위치벡터의 내분

![M](test1.png)

$$

$$

---

## 위치벡터의 내분

![M](test2.png)

- $m:n = 1:2$ 내분점
$$
\vec C = \frac{m \cdot \vec B + n \cdot \vec A}{m + n} = \frac{1 \cdot \vec B + 2 \cdot \vec A}{1 + 2}
$$

---

## 위치벡터의 내분

![M](test3.png)

- $w_A = 2$, $w_B = 1$인 가중평균
$$
\vec C = \frac{w_A \cdot \vec A + w_B \cdot \vec B}{w_A + w_B} = \frac{2 \cdot \vec A + 1 \cdot \vec B}{2 + 1}
$$

---

## 위치벡터의 내분

![M](test4.png)

- $w_A = 2$, $w_B = 0$인 가중평균
$$
\vec C = \frac{w_A \cdot \vec A + w_B \cdot \vec B}{w_A + w_B} = \frac{2 \cdot \vec A + 0 \cdot \vec B}{2 + 0}
$$

---

## 위치벡터의 외분

![M](test5.png)

- $w_A = 2$, $w_B = -1$인 가중평균
$$
\vec C = \frac{w_A \cdot \vec A + w_B \cdot \vec B}{w_A + w_B} = \frac{2 \cdot \vec A - 1 \cdot \vec B}{2 - 1}
$$

---

## 위치벡터의 외분

![M](test6.png)

- $m:n = 1:2$ 외분점
$$
\vec C = \frac{m \cdot \vec B - n \cdot \vec A}{m - n} = \frac{1 \cdot \vec B - 2 \cdot \vec A}{1 - 2}
$$

---

<!-- _class: lead -->

# 다각형의 무게중심

---

## 삼각형의 무게중심

![N](test7.png)

$$
\vec M = \frac{\vec A + \vec B + \vec C}{3}
$$

---

## 다각형의 무게중심

![N](test8.png)

---

## 다각형의 무게중심

![N](test9.png)

- 다각형을 삼각형으로 쪼개는 트릭

---

## 다각형의 무게중심

![N](test10.png)

- 각 삼각형의 무게중심을 구하고...

---

## 다각형의 무게중심

![N](test11.png)

- 각 삼각형의 무게중심을 구하고...
- **넓이를 가중치**로 하여 가중평균

---

## 다각형의 무게중심

![N](test12.png)

- 볼록다각형이 아니어도 된다

---

## 다각형의 무게중심

![N](test13.png)

- 단순다각형이 아니면 성립하지 않는다

---

<!-- _class: lead invert -->

# 감사하다
