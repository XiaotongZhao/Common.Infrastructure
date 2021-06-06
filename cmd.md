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

dotnet nuget add source --username Xiaotong.Zhao --password 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 --store-password-in-clear-text --name github "https://nuget.pkg.github.com/XiaotongZhao/index.json"

dotnet nuget push "Infrastructure.EventBus.1.0.0.nupkg"  --api-key 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 --source "github"