# Changelog

## resource-metadata

### 0.0.3 / 6.9.2023
* [Bug fix] Remove the IAM role named Default - there is no need for this role and it can cause a conflict.

### 0.0.2 / 16.8.2023
* [Update] Add an option to use an existing secret instead of creating a new one with SSM, and remove ssm_enabled variable.

### 0.0.1 / 8.8.23
* [Update] Add support for govcloud, by adding custom_s3_bucket variable.
