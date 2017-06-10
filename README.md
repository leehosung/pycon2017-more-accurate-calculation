# 파이콘 2017. 보다 정확한 숫자 계산

## 동기

저는 파이썬을 주언어로 사용해서 금융 서비스 [8퍼센트](https://8percent.kr)를 개발/운영 하고 있습니다. 금융 서비스의 특징상 정확한 숫자 계산이 필수적입니다. 따라서 이 서비스를 개발하면서 겪었던 정확한 숫자 계산에 관련된 부분들을 정리해서 공유하고자 합니다. 

## 발표자 소개

* Py행thon 을 사용하고 있는 [8퍼센트](https://8percent.kr)에서 CTO를 맡고 있습니다. 
* PyCon 2015 Korea에서 [Python 테스트 시작하기](https://www.pycon.kr/2015/program/49) 라는 주제로 발표를 했습니다.

## 대상 청중 

Python에 대한 지식이 있지 않아도 문제가 없을 정도의 초보자를 대상으로 합니다. 청중은 제 발표를 듣고 나서 Python 에서 숫자의 저장과 연산이 어떻게 이뤄지는지와 주의해야 할 점이 무엇인지를 얻을 수 있습니다. 그리고 그러한 주의점들을 해결하기 위해서 Python 에서 제공하고 있는 방법들이 무엇인지 알 수 있습니다. 

## 발표 개요

- [PEP3141](https://www.python.org/dev/peps/pep-3141/) 에 소개되어 있는 숫자 관련 클래스의 구조를 설명합니다.
- Floating Point 의 저장방식과 관련해서 발생될 수 있는 오류들을 소개합니다.
- 위의 오류와 관련된 [반올림 문제](https://stackoverflow.com/questions/10825926/python-3-x-rounding-behavior)를 설명 합니다. 
- 보다 정확한 소수점 계산을 위해 [decimal](https://docs.python.org/3/library/decimal.html#module-decimal), [fractions](https://docs.python.org/3/library/fractions.html#module-fractions) 모듈을 소개합니다.
- (optional) Django, Flask에 관련 예시를 추가로 소개합니다.
