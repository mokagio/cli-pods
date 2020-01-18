# frozen_string_literal: true

source "https://rubygems.org"

# This commit matches the fix for an issue which would prevent us from defining
# a Podfile for CLI tools that doesn't generate the Pods project to integrate.
# See https://github.com/CocoaPods/CocoaPods/issues/9288.
gem 'cocoapods', git: 'https://github.com/cocoapods/cocoapods.git', ref: 'f848680c0b0f246b50a256f1e47758a91b8223a9'
# We need to specify cocoapods-core too, otherwise `bundle pod install` will
# fail with something similar to this
# https://github.com/CocoaPods/CocoaPods/issues/9231.
gem 'cocoapods-core', git: 'https://github.com/cocoapods/core.git', ref: '5c7c11df7b4d1626292f525e747fd2732666f99d'
