## 자주쓰는 모듈 구성
### statsmodels
#### │
#### ├── 01 사후분석
#### │---│
#### │   └──stats
#### │       └── multicomp
#### │           ├── MultiComparison
#### │           │   └── allpairtest
#### │           └── pairwise_tukeyhsd
#### │
#### ├── 02 시계열분석
#### │   │
#### │   ├── graphics.tsaplots
#### │   │   ├── plot_acf
#### │   │   └── plot_pacf
#### │   └── tsa
#### │       ├── arima_model
#### │       │   └── ARIMA
#### │       └── statesplace.sarimax
#### │           └── SARIMAX
#### │
#### ├── 03 ANOVA (scipy모듈과 함께써야 모두 커버가능, 이분산 anova의 경우 pingouin모듈의 welch_anova를 사용)
#### │   │
#### │   ├── 다원분산분석 or 이원분산분석
#### │   └── 일원분산분석
#### │       └── stats.anova
#### │           └── anova_lm
#### │
#### └── 04 회귀분석
####     │
####     └── formula.api
####         └── ols
