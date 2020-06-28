# dotnetcore-blazorwasm-sample
Blazor WebAssemblyのテンプレートをベースに作成しているサンプルアプリです。

### テンプレートからのアプリ作成
1. .NET Core 3.1 SDKをインストール
2. Blazor WebAssemblyのテンプレート最新をインストール  
`dotnet new --install Microsoft.AspNetCore.Components.WebAssembly.Templates::3.2.0`
3. アプリ作成  
`dotnet new blazorwasm -o dotnetcore-blazorwasm-sample`

### 実行
`dotnet run`

### VSCodeでのデバッグ設定
1. Extensions>JavascriptDebugging>Use Preview をtrueに設定  
2. C#拡張をインストール  
3. JavaScript Debugger (Nightly)拡張をインストール  
4. 作成したアプリのフォルダーをVSCodeで開く  
5. デバッグ設定を作成するか聞いてくるのでYesを選択  
6. launch.jsonのconfigurationに以下を追記  
`"url": "http://localhost:5000"`

### 参考URL
ASP.NET Core Blazor の概要  
https://docs.microsoft.com/ja-jp/aspnet/core/blazor/?view=aspnetcore-3.1

