# Week 1: LLM의 기본 이해하기

> ### 📚 Week1 과제 제출: [PDF 데이터 추출하기](https://github.com/AI-Study-LYB/week1/blob/week1/submission/%EC%9D%B4%EC%9C%A0%EB%B9%88.md)

## 학습할 내용
* LLM API의 호출 방법을 알고 그 쓰임새에 대해 이해한다.
* LLM 을 이해할 때 `이것 만큼은 알아야 한다` 라고 하는 기본 지식을 살펴봅니다.

## 주요 개념
* LLM 을 이해할 때 꼭 알아야 하는 개념들 [BASIC_LLM.md](docs/BASIC_LLM.md)
* 프롬프트 엔지니어링이란 무엇일까? [PROMPT_ENGINEERING.md](docs/PROMPT_ENGINEERING.md)

## 미션
#### Gemini API를 이용한 PDF 데이터 정형화 추출
* `과제 목표`: Gemini API의 File API와 Structured Output 기능을 활용하여 PDF 문서에서 특정 데이터를 추출하고 Pydantic 모델로 구조화하는 방법을 이해하고 실습할 수 있습니다.
* `요구 사항`:
  * Gemini API의 File API를 이용하여 PDF 파일을 업로드하고, Pydantic 모델을 정의하여 해당 PDF 파일에서 원하는 데이터를 정형화된 형태로 추출하는 코드를 작성합니다.
  * 샘플 PDF 파일(invoice.pdf, handwriting_form.pdf) 또는 개인적으로 준비한 PDF 파일을 사용해도 좋습니다.
  * 모델은 Gemini 2.5 Flash를 이용합니다.
* `최종 결과물`: 작성된 결과물을 Pull Request로 올려주세요.
* `참고자료`: Jupyter Notebook
  * [Pdf_structured_outputs_on_invoices_and_forms.ipynb](docs/Pdf_structured_outputs_on_invoices_and_forms.ipynb)
