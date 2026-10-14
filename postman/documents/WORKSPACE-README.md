## 👋 Welcome

This workspace contains Postman collections that show how to integrate with the PaytestLab APIs.

| Collection | API |
|------------|-----|
| **Sample Commands Extensions.API V2** | **PaytestAPI** (Extensions REST API V2): drive PaytestLab test tools such as robots, multiplexers and probes through extensions. Runs on-premises. |
| **PaytestAPI - CardHub example commands** | **CardHub**, the PaytestAPI extension that shares physical payment cards from Card Multiplexers with terminals through PaytestProbe devices. |
| **PaytestHub API** | **PaytestHub Test Runs API**: start test cases and test sets in PaytestHub, poll their status, get results and abort runs. |

## 🚀 Getting started

1. Open the collection you need and set its **collection variables**:
   - **PaytestAPI:** `ApiUrl` (default `http://localhost:8000/ExtensionApi/V2`).
   - **CardHub:** `ApiBaseUrl` (default `http://localhost:8000/`) and `MultiplexerId`.
   - **PaytestHub:** `BEARER_TOKEN`, `AGENT_ID`, `ENVIRONMENT_ID`, `TEST_CASE_ID` and `TEST_SET_ID`.
2. For PaytestHub, create an API token in PaytestHub under **Administration → API Access** and copy the IDs from the PaytestHub URLs.
3. Send the requests. Each collection's description explains what it is for and which variables it needs.

The full guide, including token creation, request formats and status values, is in the repository README:
<https://github.com/Paytestlab/AutomationSoftware.API.Definitions#readme>

## 🔒 Keep secrets safe

Enter API tokens, passwords and IP addresses as local values only, or use Postman Vault. Never share or commit them.

## 📚 Reference documentation

- PaytestAPI, CardHub and extension commands: <https://docs.paytesthub.cloud>
- PaytestHub API (Swagger): <https://paytesthub.cloud/swagger>
- Support: <https://support.paytestlab.com>