---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = AgreementRequestBuilder.AgreementRequestBuilderGetQueryParameters(
		expand = ["files"],
)

request_configuration = AgreementRequestBuilder.AgreementRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.term_of_use.agreements.by_agreement_id('agreement-id').get(request_configuration = request_configuration)


```