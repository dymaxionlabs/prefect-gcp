# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## 0.1.0

Released on March 17th, 2022.

### Added

- `cloud_storage_copy_blob`, `cloud_storage_create_bucket`, `cloud_storage_download_blob_as_bytes`, `cloud_storage_download_blob_to_file`, `cloud_storage_upload_blob_from_file`, and `cloud_storage_upload_blob_from_string` tasks - [#1](https://github.com/PrefectHQ/prefect-gcp/pull/1)
- `bigquery_create_table`, `bigquery_insert_stream`, `bigquery_load_cloud_storage`, `bigquery_load_file`, and `bigquery_query`, tasks - [#2](https://github.com/PrefectHQ/prefect-gcp/pull/2)
- `create_secret`, `delete_secret`, `delete_secret_version`, `read_secret`, and `update_secret` tasks - [#3](https://github.com/PrefectHQ/prefect-gcp/pull/5)