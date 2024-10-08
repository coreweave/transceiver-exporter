# Changelog

## 1.5.0 - 2024-05-06
### Changes
* Added the option to include and exclude interfaces with regex
  * Thanks @rwxd for this contribution! 

## 1.4.1 - 2023-08-01
### Changes
* --version now returns the correct version

## 1.4.0 - 2023-07-10
### Changes
* Added the option to exclude admin down interfaces
  * `-exclude.interfaces-down`
  * Thanks @4xoc for this contribution! 

## 1.3.0 - 2023-06-14
### Changes
* Added the option to include specific interfaces
  * `-include.interfaces`
  * Thanks @SRv6d for this contribution! 

## 1.2.0 - 2023-06-07
### Changes
* Added arm binary to CI

## 1.1.0 - 2022-08-25
### Changes
* Added the option to export optical power in dBm instead of mW
  * `-collector.optical-power-in-dbm`
  * Thanks for @BarbarossaTM (Cloudflare) for contributing this feature.
* Updated dependencies
  * Switched from deprecated `prometheus/common/log` to `sirupsen/logrus`

### Notes
* For this release we moved the repository from GitLab to GitHub.

## 1.0.1 - 2020-07-14
### Changes
* Switched to GoLang compliant versioning scheme
* Fixed a bug where the scrape would fail due to reading bad data

## 1.0 -  2020-07-13
### Changes
* Initial release
