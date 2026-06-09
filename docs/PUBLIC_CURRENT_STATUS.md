# Public Current Status

Статус: публичный текущий статус Garmon World.

Эта страница суммирует, что можно сказать безопасно на публичном уровне без публикации приватных деталей реализации.

Последний review: 2026-05-12.

## Текущая позиция

Garmon World — публичная исследовательская поверхность для Garmon.

Центральная публичная идея:

> искусственный ответ может иметь происхождение до речи.

Garmon исследует путь до финальной формулировки LLM: internal state, body contour, meaning, choice boundary, trace, speech.

Компактная публичная исследовательская рамка:

```text
state → body contour → meaning → choice boundary → trace → speech
```

Эта рамка даёт читателям ясный способ понять текущую публичную работу: Garmon не сводит формирование ответа к финальной генерации текста.

## Текущий публично-безопасный результат

Garmon имеет публично-безопасный static/shadow evidence layer вокруг body-contour distinction до речи LLM.

Текущий публичный результат: несколько кандидатов body-contour остаются различимыми до финальной речи:

- quiet baseline;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- day/night rhythm.

Эти контуры не схлопываются в один generic label.

Это важно, потому что делает часть пути до речи более inspectable.

## Публично-безопасная цепочка

Помимо Body Shadow, публичный слой описывает closed static choice boundary chain:

```text
body contour
→ meaning candidate
→ passive context
→ choice visibility boundary
→ choice ownership boundary
→ behavior boundary
```

Расширенная публичная цепочка:

```text
body contour
→ meaning candidate
→ passive context
→ choice visibility boundary
→ choice ownership boundary
→ behavior boundary
→ pre-selected result boundary candidate (synthetic)
```

Этот маркер обозначает дверь прямо перед actual selected result.

## Что это показывает

Публично-безопасные саммари говорят, что Garmon имеет evidence для:

- body-contour distinction до речи;
- contours, движущихся к meaning candidates;
- passive context, остающегося отдельным;
- choice visibility;
- choice ownership;
- behavior;
- synthetic marker на pre-selected result boundary.

Это даёт Garmon более inspectable pre-speech review surface.

## Более широкое рабочее направление

Текущий результат внутри направления:

```text
internal state → meaning → choice boundary → time/trace → speech
```

Короткий закон:

```text
participation is not power
```

## Следующий публичный артефакт

Small body-contour distinction artifact, показывающий, как quiet baseline, fatigue, recovery, stress, mixed stress/recovery и day/night rhythm остаются различимыми до финальной речи.

Артефакт показывает принцип:

> разные внутренние контуры могут формировать смысл до речи, оставаясь ниже protected choice и action boundaries.

## Публичный фокус review

- Понятно ли body-contour distinction?
- Ясен ли Body Shadow как review surface?
- Понятна ли chain?
- Что минимальный artifact сделает achievement easiest to review?

## One-Line Summary

Garmon имеет public-safe review surface для origin ответа до речи: distinguishable body contours к meaning и protected choice-boundary markers.