# xcode-snippets 

![GitHub](https://img.shields.io/github/license/techinpark/xcode-snippets?style=plastic)

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
