<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# GaussDB-JDBC-Driver Changelog

## [Unreleased]

## [1.0.0] - 2026-05-04

### Added
- GaussDB JDBC Driver 8.6.1 (huaweicloud-dws-jdbc) bundled
- Standard connection support via `jdbc:gaussdb://` URL
- IAM (Access Key) authentication support via `jdbc:dws:iam://` URL
- **GaussDB IAM (Access Key)** auth provider with dedicated fields: Access Key ID, Secret Access Key (OS keychain), IAM Username (DbUser), Auto-create user
