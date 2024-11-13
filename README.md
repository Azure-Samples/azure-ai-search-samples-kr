# Azure AI Search 샘플 한국어 버전

이 리파지토리는 [Azure AI Search](https://learn.microsoft.com/ko-kr/azure/search/search-what-is-azure-search)에 대한 기본적인 샘플을 담고 있으며, python으로 실행하여 볼 수 있도록 구성되어 있습니다.

이 워크샵을 통해, 기본적인 인덱스 생성과 검색을 [Python](https://learn.microsoft.com/ko-kr/azure/search/samples-python), [Rest API](https://learn.microsoft.com/ko-kr/azure/search/samples-rest), [Azure Portal](https://portal.azure.com/#view/Microsoft_Azure_ProjectOxford/CognitiveServicesHub/~/CognitiveSearch)을 통해 수행하는 예제와 [Vector Search](https://learn.microsoft.com/ko-kr/azure/search/vector-search-how-to-create-index), [Skillset](https://learn.microsoft.com/ko-kr/azure/search/cognitive-search-working-with-skillsets), [RAG](https://learn.microsoft.com/ko-kr/azure/search/retrieval-augmented-generation-overview)에 대해 배울 수 있습니다.

## 시작하기
이 워크샵은 Python 환경에서 실핼 할 수 있으며, [Visual Sutdio Code](https://code.visualstudio.com/)나 [GitHub Codespace](https://github.com/features/codespaces) 환경을 통해서 개발 환경을 빠르게 구성하고 시작할 수 있습니다.
GitHub을 통해 빠르게 시작하기 원하시면  **아래 버튼을 클릭**하여 GitHub Codespaces에서 리파지토리를 열어서 시작하세요!

Python 실행을 위한 Runtime 환경은 `python=3.11.4`에서 테스트 되었으며 해당 버전을 추천합니다. 위 버튼을 누르고 약 7-10분이 경과되면, .devcontainer에 정의된 개발 환경 및 라이브러리 설치가 완료되며, 브라우저에 Visual Studio Code IDE가 표시됩니다.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/Azure-Samples/azure-ai-search-samples-kr?quickstart=1)

> Dev container와 Codespaces에 대해 더 자세한 내용을 알고 싶으시면 [Development Containers](https://containers.dev/), [Github Codespaces](https://docs.github.com/ko/codespaces)를 클릭하세요.

### 설정하기

안전한 로컬 환경에서의 키관리를 위해 실습에 필요한 API Endpoint 또는 API Key는 ***.env*** 파일을 활용하는 것을 추천합니다. 예를 들어 [.env.sample](./.env.sample) 파일을 복사하여 `.env` 파일을 만들고 해당 API KEY 정보를 입력하여 사용합니다.

### 더 많은 예제

이 예제 이외의 더 다양한 예제를 학습하시길 원하시면 다음 리포지토리를 방문해 보세요.

- [https://github.com/Azure-Samples/azure-search-python-samples](https://github.com/Azure-Samples/azure-search-python-samples)
- [Vector samples - Azure AI Search](https://github.com/Azure/azure-search-vector-samples)
- [REST examples for Azure AI Search](https://github.com/Azure-Samples/azure-search-rest-samples)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## License Summary

This sample code is provided under the MIT-0 license. See the LICENSE file.