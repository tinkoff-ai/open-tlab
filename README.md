# Open.TLab

В отделе исследований нам постоянно приходится придумывать новые идеи. В рамках Open.TLab, нашей новой инициативы по поддержке студентов и сочувствующих,  мы предлагаем вам вместе поработать над **вашей** исследовательской идеей. Все подробности можно найти [здесь](https://www.youtube.com/watch?v=xvFZjo5PgG0&ab_channel=Duran) (и [здесь](https://fintech.tinkoff.ru/academy/mipt_lab/open_call/)). 

Ниже мы прикладываем шаблон для пропозалов (aka исследовательская идея), мы ожидаем, что при отправке вашей идеи вы будете придерживаться именно его. При подаче заявки, вы можете приложить .pdf файл или ссылку на публичную страницу в [Notion](https://notion.so). Второй вариант нам нравится больше. 

Мы постараемся дать обратную связь на вашу идею, и если она покажется нам перспективной, то пригласим на работу в рамках [TLab](https://fintech.tinkoff.ru/academy/mipt_lab/) лаборатории при МФТИ.

## FAQ
- Сколько занимает рассмотрения пропозала?
  - От 2-х недель
- Рассматриваете ли вы идеи для курсовых и дипломных работ?
  - Нам интересно работать над идеями, у которых высокий потенциал быть опубликованными на крупных конференциях. Как показывает наша практика работы со студентами: даже workshop-level работы достаточно, чтобы собрать из неё хорошую курсовую или дипломную работу. Важно понимать: мы занимаемся исследованиями, их потенциально можно обернуть в диплом, но это уже на вашей стороне.
- Есть ли примеры пропозалов?
  - Да, мы приложили собственные пропозалы [[RL](examples/eop.md), [NLP](examples/palbert.md)] на основе которых были написаны и опубликованы статьи на [ICML2022](https://proceedings.mlr.press/v162/kurenkov22a.html) и [NeurIPS2022](https://arxiv.org/abs/2204.03276).
- В каких областях вы рассматриваете пропозалы?
  - Reinforcement Learning, Natural Language Processing, Recommender Systems, Computer Vision, Speech Processing
- Что если идея не взлетела спустя пару недель, меня уволят?
  - Нет, работа в рамках TLab'a подразумевает полугодовой срок. За это время мы успеем проитерироваться несколько раз по новым пропозалам.
- А что после полугода совместной работы?
  - Самых топовых ребят мы готовы брать в штат команды исследований (из плюсов - вы сможете постить мемы в [Желтый AI](https://t.me/tinkoffai)).
- Какая загруженность?
  - Мы ожидаем около 30 часов в неделю. При этом, мы понимаем, что у вас могут быть сессии или непредвиденные обстоятельства, с этим никаких проблем нет -- take your time, but plan in advance.
- Мне пришел фидбек по пропозалу, и его решили не брать в совместную работу. Стоит ли мне присылать новый или доработать старый?
  - Мы укажем в фидбеке, стоит ли доделать пропозал и сделать ресабмит. Новые пропозалы всегда приветствуются.
- Могу ли я отправить сразу несколько пропозалов?
  - Да. Однако, лучше ограничиться 2-3, которые кажутся вам наиболее интересными.

## Foreword

Представьте, что у вас есть доступ к 8x A100 80Gb, полгода на эксперименты и желание опубликоваться на топовой конференции (последнее, надеемся, у вас и так есть, поэтому особо представлять не придется). Что бы вы тогда делали? 

Ниже для простоты мы кратко перечислили самые важные вопросы, на которые хочется услышать ответ. Всё это важные пункты, потому что они отличают идею, которую реально реализовать, от Research Proposal “Давайте обучим GPT-5”.

Если у вас прям сейчас нет готовой идеи, то можно воспользоваться хитрым ~~kernel~~ трюком и посмотреть на принятые статьи с конференций последних лет (ICML, NeurIPS, ICLR, ACL).


## Research Proposal Template

### TL;DR

Опишите идею в паре предложений.

- 

### Motivation

Опишите проблему, которую хочется решить. Почему это важно?

- 

### Related Work

Что уже есть по этой теме? В первую очередь статьи, потом имплементации и всё остальное. Напишите по 1-2 предложению для каждой из статьи, чтобы было понятно, о чем они, какие результаты они получили и насколько им можно доверять.

- 

### Idea

Как предлагается решить проблему? Что нового в этом решении? Здесь хочется увидеть достаточно подробное описание.

- 

### Discussion

Почему это будет работать? Может быть, есть работы, из которых можно сделать такой вывод или построить некую интуицию. Bonus: почему это может не заработать? На что стоит обратить внимание.

- 

### Experiments A

Как быстро проверить идею на работоспособность (условно, за пару недель), чтобы решить, стоит ли копать в нее дальше.

Из важных пунктов здесь это:

1) Какие датасеты придется использовать? Доступны ли они публично?

2) Какие есть baselines для предложенного метода? Есть ли они вообще? Доступны ли они публично?

3) Какие метрики будут использоваться, чтобы показать, что идея работает? Насколько сложно посчитать эти метрики (e.g., human eval на Mechanical Turk может быть посчитать сложно)?

4) Как решить спустя пару недель, работает ли идея? Какие для этого есть критерии? Какие критерии того, что идея все-таки не работает?

### Experiments B

Что делать, если идея все-таки заработает?

- 
