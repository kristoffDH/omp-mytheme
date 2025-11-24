# omp-mytheme

window oh-my-posh theme 파일입니다.
해당 파일의 경로는 $HOME/.mytheme.omp.json 파일에 저장하고 $profile 파일에서 아래처럼 지정하여 적용합니다.
```powershell
oh-my-posh init pwsh --config $HOME/.mytheme.omp.json | Invoke-Expression
```

string tag 적용 방법은 다음과 같습니다.
```powershell
$env:OMP_TAG = "표시할 문자열"

```