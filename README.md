# xcode-snippets 
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

![GitHub](https://img.shields.io/github/license/techinpark/xcode-snippets?style=plastic) [![Twitter: @techinpark](https://img.shields.io/badge/contact-@techinpark-blue.svg?style=flat)](https://twitter.com/techinpark)


ios 개발시 유용한 snippet 들을 모아놓은 repository 입니다. 


### Installation

<img src='./images/install.png'>

- scripts
```bash 
git clone https://github.com/techinpark/xcode-snippets.git
cd xcode-snippets
chmod +x ./install.sh 
./install.sh 
```

## Snippets List :memo:

#### A. Rx+Snippets 🚀
 ##### `RxSwift` 와 함께 사용하면 유용한 `Snippet` 모음입니다. 

### 01. subscribe(onNext)

 |파일명|[rx-subscribe-onNext.codesnippet](./rx-subscribe-onNext.codesnippet)|
 |--|--|
 |단축어|`_subscribeOnNext`|
 
 
```swift
.subscribe(onNext: {[weak self] _ in
                guard let self = self else { return }
                
            })
            .disposed(by: self.disposeBag)
```
#### B. UI+Snippets 🚀
 ##### `UI` 개발시 사용하면 유용한 `Snippet` 모음입니다. 

### 01. Appearance Settings 

|파일명|[ui-appearance-settings.codesnippet](./ui-appearance-settings.codesnippet)|
 |--|--|
 |단축어|`_appearanceSettings`|
 
```swift
private struct Metric {
        
}
    
private struct Font {
        
}
    
private struct Color {
        
}
```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="http://bit.ly/31Lsy5q"><img src="https://avatars1.githubusercontent.com/u/6590255?v=4" width="100px;" alt="Sungwook Kang"/><br /><sub><b>Sungwook Kang</b></sub></a><br /><a href="https://github.com/techinpark/xcode-snippets/commits?author=87kangsw" title="Code">💻</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!