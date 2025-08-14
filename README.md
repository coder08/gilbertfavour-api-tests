# reqres-api-tests

Starter repo for API Test Automation assignment (ReqRes + Postman).

## What is here
- `postman/reqres-api-tests.postman_collection.json` — collection with tests and variables
- `postman/reqres-env.postman_environment.json` — optional Postman environment
- `.github/workflows/postman-ci.yml` — GitHub Actions workflow using **Postman CLI**

## Quick start
1. Import the collection and environment into Postman.
2. Run the **Main Flow** folder in the Collection Runner.
3. (Optional) Run the **Negative Tests** folder.

## CI setup
- Create a repo secret **POSTMAN_API_KEY** with your Postman API key.
- Push to the `dev` branch to trigger CI.
- Open a PR from `dev` to `master` or `main` to trigger CI.

## Notes
- Uses `{base_url}`, `{user_id}`, `{name}`, `{job}`, `{email}`, `{page}` variables.
- Default `user_id` is `2`, which exists on ReqRes.
