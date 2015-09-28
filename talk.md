# CocoaPods

## OpenSourceBash, September 2015

### Boris Bügling - @NeoNacho

![20%, original, inline](images/contentful.png)

![](images/cocoapods.jpg)

<!--- use Sketchnote theme, white -->

---

## CocoaPods is the dependency manager for Swift and Objective-C Cocoa projects.

![](images/cocoapods.jpg)

---

![inline](images/community.png)

![](images/cocoapods.jpg)

---

# Reducing this

![inline](images/setup.png)

![](images/cocoapods.jpg)

---

# to this

```ruby
pod 'ReactiveCocoa'
```

![](images/cocoapods.jpg)

---

# but also

- Declarative language for libraries
- Transitive dependencies
- Discovery of new libraries
- Plugin system

![](images/cocoapods.jpg)

---

# podspec

```ruby
Pod::Spec.new do |s|
  s.name             = "Contentful"
  s.version          = "0.1.0"
  s.summary          = "Swift SDK for Contentful's Content Delivery API."
  s.homepage         = "https://github.com/contentful/contentful.swift/"
  s.social_media_url = 'https://twitter.com/contentful'

  s.license = {
    :type => 'MIT',
    :file => 'LICENSE'
  }

  s.authors      = { "Boris Bügling" => "boris@buegling.com" }
  s.source       = { :git => "https://github.com/contentful/contentful.swift.git",
                     :tag => s.version.to_s }
  s.requires_arc = true

  s.source_files         = 'Code/*.swift'

  s.ios.deployment_target     = '9.0'
  s.osx.deployment_target     = '10.11'

  s.dependency 'Interstellar', '~> 1.1.0'
end
```

---

```bash
$ pod install
Analyzing dependencies
Downloading dependencies
Using Interstellar (1.1.0)
Using Nimble (2.0.0-rc.3)
Using Quick (0.6.0)
Generating Pods project
Integrating client project
Sending stats
```

---

# Technologies

- Written in Ruby
- Relies heavily on Xcode

![](images/cocoapods.jpg)

---

# Websites

![](images/cocoapods.jpg)

---

![inline](images/pod-page.png)

![](images/cocoapods.jpg)

---

![inline](images/cocoadocs.png)

![](images/cocoapods.jpg)

---

# Community

![](images/cocoapods.jpg)

---

# Test Jam 2015

![inline](images/testjam.jpg)

![](images/cocoapods.jpg)

---

# Contributor Coins

![inline](images/coins.jpg)

![](images/cocoapods.jpg)

<!-- top 80 contributors of CocoaPods/CocoaPods -->

---

# RailsGirls Summer of Code

![inline](images/rgsoc.jpg)

![](images/cocoapods.jpg)

---

# Contributing

![](images/cocoapods.jpg)

---

# Resources

- <http://cocoapods.org>
- <http://blog.cocoapods.org/starting-open-source/>
- <https://github.com/CocoaPods/CocoaPods/labels/d1%3Aeasy>

![](images/cocoapods.jpg)
