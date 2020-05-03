## FizzBuzz仕様
* 最初のプレイヤーは「1」と数字を発言する。
* 次のプレイヤーは直前のプレイヤーの次の数字を発言していく。
* ただし、以下の場合は数字ではないものを発言する
  * 3で割り切れる場合は「Fizz」
  * 5で割り切れる場合は「Buzz」
  * 両者で割り切れる場合（すなわち15で割り切れる場合）は「Fizz Buzz」
  
* フィズ・バズ、Bizz BuzzやBuzzとも呼ばれる


## IssueFactory仕様
入力  
質問
```
DDDについて〜ですか？

それとも〜ですか？
@Transactionalはどこにつければいいですか？
```
回答 
```
それは〜です。
なぜなら〜だからです。
```

出力
```
### Question
> DDDについて〜ですか？
> 
> それとも〜ですか？
> `@Transactional`はどこにつければいいですか？

### Answer
それは〜です。
なぜなら〜だからです。
```
