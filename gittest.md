# 통계 함수 공식

정규분포는 다음과 같은 수식으로 표현됩니다:

$$
f(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} \exp\left( -\frac{(x - \mu)^2}{2 \sigma^2} \right)
$$

카이제곱 분포는 다음과 같습니다:

$$
f(x; k) = \frac{1}{2^{k/2} \Gamma(k/2)} x^{(k/2) - 1} \exp\left( -\frac{x}{2} \right)
$$

초기하 분포의 공식은 다음과 같습니다:

$$
P(X = k) = \frac{\binom{K}{k} \binom{N - K}{n - k}}{\binom{N}{n}}
$$

기하 분포는 다음과 같습니다:

$$
P(X = k) = (1 - p)^{k} p
$$

포아송 분포는 다음과 같은 수식으로 표현됩니다:

$$
P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}
$$

음이항 분포의 공식은 다음과 같습니다:

$$
P(X = k) = \binom{k + r - 1}{k} p^r (1 - p)^k
$$
