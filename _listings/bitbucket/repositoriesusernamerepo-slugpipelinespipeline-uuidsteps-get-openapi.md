---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Get Repositories Username Repo Slug Pipelines Pipeline Uu Steps
  description: Get repositories username repo slug pipelines pipeline uu steps
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pipelines/{pipeline_uuid}/steps/:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Pipeline Uu Steps
      description: Get repositories username repo slug pipelines pipeline uu steps
      operationId: getRepositoriesUsernameRepoSlugPipelinesPipelineUuSteps
      x-api-path-slug: repositoriesusernamerepo-slugpipelinespipeline-uuidsteps-get
      parameters:
      - in: path
        name: pipeline_uuid
        description: The UUID of the pipeline
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Pipeline
      - Uu
      - Steps
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---