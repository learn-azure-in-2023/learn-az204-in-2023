# Learn AZ-204 in 2024

I am learning AZ-204 from different video courses, websites, and books.

## Few Points

> 1. `curl -kL https://localhost:7139/`

```powershell
cd ~/BestBikeApp
dotnet publish -o pub
cd pub
zip -r site.zip *
```

```powershell
$rgname = 'rg-az104-dev-001'
$webappname = 'app-bestbikesweb'
az webapp deployment source config-zip --src site.zip --resource-group $rgname --name $webappname
```
