# dnscrypt_proxy_osx_ios

A Mac (GUI) client for DNSCrypt-proxy v2.0+. Basically an adapter and a UI wrapped over the dnscrypt-proxy executable. It is worth repeating this app uses the DNSCrypt-proxy and does not implement the dnscrypt protocol itself.

Built using the [Flutter Multi-Platform Framework](https://docs.flutter.dev/get-started/install/macos#macos-setup).


# Releases

TODO

GH Releases DL page

# Usage

TODO


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Dependencies

* [Flutter Framework](https://flutter.dev/)
* [Fastlane](https://docs.fastlane.tools/)
* * [Fastlane.match](https://fastlane.tools/match)

## Setting up a Development Env.

Development environment is `Mac OS/OS X` because this is a Mac/iOS app!
You will also need to:

* install the Mac XCode app
* run `xcode-select --install` from a terminal

First time setup steps:

* Install [Fastlane](https://docs.fastlane.tools/)
* From the project root directory, install Ruby gem bundler and run:
  ```
    gem install bundler
    touch Gemfile
    echo "" >> Gemfile
    echo "" >> Gemfile
    bundle update
    bundle exec fastlane --init
  ```

## Licensing

This DNSCrypt-Proxy client was developed under a GNU public license and is free.

